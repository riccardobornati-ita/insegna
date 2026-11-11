# Insegna: app per il banner LED iledcolor (96 × 16, a colori)

## Cosa c'è in questa cartella
- `index.html`: l'app completa
- `manifest.webmanifest`, `sw.js`, `icon.svg`: servono per installarla sulla schermata Home e per aprirla anche senza rete

## Metterla online (una volta sola, gratis)
Chrome accende il Bluetooth solo per le pagine aperte da un indirizzo **https://**. Aperta come file dal telefono, l'app non riesce a collegarsi al banner.

### GitHub Pages, anche dal telefono
1. Crea un account su github.com, se non ce l'hai.
2. Crea un nuovo repository pubblico, per esempio `insegna`.
3. Scegli **Add file → Upload files** e carica i 4 file della cartella.
4. Vai in **Settings → Pages**, alla voce **Branch** scegli `main` e premi **Save**.
5. Dopo un minuto circa l'app è su `https://TUONOME.github.io/insegna/`.

### Netlify Drop, da computer
Apri app.netlify.com/drop e trascina la cartella: ricevi subito un indirizzo https.

## Primo utilizzo
1. Apri l'indirizzo con **Chrome su Android**, con Bluetooth e posizione attivi.
2. Dal menu ⋮ scegli **Aggiungi a schermata Home**: l'app si apre come le altre app.
3. Chiudi del tutto l'app originale: il banner accetta una connessione alla volta.
4. Tocca **Collega banner** e scegli `iledcolor-AEB1`.
5. Apri **Banner** e tocca **Trova il formato giusto con 4 prove**. Serve una volta sola: fa capire all'app come il pannello vuole i colori.

## Se qualcosa non va
In **Banner** trovi la voce **Registro di comunicazione**. Copialo e mandalo: si vede esattamente cosa ha risposto il banner.
