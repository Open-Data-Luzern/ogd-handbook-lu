---
sidebar_position: 1
slug: /
---

import { CardGrid, Card } from "@site/src/components/CardGrid";
import StartseiteHero from "@site/src/components/StartseiteHero";

# Los geht's

<StartseiteHero
image={require('/img/intro_cristina_gaidau.jpg').default}
text="Dein Einstieg in Open Government Data (OGD) im Kanton Luzern. Das Handbuch richtet sich an alle, die offene Verwaltungsdaten verstehen, publizieren oder nutzen möchten."
sourceHref="https://www.istockphoto.com"
sourceLabel="Cristina Gaidau / iStockphoto"
layout="stacked"
/>

## Für wen ist dieses Handbuch?

**Mitarbeitende der kantonalen Verwaltung** finden hier Grundlagen zu OGD und Anleitungen, um Daten zu prüfen, aufzubereiten und zu publizieren.

**Wer offene Verwaltungsdaten nutzen möchte**, findet hier eine [Einführung zu OGD](/ogd-handbook/ogd_grundlagen/ogd-in-kuerze). Bereits verfügbare Luzerner Datensätze findest du auf [opendata.swiss](https://opendata.swiss/de/organization/kanton_luzern) und im [Geodatenshop des Kantons Luzern](https://daten.geo.lu.ch/).

---

## Was findest du in diesem Handbuch?

Die Kapitel werden schrittweise für den Kanton Luzern überarbeitet.

<CardGrid cols={3}>
  <Card title="1. OGD Grundlagen" href="/ogd-handbook/ogd_grundlagen/ogd-in-kuerze" emoji="💡">
    Grundlagen zu Open Government Data, Informations- und Datenzugang, Prinzipien, FAIR & CARE und Schweizer OGD-Landschaft.
  </Card>
  <Card title="2. OGD im Kanton Luzern" href="/ogd-handbook/ogd_kanton_zh/daten-publizieren" emoji="🏛️">
    Publikation, Nutzung und Visualisierung offener Daten, rechtliche Grundlagen, Zuständigkeiten und Datenschutz im Kanton Luzern.
  </Card>
  <Card title="3. Daten" href="/ogd-handbook/daten_struktur_format/datenformate" emoji="🗂️">
    Datenformate, Datenstruktur, Spaltenüberschriften, Datentypen, geografische Referenzierung und Aktualisierungsstrategien.
  </Card>
  <Card title="4. Metadaten" href="/ogd-handbook/metadaten" emoji="🏷️">
    Datensätze und ihre Distributionen beschreiben und Metadaten nach DCAT-AP CH erfassen.
  </Card>
  <Card title="5. Anleitungen" href="/ogd-handbook/anleitungen/daten-aufbereiten" emoji="🛠️">
    Anleitungen zur Datenaufbereitung mit R, zur Umwandlung von Excel in CSV und zur Metadatenverwaltung.
  </Card>
  <Card title="6. Kontakt" href="https://opendata.lu.ch/" emoji="💌">
    Die OGD-Koordinationsstelle des Kantons Luzern hilft bei Fragen zu OGD und bei Publikationsvorhaben.
  </Card>
</CardGrid>

---

## Herausgeberin

**Kanton Luzern**, [OGD-Koordinationsstelle](https://opendata.lu.ch/).

## Dank

Wir danken dem **Amt für Statistik und Daten des Kantons Zürich** dafür, dass es den Quelltext seines [OGD-Handbuchs](https://github.com/openZH/ogd-handbook) öffentlich zur Verfügung stellt. Das Zürcher Handbuch dient uns als Vorlage für die Anpassung an den Kanton Luzern.
