# Rimborsi Missionari

Web app (PWA) per preparare la nota spese e i giustificativi dei rimborsi dei missionari ADI.
Funziona nel dispositivo: foto, importi e IBAN non vengono caricati su nessun server.

- `index.html`: l'intera app (file unico, librerie incluse)
- `sw.js`, `manifest.json`, `icon*.png`: installazione e uso offline

Per aggiornare l'app: sostituire `index.html` e `sw.js` e cambiare il numero `rimborsi-vN` in `sw.js`.
