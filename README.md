![NaturaSì Rollout Manager](NaturaSi_Rollout_Manager_Logo.png)

# NaturaSì Rollout Manager

Minimi e massimi d'impianto per i negozi NaturaSì nuovi, che non hanno vendite proprie: usa le vendite dei negozi vicini e lo stesso motore del Category Optimizer (V4.2.11).

## Come si usa

1. **Dati**: ordine d'impianto (Excel e/o PDF Ecor «Notifica ordine» e «Inevasi ordine»), da 1 a 3 negozi vicini con il loro peso, estrazione RELEX del negozio nuovo (consigliata), giorni di scarico e booster.
2. **Rollout**: Copia Codici nel filtro di RELEX, poi Copia SÌ, MIN e MAX, vista per vista.
3. **Verifica**: dopo l'incolla, l'estrazione RELEX del negozio nuovo: l'app trova le righe sbagliate o slittate e prepara le correzioni.

Per aprire la pagina serve internet (librerie per Excel e PDF); i file caricati restano sul computer e non vengono inviati a nessuno.

## Pubblicazione

Carica tutto il contenuto di questa cartella (anche `.nojekyll`) in un repository a parte, oppure in una sottocartella del repository del Category Optimizer (per esempio `rollout/`), così non sovrascrive l'`index.html` né le icone del Category Optimizer. Icone e manifest sono nella stessa cartella di `index.html` e funzionano in tutti e due i casi.

## Icone

- `favicon.ico`, `favicon.svg`, `favicon-16x16.png`, `favicon-32x32.png`: schede del browser (Windows, macOS, Linux)
- `apple-touch-icon.png`: iPhone e iPad (Aggiungi a Home)
- `android-chrome-192x192.png`, `android-chrome-512x512.png`, `maskable-512x512.png`, `site.webmanifest`: Android e app installata da Chrome o Edge
- `safari-pinned-tab.svg`: schede fissate di Safari
- `NaturaSi_Rollout_Manager_Logo.png/.svg`: logo orizzontale; `NaturaSi_Rollout_Manager_Icon.png`: icona 1024 px (anteprima del repository)
