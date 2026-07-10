# Hausstil für `claude-austria-law`

Diese Datei dokumentiert den Hausstil für Beiträge in diesem Repository — sowohl für menschliche Mitwirkende als auch für Claude/KI-Assistenten, die SKILL.md-Dateien verfassen oder ergänzen.

## Quellenhygiene (nicht verhandelbar)

- **Normen.** Nur österreichische Normen zitieren, deren idgF über RIS (`ris.bka.gv.at`) frei prüfbar ist. Form: `§ 879 ABGB`, `§ 9 Abs 2 RAO`, `Art 28 DSGVO`. Bei Bundesgesetzblatt-Verweis: `BGBl I 165/1999` oder bei älteren Stammgesetzen `RGBl 96/1868`.
- **Judikatur.** Nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle (RIS-Justiz). Form: `OGH 12.3.2024, 1 Ob 42/24x`, `VfGH 23.6.2023, G 234/2022`, `VwGH 15.2.2023, Ra 2022/01/0042`. RS-Sätze: `RS0123456`.
- **Keine Blindzitate.** Keine Entscheidung, kein Aufsatz, kein Kommentar, der nicht mit konkretem Beleg (RIS-Link, RDB-Treffer mit Aktenzeichen, Verlagsbeleg mit Auflage und Randnummer) belegt ist.
- **Keine erfundenen Aktenzeichen.** Lieber leerlassen oder mit `[TODO: Az ergänzen]` markieren als raten.
- **Keine erfundenen RS-Nummern.** RIS-Justiz-RS-Nummern sind konkrete Sachregistereinträge; nicht erfinden.
- **Bei Unsicherheit:** lieber generisch formulieren (»Nach hL/stRsp …«) als ein konkretes Zitat halluzinieren.

## Stil und Methodik

- **Methodik nach §§ 6, 7 ABGB.** Reihenfolge: wörtlich → systematisch → teleologisch → historisch. Analogie und Umkehrschluss nur mit ausdrücklichem Methodenargument.
- **Anspruchsaufbau / Prüfungsschema.** Anspruchsgrundlage → Tatbestand → Rechtsfolge → Einwendungen/Einreden. Bei Verträgen: Zustandekommen → Wirksamkeit → Inhalt → Erfüllung/Leistungsstörung.
- **Verfahrensrecht.** Zuständigkeit (sachlich, örtlich, funktionell) immer mit konkreter Norm (JN, ZPO, ASGG, AußStrG, AVG, VwGVG).
- **Sprache.** Österreichisches Deutsch (Jänner statt Januar, heuer, Spital statt Krankenhaus); juristisches Vokabular gemäß österreichischer Praxis (»Begehren« statt »Antrag«, »Bescheid« statt »Verwaltungsakt«, »Wahrungsfrist« etc.).

## Berufsrechtliche und datenschutzrechtliche Disziplin

Jeder Skill, der mit personenbezogenen Daten, Mandatsmaterial oder Strafverfolgungs­bezug arbeitet, **muss** an prominenter Stelle daran erinnern:

- Mandatsgeheimnis nach § 9 Abs 2 RAO und Strafbarkeit nach § 121 StGB.
- DSGVO + DSG: Rechtsgrundlage, Informationspflicht, AVV, Drittlandtransfer.
- KI-VO: Hochrisiko-Einstufung nach Art 6 iVm Anhang III prüfen, Transparenzpflichten nach Art 50, Betreiberpflichten nach Art 26.
- Bei Eingriff in fremde IT/Daten: §§ 118a ff StGB, §§ 62, 63 DSG (Verwaltungsstraf- bzw gerichtliche Strafbestimmung).

Skills dürfen **nie** behaupten, sie selbst hätten irgendwelche Compliance-Fragen abschließend beantwortet.

## Format der `SKILL.md`

```markdown
---
name: <kebab-case-name>
description: "Einleitung, Triage und Routing für <Rechtsgebiet>: ordnet Rolle, markiert Fristen, wählt Norm, leitet zum passenden Spezial-Skill."
---

# <Titel des Skills>

## Einsatzlage

Wann wird dieser Skill aktiv? Welcher Sachverhalt löst ihn aus?

## Regelungs- und Quellenanker

Stichpunktliste der einschlägigen Normen mit kurzer Funktion. **Nur** Normen, die zum Output dieses Skills wirklich beitragen.

## Arbeitsweg

Strukturierter Ablauf: Was der Skill in welcher Reihenfolge prüft. Frist- und Beweisweichen explizit benennen.

## Qualitätsanker

- Zitierregeln nach `zitierweise-oesterreichisches-recht/references/zitierweise.md`.
- Bei Spezialfragen den passenden Anschluss-Skill nennen.
- Compliance-Hinweise (Mandatsgeheimnis, DSGVO, KI-VO) am Output mitführen, soweit einschlägig.
```

## Was NICHT in einen Skill gehört

- Konkrete Mandatsdaten oder personenbezogene Daten (auch nicht in Beispielen).
- Werbung für bestimmte Anbieter, Verlage oder Tools.
- Politische Stellungnahmen jenseits der einschlägigen Rechtsdogmatik.
- »Garantien« zu Rechtsfolgen, Fristen oder Zulässigkeit.

## Versionierung

Plugin-Versionen folgen `MAJOR.MINOR.PATCH` (SemVer-ähnlich):

- **MAJOR**: Bruch an Schnittstellen oder fachlicher Ausrichtung.
- **MINOR**: Neuer Skill oder substanzielle Erweiterung.
- **PATCH**: Korrekturen, Klarstellungen, Quellenupdate.

Die zentrale `.claude-plugin/marketplace.json` führt die jeweilige Pluginversion.
