---
name: datenpannen-art-33-34
description: "Data Breach nach Art 33, 34 DSGVO: Verletzung erkennen und eindämmen, Risikobewertung, 72-Stunden-Meldung an die DSB, Benachrichtigung der Betroffenen bei hohem Risiko, Breach-Register und Nachbereitung."
---

# Datenpannen — Meldung und Benachrichtigung (Art 33, 34 DSGVO)

## Einsatzlage

Aktiv im Akutfall (Ransomware, Fehlversand, verlorenes Gerät, unbefugter Zugriff, Cloud-Leak) und bei der präventiven Einrichtung des Breach-Prozesses. Im Akutfall gilt: **Uhr läuft ab Kenntnis** — zuerst Zeitpunkt der Kenntniserlangung dokumentieren, dann eindämmen, dann bewerten.

## Regelungs- und Quellenanker

- **Art 4 Z 12 DSGVO** — Definition: Verletzung der Sicherheit, die zu Vernichtung, Verlust, Veränderung, unbefugter Offenlegung oder unbefugtem Zugang führt (auch Verfügbarkeitsverlust!).
- **Art 33 Abs 1 DSGVO** — Meldung an die DSB **unverzüglich, möglichst binnen 72 Stunden** ab Kenntnis; Ausnahme: voraussichtlich **kein** Risiko; verspätete Meldung mit Begründung.
- **Art 33 Abs 2 DSGVO** — Auftragsverarbeiter meldet dem Verantwortlichen unverzüglich.
- **Art 33 Abs 3, 4 DSGVO** — Mindestinhalt; Nachreichung in Schritten zulässig.
- **Art 33 Abs 5 DSGVO** — **Breach-Register:** jede Verletzung dokumentieren, auch nicht meldepflichtige.
- **Art 34 DSGVO** — Benachrichtigung der Betroffenen bei voraussichtlich **hohem** Risiko; Ausnahmen Abs 3 (Verschlüsselung, nachträgliche Maßnahmen, öffentliche Bekanntmachung).
- **Art 32 DSGVO** — TOMs als Prävention; **§§ 118a ff StGB** — bei Angriffen durch Dritte: Strafanzeige erwägen.
- **NIS-Regime / sektorale Meldepflichten** — parallel prüfen (kritische Infrastruktur, Finanz: DORA), ersetzen die DSGVO-Meldung nicht.

## Arbeitsweg

1. **Sofortmaßnahmen (parallel zur rechtlichen Prüfung):** Vorfall eindämmen (Zugänge sperren, Systeme isolieren), Beweise sichern (Logs, forensische Kopien), Kenntniszeitpunkt und Meldekette minutengenau protokollieren.
2. **Breach-Qualifikation:** Liegt eine Verletzung iSd Art 4 Z 12 vor? Auch temporärer Verfügbarkeitsverlust und interner Fehlzugriff zählen. Prozessor-Konstellation: Wer ist Verantwortlicher, wessen 72-h-Frist läuft (Kenntnis des Verantwortlichen; Prozessor-Meldung nach Art 33 Abs 2 auslösen)?
3. **Risikobewertung dokumentieren** (dreistufig):
   - **Kein Risiko** → keine DSB-Meldung, aber Registereintrag (Art 33 Abs 5).
   - **Risiko** → DSB-Meldung binnen 72 h.
   - **Hohes Risiko** → zusätzlich Benachrichtigung der Betroffenen (Art 34) »unverzüglich«.
   Kriterien: Datenart (Art 9!), Volumen, Identifizierbarkeit, Folgenschwere, Verschlüsselung, Empfängerkreis.
4. **DSB-Meldung erstellen** (Art 33 Abs 3): Art der Verletzung, Kategorien und ungefähre Zahl der Betroffenen und Datensätze, Kontakt (DSB-Meldewege auf `dsb.gv.at`), wahrscheinliche Folgen, ergriffene/vorgeschlagene Maßnahmen. Lieber fristgerecht unvollständig melden und nachreichen (Abs 4) als vollständig zu spät.
5. **Betroffenen-Benachrichtigung (Art 34):** klare, einfache Sprache; konkrete Schutzempfehlungen (Passwortwechsel, Kartensperre); Ausnahmen des Abs 3 prüfen und Entscheidung dokumentieren.
6. **Nachbereitung:** Ursachenanalyse, TOM-Anpassung (Art 32), DSFA-Review, Schulung; zivilrechtliche Exposition (Art 82 DSGVO, § 29 DSG) und Versicherungsmeldung (Cyber-Police, Obliegenheiten!) prüfen.

## Qualitätsanker

- Zitierregeln nach `zitierweise-oesterreichisches-recht/references/zitierweise.md`; EDSA Guidelines 9/2022 (Data Breach Notification) nur mit Version und Datum.
- Nie von einer Meldung »abraten«, um Bußgeldrisiken zu vermeiden — unterlassene Meldung ist ein eigener Verstoß (Art 83 Abs 4 DSGVO); Entscheidungsgrundlagen transparent dokumentieren.
- Anschluss-Skills: `verfahren-vor-der-dsb` (Folgeverfahren), `auftragsverarbeitung-art-26-28` (Meldeketten im AVV), `dsfa-art-35` (Prävention).
- **Compliance:** Breach-Sachverhalte sind maximal sensibel (betroffene Daten + Sicherheitslücken + potenzielle Straftaten). Mandatsgeheimnis (§ 9 Abs 2 RAO, § 121 StGB), DSGVO/DSG, §§ 118a ff StGB und KI-VO beachten; keine Weitergabe von Vorfalldetails an unbeteiligte Systeme. Dieser Skill beantwortet keine Compliance-Frage abschließend.
