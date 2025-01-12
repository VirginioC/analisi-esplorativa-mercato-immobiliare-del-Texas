# Analisi esplorativa del mercato immobiliare del Texas

## **Descrizione**  
Questo progetto, prodotto durante il Master in Data Science di Profession AI, consiste nell'effettuare un'analisi esplorativa tramite l'utilizzo del linguaggio **R**.  
L'azienda immaginaria Texas Realty Insights desidera analizzare le tendenze del mercato immobiliare nello stato del Texas, sfruttando i dati storici relativi alle vendite di immobili. L'obiettivo è fornire insight statistici e visivi che supportino le decisioni strategiche di vendita e ottimizzazione delle inserzioni immobiliari.

Il progetto include:  
- Un file `.R` contenente tutto il codice eseguibile.  
- Un documento `PDF` che spiega nel dettaglio ogni passaggio dell'analisi.  
- Il dataset utilizzato (`Real Estate Texas.csv`).

## Obiettivi del progetto
- Identificare e interpretare i trend storici delle vendite immobiliari in Texas.
- Valutare l’efficacia delle strategie di marketing delle inserzioni immobiliari.
- Offrire una rappresentazione grafica dei dati che evidenzi la distribuzione dei prezzi e delle vendite tra città, mesi e anni.

## Valore aggiunto
L'analisi statistica proposta permetterà a Texas Realty Insights di ottimizzare le loro strategie di mercato, identificando città con opportunità di crescita e valutando l'efficacia delle inserzioni immobiliari nel tempo. Grazie a una visione chiara e strutturata dei dati, l'azienda potrà prendere decisioni basate su informazioni concrete, migliorando la gestione delle vendite immobiliari in Texas.

## **Analisi effettuate**  
- Analisi delle variabili presenti nel dataset (tipologia di variabile statistica).
- Calcolo di indici di posizione, variabilità e forma per le variabili quantitative.
- Identificazione delle variabili con maggiore variabilità e asimmetria.
- Suddivisione del **prezzo mediano di vendita** in classi, costruzione della distribuzione di frequenza e calcolo dell'indice di Gini.  
- Creazione di nuove variabili utili all'analisi, come:  
  - Il **prezzo medio di vendita**.  
  - Il **tasso di conversione degli annunci di vendita**.  
- Utilizzo del pacchetto `dplyr` per generare summary condizionati a città, anni e mesi.  
- Visualizzazioni grafiche avanzate con `ggplot2`, tra cui:  
  - Boxplot.  
  - Grafici a barre.  
  - Line chart.

## **Tecnologie utilizzate**  
- **Linguaggio**: R  
- **Pacchetti principali**:  
  - `dplyr` (manipolazione dati)  
  - `ggplot2` (visualizzazione dati)  
  - `moments` (calcolo di asimmetria e curtosi)

## **Come eseguire l'analisi**  
1. Scarica o clona il repository.
2. Apri il file `analisi_mercato_immobiliare_Texas.R` in RStudio o un altro ambiente R.
3. Esegui il codice passo-passo per ottenere i risultati dell'analisi e le visualizzazioni grafiche.
4. Il dataset utilizzato (`Real Estate Texas.csv`) è incluso nel repository. Assicurati che il file si trovi nella stessa directory del file .R.

## Autore
[Virginio Cocciaglia](https://github.com/VirginioC)

---
