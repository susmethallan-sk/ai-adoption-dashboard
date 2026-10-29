<p align="right">
  <a href="README.md"><img alt="English" src="https://img.shields.io/badge/English-c8ced8?style=flat-square"></a>
  <a href="README.de.md"><img alt="Deutsch" src="https://img.shields.io/badge/Deutsch-1f4e8c?style=flat-square"></a>
</p>

# KI-Einführung in deutschen Großunternehmen

**Eine Power-BI-Analyse, wie 15 große deutsche Unternehmen künstliche Intelligenz einführen: was sie antreibt, was sie bremst und was sich dadurch für Teams verändert.**

Grundlage ist meine Bachelorarbeit *„AI Tool Selection and Implementation in Project Management Teams“* an der SRH Hochschule Heidelberg (Note der Abschlussarbeit: **1,0**).

<p>
  <a href="https://susmethallan-sk.github.io/ai-adoption-dashboard/"><img alt="Interaktives Dashboard öffnen" src="https://img.shields.io/badge/Interaktives_Dashboard_%C3%B6ffnen-2f5597?style=for-the-badge"></a>
  &nbsp;
  <a href="power-bi/AI_Adoption_German_Enterprises_Portfolio.pbix"><img alt="Power-BI-Datei herunterladen" src="https://img.shields.io/badge/Power--BI--Datei_herunterladen-f2c811?style=for-the-badge"></a>
</p>

*Das Dashboard selbst ist auf Englisch.*

![Seite „Executive Overview“ des Power-BI-Berichts](screenshots/01-executive-overview.png)

## Auf einen Blick

| Umfang | |
|---|---:|
| Analysierte Unternehmen | 15 |
| Branchen | 8 |
| Datensätze (Belegstellen) | 106 |
| Zeitraum | 2023–2025 |
| Quellen | Geschäfts- und Unternehmensberichte |

**Unternehmen:** Adidas · Allianz · BASF · Bayer · BMW Group · Bosch · Continental · Deutsche Bank · Deutsche Post DHL · Deutsche Telekom · Merck KGaA · SAP · Siemens · Volkswagen Konzern · Zalando

## Zentrale Ergebnisse

1. **Strategie treibt die Einführung.** Strategische Reife ist der am häufigsten genannte Treiber (21 Nennungen), deutlich vor allen anderen Reifedimensionen.
2. **Die größte Hürde sind die Menschen.** Fehlende Kompetenzen und die Bereitschaft der Belegschaft sind das am häufigsten genannte Hindernis (22 Nennungen), gefolgt von technischer Reife (10) und Datenreife (9).
3. **Daten werden unterschätzt.** Daten werden kaum als Grund für den KI-Einsatz genannt (1 Nennung), aber häufig als Grund, warum die Umsetzung schwierig ist (9 Nennungen).
4. **Teams berichten von Produktivität, schnelleren Entscheidungen und Unterstützung.** Die genannten Ergebnisse auf Teamebene betreffen vor allem Produktivitätsgewinne, schnellere Entscheidungen und KI als Unterstützung statt als Ersatz für Mitarbeitende.

## Die drei Berichtsseiten

| Seite | Leitfrage |
|---|---|
| **Executive Overview** | Wie viele Belege gibt es, nach Branche und Forschungsthema? |
| **Drivers & Barriers** | Welche Reifedimensionen fördern die KI-Einführung, welche bremsen sie? |
| **Team-Level Outcomes** | Welche Veränderungen berichten Unternehmen für ihre Teams nach der KI-Einführung? |

Alle Seiten lassen sich nach Unternehmen und Branche filtern. Die Detailtabellen verweisen bei jedem Beleg auf den Quellbericht und die Seitenzahl.

<details>
<summary><b>Die beiden anderen Seiten ansehen</b></summary>

<br>

![Seite „Drivers & Barriers“ des Power-BI-Berichts](screenshots/02-drivers-and-barriers.png)

![Seite „Team-Level Outcomes“ des Power-BI-Berichts](screenshots/03-team-level-outcomes.png)

</details>

## Vorgehen

1. **Datenerhebung:** Auswertung der Geschäfts- und Unternehmensberichte 2023–2025 von 15 deutschen Unternehmen; relevante Aussagen zum KI-Einsatz wurden mit Quelle und Seitenangabe erfasst.
2. **Kodierung:** Zuordnung jeder Aussage zu einer Forschungsfrage (Treiber, Hürden, Ergebnisse auf Teamebene) und zu einer Reifedimension (strategisch, organisatorisch, Daten, Technik, Mensch).
3. **Datenaufbereitung:** Strukturierung der Belege in Excel und Bereinigung mit Power Query.
4. **Datenmodell:** Sternschema mit Tabellen für Unternehmen, Branche, Quelle, Forschungsfrage und Reifedimension.
5. **Kennzahlen und Bericht:** DAX-Measures für die KPIs und ein interaktiver Bericht mit drei Seiten, Datenschnitten, Kreuzfilterung und Detailtabellen.

**Werkzeuge:** Microsoft Power BI · Power Query · DAX · Excel · qualitative Inhaltsanalyse

## Zur Web-Version

Der Originalbericht wurde in **Microsoft Power BI** erstellt; die `.pbix`-Datei liegt in diesem Repository.

Für eine öffentliche Veröffentlichung eines Power-BI-Berichts ist ein Microsoft-Geschäfts- oder Schulkonto mit Power-BI-Lizenz erforderlich, das für dieses eigenständige Projekt nicht zur Verfügung stand. Damit der Bericht trotzdem ohne Anmeldung erkundet werden kann, ist das oben verlinkte **interaktive Dashboard** eine Web-Nachbildung des Power-BI-Berichts. Es nutzt dieselben Daten und bildet dieselben Seiten und Filter ab.

## Inhalt des Repositorys

| Ordner | Inhalt |
|---|---|
| [`power-bi/`](power-bi/) | Der Original-Power-BI-Bericht (`.pbix`), der sich in Power BI Desktop öffnen lässt |
| [`data/`](data/) | Der kodierte Datensatz (Excel) |
| [`screenshots/`](screenshots/) | Screenshots der drei Berichtsseiten |

## Kontakt

**Susmeth Allan Sathees Kumar** · Mannheim

[LinkedIn](https://www.linkedin.com/in/susmethsathees) · [susmethallan@gmail.com](mailto:susmethallan@gmail.com)
