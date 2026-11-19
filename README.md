# Rebus a livelli

Un gioco di rebus in italiano: 301 livelli a difficoltà crescente divisi in 31 capitoli.
Risolvi un rebus per sbloccare il successivo, conquista fino a tre stelle e usa le lampadine 💡 per gli aiuti.

**Gioca:** https://davidino99.github.io/rebus/

## Installarla sul telefono

- **iPhone (Safari):** apri il link, tocca *Condividi* → *Aggiungi alla schermata Home*.
- **Android (Chrome):** apri il link, tocca ⋮ → *Installa app* (o *Aggiungi a schermata Home*).

Dopo la prima apertura funziona anche senza internet. I progressi restano sul telefono;
per portarli su un altro dispositivo usa *Livelli → Sposta i progressi su un altro dispositivo*.

## Come funziona

È un'app web statica, senza server e senza dipendenze:

- `index.html` contiene tutto il gioco e i rebus;
- `sw.js` tiene l'app in memoria per l'uso offline (cambia `VERSION` a ogni aggiornamento);
- `manifest.webmanifest` e `icons/` servono per l'installazione;
- `fonts/` contiene Alfa Slab One e Figtree (licenza SIL Open Font License).

Si pubblica con GitHub Pages dal branch `main`, cartella principale.
