# IoTools

PDF-Nachbearbeitung (optimiert für Musiknoten): Eine statische HTML-Seite (`index.html`), die Scans manipulieren kann. Die Verarbeitung läuft vollständig im Browser.

## Verwendung

1. `index.html` im Browser öffnen (kein Server nötig).
2. Internetverbindung beim ersten Laden, da `pdf.js` und `pdf-lib` von cdnjs geladen werden.

## Technik

- Reines HTML, CSS und JavaScript, keine Build-Schritte
- Bibliotheken: [pdf.js](https://mozilla.github.io/pdf.js/) 3.11.174, [pdf-lib](https://pdf-lib.js.org/) 1.17.1
