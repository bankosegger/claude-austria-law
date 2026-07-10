---
name: einstieg-routing
description: "Einleitung, Triage und Routing für das österreichische Datenschutzrecht: ordnet Rolle (Verantwortlicher, Auftragsverarbeiter, betroffene Person), markiert Fristen (72-h-Meldung, Monatsfrist, § 24 DSG), wählt Norm und leitet zum passenden Spezial-Skill."
---

# Einstieg und Routing — Datenschutzrecht Österreich

## Einsatzlage

Dieser Skill ist der Einstieg in jeden datenschutzrechtlichen Sachverhalt: neue Verarbeitung geplant, Betroffenenanfrage eingelangt, Datenpanne passiert, DSB-Verfahren anhängig, Dienstleister einzubinden, Datenexport ins Drittland. Er klärt Rolle und Dringlichkeit und leitet zum Spezial-Skill.

## Fachlandkarte dieses Plugins

- `rechtsgrundlagen-art-6-9` — Rechtsgrundlage der Verarbeitung.
- `betroffenenrechte` — Auskunft, Löschung & Co.
- `auftragsverarbeitung-art-26-28` — Rollenabgrenzung, AVV, Joint Control.
- `dsfa-art-35` — Folgenabschätzung und Konsultation.
- `datenpannen-art-33-34` — Data Breach.
- `verfahren-vor-der-dsb` — Beschwerde, Strafverfahren, Instanzenzug.
- `drittlandtransfer-kapitel-v` — Kapitel V DSGVO.

## Regelungs- und Quellenanker

- **DSGVO** (VO (EU) 2016/679) — Kernregime, unmittelbar anwendbar.
- **DSG** (BGBl I 165/1999 idgF) — § 1 (Grundrecht), § 6 (Datengeheimnis), §§ 24 ff (Verfahren).
- Überblick: [`references/datenschutz-quellen.md`](../../references/datenschutz-quellen.md), [`references/behoerden-und-rechtsschutz.md`](../../references/behoerden-und-rechtsschutz.md).

## Arbeitsweg

1. **Anwendbarkeit prüfen:** Personenbezogene Daten (Art 4 Z 1 DSGVO)? Sachlicher Anwendungsbereich (Art 2 — Haushaltsausnahme?), räumlicher (Art 3 — Niederlassung, Marktort)? Sonderregime (Strafverfolgung → 3. Hauptstück DSG; TKG 2021 für Cookies)?
2. **Rolle festlegen:** Verantwortlicher, gemeinsamer Verantwortlicher, Auftragsverarbeiter oder betroffene Person? Die Rolle bestimmt Pflichten und Haftung (→ `auftragsverarbeitung-art-26-28`).
3. **Fristen SOFORT markieren:**
   - **Data Breach:** Meldung an die DSB unverzüglich, möglichst binnen **72 Stunden** (Art 33 DSGVO) → `datenpannen-art-33-34`.
   - **Betroffenenanfrage:** Antwort binnen **eines Monats**, verlängerbar um zwei Monate (Art 12 Abs 3 DSGVO) → `betroffenenrechte`.
   - **DSB-Beschwerde:** ein Jahr ab Kenntnis, längstens drei Jahre (§ 24 Abs 4 DSG) → `verfahren-vor-der-dsb`.
   - **BVwG-Beschwerde:** vier Wochen ab Bescheidzustellung (§ 7 Abs 4 VwGVG).
4. **Verarbeitung inventarisieren:** Zwecke, Datenkategorien, Betroffenenkreise, Empfänger, Speicherdauer — entspricht dem Verzeichnis von Verarbeitungstätigkeiten (Art 30 DSGVO). Ohne dieses Inventar keine belastbare Aussage zu Rechtsgrundlage oder DSFA-Pflicht.
5. **Risikoschwellen prüfen:** Besondere Kategorien (Art 9)? Systematische Überwachung? Neue Technologie (KI!)? → `dsfa-art-35`; bei KI-Einsatz zusätzlich KI-VO-Einstufung (Art 6 iVm Anhang III) ansprechen.
6. **Drittlandbezug prüfen:** Server-, Support- oder Konzernstandorte außerhalb EU/EWR → `drittlandtransfer-kapitel-v`.
7. **Spezial-Skill routen** und fehlende Tatsachen als Rückfragen formulieren.

## Qualitätsanker

- Zitierregeln nach `zitierweise-oesterreichisches-recht/references/zitierweise.md`; DSGVO-Artikel immer mit Absatz/Litera und Zusatz »DSGVO« zitieren.
- Keine erfundenen DSB-Geschäftszahlen oder EDSA-Dokumentnummern; EuGH nur mit Rechtssachennummer.
- **Compliance:** Mandatsgeheimnis (§ 9 Abs 2 RAO, § 121 StGB); DSGVO/DSG gelten auch für die eigene Beratungs- und KI-Nutzung (Rechtsgrundlage, Informationspflicht, AVV, Drittlandtransfer); KI-VO-Pflichten (Art 26, 50, Hochrisiko-Prüfung nach Art 6 iVm Anhang III) prüfen. Dieser Skill beantwortet keine Compliance-Frage abschließend.
