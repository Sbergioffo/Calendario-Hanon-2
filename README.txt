# Calendario Hanon — app installabile

Questa cartella contiene una Progressive Web App (PWA) del Calendario Hanon.

## Installazione sul telefono Android
1. Pubblica tutti i file di questa cartella su un sito raggiungibile tramite HTTPS (per esempio GitHub Pages).
2. Apri l'indirizzo pubblicato in Chrome sul telefono.
3. Apri il menu ⋮ e scegli **Installa app** oppure **Aggiungi a schermata Home**.
4. Avvia l'app dall'icona Hanon.

## Dati e cronometri
- I cronometri, le spunte e le note sono salvati automaticamente nel local storage del browser/app sul dispositivo.
- I dati non vengono sincronizzati tra dispositivi.
- Usa **Esporta backup JSON** nell'app per conservare una copia.
- La cache permette di riaprire la pagina anche senza rete dopo il primo caricamento, ma l'installazione iniziale richiede HTTPS.

## File
- `index.html`: interfaccia e cronometri
- `manifest.webmanifest`: impostazioni d'installazione
- `sw.js`: cache/offline di base
- `icon.svg`: icona dell'app
