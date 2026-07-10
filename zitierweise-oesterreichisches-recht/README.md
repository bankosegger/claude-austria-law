# zitierweise-oesterreichisches-recht

Österreichische juristische **Hauszitierweise**: ABGB, Bundesgesetzblatt (BGBl I/II/III), OGH/VfGH/VwGH-Aktenzeichen, RIS-Justiz, RS-Nummern, Literatur und Kommentare. Mit eingebauter Sperre gegen Blindzitate.

## Wofür dieses Plugin?

Wer Schriftsätze, Memos oder Gutachten in Österreich verfasst, braucht eine saubere Zitierweise mit:

- Norm: konkrete Paragrafenangabe nach österreichischer Konvention (kein Punkt nach »Abs«, »Z« für Ziffer).
- Bundesgesetzblatt-Fundstelle: korrekt zwischen BGBl I (Bundesgesetze), BGBl II (Verordnungen), BGBl III (Staatsverträge), RGBl (Stammgesetze vor 1918) und StGBl (1918–1920) unterscheiden.
- Judikatur: Gericht, Datum, Aktenzeichen, frei prüfbare Quelle (RIS-Justiz, VfGH-Website, VwGH-Website).
- RS-Satz: bei OGH-Standpunkten zusätzlich die RIS-Justiz-RS-Nummer.
- Literatur: nur mit konkretem Beleg (Autor, Werk, Auflage, Jahr, Rz/Seite).

## Was dieses Plugin **nicht** macht

- Es generiert **keine** Aktenzeichen oder RS-Nummern, die nicht im Sachverhalt belegt sind.
- Es zitiert **keine** Entscheidung, die nicht über RIS-Justiz frei nachprüfbar ist (oder mit konkretem RDB-/Manz-Treffer belegt wird).
- Es übersetzt keine ausländischen Zitate »über den Daumen« in österreichisches Format.

## Skills

| Skill | Funktion |
| --- | --- |
| [`einstieg-routing`](./skills/einstieg-routing) | Triage: welcher Zitierfall liegt vor (Norm, Judikatur, Literatur, RS-Satz)? |
| [`normzitierung-bundesgesetze`](./skills/normzitierung-bundesgesetze) | Form: `§ 879 ABGB`, `§ 9 Abs 2 RAO`, `Art 28 DSGVO`. |
| [`bgbl-fundstellen`](./skills/bgbl-fundstellen) | BGBl I/II/III, RGBl, StGBl: korrekt einordnen und zitieren. |
| [`ogh-judikatur`](./skills/ogh-judikatur) | OGH-Aktenzeichen, Senate (»Ob« zivil, »Os« strafrechtlich), Datum, RIS-Link. |
| [`vfgh-vwgh-judikatur`](./skills/vfgh-vwgh-judikatur) | VfGH (G/V/E-Verfahren), VwGH (Ra seit 2014; Zl davor). |
| [`ris-justiz-rs-saetze`](./skills/ris-justiz-rs-saetze) | RS-Sätze (RS0123456) — was sie sind, wann sie helfen, wann nicht. |
| [`literatur-und-kommentare`](./skills/literatur-und-kommentare) | Kommentar, Lehrbuch, Aufsatz: nur mit konkretem Beleg. |
| [`pflichtcheckliste-vor-ausgabe`](./skills/pflichtcheckliste-vor-ausgabe) | Letzte Kontrolle vor Versand: jede Fußnote belegt? Aktenzeichen plausibel? RS-Satz existiert? |

## Referenzen

- [`references/zitierweise.md`](./references/zitierweise.md) — Konkrete Formvorgaben.
- [`references/quellenhygiene.md`](./references/quellenhygiene.md) — Was darf zitiert werden, was nicht.
