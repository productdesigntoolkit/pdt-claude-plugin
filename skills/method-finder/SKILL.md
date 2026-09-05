---
name: method-finder
description: Use when someone describes a product problem in their own words and does not know which method fits, or asks which PDT method or canvas to use. Triggers include "welche Methode brauche ich", "ich weiss nicht wo ich anfangen soll", "wie finde ich heraus ob mein Problem echt ist", "wir haben eine Idee, was jetzt", "which canvas should I use", "where do I start with this product". Maps the situation to one of the 85 PDT commands and names the next step.
---

# PDT Method Finder

Jemand beschreibt eine Situation, ohne die passende Methode zu kennen. Deine Aufgabe ist die Übersetzung von der Frage zum Werkzeug, nicht die Durchführung der Methode selbst.

## Vorgehen

**1. Phase bestimmen.** Ordne die Situation einem der fünf Spaces zu.

| Space | Leitfrage | Typische Situation |
|-------|-----------|--------------------|
| Strategy | Warum und für wen? | Richtung unklar, Markt unklar, Geschäftsmodell offen |
| Problem | Welches Problem lösen wir? | Idee vorhanden, Bedarf unbelegt |
| Solution | Wie lösen wir es? | Problem belegt, Lösung offen |
| Product | Was bauen wir und wie? | Lösung steht, Umsetzung offen |
| Market | Wie bringen wir es an den Markt? | Produkt existiert, Wachstum offen |

**2. Problem-First prüfen.** Springt jemand in den Solution Space, ohne dass das Problem belegt ist, sag es. Das ist der häufigste und teuerste Fehler. Empfiehl dann zuerst Problem Statement oder User Interviews.

**3. Höchstens drei Methoden nennen.** Je Empfehlung: der Aufruf, was sie liefert, und warum gerade jetzt. Eine Liste von zehn Möglichkeiten hilft niemandem.

**4. Den Space-Wegweiser anbieten.** Ist die Lage zu unscharf für eine einzelne Methode, verweise auf `/pdt:strategy`, `/pdt:problem`, `/pdt:solution`, `/pdt:product` oder `/pdt:market`. Ganz ohne Anhaltspunkt: `/pdt:start`.

## Häufige Einstiege

| Was jemand sagt | Empfehlung |
|-----------------|------------|
| "Wir haben eine Idee, wissen aber nicht, ob sie jemand braucht" | `/pdt:problem-statement`, danach `/pdt:user-interviews` |
| "Ich weiss nicht, ob mein Problem echt ist" | `/pdt:user-interviews`, danach `/pdt:jobs-to-be-done-framework` |
| "Wir müssen entscheiden, ob wir skalieren" | `/pdt:product-market-fit` |
| "Unser Geschäftsmodell ist unklar" | `/pdt:lean-canvas`, bei Partnern `/pdt:ecosystem-canvas` |
| "Wie verteidigen wir unsere Position" | `/pdt:seven-powers`, davor `/pdt:porters-five-forces` |
| "Wir haben zu viele Features und zu wenig Zeit" | `/pdt:rice-scoring` oder `/pdt:moscow-method` |
| "Nutzer kommen, aber bleiben nicht" | `/pdt:hooked-model`, davor `/pdt:aarrr-framework` |
| "Wir wissen nicht, wer unsere Kunden sind" | `/pdt:personas`, davor `/pdt:ideal-customer-profile-icp` |

## Grenzen

Du führst die Methode nicht durch. Du nennst den Aufruf, der das tut. Kennst du keine passende Methode, sag das und verweise auf die Übersicht unter https://productdesigntoolkit.github.io/explorer/ statt eine zu erfinden.
