PIZZAPP — PACCHETTO PER PUBBLICAZIONE HTTPS

File inclusi:
- index.html: applicazione PizzApp
- manifest.webmanifest: impostazioni per installazione
- sw.js: cache offline
- icon-192.png e icon-512.png: icone

PUBBLICAZIONE SU GITHUB PAGES
1. Estrai lo ZIP.
2. Nel repository GitHub pizzapp, carica TUTTI e cinque i file nella cartella principale (root).
3. Apri Settings > Pages.
4. In Build and deployment scegli Deploy from a branch.
5. Seleziona Branch: main e Folder: /(root), poi Save.
6. Attendi la pubblicazione e apri l'indirizzo HTTPS indicato da GitHub Pages con Safari.

INSTALLAZIONE SU IPHONE
1. Apri l'indirizzo HTTPS in Safari mentre sei online.
2. Attendi il caricamento completo.
3. Tocca Condividi > Aggiungi alla schermata Home.
4. Apri PizzApp dalla nuova icona almeno una volta mentre sei online.
5. Poi puoi provare ad attivare la modalità aereo: i calcoli sono locali e la pagina è memorizzata per l'uso offline.

Nota: il file HTML aperto direttamente dall'app File non è sufficiente per installare una PWA offline affidabile. La prima visita all'indirizzo HTTPS è necessaria per scaricare e memorizzare l'app.
