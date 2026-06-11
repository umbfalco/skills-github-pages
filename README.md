# AlgoritmiExplorer

Web App didattica per il laboratorio di Informatica (classe di concorso A-041).  
Permette agli studenti di visualizzare e comprendere il funzionamento degli algoritmi attraverso animazioni interattive, spiegazioni passo-passo e strumenti di analisi della complessita computazionale.

**Realizzato da:** Prof. Umberto Falcomata  
**Tecnologie:** HTML5, CSS3, Vanilla JavaScript -- nessun framework esterno.  
**Accessibilita:** interfaccia conforme alle linee guida BES/DSA (font ad alta leggibilita, contrasto elevato, interlinea aumentata).

**Demo online:** [https://umbfalco.github.io/RicorsioneHanoi/hanoi.html](https://umbfalco.github.io/RicorsioneHanoi/hanoi.html)

---

## Pagine dell'applicazione

| Pagina | Descrizione |
|--------|-------------|
| [**index.html**](index.html) | **Algoritmi di ordinamento** -- Bubble Sort e Selection Sort animati con barre colorate, log dei passaggi, contatori in tempo reale e legenda visiva |
| [**hanoi.html**](hanoi.html) | **Torre di Hanoi** -- Simulazione ricorsiva con animazione dei dischi, Call Stack visivo a blocchi impilati e visualizzazione della memoria (stack frames con indirizzi fittizi) |
| [docs.html](docs.html) | Documentazione tecnica -- Architettura, funzioni, complessita Big-O |
| [valutazione.html](valutazione.html) | Rubrica di valutazione delle competenze -- Piano della Prova di Laboratorio |

## Struttura del progetto

```
AlgoritmiExplorer/
|-- index.html          # Pagina principale: Bubble Sort e Selection Sort
|-- hanoi.html          # Torre di Hanoi con ricorsione animata
|-- app.js              # Logica ordinamenti + gestione eventi
|-- hanoi.js            # Logica Torre di Hanoi + Call Stack + Memoria
|-- style.css           # Stili CSS3 con accessibilita BES/DSA
|-- docs.html           # Documentazione tecnica
|-- valutazione.html    # Rubrica competenze ministeriali
+-- README.md           # Questo file
```

## Funzionalita principali

- **Bubble Sort e Selection Sort** animati con evidenziazione dei confronti, scambi e posizioni definitive
- **Torre di Hanoi** con animazione a 3 fasi (sale, vola, scende) dei dischi tra i pioli
- **Call Stack visivo** con blocchi colorati per livello di ricorsione e badge di stato (Attiva / Completata)
- **Visualizzazione Memoria** stile debugger con indirizzi esadecimali fittizi e deallocazione animata
- **Tabella confronto complessita** -- O(n^2) vs O(2^n)
- **Log dei passaggi** con pallini colorati che descrivono ogni azione dell'algoritmo
- **Contatori in tempo reale** -- mosse, confronti, scambi, profondita ricorsione

## A.S. 2025/2026 -- Laboratorio di Informatica
