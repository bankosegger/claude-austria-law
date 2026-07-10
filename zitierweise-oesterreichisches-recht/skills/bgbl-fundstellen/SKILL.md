---
name: bgbl-fundstellen
description: "BGBl-Fundstellen für österreichische Normen: BGBl I (Bundesgesetze), BGBl II (Verordnungen), BGBl III (Staatsverträge), RGBl (vor 1918), StGBl (1918–1920); idgF und Novellenangabe."
---

# BGBl-Fundstellen

## Einsatzlage

Aktiv, wenn der Stammgesetz- oder Novellenverweis angegeben werden muss: bei Erstnennung eines Spezialgesetzes, bei Fassungsstreit, bei historischer Bezugnahme.

## Regelungs- und Quellenanker

- Bundesgesetzblattgesetz (BGBlG), BGBl I 100/2003 idgF — regelt die Veröffentlichung im Bundesgesetzblatt.
- Aufteilung in BGBl I/II/III: Bundesgesetzblattgesetz 1996, BGBl 660/1996 (in Kraft 1.1.1997).
- Frei prüfbar über RIS: `ris.bka.gv.at/Bundesrecht` und `ris.bka.gv.at/Bgbl`.

## Arbeitsweg

### Veröffentlichungsorgan bestimmen

| Norm | Veröffentlichungsorgan |
| --- | --- |
| Bundesgesetze (seit 1997) | **BGBl I** |
| Verordnungen, Kundmachungen (seit 1997) | **BGBl II** |
| Staatsverträge (seit 1997) | **BGBl III** |
| Bundesgesetz 1920–1938 und 1945–1996 | **BGBl Nr X/JJJJ** (ohne I/II/III) |
| Stammgesetz vor 1918 | **RGBl** (Reichsgesetzblatt) |
| Stammgesetz 1918–1920 sowie 1945 | **StGBl** (Staatsgesetzblatt) |
| Landesgesetze | jeweiliges **LGBl** (`LGBl NÖ X/JJJJ`) |

### Form der Fundstelle

- Modern: `BGBl I 165/1999` — **kein** Punkt nach »I«, Trennzeichen ist der Schrägstrich.
- Mit Fassung: `BGBl I 165/1999 idF BGBl I 14/2019`.
- Sammelverweis auf »in der jeweils geltenden Fassung«: `BGBl I 165/1999 idgF`.
- Pre-1997: `BGBl 100/1996` (kein römisches Kennzeichen).
- RGBl: `RGBl 96/1868` (z. B. RAO-Stammgesetz).
- StGBl: `StGBl Nr 209/1919`.

### Verlinkung in RIS

- Stammgesetze: `https://www.ris.bka.gv.at/GeltendeFassung.wxe?Abfrage=Bundesnormen&Gesetzesnummer=<id>`.
- BGBl-Einzelnummer: `https://www.ris.bka.gv.at/Dokument.wxe?Abfrage=BgblAuth&Dokumentnummer=BGBLA_<Jahr>_<Teil>_<Nr>`.
- Wenn ein RIS-Link angegeben wird, muss er funktionieren — vor Versand prüfen.

## Beispiele

| Norm | Form |
| --- | --- |
| ABGB (Stammgesetz 1811) | Üblich nur `ABGB`, idgF mehrfach novelliert; bei historischem Bezug `JGS Nr 946/1811`. |
| RAO (Stammgesetz 1868) | `RAO, RGBl 96/1868 idgF`. |
| DSG (Stammgesetz 1999) | `DSG, BGBl I 165/1999 idF BGBl I 14/2019`. |
| ArbVG (Stammgesetz 1974) | `ArbVG, BGBl 22/1974 idgF`. |
| AngG (Stammgesetz 1921) | `AngG, BGBl Nr 292/1921 idgF`. |
| Insolvenzordnung (IO, Neufassung 2010) | `IO, RGBl 337/1914 idF BGBl I 29/2010` (IRÄG 2010 als Umbenennung der KO). |
| KI-VO (EU) | `Verordnung (EU) 2024/1689` — keine BGBl-Veröffentlichung; EU-Verordnungen gelten unmittelbar. |

## Qualitätsanker

- Vor Übernahme einer BGBl-Fundstelle in RIS prüfen: existiert die Nummer im jeweiligen Jahrgang?
- Bei `idF` immer die **konkrete** Novellen-Fundstelle angeben; nur bei generischer Bezugnahme auf den aktuellen Stand `idgF`.
- Bei Stammgesetz aus der Monarchie (RGBl): die ältere Schreibweise »JGS« (Justizgesetzsammlung) gilt für Justizgesetze bis 1849; ab 1849 RGBl.

## Anschluss-Skills

- Form innerhalb des Gesetzes: `normzitierung-bundesgesetze`.
- Bei Spezialgesetzen mit Judikatur: `ogh-judikatur` / `vfgh-vwgh-judikatur`.
