---
name: einstieg-routing
description: "Einleitung, Triage und Routing für das österreichische Arbeitsrecht: ordnet Rolle (AN/AG/BR), markiert Fristen (§ 105 ArbVG, Unverzüglichkeit bei Entlassung, GlBG), wählt Norm und leitet zum passenden Spezial-Skill."
---

# Einstieg und Routing — Arbeitsrecht Österreich

## Einsatzlage

Dieser Skill ist der Einstieg in jeden arbeitsrechtlichen Sachverhalt: Beendigung (Kündigung, Entlassung, Austritt, einvernehmliche Auflösung, Fristablauf), Vertragsgestaltung, Einstufungsfragen, Arbeitszeit, Urlaub, Abfertigung, Diskriminierung. Er klärt Rolle, Personengruppe und Zeitdruck und leitet dann zum Spezial-Skill.

## Fachlandkarte dieses Plugins

- `dienstvertrag-und-werkvertrag` — Vertragstyp und sozialversicherungsrechtliche Einordnung.
- `kuendigungsfristen-harmonisiert` — Fristen und Termine nach § 1159 ABGB / § 20 AngG.
- `kuendigungsschutz-allgemein-105-arbvg` — Anfechtung wegen verpönten Motivs oder Sozialwidrigkeit.
- `kuendigungsschutz-besonderer` — MSchG, VKG, BEinstG, § 120 ArbVG (Zustimmungserfordernisse).
- `entlassung-und-austritt` — vorzeitige Auflösung aus wichtigem Grund.
- `arbeitszeit-und-urlaub` — AZG, ARG, UrlG.
- `abfertigung-alt-und-neu` — § 23 AngG vs BMSVG.

## Regelungs- und Quellenanker

- **§§ 1151 ff ABGB** — Dienstvertrag als Auffangregime.
- **AngG / GewO 1859 / ArbVG / AZG / ARG / UrlG / MSchG / VKG / BEinstG / GlBG / BMSVG** — Überblick in [`references/arbeitsrecht-quellen.md`](../../references/arbeitsrecht-quellen.md).
- **ASGG** (BGBl 104/1985 idgF) — Zuständigkeit der Arbeits- und Sozialgerichte (§ 50 ASGG: Arbeitsrechtssachen).

## Arbeitsweg

1. **Rolle klären:** Wer fragt — Arbeitnehmer:in, Arbeitgeber:in, Betriebsrat, Berater:in? Das bestimmt Blickwinkel, Fristenlauf und taktische Optionen.
2. **Personengruppe einordnen:** Angestellte:r (§ 1 AngG) oder Arbeiter:in? Lehrling (BAG)? Freie:r Dienstnehmer:in oder Werkunternehmer:in (→ `dienstvertrag-und-werkvertrag`)? Besonders geschützt (Schwangerschaft, Karenz, begünstigte Behinderung, Betriebsratsmandat → `kuendigungsschutz-besonderer`)?
3. **Fristen SOFORT markieren.** Die kürzesten und gefährlichsten:
   - **Anfechtung einer Kündigung/Entlassung** nach §§ 105–107 ArbVG: Wochenfristen ab Zugang bzw ab Verständigung — genauen Lauf nach § 105 Abs 4 ArbVG idgF prüfen (→ `kuendigungsschutz-allgemein-105-arbvg`).
   - **Entlassung/Austritt:** Unverzüglichkeitsgrundsatz — Zuwarten kann das Auflösungsrecht verwirken (→ `entlassung-und-austritt`).
   - **Bekanntgabe der Schwangerschaft** nach Ausspruch einer Kündigung: kurze Frist nach § 10 Abs 2 MSchG.
   - **GlBG:** Fristen für die Geltendmachung nach § 15 GlBG; Anfechtung diskriminierender Beendigungen binnen 14 Tagen (§ 12 GlBG).
   - **Verfallsklauseln** in KV oder Dienstvertrag (oft 3–6 Monate für Entgeltansprüche) — konkreten KV prüfen.
4. **Normquellen-Hierarchie prüfen:** Gesetz → Kollektivvertrag (§§ 2 ff ArbVG) → Betriebsvereinbarung (§§ 29 ff ArbVG) → Dienstvertrag → Weisung. Günstigkeitsprinzip (§ 3 ArbVG) beachten. Ohne Kenntnis des anwendbaren KV keine abschließende Aussage zu Entgelt, Fristen oder Verfall.
5. **Beweisweiche stellen:** Zugang der Beendigungserklärung (Datum, Form), Arbeitszeitaufzeichnungen (§ 26 AZG), Dienstzettel (§ 2 AVRAG), Zeugen. Beweissicherung vor Rechtsberatung im engeren Sinn.
6. **Zuständigkeit:** Arbeitsrechtssachen vor dem ASG Wien bzw dem Landesgericht als Arbeits- und Sozialgericht (§ 50 ASGG); örtliche Zuständigkeit nach § 4 ASGG (ua Betriebsstätte, Wohnsitz des AN).
7. **Spezial-Skill routen** und offene Tatsachenfragen als Rückfragen formulieren.

## Qualitätsanker

- Zitierregeln nach `zitierweise-oesterreichisches-recht/references/zitierweise.md`; keine erfundenen Aktenzeichen oder RS-Nummern.
- Ohne konkreten KV nur unter Vorbehalt antworten (»vorbehaltlich abweichender KV-Regelung«).
- **Compliance:** Arbeitsrechtliche Sachverhalte enthalten regelmäßig personenbezogene Daten (Gesundheit, Schwangerschaft, Behinderung — Art 9 DSGVO!). Mandatsgeheimnis (§ 9 Abs 2 RAO, § 121 StGB), DSGVO/DSG-Rechtsgrundlage und KI-VO-Pflichten (Art 26, 50; Hochrisiko-Prüfung nach Art 6 iVm Anhang III — Beschäftigung ist dort genannt) bleiben in der Verantwortung der Nutzer; dieser Skill beantwortet keine Compliance-Frage abschließend.
- Keine Garantien zu Fristen oder Prozessausgang; Fristen immer am Gesetzestext idgF (RIS) gegenprüfen.
