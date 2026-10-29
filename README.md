![MCGoL Banner](./plakat.png)

# MCGoL

MCGoL ist ein modulares Open-Source-Platinendesign für **Conway's Game of Life**, das als kollaborative Aufgabe in einzelnen Modulen aufgebaut und zusammengesetzt werden kann.

## Was ist Conway's Game of Life?

Conway's Game of Life ist ein zellulärer Automat auf einem Raster aus Zellen. Jede Zelle ist entweder „lebendig“ oder „tot“. In jedem Schritt wird der nächste Zustand ausschließlich aus den Nachbarzellen berechnet – dadurch entstehen aus einfachen Regeln komplexe, oft überraschende Muster.

## Technischer Ansatz von MCGoL

Die Matrix ist **ausschließlich aus diskreten Logikbausteinen** aufgebaut.
Dazu gehören unter anderem:

- 4-Bit-Addierer
- Schmitt-Trigger
- Triple-AND-Gatter
- Flip-Flops

In der Matrix selbst werden **keine Mikrocontroller** eingesetzt.

## Anleitung

➡️ **[Anleitung öffnen (PDF)](./docs/Anleitung.pdf)**

## Interaktive BOM-/Board-Ansicht

Die interaktive Ansicht ist hier im Repository enthalten:

- [iBOM lokal im Repository öffnen](https://emilaltmann.github.io/mcgol/ibom.html)

Nach Aktivierung von GitHub Pages ist sie typischerweise erreichbar unter:

- `https://<owner>.github.io/<repo>/ibom.html`

Für dieses Repository wäre das:

- `https://emilaltmann.github.io/mcgol/ibom.html`

Falls die Seite noch nicht erreichbar ist, muss in den Repository-Einstellungen unter **Settings → Pages** die Quelle auf **GitHub Actions** gesetzt werden.

## Projektstruktur

- `README.md` – Projekt-Startseite
- `plakat.png` – Bannerbild
- `ibom.html` – interaktive BOM-/Board-Ansicht
- `docs/Anleitung.pdf` – Projektanleitung
- `hardware/pcb/` – KiCad-Projektdateien (Schaltplan, PCB, Projektdatei)
- `hardware/cad/` – CAD-/3D-Artefakte
