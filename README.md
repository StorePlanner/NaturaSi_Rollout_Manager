# NaturaSì Rollout Manager

Minimi e massimi d'impianto per i negozi NaturaSì nuovi, senza vendite: usa le vendite dei negozi vicini e lo stesso motore del Category Optimizer (V4.2.11).

## Come si usa

1. **Dati**: ordine d'impianto (Excel e/o PDF Ecor «Notifica ordine» e «Inevasi ordine»), da 1 a 3 negozi vicini con il loro peso, estrazione RELEX del negozio nuovo (consigliata), giorni di scarico e booster.
2. **Rollout**: Copia Codici nel filtro di RELEX, poi Copia SÌ, MIN e MAX, vista per vista.
3. **Verifica**: dopo l'incolla, l'estrazione RELEX del negozio nuovo: l'app trova le righe sbagliate o slittate e prepara le correzioni.

Per aprire la pagina serve internet (librerie per Excel e PDF); i file caricati restano sul computer e non vengono inviati a nessuno.

## Pubblicazione

Questa cartella contiene `index.html`: va in un repository a parte, oppure in una sottocartella del repository del Category Optimizer (per esempio `rollout/`), così non sovrascrive l'`index.html` del Category Optimizer. La pagina non usa altri file.
