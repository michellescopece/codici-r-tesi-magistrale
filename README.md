# Analisi predittiva dei guasti: confronto tra approcci frequentisti e bayesiani in R

Questo repository contiene l'appendice con i codici 'r' della mia tesi magistrale "Metodi di machine learning per la manutenzione predittiva". L'obiettivo del progetto è stato sviluppare ed ottimizzare diversi metodi di classificazione, per poter confrontare la loro accuratezza predittiva sui guasti di un motore diesel bilanciandola con la loro efficienza computazionale.

## Tecnologie e strumenti utilizzati
*   **Linguaggio di Programmazione:** R
*   **Framework di Machine Learning:** `tidymodels` (approccio moderno per il workflow di modellazione)
*   **Pacchetti Chiave:** `here` (gestione riproducibile dei percorsi), `embed` (encoding avanzato dei dati)
*   **Reportistica Scientifica:** Quarto (Posit / RStudio)
*   **Metodologie Statistiche:** Approccio frequentista e bayesiano per il confronto tra i modelli
*   **Ottimizzazione dei Parametri:** Tuning tramite *Grid Search*

## Struttura del Codice e Riproducibilità

Il codice è organizzato per essere completamente **modificabile e riutilizzabile** su dataset differenti per futuri confronti tra modelli. 

L'intero lavoro è stato redatto tramite **Quarto**, che ha permesso di integrare la stesura del testo con l'esecuzione del codice R in un unico ambiente. Nel documento principale i blocchi di codice (*chunk*) sono stati nascosti per favorire la leggibilità del testo (opzione `include=FALSE`), mentre nel file allegato in questo repository sono stati resi visibili (`echo=TRUE`) e non eseguiti (`eval=FALSE`) per facilitarne la consultazione e il riutilizzo.

La struttura rispecchia fedelmente le fasi dell'analisi dei risultati:
1.  **Adattamento del Dataset:** Installazione dei pacchetti e preparazione dei dati del motore marino.
2.  **Sviluppo dei modelli:** Implementazione degli algoritmi per la creazione dei modelli.
3.  **Grid Search:** Codici dedicati al fine-tuning dei parametri per massimizzare l'accuratezza dei modelli.
4.   **Analisi della performance:** Confronto dei modelli utilizzati con approccio frequentista e bayesiano.

---

## Contenuto del Repository

*   [Codici_e_bibliografia_tesi.pdf](./Codici_e_bibliografia_tesi.pdf): Il documento completo in formato PDF contiene l'appendice della tesi in cui sono presenti tutti i chunk di codice suddivisi secondo le sezioni della tesi, accompagnati da alcuni commenti esplicativi. Inoltre, per completezza e trasparenza, viene riportata la bibliografia  utilizzata per la stesura dell'opera.

---
*Nota: I modelli teorici di partenza sono stati riadattati e ingegnerizzati ad hoc per rispondere alle specifiche metriche del dataset sui motori marini utilizzato nella ricerca.*
