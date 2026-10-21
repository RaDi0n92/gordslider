# Gordslider

> Deutsch zuerst. English below.

## Deutsch

Gordslider ist ein früher browserbasierter Spiel- und Simulationsprototyp aus meinem Arbeitsweg Anfang 2026. Das Repository zeigt keinen fertigen Produktzustand, sondern einen erhaltenen Entwicklungsstand, an dem ich Spielmechanik, Zustandslogik, deterministische Tests und Instrumentierung ausprobiert habe.

Die Git-Historie dieses Repositories enthält belegte Commits vom **12. bis 21. Februar 2026**.

### Was im Prototyp steckt

- ein eigenständiger HTML/CSS/JavaScript-Prototyp
- umschaltbare Spielfelder mit **3×5, 6×5 und 9×5**
- Kaskaden- und Drop-Mechanik
- Freispiele und simulierte Free-Spin-Buys
- deterministische Seeds für reproduzierbare Abläufe
- Paytable-Anzeige und Paytable-Editor
- eine Waves-Anzeige als Zustands-/Gefühlsindikator
- Debug- und Instrumentierungsfunktionen
- schnelle Simulationsläufe für 100, 1.000 und 10.000 Spins sowie Drop-Simulationen
- eigene Bildassets unter `bilder/`

### Warum das heute noch im Portfolio liegt

Gordslider ist für mich weniger wegen eines „fertigen Slots“ interessant, sondern als frühe Spur dafür, wie ich angefangen habe, interaktive Systeme nicht nur sichtbar zu bauen, sondern auch reproduzierbar zu testen und ihr Verhalten zu beobachten.

Der Code ist entsprechend historisch gewachsen und nicht nachträglich auf eine saubere Tutorial-Struktur umgeschrieben worden.

### Einstieg

Die Hauptfassung liegt in [`gordslider.html`](gordslider.html).

---

## English

Gordslider is an early browser-based game and simulation prototype from my development path in early 2026. The repository is not presented as a finished product. It preserves a working stage in which I experimented with game mechanics, state logic, deterministic testing and instrumentation.

The Git history of this repository contains evidenced commits from **February 12 through February 21, 2026**.

### What is inside

- a self-contained HTML/CSS/JavaScript prototype
- switchable **3×5, 6×5 and 9×5** play-field modes
- cascade and drop mechanics
- free spins and simulated free-spin buys
- deterministic seeds for reproducible runs
- paytable display and paytable editor
- a Waves indicator for visible state/feel feedback
- debugging and instrumentation controls
- fast simulation runs for 100, 1,000 and 10,000 spins plus drop simulations
- project image assets under `bilder/`

### Why it remains part of the portfolio

Gordslider matters less to me as a “finished slot” than as an early trace of learning to build interactive systems that could also be reproduced, measured and inspected.

The code is therefore preserved as a historical working body rather than being retrospectively rewritten into a clean tutorial project.

### Entry point

The main version is [`gordslider.html`](gordslider.html).
