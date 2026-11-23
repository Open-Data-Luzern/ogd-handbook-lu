# AGENTS.md

## Git

Hole vor jedem Commit und vor jedem Push die ausdrückliche Zustimmung
der Nutzerin oder des Nutzers ein. Das gilt auch für Änderungen über
GitHub-Werkzeuge, die direkt einen Commit erstellen.

Schreibe Commit-Nachrichten auf Englisch im Conventional-Commits-Format.
Verwende einen passenden Typ wie `chore`, `feat`, `fix` oder `docs`.
Beispiel: `chore: configure engineering skills`.

## Pull Requests

Erstelle Pull Requests ausschliesslich mit dem Basis-Repository
`Open-Data-Luzern/ogd-handbook-lu` und dem Basis-Branch `main`.
Gib das Ziel explizit an, bei der GitHub CLI mit
`gh pr create --repo Open-Data-Luzern/ogd-handbook-lu --base main`.
Prüfe bei angelegten PRs und vor einem Merge das Basis-Repository und
den Basis-Branch. Brich den Vorgang bei einem abweichenden Ziel ab.

## Agent skills

### Issue tracker

Aufgaben und Spezifikationen werden in GitHub Issues im Repository
`Open-Data-Luzern/ogd-handbook-lu` verwaltet.
Siehe `docs/agents/issue-tracker.md`.

### Triage labels

Verwende die fünf vereinbarten Standardlabels.
Siehe `docs/agents/triage-labels.md`.

### Domain docs

Das Projekt verwendet ein gemeinsames Glossar in `GLOSSARY.md`.
Architekturentscheide werden bei Bedarf unter `docs/adr/` dokumentiert.
Siehe `docs/agents/domain.md`.
