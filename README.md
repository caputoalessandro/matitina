# Matitina ✏️

Compagna di studio per *Drawing on the Right Side of the Brain* di Betty Edwards (4ª edizione, 2012), con Matitina la matita come mascotte.
Per ogni capitolo: l'idea principale, i concetti chiave e le schede degli esercizi con la pagina del PDF da aprire.
Funziona nel browser, si installa sulla schermata Home e funziona anche offline.

## Cosa c'è

- **Libro**: i 12 capitoli più l'introduzione, ognuno «In breve» (idea e concetti chiave) e «Approfondito» (spiegazione estesa), con avanzamento; il prossimo esercizio da fare; «Ho disegnato oggi» per i giorni di fila.
- **Esercizi**: tutti i 34 esercizi; ognuno con pagine del PDF, materiali, passi in breve, «perché», segna come fatto e appunti personali.
- **Promemoria**: lista dei materiali da spuntare e le regole da tenere sottomano (routine di partenza, prospettiva, proporzioni della testa, logica della luce).
- **Opzioni**: lingua (inglese, predefinita, o italiano), 5 scatole di colori (Fauve, Laguna, Pastelli, Sanguigna, Carboncino), scarto dei numeri di pagina (se il tuo PDF è diverso), backup.

Riassunti e schede sono scritti apposta per l'app, in inglese e in italiano: le istruzioni complete restano nel libro.

## File

| File | A cosa serve |
|---|---|
| `index.html` | L'app intera: contenuti, schermate, grafica |
| `manifest.webmanifest` | Nome, colori e icona per l'installazione |
| `sw.js` | Funzionamento offline |
| `icon-*.png` | Icone con la mascotte |
| `.nojekyll` | Dice a GitHub Pages di servire i file così come sono |

## Pubblicare un aggiornamento

1. Sostituisci `index.html` (e gli altri file cambiati) con la nuova versione: Add file → Upload files → Commit.
2. In `sw.js` cambia `VERSION` (per esempio da `matitina-v1` a `matitina-v2`), così i telefoni scaricano la versione nuova.
3. GitHub Pages aggiorna il sito in un paio di minuti: riapri l'app con la connessione attiva.

I dati restano salvati nel browser di ogni dispositivo e non vengono toccati dagli aggiornamenti.

## Installare l'app

- iPhone: apri il sito in Safari → Condividi → "Aggiungi alla schermata Home".
- Android: apri il sito in Chrome → menu ⋮ → "Installa app".
