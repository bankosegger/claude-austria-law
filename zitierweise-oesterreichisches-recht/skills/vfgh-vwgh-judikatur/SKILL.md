---
name: vfgh-vwgh-judikatur
description: "Judikatur des VfGH und VwGH zitieren: Verfahrensarten (G, V, E, B), Aktenzeichenformate (Ra-Format des VwGH seit 1.1.2014), VfSlg/VwSlg-Sammlungen, RIS-Suchpfade."
---

# VfGH- und VwGH-Judikatur

## Einsatzlage

Aktiv, wenn eine Entscheidung des Verfassungsgerichtshofs oder Verwaltungsgerichtshofs zitiert werden soll — bei verfassungsrechtlichen Fragen, Normenkontrolle, Verwaltungsgerichtsbarkeit.

## Regelungs- und Quellenanker

- VfGH: Art 137–148 B-VG, VfGG (Verfassungsgerichtshofgesetz 1953).
- VwGH: Art 133–136 B-VG, VwGG (Verwaltungsgerichtshofgesetz 1985); umfassende Neuorganisation durch die **Verwaltungsgerichtsbarkeits-Novelle 2012** (BGBl I 51/2012, in Kraft 1.1.2014).
- Frei prüfbar:
  - VfGH: `vfgh.gv.at` oder RIS (`ris.bka.gv.at/Vfgh`).
  - VwGH: `vwgh.gv.at` oder RIS (`ris.bka.gv.at/Vwgh`).

## Arbeitsweg

### VfGH — Verfahrensarten und Aktenzeichen

| Verfahren | Aktenzeichen-Code |
| --- | --- |
| Gesetzesprüfung (Art 140 B-VG) | `G` |
| Verordnungsprüfung (Art 139 B-VG) | `V` |
| Erkenntnis im Beschwerdeverfahren (Art 144 B-VG, seit 2014) | `E` |
| Bescheidbeschwerde (Art 144 B-VG aF, bis 2013) | `B` |
| Kompetenzkonflikt | `KR` |
| Wahlanfechtung | `WI` |
| Anwendungskontrolle (Art 137 B-VG) | `A` |

Form: `VfGH 23.6.2023, G 234/2022`, `VfGH 5.3.2024, E 1234/2023`.

Veröffentlichung in der Sammlung: `VfSlg 21.345/2023` (Band/Nr; bis Bd 17 römisch, ab 18 arabisch — moderne Praxis arabisch).

### VwGH — Aktenzeichen-Wandel 2014

- **Seit 1.1.2014:** Revisionsverfahren, Aktenzeichen `Ra` + Jahr + Materiezahl + lfd Nr.
  - Form: `VwGH 15.2.2023, Ra 2022/01/0042`.
  - `Ra` = Revision; Materiezahl entspricht der jeweiligen Sachmaterie.
- **Vor 2014:** Beschwerdeverfahren, Aktenzeichen `Zl` + Jahr + Materie + Nr.
  - Form: `VwGH 4.5.2010, 2009/05/0123` (»Zl« oft weggelassen, da das Format selbsterklärend ist).
- **Außerordentliche Revision** und sonstige Verfahren mit eigenen Präfixen (zB `Ro` für ordentliche Revision).
- Veröffentlichung: `VwSlg 19.345/A` (administrative Sammlung) oder `/F` (finanzrechtliche Sammlung — bis 2014; danach BFG zuständig).

### Pinpoint und Trägersätze

- VfGH und VwGH veröffentlichen ebenfalls **Rechtssätze** in der RIS-Justiz/RIS-Datenbank.
- Form: `RIS-Justiz RS0123456` (gleiches Format wie OGH).
- Bei Pinpoint im Erkenntnistext: Randzahl bzw. Punkt der Begründung (`Rz 17`, `Pkt 3.2.`).

### Plausibilitätsprüfung

1. **Bei VwGH:** Datum 2014+ → muss `Ra`/`Ro`-Format sein. Wenn ein KI-Modell für 2020 ein »Zl«-Format vorschlägt, ist es falsch.
2. **Bei VfGH:** `B`-Verfahren nach 1.1.2014 unzulässig — wurde durch `E`-Verfahren abgelöst.
3. **Veröffentlichung in VfSlg/VwSlg:** prüfen, ob Band/Nr existiert.

## Beispiele (Form, keine konkrete Entscheidung)

| Sachverhalt | Form |
| --- | --- |
| Gesetzesprüfung VfGH | `VfGH 23.6.2023, G 234/2022` |
| Verordnungsprüfung VfGH | `VfGH 12.10.2023, V 56/2023` |
| Beschwerdeerkenntnis VfGH (modern) | `VfGH 5.3.2024, E 1234/2023` |
| Revision VwGH (modern) | `VwGH 15.2.2023, Ra 2022/01/0042` |
| Beschwerde VwGH (vor 2014) | `VwGH 4.5.2010, 2009/05/0123` |

## Qualitätsanker

- **Keine Verwechslung VfGH/VwGH.** Verfassungsmäßigkeit einer Norm → VfGH; Verfahrensfehler oder einfachgesetzliche Auslegung → VwGH.
- **Kein erfundenes Aktenzeichen.** Im Zweifel über RIS-Justiz oder direkt VfGH/VwGH-Website prüfen.
- **Datum prüfen.** Bei VwGH-`Ra` muss Jahr im Az mit Tagungsdatum konsistent sein.

## Anschluss-Skills

- Bei OGH-Verweis: `ogh-judikatur`.
- Bei RS-Satz: `ris-justiz-rs-saetze`.
- Vor Versand: `pflichtcheckliste-vor-ausgabe`.
