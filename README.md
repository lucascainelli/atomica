# Atomica

Note glifate (☿ citazione, ∆ pensiero, ⚙ azione, ∅ dubbio), Biblioteca di testi e Atomizzatore AI.

App a file unico: `index.html`. Dati nel localStorage; sync Firebase e chiave Anthropic opzionali, impostate da Impostazioni.

## Inserire materiale
Le note nuove si aggiungono a `notes.json` (array di note, stesso formato dell'export) e si pubblica con un commit. All'apertura l'app importa ogni nota una sola volta e la sincronizza su Firebase.
