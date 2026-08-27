# Product Design Toolkit für Claude Code

85 Methoden für die Produktentwicklung, geführt statt nachgeschlagen. Von der Strategie bis zum Markt, mit fünf Space-Agents und sechs Funktions-Spezialisten.

![PDT](assets/cover.jpg)

**Autor:** Ralph Hutter · [productdesigntoolkit.net](https://productdesigntoolkit.net)
**Methodenübersicht:** [Explorer](https://productdesigntoolkit.github.io/explorer/)
**Lizenz:** CC BY-NC-SA 4.0

> **Lizenz:** CC BY-NC-SA 4.0. Weitergabe und Veränderung erlaubt, kommerzielle Nutzung nicht.
> Herkunft und Bedingungen je Methode: [`NOTICE`](NOTICE).


---

## Installation

Du bekommst eine Datei `pdt-claude-plugin.zip`. Drei Schritte, kein GitHub-Konto nötig.

```bash
# 1. entpacken, zum Beispiel in dein Home-Verzeichnis
unzip pdt-claude-plugin.zip -d ~

# 2. als lokalen Marketplace anmelden
claude plugin marketplace add ~/pdt-claude-plugin

# 3. installieren
claude plugin install pdt@pdt
```

Prüfen, ob es geklappt hat:

```bash
claude plugin details pdt
```

Ausführlich mit Screenshots: [`docs/installation.md`](docs/installation.md).

---

## Die ersten zehn Minuten

```
/pdt:start
```

Der Einstieg fragt, woran du arbeitest, und schlägt die passende Methode vor. Wenn du schon weisst, was du brauchst, ruf sie direkt auf:

```
/pdt:business-model-canvas
/pdt:problem-statement
/pdt:product-market-fit
```

Du kannst auch einfach fragen. „Ich weiss nicht, ob mein Problem echt ist" genügt, dann meldet sich der Method Finder von selbst.

Jede Methode endet mit einer Datei in `pdt-workspace/` in deinem Projekt. Das ist dein Ergebnis, nicht nur ein Gespräch.

Schritt für Schritt: [`docs/erste-schritte.md`](docs/erste-schritte.md).

---

## Was drin ist

| | |
|---|---|
| 85 Methoden als Befehle | von BCG Matrix bis User Story Mapping |
| 5 Space-Wegweiser | `/pdt:strategy`, `/pdt:problem`, `/pdt:solution`, `/pdt:product`, `/pdt:market` |
| 11 Agents | fünf für die Spaces, sechs für Querschnittsthemen wie Security, Recht, Branding |
| 2 Skills | Method Finder und Projektgedächtnis, beide melden sich von selbst |

Die fünf Spaces:

| Space | Frage | Methoden |
|-------|-------|----------|
| Strategy | Warum und für wen? | 18 |
| Problem | Welches Problem lösen wir? | 17 |
| Solution | Wie lösen wir es? | 14 |
| Product | Was bauen wir und wie? | 15 |
| Market | Wie bringen wir es an den Markt? | 21 |

---

## Gut zu wissen

Das Plugin belegt rund 9000 Token in jeder Sitzung, weil alle Methoden sofort verfügbar sind. Wenn du an etwas anderem arbeitest, schalte es ab und später wieder an:

```bash
claude plugin disable pdt@pdt
claude plugin enable pdt@pdt
```

Deinstallieren: `claude plugin uninstall pdt@pdt`

---

## Lizenz und Quellen

Das PDT-Framework, also Struktur, redaktionelle Aufbereitung und Anleitungen, steht unter CC BY-NC-SA 4.0, Ralph Hutter.

Die einzelnen Methoden stammen von ihren jeweiligen Urhebern und sind nicht durch diese Lizenz abgedeckt. Herkunft und Bedingungen je Methode stehen in [`NOTICE`](NOTICE).
