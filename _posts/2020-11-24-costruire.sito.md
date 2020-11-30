---
layout: single
title: Giorno 1 - Costruire (più) di un sito
categories: Tecnicismi
---

L'idea c'è, la voglia pure, restava da creare la pubblica vetrina per questo progetto!

Il primo step è stato la conversione del SRD, fortunatamente distribuito nella versione modificabile in formato docx, in markdown.

In questa operazione è stato fondamentale il contributo di pandoc, la conversione è durata pochi secondi e il markdown bello fiammante era pronto all'uso.

Il problema principale è che, come il [file originale del SRD](https://www.drivethrurpg.com/product/187941/Cepheus-Engine-SRD-Modifiable-Version), il file di output è francamente ingestibile. Occorreva frammentarlo nei vari capitoli.

Qui, soluzioni facili non ce ne sono state. Credevo che splittare un markdown sarebbe stata un'operazione banale, ma non è stato così immediato. Lavoro su macchine windows, quindi workaround come csplit non mi sono concesse.

Fortunatamente ho trovato una bella dritta su [stackoverflow](https://stackoverflow.com/questions/33889814/how-do-i-split-a-markdown-file-into-separate-files-at-the-heading), che in sostanza prevede di convertire prima il file markdown in epub:

```bash
pandoc -f markdown -t epub -o my-book.epub my-book.md
```
quindi, dopo aver scompattato l'epub, che è semplicemente un file compresso con estensione peculiare, scendere nel livello dell'archivio che contiene i file xhtml e rinominarli in html:

```powershell
Get-ChildItem *.xhtml | ForEach-Object{Rename-Item -Path $_ -NewName ($_.basename + ".md") }
```
e quindi convertire il tutto in markdown con pandoc:

```powershell
Get-ChildItem *.html | ForEach-Object{pandoc -f html -t gfm -o ($_.basename + ".md") -s $_}
```
Fin qui, la parte semplice! Restava organizzare come mettere il tutto online.

Sono un fan delle GitHub Pages e di Jekyll, quindi sin dal concepimento, sapevo che il progetto sarebbe stato ospitato su questa piattaforma e servito dal generatore di siti statici per eccellenza.

I vantaggi sono evidenti: le pagine vengono scritte in markdown, che è semplice da imparare e scrivere anche per i non informatici e viene renderizzato meravigliosamente in html da Jekyll una volta caricate sul repository del sito.

Il progetto attualmente consta di quattro (!) repository:

1. [la vetrina principale](https://cepheus-engine-ita.github.io), una semplice landing page che rimanda alle altre componenti;

2. [un documentale](https://cepheus-engine-ita.github.io/srd/), il vero e proprio cuore del progetto, che ospiterà la traduzione del SRD man mano che viene completata;

3. [un repository senza vetrina](https://cepheus-engine-ita.github.io/project/), che ospita i file sorgenti in inglese, i work in progress e i candidati alla pubblicazione sul documentale

4. questo blog, ovviamente.

Il tutto ha richiesto qualche ora di lavoro, tra ricerca dei temi da utilizzare, prove e messa online dei tre siti, ma credo che ne sia valsa la pena!

Dal prossimo post, promesso, basta con intelocuzioni e tecnicismi vari e si entrerà nel vivo dei dettaglio dei progressi di traduzione.
