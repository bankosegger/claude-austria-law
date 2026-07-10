---
name: einstieg-routing
description: "Einstieg, Triage und Routing für die österreichische juristische Zitierweise: erkennt, ob Norm, Judikatur, RS-Satz oder Literatur zitiert werden soll, prüft Vollständigkeit der Belegangaben und leitet zum passenden Spezial-Skill."
---

# Einstieg und Routing — Zitierweise österreichisches Recht

## Einsatzlage

Dieser Skill ist der Einstieg in alle Zitierfragen. Er ordnet den Belegtyp (Norm, Judikatur, RS-Satz, Literatur), prüft die Vollständigkeit der Angaben und leitet zum passenden Spezial-Skill.

## Fachlandkarte dieses Plugins

- `normzitierung-bundesgesetze` — Form für ABGB, Bundesgesetze, EU-Verordnungen.
- `bgbl-fundstellen` — BGBl I/II/III, RGBl, StGBl einordnen.
- `ogh-judikatur` — Aktenzeichen, Senate, Datum für den OGH.
- `vfgh-vwgh-judikatur` — Verfassungs- und Verwaltungsgerichtshof.
- `ris-justiz-rs-saetze` — RS-Sätze und ihr Stellenwert.
- `literatur-und-kommentare` — Kommentar, Lehrbuch, Aufsatz.
- `pflichtcheckliste-vor-ausgabe` — letzte Kontrolle vor Versand.

## Regelungs- und Quellenanker

Dieser Skill enthält keine eigenen materiell-rechtlichen Anker. Die Quellenhygiene ergibt sich aus:

- [`references/zitierweise.md`](../../references/zitierweise.md) — Formvorgaben.
- [`references/quellenhygiene.md`](../../references/quellenhygiene.md) — was zitiert werden darf.
- Berufsrechtlich: § 9 Abs 2 RAO (Sorgfalt), RL-BA 2015 (Standesregeln der ÖRAK).

## Arbeitsweg

1. **Belegtyp erkennen:** Geht es um einen Normverweis, eine konkrete Entscheidung, einen RS-Satz, einen Kommentar oder einen Aufsatz?
2. **Vollständigkeit prüfen.** Für eine zitierfähige Belegangabe brauchen wir:
   - **Norm:** Paragraf/Artikel, Gesetz, ggf BGBl-Fundstelle und idF.
   - **Judikatur:** Gericht, Datum, Aktenzeichen, frei prüfbare Quelle.
   - **RS-Satz:** sechsstellige RS-Nummer und (optional) Trägerentscheidung.
   - **Literatur:** Autor, Werk, Auflage, Jahr, Rz/Seite.
3. **Quellenart einordnen** (siehe `references/quellenhygiene.md`):
   - Vom Nutzer eingebracht? Plausibilisieren.
   - Frei online prüfbar? RIS/curia/hudoc öffnen.
   - Lizenzierter Live-Zugriff? Bestätigung in der Akte.
4. **Bei Lücken nicht raten.** Lieber `[TODO: Az ergänzen]` oder generische Formulierung (»nach hL/stRsp«) als ein erfundenes Konkretzitat.
5. **Spezial-Skill routen:** Nach Belegtyp den passenden Skill aus der Fachlandkarte aufrufen.

## Qualitätsanker

- **Keine BeckRS-/Halluzinationszitate.** Beck-Online ist Deutschland; für AT-Quellen sind RIS, RDB, Manz, LexisNexis einschlägig.
- **Pinpoint Pflicht.** Bei Judikatur: Randzahl/Spruchpunkt; bei Kommentar: Rz; bei Aufsatz: konkrete Seite.
- **Bei Spezialfragen:** den passenden Anschluss-Skill nennen und kurz begründen, warum.
- **Vor jeder Ausgabe:** `pflichtcheckliste-vor-ausgabe` aufrufen.

## Wenn die Quelle nicht passt

Wenn der Belegtyp nicht aus den Standardkategorien stammt (z. B. Gesetzesmaterialien, Erläuterungen zur RV, Entschließungsantrag, Verwaltungsbescheid, EU-Soft-Law): Quelle exakt benennen und Aktenzeichen/Identifier mitnennen. Beispiele:

- Gesetzesmaterialien: `ErläutRV 1234 BlgNR 27. GP 5` (Erläuterungen zur Regierungsvorlage, Beilage Nr, Gesetzgebungsperiode, Seite).
- Ausschussbericht: `AB 567 BlgNR 27. GP 3`.
- Verwaltungsbescheid: Behörde, GZ, Datum.
- EU-Soft-Law: konkret bezeichnen (Leitlinien des EDSA, Mitteilung der Kommission), Fundstelle (Amtsblatt oder Webadresse).
