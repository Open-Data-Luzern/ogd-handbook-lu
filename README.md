# OGD-Handbuch des Kantons Luzern

In diesem Repository entsteht das **Handbuch für offene Verwaltungsdaten (Open Government Data, OGD) des Kantons Luzern**. Es richtet sich an Mitarbeitende der kantonalen Verwaltung, die Daten als OGD veröffentlichen möchten, sowie an alle, die offene Verwaltungsdaten des Kantons Luzern finden und weiterverwenden wollen.

Informationen zu OGD und den verfügbaren Datenangeboten findest du auf der [OGD-Seite des Kantons Luzern](https://opendata.lu.ch/).

## Inhalt

| Kapitel | Thema                                       |
| ------- | ------------------------------------------- |
| 1       | OGD Grundlagen                              |
| 2       | OGD im Kanton Luzern                        |
| 3       | Datenstruktur & Format                      |
| 4       | Metadaten                                   |
| 5       | Anleitungen (R, Excel, Metadatenverwaltung) |
| 6       | Kontakt                                     |

## Technologie

Das Handbuch wird mit [Docusaurus](https://docusaurus.io/) gebaut. Inhalte liegen als Markdown-Dateien in [`docs/`](docs/). Interaktive Komponenten sind als React-Komponenten in [`src/components/`](src/components/) ausgelagert.

### Lokale Entwicklung

```bash
npm install    # Abhängigkeiten installieren
npm run build  # Produktions-Build erstellen
npm run serve  # Build lokal im Browser öffnen

```

## Dank

Wir danken dem Amt für Statistik und Daten des Kantons Zürich, dass es sein [OGD-Handbuch](https://github.com/openZH/ogd-handbook) zur Verfügung stellt. Es dient als Grundlage für die Luzerner Fassung.
