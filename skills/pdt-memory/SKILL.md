---
name: pdt-memory
description: Use when work with PDT methods spans more than one session and earlier results should be picked up instead of asked again. Triggers include "mach weiter wo wir aufgehört haben", "was haben wir letztes Mal entschieden", "wo stehen wir im Projekt", "continue our product work", or the start of any PDT command in a project that already has a pdt-workspace folder. Reads and updates pdt-workspace/memory.md.
---

# PDT Memory

Hält den Projektstand über Sessions hinweg, damit eine Methode auf der vorherigen aufbaut statt bei null zu beginnen.

## Wo

`pdt-workspace/memory.md` im Projekt des Nutzers, nicht im Plugin. Existiert die Datei nicht und beginnt gerade eine PDT-Methode, lege sie an.

## Aufbau

```markdown
# PDT Memory

**Projekt:** {name}
**Zuletzt:** {datum}

## Vorhaben
{Ein bis zwei Sätze: was gebaut wird, für wen}

## Stand je Space
| Space | Stand | Artefakte |
|-------|-------|-----------|
| Strategy | offen / in Arbeit / belegt | {Dateien} |

## Entscheidungen
| Datum | Entscheidung | Begründung |
|-------|--------------|------------|

## Offene Annahmen
| Annahme | zu prüfen mit | seit |
|---------|---------------|------|
```

## Regeln

**Vor einer Methode lesen.** Frage nicht nach, was in der Memory steht. Fass den Stand in einem Satz zusammen und frage nur nach dem, was fehlt.

**Nach einer Methode schreiben.** Neues Artefakt in der Tabelle eintragen, getroffene Entscheidungen mit Begründung festhalten, offene Annahmen ergänzen oder als geprüft streichen.

**Entscheidungen nie stillschweigend ändern.** Widerspricht ein neues Ergebnis einer früheren Entscheidung, weise darauf hin und lass den Nutzer entscheiden, statt die Zeile zu überschreiben.

**Kurz halten.** Die Memory ist ein Stand, kein Protokoll. Was in einem Artefakt steht, gehört nicht noch einmal hierher, nur der Verweis darauf.

**Keine personenbezogenen Daten Dritter.** Namen von Interviewpartnern gehören nicht in die Memory, Rollen genügen.
