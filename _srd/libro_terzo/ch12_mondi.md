---
layout: single
permalink: /srd/capitolo-12/
sidebar:
  nav: srd
toc: true
toc_label: Indice
title: 'CAPITOLO 12: MONDI'
published: true

---
Le caratteristiche planetarie fondamentali sono Dimensioni,
Atmosfera, Idrologia, Popolazione, Governo, Livello di Legge,
Livello Tecnologico, Astroporto e Basi, e sono generati usando
lanci di due dadi, con MD applicati in base ad altre caratteristiche.
Queste caratteristiche stabiliscono l’identità di base di un mondo, e
vengono chiamate Profilo di Mondi Universale (PMU). È possibile,
anzi doveroso, generare ulteriori informazioni per descrivere un
mondo più a fondo.

## Il Profilo di Mondi Universale (PMU)

Il Cepheus Engine utilizza un codice a singola riga per incapsulare i dati di un solo mondo in modo che, con un po' di pratica, possa essere letto velocemente e facilmente. Le specifiche del Profilo di Mondi Universale possono essere trovate di seguito:

> NomeMondo 0000 A123456-7x Ni R 123 Na

### Spiegazione

“**NomeMondo**” indica il nome comune per il mondo che è stato profilato.

“**0000**” fornisce la posizione dell'esagono del mondo (colonna, poi riga) nella mappa del settore o del sottosettore.

“**A123456-7**” è il profilo di mondo classico. Ogni numero o lettera è un codice pseudo-esadecimale che rappresenta uno specifico valore nelle corrispondenti tabelle dei dati dei mondi. In ordine, il profilo definisce i seguenti elementi: Astroporto, Dimensione, Atmosfera, Idrografia, Popolazione, Governo, Livello di legge, seguito da un trattino e infine il Livello Tecnologico.

“**X**” indica dove le informazioni riguardanti le basi di un mondo sono annotate. Uno spazio vuoto qui indica che quel mondo non ha basi degne di menzione a livello interstellare.

“**Ni**” è usato per indicare punti di interesse e codici di commercio come parte dei dati del profilo di mondo.

“**R**” fornisce le informazioni riguardanti la classificazione di Zona di Viaggio del mondo. Una "A" rappresenta una Zona Ambra, che indica un mondo che gli avventurieri dovrebbero affrontare con più precauzione del normale. Una "R" indica una Zona Rossa, un mondo verso cui il viaggio è proibito per un certo numero di motivi, da pericoli fisici a riserbo politico.

“**123**” rappresenta una breve sintesi di tre specifici dati: un Moltiplicatore di Popolazione per il mondo principale, il numero di Cinture di Asteroidi nel sistema e il numero di Giganti Gassosi nel sistema.

**“Na**” indica la lealtà interstellare del sistema. “Na” è usato per mondi non allineati.

## Star Mapping

Per universi in Cepheus Engine, la presenza di un sistema stellare è segnata su mappa esagonali, dove ogni esagono rappresenta un parsec. Per ogni sistema, genera un Profilo di Mondi Universale per il mondo principale di quel sistema. La dimensione più piccola di una mappa di astrogazione, il sottosettore, misura otto esagoni in larghezza e dieci in altezza. Una dimensione intermedia, il quadrante, misura due sottosettori per due, mentre la dimensione di mappa più grande, il settore, misura due quadranti per due quadranti.

C’è una possibilità su due, di base, che un
mondo (e il relativo sistema) si trovino in un esagono. Verifica sistematicamente un
esagono alla volta sulla mappa del sottosettore, lanciando
un dado e segnando l’esagono con un cerchio se il risultato è 4, 5
o 6. Questo indica che è presente un mondo; altrimenti, lasciate
l’esagono vuoto. L’Arbitro può scegliere di alterare le normali probabilità della
presenza di mondi, rendendoli più o meno frequenti per
corrispondere a regioni specifiche della galassia. Una densità del
50% (senza MD) è appropriata per le braccia della spirale galattica.
Applicate un MD di -2 per i “settori del crepaccio”, un MD di -1 per
i settori sparsi e un MD di +1 per i settori densamente popolati.

## Dimensioni

La caratteristica Dimensioni per i mondi abitabili va da 0 a 10, e
si ottiene tirando 2d6 – 2.

#### Tabella: Dimensioni

| Cifra  | Dimensioni                      | Gravità di
Superficie (g) |
| ------ | ------------------------------- | ------------------------- |
| 0      | 800 km (di solito un asteroide) | Trascurabile              |
| 1      | 1.600 km                        | 0,05                      |
| 2      | 3.200 km                        | 0,15                      |
| 3      | 4.800 km                        | 0,25                      |
| 4      | 6.400 km                        | 0,35                      |
| 5      | 8.000 km                        | 0,45                      |
| 6      | 9.600 km                        | 0,7                       |
| 7      | 11.200 km                       | 0,9                       |
| 8      | 12.800 km                       | 1,0                       |
| 9      | 14.400 km                       | 1,25                      |
| 10 (A) | 16.000 km                       | 1,4                       |

### Mondi a Gravità Alta e Bassa

I mondi su cui la gravità è 0,75 o meno sono mondi a bassa
gravità. Hanno come caratteristiche comuni formazioni rocciose
dall’aspetto improbabile, forme di vita sottili e affusolate e il volo
come forma comune di locomozione (se l’atmosfera è abbastanza
densa da supportare il volo). Inizialmente, gli umani tendono a
trovare la vita sui mondi a bassa gravità piacevole, ma sono
necessari regimi di esercizi regolari e integratori medicinali per
impedire la degradazione di ossa e muscoli. Chi ha passato troppo
tempo su mondi a bassa gravità non riesce a tollerare gravità
maggiori. I personaggi sui mondi a bassa gravità subiscono un MD
di -1 a tutte le prove di abilità fino a quando si adattano, processo
che dura 1d6 settimane. I personaggi con l’abilità G-Zero a livello 0
o più si adattano istantaneamente.

I mondi ad alta gravità hanno gravità 1,25 volte o più quella
della Terra. Tendono ad essere mondi estremamente densi; le
caratteristiche comuni includono ampie pianure rocciose, creature
tozze e muscolose e vegetazione che si diffonde in orizzontale,
come i licheni, invece di crescere verso l’alto. Le forme di
locomozione più comune sono strisciare, scavare o nuotare. Gli
umani trovano spiacevoli i mondi ad alta gravità. I mondi con gravità
particolarmente alta richiedono l’utilizzo di tute pressurizzate o
potenziate per supportare il corpo umano. I personaggi su mondi
ad alta gravità subiscono un MD di -1 a tutte le prove di abilità
finché non si adattano, processo che dura 1d6 settimane.

## Atmosfera

L’Atmosfera di un pianeta viene generata tirando 2d6 – 7 e
sommando la Dimensione del pianeta. Se la Dimensione di un mondo è pari a 0, allora l'Atmosfera di quel mondo sarà 0. Il codice di Atmosfera non dovrebbe mai superare 15(F).

#### Tabella: Atmosfera

| Cifra  | Atmosfera                 | Pressione       | Attrezzatura necessaria alla Sopravvivenza |
| ------ | ------------------------- | --------------- | ------------------------------------------ |
| 0      | Nessuna                   | 0,00            | Tuta Spaziale                              |
| 1      | Tracce                    | da 0,001 a 0,09 | Tuta Spaziale                              |
| 2      | Molto rarefatta, Velenosa | da 0,1 a 0,42   | Respiratore, Filtro                        |
| 3      | Molto rarefatta           | da 0,1 a 0,42   | Respiratore                                |
| 4      | Rarefatta, Velenosa       | da 0,43 a 0.7   | Filtro                                     |
| 5      | Rarefatta                 | da 0,43 a 0,7   |                                            |
| 6      | Standard                  | da 0,71 a 1,49  |                                            |
| 7      | Standard, Velenosa        | da 0,71 a 1,49  | Filtro                                     |
| 8      | Densa                     | da 1.5 a 2.49   |                                            |
| 9      | Densa, Velenosa           | da 1.5 a 2.49   | Filtro                                     |
| 10 (A) | Esotica                   | Varia           | Scorta aria                                |
| 11 (B) | Corrosiva                 | Varia           | Tuta Spaziale                              |
| 12 (C) | Insidiosa                 | Varia           | Tuta Spaziale                              |
| 13 (D) | Densa, Alta               | 2,5+            |                                            |
| 14 (E) | Rarefatta, Bassa          | 0.5 o meno      |                                            |
| 15 (F) | Insolita                  | Varia           | Varia                                      |

### Tipi di Atmosfera

**Velenosa**: Le atmosfere velenose contengono elementi dannosi
per gli umani, ad esempio proporzioni eccessive di diossido di
carbonio. Un personaggio che respira un’atmosfera velenosa
senza filtro subisce 1d6 danni ogni pochi minuti (o ore, a seconda
del livello di velenosità).

**Esotica**: Un’atmosfera esotica è irrespirabile dagli umani, ma per il
resto non è pericolosa. Un personaggio ha bisogno di una scorta
d’aria per respirare in un’atmosfera esotica.

**Corrosiva**: Le atmosfere corrosive sono pericolosissime. Un
personaggio che respira in un’atmosfera corrosiva subisce 1d6
danni ogni round.

**Insidiosa**: Un’atmosfera insidiosa è come quella corrosiva, ma è
così corrosiva che attacca anche l’equipaggiamento. Il pericolo
principale in un’atmosfera insidiosa è che i gas tossici distruggono
i sigilli e i filtri dell’attrezzatura protettiva del personaggio. Un’atmosfera insidiosa si apre la strada oltre le protezioni dopo 2d6
ore in media, anche se una attenta manutenzione o un’attrezzatura
protettiva avanzata può prolungare i tempi di sopravvivenza.

**Densa, Alta (D)**: Questi mondi hanno atmosfere dense di N2/O2,
ma la pressione media in superficie è troppo alta per supportare la
vita umana senza protezioni (azoto e ossigeno ad alta pressione
sono letali per l’uomo). La pressione, però, decresce naturalmente
con l’aumentare dell’altitudine, per cui se ci sono altopiani alla
giusta altezza la pressione può scendere abbastanza da supportare
la vita umana. In alternativa, possono non esserci elementi
topografici abbastanza alti perché gli umani vi abitino, richiedendo
habitat fluttuanti grav o dirigibili, o habitat sigillati sulla superficie.

**Rarefatta, Bassa (E)**: L’opposto dell’atmosfera Densa, Alta.
Questi mondi massicci hanno atmosfere di N2/O2 sottili, che
si stabilizzano nei bassopiani e nelle depressioni, e solo lì sono
respirabili – la pressione scende così rapidamente con l’altitudine
che i punti topografici più alti della superficie possono essere vicini
al vuoto.

**Insolita (F)**: Insolita è un termine generico per un’atmosfera
che si comporta in modo strano. Alcuni esempi sono atmosfere
ellissoidali, che sono rarefatte ai poli e dense all’equatore; mondi
pantalassici composti di un nucleo roccioso circondato da uno
strato d’acqua spesso centinaia di chilometri; mondi devastati da
tempeste così intense che la pressione dell’aria localmente cambia
da densa a rarefatta a seconda del clima del momento; e altri
pianeti con condizioni atmosferiche insolite e pericolose.

## Idrografia

La percentuale idrografica si ottiene tirando 2d6 – 7 e sommando la Dimensione
del pianeta, modificata dall’atmosfera o dalla dimensione del
pianeta come descritto nella tabella MD Idrografico rispetto a Dimensione e Atmosfera.

#### Tabella: MD Idrografico rispetto a Dimensione e Atmosfera

| Condizione               | MD                       |
| ------------------------ | ------------------------ |
| Dimensione 0 o 1         | Idrografia deve essere 0 |
| Atmosfera 0, 1, A, B o C | –4                       |
| Atmosfera E              | –2                       |

Il valore Idrografico di un mano non dovrebbe mai superare 10 (a), né essere più basso di 0.

#### Tabella: Idrografia

| Cifra  | Percentuale
Idrografica | Descrizione                     |
| ------ | ----------------------- | ------------------------------- |
| 0      | 0%–5%                   | Mondo Desertico                 |
| 1      | 6%–15%                  | Mondo Asciutto                  |
| 2      | 16%–25%                 | Qualche piccolo mare            |
| 3      | 26%–35%                 | Piccoli mari e oceani           |
| 4      | 36%–45%                 | Mondo bagnato                   |
| 5      | 46%–55%                 | Grandi oceani                   |
| 6      | 56%–65%                 |                                 |
| 7      | 66%–75%                 | Simile alla Terra               |
| 8      | 76%–85%                 | Mondo d’acqua                   |
| 9      | 86%–95%                 | Solo qualche isola e
arcipelago |
| 10 (A) | 96–100%                 | Quasi solo acqua                |

## Popolazione

La Popolazione di un mondo è generata tirando 2D6-2, modificato da la Dimensione, l'Atmosfera e l'Idrografia come descritto nella Tabella MD di Popolazione. Il valore di popolazione non dovrebbe mai superare 10(A). Se un mondo ha popolazione di 0, è inabitato e quel mondo ha anche Governo, Livello di Legge e Livello Tecnologico di 0.

#### Tabella: MD di Popolazione

| Condizione                               | MD  |
| ---------------------------------------- | --- |
| Dimensione è 2 o meno                    | -1  |
| Atmosfera è A o superiore                | -2  |
| Atmosfera è 6                            | +3  |
| Atmosfera è 5 o 8                        | +1  |
| Idrografia è 0 and Atmosfera è meno di 3 | -2  |

#### Tabella: Popolazione

| Cifra  | Popolazione           | Numero di Abitanti | Descrizione                              |
| ------ | --------------------- | ------------------ | ---------------------------------------- |
| 0      | Nessuna               | 0                  |                                          |
| 1      | Poca                  | 10+                | Una piccola fattoria
o una famiglia sola |
| 2      | Centinaia             | 100+               | Un villaggio                             |
| 3      | Migliaia              | 1,000+             |                                          |
| 4      | Decine di migliaia    | 10,000+            | Cittadina                                |
| 5      | Centinaia di migliaia | 100,000+           | Città media                              |
| 6      | Milioni               | 1,000,000+         |                                          |
| 7      | Decine di milioni     | 10,000,000+        | Grande città                             |
| 8      | Centinaia di milioni  | 100,000,000+       |                                          |
| 9      | Miliardi              | 1,000,000,000+     | Terra ai giorni nostri                   |
| 10 (A) | Decine di miliardi    | 10,000,000,000+    |                                          |

### Modificatore di Popolazione

A volte è sufficiente conoscere che su un mondo vivono centinaia o milioni di persone. Altre volte, un Arbitro o il giocatore potrebbero volere un numero più specifico. Il Modificatore di Popolazione è determinato tirando 2D6-2. Se il codice di Popolazione è più alto di 0, il Modificatore di Popolazione minimo è 1. Il codice di Popolazione è 0, anche il Modificatore di Popolazione è 0. Il Modificatore di Popolazione è moltiplicato di 10 elevato alla potenza del codice di Popolazione per determinare un numero più preciso di persone che vivono sul quel mondo. Per esempio, se l'Arbitro genera un Modificatore di Popolazione di 4 per un mondo con un codice di Popolazione di 8, allora  400,000,000 (**4**x10<sup>**8**</sup>) persone vivono su quel pianeta.

## Astroporto

Molti mondi possiedono astroporti, dato che la loro presenza è essenziale per scambi e commerci interstellari. Per determinare l'astroporto principale di un mondo, tira 2D6-7 e quindi aggiungi il valore di Popolazione di quel mondo. Confronta il risultato con la tabella Astroporto Principale per determinare la classe dell'astroporto di quel mondo. Ciascuna classe di astroporto offre differenti livelli di servizio. La tabella Classe di Servizi dell'Astroporto fornisce dettagli più specifici.

#### Tabella: Astroporto Principale

| Tiro     | Classe Astroporto |
| -------- | ----------------- |
| 2 o meno | X                 |
| 3        | E                 |
| 4        | E                 |
| 5        | D                 |
| 6        | D                 |
| 7        | C                 |
| 8        | C                 |
| 9        | B                 |
| 10       | B                 |
| 11+      | A                 |

#### 

#### Tabella: Classe di Servizi dell'Astroporto

| Classe | Descrizione | Miglior Carburante | Manutenzione Annuale | Potenziale del Cantiere Navale                          | Basi Possibili      |
| ------ | ----------- | ------------------ | -------------------- | ------------------------------------------------------- | ------------------- |
| A      | Eccellente  | Raffinato          | Sì                   | Può costruire astronavi interstellari e interplanetarie | Navale, Esploratori |
| B      | Buono       | Raffinato          | Sì                   | Può costruire astronavi interplanetarie                 | Navale, Esploratori |
| C      | Routine     | Greggio            | No                   | Può effettuare riparazioni di routine                   | Esploratori         |
| D      | Povero      | Greggio            | No                   | Nessuno                                                 | Esploratori         |
| E      | Frontiera   | Nessuno            | No                   | Nessuno                                                 | Nessuno             |
| X      | Nessuno     | Nessuno            | No                   | Nessuno                                                 | Nessuno             |

## Governo

La caratteristica Governo è determinata tirando 2d6 – 7 e sommando la
Popolazione del pianeta. Se la Popolazione di un mondo è pari a 0, anche il Governo è pari a 0. Il codice di Governo non dovrebbe mai superare 15(F), né essere inferiore a 0.

#### Tabella: Governo

| Tipo   | Governo                          |
| ------ | -------------------------------- |
| 0      | None                             |
| 1      | Compagnia/corporazione           |
| 2      | Democrazia partecipativa         |
| 3      | Oligarchia autoperpetuante       |
| 4      | Democrazia rappresentativa       |
| 5      | Tecnocrazia feudale              |
| 6      | Governo ostaggio                 |
| 7      | Balcanizzazione                  |
| 8      | Burocrazia del servizio
pubblico |
| 9      | Burocrazia Impersonale           |
| 10 (A) | Dittatore carismatico            |
| 11 (B) | Capo non carismatico             |
| 12 (C) | Oligarchia carismatica           |
| 13 (D) | Dittatura religiosa              |
| 14 (E) | Autocrazia religiosa             |
| 15 (F) | Oligarchia totalitaria           |

## Livello di Legge

Il Livello di legge è determinato tirando 2D6-7 e sommando la caratteristica di Governo. Se un mondo ha Governo pari a 0, anche il Livello di Legge sarà 0. Il Livello di Legge non dovrebbe mai essere inferiore a 0.

#### Tabella: Livello di Legge

| Cifra  | Descrizione                    | Attività non permesse                                                                       |
| ------ | ------------------------------ | ------------------------------------------------------------------------------------------- |
| 0      | Nessuna Legge                  | Nessuna restrizione, candidato per lo stato di Zona Ambra                                   |
| 1      | Legge Blanda                   | Gas velenosi, esplosivi, armi non rilevabili, armi di distruzione di massa                  |
| 2      | Legge Blanda                   | Armi portatili a energia (fatta eccezione per armi montate sulle navi)                      |
| 3      | Legge Blanda                   | Armi pesanti                                                                                |
| 4      | Legge Moderata                 | Armi d'assalto leggere e fucili mitragliatori                                               |
| 5      | Legge Moderata                 | Armi portatili occultabili                                                                  |
| 6      | Legge Moderata                 | Tutte le armi da fuoco tranne i fucili da caccia e gli storditori; portare armi scoraggiato |
| 7      | Legge Restrittiva              | Doppiette                                                                                   |
| 8      | Legge Restrittiva              | Tutte le armi a lama, storditori                                                            |
| 9      | Legge Restrittiva              | Qualsiasi arma al di fuori della propria residenza; candidato per lo stato di Zona Ambra    |
| 10(A)+ | Legge Estremamente Restrittiva | Nessun arma consentita; candidato per lo stato di Zona Ambra                                |

## Livello Tecnologico

Il Livello Tecnologico (abbreviato LT) del mondo è
determinato tirando 1D6 e aggiungendo gli MD che si trovano nella tabella MD di Livello Tecnologico per valori di PMU. Il Livello di Tecnologia di un mondo non può essere inferiore a 0.

#### Tabella: MD di Livello Tecnologico per valori di PMU

| Valore | Astroporto | Dimensione | Atmosfera | Idrografia | Popolazione | Governo |
| ------ | ---------- | ---------- | --------- | ---------- | ----------- | ------- |
| 0      |            | +2         | +1        | +1         |             | +1      |
| 1      |            | +2         | +1        |            | +1          |         |
| 2      | \`         | +1         | +1        |            | +1          |         |
| 3      |            | +1         | +1        |            | +1          |         |
| 4      |            | +1         |           |            | +1          |         |
| 5      |            |            |           |            | +1          | +1      |
| 6      |            |            |           |            |             |         |
| 7      |            |            |           |            |             | +2      |
| 8      |            |            |           |            |             |         |
| 9      |            |            |           | +1         | +1          |         |
| 10 (A) | +6         |            | +1        | +2         | +2          |         |
| 11 (B) | +4         |            | +1        |            | +3          |         |
| 12 (C) | +2         |            | +1        |            | +4          |         |
| 13 (D) |            |            | +1        |            |             | –2      |
| 14 (E) |            |            | +1        |            |             | –2      |
| 15 (F) |            |            | +1        |            |             |         |
| X      | –4         |            |           |            |             |         |

Alcune condizioni di un mondo devono soddisfare requisiti minimi di Livello Tecnologico. Se il mondo possiede un Livello Tecnologico inferiore ai requisiti, allora il
l'Arbitro dovrebbe aumentare il Livello Tecnologico di un mondo al minimo richiesto.

#### Tabella: Valori Minimi di Livello Tecnologico

| Condizioni                                        | LT Minimo |
| ------------------------------------------------- | --------- |
| Idrografia è 0 o 10 (A), Popolazione è almeno 6   | 4         |
| Atmosfera è 4, 7 o 9                              | 5         |
| Atmosfera è pari o inferiore a 3 o 10 (A) -12 (C) | 7         |
| Atmosfera è 13 (D) o 14 (E), Idrografia è 10 (A)  | 7         |

## Codici di Commercio

I Codici di Commercio vengono assegnati in base ai valori PMU di un mondo, come indicato nella tabella Valori PMU per i Codici di Commercio.

#### Tabella: Valori PMU per i Codici di Commercio

| Classificazione      | Codice | Dimensione | Atmosfera    | Idrografia | Popolazione | Governo | LL  | LT  |
| -------------------- | ------ | ---------- | ------------ | ---------- | ----------- | ------- | --- | --- |
| Agricolo             | Ag     |            | 4–9          | 4–8        | 5–7         |         |     |     |
| Asteroide            | As     | 0          | 0            | 0          |             |         |     |     |
| Brullo               | Ba     |            |              |            | 0           | 0       | 0   |     |
| Deserto              | De     |            | 2+           | 0          |             |         |     |     |
| Oceano Fluido        | Fl     |            | 10+          | 1+         |             |         |     |     |
| Giardino             | Ga     |            | 5, 6, 8      | 4–9        | 4–8         |         |     |     |
| Densamente Popolato  | Hi     |            |              |            | 9+          |         |     |     |
| Alta Tecnologia      | Ht     |            |              |            |             |         |     | 12+ |
| Coltre di Ghiaccio   | Ic     |            | 0–1          | 1+         |             |         |     |     |
| Industriale          | In     |            | 0–2, 4, 7, 9 |            | 9+          |         |     |     |
| Scarsamente Popolato | Lo     |            |              |            | 1–3         |         |     |     |
| Bassa Tecnologia     | Lt     |            |              |            |             |         |     | 5-  |
| Non-Agricolo         | Na     |            | 0–3          | 0–3        | 6+          |         |     |     |
| Non-Industriale      | Ni     |            |              |            | 4–6         |         |     |     |
| Povero               | Po     |            | 2–5          | 0–3        |             |         |     |     |
| Ricco                | Ri     |            | 6, 8         |            | 6–8         |         |     |     |
| Mondo d'Acqua        | Wa     |            |              | 10         |             |         |     |     |
| Vuoto                | Va     |            | 0            |            |             |         |     |     |

## Fasce di Asteroidi

Le cinture di asteroidi esistono in molti sistemi e vengono usate dai Cinturiani per estrarre ghiaccio, minerali e altre cose interessanti. Per determinare la presenza di cinture di asteroidi in un dato sistema stellare, lancia 4+ su 2D6. Se sono presenti cinture di asteroidi nel sistema, allora il loro numero è di 1D6-3, minimo di 1. Se
il mondo principale del sistema ha dimensione 0, esiste automaticamente almeno una cintura di asteroidi nel sistema .

## Giganti Gassosi

Un sistema stellare può avere uno o più pianeti giganti gassosi. La presenza di a
gigante gassoso permette alle navi stellari dotate di serbatoi di carburante di fare rifornimento sfiorandone la superficie; questo elimina il costo del carburante per la nave e aumenta il profitto. Permette inoltre il rifornimento in sistemi che non hanno astroporto. Il rifornimento in questa modalità richiede 1D6 ore per 40 tonnellate di carburante.

I giganti gassosi sono relativamente comuni. Per ogni sistema tira 5+ su 2D6 per determinare la presenza di almeno un gigante gassoso nel sistema. Se i giganti gassosi sono presenti, il loro numero è 1D6-2, minimo 1.

## Basi

I sistemi stellari possono avere basi per le forze militari, la marina, gli esploratori, o per altre forze armate del governo interstellare. Le basi possono aiutare a
determinare i confini politici all'interno di una data regione dello spazio. Un
governo interstellare porrà basi lungo i suoi confini a guardia di eventuali aggressioni di stati rivali o per controllare i sistemi locali. La presenza di più basi entro pochi parsec potrebbe indicare un confine conteso, o una potente roccaforte. Sebbene possano esistere altre basi, le due basi primarie sono la Base Navale e la Base degli Esploratori.

### Base Navale

Una Base Navale è un deposito di rifornimenti, stazione di rifornimento, cantiere di riparazione o fortezza della Marina. Le navi militari possono qui ottenere carburante raffinato e rifornimenti. Se un mondo possiede un astroporto di Classe A o B, tira 8+ su 2D6 per determinare la presenza di una base navale nel sistema.

### Base degli Esploratori

Una Base o un Avamposto degli Esploratori offre carburante raffinato e rifornimenti alle navi degli Esploratori. Se un mondo non possiede un astroporto di Classe E o Classe X, tira 7+ su 2D6 per determinare la presenza di una base degli esploratori nel sistema. Questo tiro subisce un MD-1 se il mondo ha un astroporto di Classe C, un MD-2 per un astroporto di classe B e un MD-3 per un astroporto di classe A.

### Base Pirata

Una base pirata funge da rifugio per i pirati interstellari. Se un mondo
non possiede un astroporto di Classe A o una base navale, tira 12+ su 2D6 per
determinare la presenza di una base pirata nel sistema.

### Codici delle Basi

La presenza di una o più basi è indicata sulla mappa esagonale con un
codice di base in alto a sinistra dell'esagono del mondo. La tabella Codici della Basi
identifica quali basi degne di nota ci sono, se presenti.

#### Tabella: Codici delle Basi

| Codice | Descrizione                                    |
| ------ | ---------------------------------------------- |
| A      | Base Navale e Base degli Esploratori/Avamposto |
| G      | Base degli Esploratori/Avamposto e Base Pirata |
| N      | Base Navale                                    |
| P      | Base Pirata                                    |
| S      | Base degli Esploratori/Avamposto               |

## Zone di Viaggio

Si presume che la maggior parte dei mondi sia civilizzata, o almeno aperti ad avventurieri e altri visitatori. Alcuni, tuttavia, sono stretti nella morsa
della guerra, afflitti da malattie o semplicemente non pronti per visitatori interstellari. Tali mondi sono classificati da zone di viaggio per notificare questo stato. Nella maggior parte dei casi, l'Arbitro dovrebbe indicare le zone di viaggio basate su
le informazioni disponibili. Esistono due di questi tipi di zone: ambra e rosse.

### Zone Ambra

Un mondo Ambra è stato ritenuto pericoloso e i viaggiatori sono avvertiti di restare
in guardia. I mondi Ambra sono spesso sottoposti a sconvolgimenti o
rivoluzioni, oppure sono ambienti naturalmente pericolosi. Un mondo con
un'Atmosfera di 10+, un Governo di 0, 7 o 10 o un Livello di Legge di 0 o
9+ dovrebbe essere candidato per lo stato Amber.

### Zone Rosse

I mondi Rossi sono interdetti e viaggiare verso di loro è proibito.
Le interdizioni vengono applicate dalla Marina. Le Zone Rosse possono indicare che il mondo è troppo pericoloso per consentire l'accesso a visitatori. L'Arbitro assegna i mondi Rossi a sua discrezione.

## Entità Politiche e Fedeltà

I mondi possono essere indipendenti o far parte di un sistema politico più ampio che abbraccia uno o più sistemi. Le entità politiche variano da blande confederazioni di pochi mondi con politiche commerciali o di difesa comuni o legami culturali, a grandi imperi stellari che si contendono migliaia di sistemi e trilioni di cittadini.
I confini di un'entità politica dovrebbero essere tracciati sulla mappa. Notare che le entità politiche più grandi di solito avranno sottodomini, che dovrebbero anch'essi essere contrassegnati.

## Rotte di Comunicazione e Rotte Commerciali

All'interno del sottosettore, i governi avranno stabilito le comunicazioni
e rotte commerciali che collegano alcuni (ma non tutti) mondi. Messaggi tra
le imprese, i governi e le persone generalmente seguono questi percorsi.

Le vie di comunicazione dovrebbero essere tracciate con attenzione in modo da evitare di rendere tutte le parti del sottosettore accessibili; un sottosettore dovrebbe avere alcune aree come retrovie per l'esplorazione e l'avventura. Le vie di comunicazione
sono tracciate come linee singole che collegano esagoni sulla griglia dei sottosettori.

Le rotte commerciali collegano mondi che hanno forti legami commerciali. Consulta il
Tabella Rotte Commerciali - se i mondi di una coppia corrispondono ai valori in tabella e i due mondi si trovano entro quattro parsec l'uno dall'altro ed è possibile una rotta di Balzo–1 o Balzo–2 tra di loro, allora segna una rotta commerciale che collega questi due mondi.

#### Tabella: Rotte Commerciali

| Caratteristiche del Mondo al Primo Estremo | Caratteristiche del Mondo al Secondo Estremo            |
| ------------------------------------------ | ------------------------------------------------------- |
| Industriale o Alta Tecnologia              | Asteroide, Deserto, Coltre di Ghiaccio, Non-Industriale |
| Densamente Popolato o Ricco                | Agricolo, Giardino, Mondo d'Acqua                       |
