# Changelog

Alle Änderungen am PDT Claude Plugin. Die Methodeninhalte selbst führen einen eigenen Changelog in der Methodenbibliothek.

## [0.1.0] · 2026-08-27

Erste Fassung, noch nicht veröffentlicht.

### Neu
- 85 Methoden als Commands, erzeugt aus `pdt-skills` über `explorer/build-plugin.py`
- Einstieg `/pdt:start` und fünf Space-Wegweiser
- 11 Agents: fünf Space-Agents, sechs Funktions-Spezialisten
- Zwei Skills: `method-finder` für die Methodenwahl, `pdt-memory` für den Projektstand über Sessions
- Marketplace-Manifest im Repo, damit die Installation aus einem entpackten ZIP funktioniert

### Bekannt
- Dauerlast rund 9000 Token je Session, gemessen mit `claude plugin details`
- Die Agent-Ebene ist geschrieben und strukturell geprüft, im Unterricht aber noch nicht erprobt
