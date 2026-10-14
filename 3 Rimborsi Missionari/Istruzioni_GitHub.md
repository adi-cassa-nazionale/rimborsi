# Mettere online Rimborsi Missionari su GitHub Pages

Servono 10 minuti. Cartella da caricare: **PER GITHUB** (6 file + README).

## 1. Account
- Meglio un'**organizzazione** dell'Opera (github.com > icona + > New organization, piano Free), non l'account personale.
- Se non c'è ancora, per ora va bene il tuo account: si può trasferire il repository all'organizzazione in seguito (Settings > Transfer).

## 2. Crea il repository
1. github.com > **New repository**
2. Nome: `rimborsi-missionari`
3. **Public** (sul piano gratuito Pages lo richiede; nel codice non ci sono dati personali)
4. Spunta "Add a README"? **No**. Crea.

## 3. Carica i file
1. Nella pagina del repository: **uploading an existing file**
2. Apri la cartella PER GITHUB, seleziona **tutti i file dentro** (non la cartella) e trascinali nella pagina.
3. Attendi il caricamento (index.html pesa 2,4 MB), poi **Commit changes**.

## 4. Attiva Pages
1. Repository > **Settings** > **Pages**
2. Source: **Deploy from a branch**; Branch: **main**, cartella **/ (root)** > Save
3. Dopo 1-2 minuti compare l'indirizzo:
   `https://NOME-ACCOUNT.github.io/rimborsi-missionari/`

## 5. Prova
- Apri l'indirizzo da telefono e da computer, fai una richiesta di prova con "Esempio".
- Poi "Aggiungi a schermata Home" (iPhone: Condividi; Android: menu del browser).
- Mandami l'indirizzo: aggiorno la guida PDF con il link nuovo.

## Per aggiornare in futuro
Repository > Add file > Upload files > ripeti con index.html e sw.js nuovi (stesso nome: li sostituisce). Non consuma crediti.
Per tornare a una versione precedente: History del file > Revert.

## Nota
Chi ha installato l'app dal vecchio indirizzo Netlify deve reinstallare dal nuovo: i dati salvati nel dispositivo non si spostano da un indirizzo all'altro.
