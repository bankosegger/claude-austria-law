---
name: drittlandtransfer-kapitel-v
description: "Drittlandtransfer nach Kapitel V DSGVO (Art 44–49): Angemessenheitsbeschluss (inkl EU-US Data Privacy Framework), Standardvertragsklauseln samt Transfer Impact Assessment nach Schrems II (EuGH C-311/18), BCR, Ausnahmen des Art 49."
---

# Drittlandtransfer (Kapitel V DSGVO)

## Einsatzlage

Aktiv, sobald personenbezogene Daten EU/EWR verlassen (können): Cloud- und KI-Anbieter mit US-Bezug, Konzern-Reporting, Support-Zugriffe aus Drittländern, internationale Mandate. Auch der bloße **Fernzugriff** aus dem Drittland ist ein Transfer.

## Regelungs- und Quellenanker

- **Art 44 DSGVO** — Grundsatz: Transfer nur bei gesichertem Schutzniveau; Kapitel V zusätzlich zu Art 6 (Zwei-Stufen-Prüfung).
- **Art 45 DSGVO** — Angemessenheitsbeschluss der Kommission; für die USA: **EU-US Data Privacy Framework** (Angemessenheitsbeschluss vom 10.7.2023, nur für zertifizierte US-Unternehmen).
- **Art 46 DSGVO** — geeignete Garantien, insb **Standardvertragsklauseln** (Durchführungsbeschluss (EU) 2021/914, vier Module) und **Binding Corporate Rules** (Art 47).
- **Art 49 DSGVO** — eng auszulegende Ausnahmen (ausdrückliche Einwilligung, Vertragserfüllung, Rechtsansprüche); keine Grundlage für strukturelle Dauertransfers.
- **EuGH 16.7.2020, C-311/18 (Schrems II)** — Privacy Shield ungültig; SCC nur mit einzelfallbezogener Prüfung des Drittlandrechts (**Transfer Impact Assessment**) und ggf zusätzlichen Maßnahmen.
- **EDSA Recommendations 01/2020** (supplementary measures) — Prüfschema und Maßnahmenkatalog.
- **Art 30 Abs 1 lit e, Art 13 Abs 1 lit f DSGVO** — Transfer im Verzeichnis und in der Datenschutzinformation ausweisen.

## Arbeitsweg

1. **Transfer identifizieren:** Datenflüsse kartieren — Primärspeicherung, Backups, Sub-Prozessoren (AVV-Liste!), Support-/Admin-Zugriffe, Telemetrie. »EU-Region« eines US-Anbieters beseitigt den Drittlandbezug nicht automatisch (Zugriffsmöglichkeit der Konzernmutter; extraterritoriale Befugnisse wie US CLOUD Act / FISA 702 in der Risikoanalyse berücksichtigen).
2. **Zwei-Stufen-Prüfung:** Erst Rechtsgrundlage der Verarbeitung/Übermittlung (→ `rechtsgrundlagen-art-6-9`), dann Kapitel-V-Instrument.
3. **Instrument wählen (Prüfreihenfolge):**
   - **Angemessenheitsbeschluss (Art 45):** Liste der Kommission prüfen; bei USA zusätzlich die konkrete **DPF-Zertifizierung** des Empfängers verifizieren (öffentliche DPF-Liste) und den Fortbestand des Beschlusses beobachten.
   - **SCC (Art 46):** richtiges Modul (C2C, C2P, P2C, P2P) wählen, Annexe (Datenbeschreibung, TOMs) konkret befüllen — leere Annexe machen die Klauseln wertlos.
   - **BCR (Art 47):** nur für Konzerne mit genehmigten Rules.
   - **Art 49:** nur für gelegentliche Einzelfälle; dokumentiert und restriktiv.
4. **Transfer Impact Assessment (bei Art-46-Instrumenten):** Rechtslage und Praxis im Drittland bezogen auf die konkreten Daten und Empfänger bewerten (EDSA 01/2020-Schema); **zusätzliche Maßnahmen** festlegen: technisch (Ende-zu-Ende- bzw kundenseitige Verschlüsselung, Pseudonymisierung), vertraglich (Transparenz-/Anfechtungspflichten bei Behördenanfragen), organisatorisch. Ergebnis schriftlich — Rechenschaftspflicht.
5. **Dokumentation nachziehen:** Verzeichnis (Art 30), Datenschutzinformation (Art 13/14), AVV-Annexe, DSFA (Transferrisiko als Risikofaktor → `dsfa-art-35`).
6. **Monitoring einrichten:** Angemessenheitsbeschlüsse und DPF-Zertifizierungen sind widerruflich/anfechtbar; Re-Evaluierungstermine und Exit-Szenarien (Datenrückholung, EU-Alternative) vorsehen.

## Qualitätsanker

- Zitierregeln nach `zitierweise-oesterreichisches-recht/references/zitierweise.md`; EuGH-Zitate mit Rechtssachennummer (C-311/18), Kommissionsbeschlüsse mit Nummer und Datum; aktuellen Stand der Angemessenheitsbeschlüsse vor Ausgabe verifizieren (Stand der Trainingsdaten genügt nicht).
- Kein Anbieter wird pauschal als »zulässig« oder »unzulässig« bewertet — nur das Prüfschema mit offenen Tatsachenfragen ausgeben.
- Anschluss-Skills: `auftragsverarbeitung-art-26-28` (Sub-Prozessor-Ketten), `dsfa-art-35`, `rechtsgrundlagen-art-6-9`.
- **Compliance:** Gerade beim KI-Einsatz in Kanzleien ist der Transferpfad (Anbieter, Region, Support) zentral — Mandatsgeheimnis (§ 9 Abs 2 RAO, § 121 StGB), DSGVO/DSG, KI-VO; siehe auch die Kontrollliste in der Wurzel-README. Dieser Skill beantwortet keine Compliance-Frage abschließend.
