# SulcisOca – Android

Gioco dell'oca low-poly ambientato nel Sulcis, **in singolo contro da 1 a 5 bot** (difficoltà facile, normale, difficile, demon).
Gira **tutto offline** sul telefono: nessun server, nessuna connessione (l'app non chiede nemmeno il permesso Internet).

## Scarica
Vai su **Releases** → ultima versione → `SulcisOca.apk`, aprilo sul telefono e consenti l'installazione da origini sconosciute.

## Controller
Supporta i controller Xbox (e simili) via Bluetooth:
croce / levetta sinistra = sposta la selezione · **A** = premi · **B** = indietro · **X** = tira il dado · **Y** = ricentra la camera ·
**LB/RB** o levetta destra = ruota la camera · **LT/RT** = zoom · **Menu** = regole · **Visualizza** = giocatori.

## Build
Ogni push su `main` compila l'APK con GitHub Actions e lo pubblica nelle Releases.
Il gioco è in `app/src/main/assets/www`.
