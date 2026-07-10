---
name: ogh-judikatur
description: "OGH-Judikatur zitieren: Senat (Ob zivil / Os strafrechtlich), Datum, Aktenzeichen mit Prüfsumme; verbindlich nur mit frei prüfbarer Quelle (RIS-Justiz). Sperre gegen halluzinierte Aktenzeichen."
---

# OGH-Judikatur zitieren

## Einsatzlage

Aktiv, sobald eine Entscheidung des Obersten Gerichtshofs zitiert werden soll — sei es zur Anspruchsstütze, zur Auslegung oder als Trägerentscheidung eines RS-Satzes.

## Regelungs- und Quellenanker

- OGH ist nach Art 92 B-VG oberste Instanz in Zivil- und Strafsachen.
- Geschäftsverteilung des OGH regelt die Senate (1 Ob, 2 Ob, … für Zivil; 11 Os, 12 Os, 13 Os, 14 Os, 15 Os für Straf).
- Veröffentlichungssammlungen: SZ (Entscheidungen des österreichischen Obersten Gerichtshofes in Zivilsachen), EvBl (Evidenzblatt), JBl (Juristische Blätter), ÖJZ.
- Frei prüfbar: RIS-Justiz (`ris.bka.gv.at/Jus`).

## Arbeitsweg

### Schritt 1 — Aktenzeichen verstehen

Form: `<Senatsnummer> Ob <laufende Nr>/<Jahr><Prüfziffer>`.

- Senatsnummer: 1–10 typischerweise für Zivil (variiert nach Geschäftsverteilung).
- »Ob«: civil; »Os«: criminal.
- Laufende Nr: pro Senat und Jahr fortlaufend.
- Jahr: zweistellig.
- Prüfziffer: Buchstabe nach modulo-basiertem Algorithmus.

Beispiele (struktureller Form, keine konkrete Entscheidung):

- Zivilsenat: `1 Ob 42/24x`, `4 Ob 123/23a`, `8 Ob 78/22d`.
- Strafsenat: `11 Os 17/24w`, `14 Os 89/23b`.

### Schritt 2 — Datum

- Datum ist das **Tagungsdatum** der Entscheidung, nicht das Veröffentlichungsdatum.
- Form: `12.3.2024` (Tag.Monat.Jahr, keine führenden Nullen in der österreichischen Praxis).

### Schritt 3 — Zitierform

- Minimal: `OGH 12.3.2024, 1 Ob 42/24x`.
- Mit Fundstelle in Druckwerk: `OGH 12.3.2024, 1 Ob 42/24x = SZ 97/12 = JBl 2024, 234`.
- Mit RS-Satz: `OGH 12.3.2024, 1 Ob 42/24x; RIS-Justiz RS0123456`.
- Mit Pinpoint: `OGH 12.3.2024, 1 Ob 42/24x [Rz 5]`.

### Schritt 4 — Plausibilitätsprüfung

Vor Übernahme eines Aktenzeichens:

1. **Existiert das Aktenzeichen?** RIS-Justiz öffnen, Az im Format `1 Ob 42/24x` eingeben (mit Leerzeichen, Schrägstrich, Kleinbuchstaben).
2. **Passt das Jahr?** Bei Az `…/24x` muss das Tagungsdatum 2024 sein.
3. **Passt der Senat?** Bestimmte Senate sind für bestimmte Sachgebiete zuständig (zB 4 Ob: Wettbewerb, Marken, Urheber; 9 Ob: Konsumentenrecht — Geschäftsverteilung **prüfen**, nicht raten).
4. **Trägt die Entscheidung wirklich?** Leitsatz und RS-Satz abgleichen.

Wenn auch nur eine Frage offenbleibt: nicht zitieren oder generisch formulieren.

## Qualitätsanker

- **Niemals ein Aktenzeichen erfinden.** Format-Bekanntheit ≠ konkrete Entscheidung.
- **Keine »Mantelzitate«.** `vgl OGH …` ohne Az ist kein Beleg.
- **Bei mehreren Trägerentscheidungen** eines RS-Satzes: die markante zitieren, RS-Nr ergänzen.
- **Senatsnummer korrekt zuordnen.** Falsche Senatsangabe macht den Beleg unauffindbar.

## Wenn die Entscheidung nicht in RIS-Justiz steht

- Möglich bei sehr alten Entscheidungen (vor RIS-Justiz-Einspeisung) oder nicht veröffentlichten Beschlüssen.
- Dann: Fundstelle in Druckwerk angeben (`SZ`, `EvBl`, `JBl`, `ÖJZ`) und Plausibilität über Band/Jahr/Nr prüfen.
- Bei unveröffentlichten Entscheidungen: Quelle (Akteneinsicht, Anwalts-Kopie) konkret bezeichnen.

## Anschluss-Skills

- RS-Satz dazu: `ris-justiz-rs-saetze`.
- VfGH/VwGH-Entscheidung: `vfgh-vwgh-judikatur`.
- Pflichtcheckliste: `pflichtcheckliste-vor-ausgabe`.
