# TaskFlow

Web app statica per gestire task e visualizzarli in un Gantt, separati per progetto. Funziona su PC e iPhone tramite GitHub Pages.

## Pubblicazione su GitHub Pages
1. Crea un repository pubblico su GitHub.
2. Carica nella root: `index.html`, `manifest.json`, `sw.js`.
3. Apri **Settings > Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**.
5. Seleziona `main` e `/ (root)`, poi **Save**.
6. Apri l'URL indicato da GitHub Pages.

## iPhone
Apri il sito in Safari, tocca **Condividi**, quindi **Aggiungi alla schermata Home**.

## Dati e backup
I dati sono salvati nel `localStorage` del singolo browser/dispositivo. Usa **Esporta JSON** e **Importa JSON** per backup o trasferimenti. Questa versione non sincronizza automaticamente PC e iPhone.

## Evoluzione consigliata
Per sincronizzazione multi-dispositivo, aggiungere Supabase (autenticazione + database PostgreSQL) mantenendo GitHub Pages come frontend.
