# Analisi dei dialoghi de *Il Re Leone* con RStudio

Questo progetto esplora i dialoghi e i sentiment dei personaggi nel film *Il Re Leone* utilizzando il linguaggio di programmazione R. L'analisi si concentra sui seguenti aspetti principali:

- **Personaggi con più battute:** Analisi dei personaggi con il maggior numero di battute nel film.
- **Wordcloud dei dialoghi:** Creazione di una wordcloud che visualizza le parole più frequenti nei dialoghi.
- **Sentimenti nei dialoghi:** Analisi dei sentiment espressi nei dialoghi dei personaggi (positivo/negativo).
- **Confronto sentimentale tra personaggi:** Analisi e confronto dei sentimenti nei dialoghi di tre personaggi principali: Simba, Scar e Timon.

## Struttura del Progetto

1. **Caricamento e Pulizia dei Dati:**
   - Il file CSV contenente i dialoghi è stato caricato e pulito per rimuovere eventuali valori mancanti o formattazioni errate.
   - I nomi dei personaggi sono stati standardizzati per facilitare l'analisi.

2. **Visualizzazione dei Personaggi con Più Battute:**
   - È stato creato un grafico a barre che mostra i personaggi con il maggior numero di battute nel film.

3. **Creazione di una Wordcloud:**
   - È stata generata una wordcloud che visualizza le parole più frequenti nei dialoghi.
4. **Analisi del Sentiment:**
   - Sono stati analizzati i sentimenti (positivi e negativi) nei dialoghi complessivi.
   - Successivamente, è stato creato un confronto tra i sentimenti espressi dai personaggi principali (Simba, Scar e Timon).

5. **Wordcloud Personalizzata:**
   - È stata creata una wordcloud personalizzata per Simba utilizzando una maschera che rappresenta il personaggio.

## Librerie Utilizzate

Il progetto utilizza diverse librerie R per l'analisi dei dati, tra cui:

- `dplyr` per la manipolazione dei dati
- `ggplot2` per la visualizzazione grafica
- `tidytext` per l'analisi del testo e la creazione di wordcloud
- `wordcloud2` per la generazione di wordclouds personalizzate
- `tm` e `stopwords` per il pre-processing del testo
- `RColorBrewer` per la selezione dei colori nelle wordclouds


