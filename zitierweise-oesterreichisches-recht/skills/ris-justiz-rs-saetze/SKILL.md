---
name: ris-justiz-rs-saetze
description: "RIS-Justiz-Rechtssätze (RS0123456) zitieren: was ein RS-Satz ist, wann er trägt, wann er nicht trägt, Verbindung mit Trägerentscheidung. Sperre gegen erfundene RS-Nummern."
---

# RIS-Justiz Rechtssätze (RS-Sätze)

## Einsatzlage

Aktiv, wenn ein RS-Satz zitiert werden soll — typischerweise zur Belegung einer ständigen Rechtsprechungslinie des OGH oder zur Verdichtung mehrerer Entscheidungen auf einen abstrakt-generellen Satz.

## Regelungs- und Quellenanker

- RIS-Justiz ist das Sachregister der Rechtssprechung im Rechtsinformationssystem des Bundes (`ris.bka.gv.at/Jus`).
- RS-Sätze werden vom Evidenzbüro des OGH (und parallel von VfGH/VwGH) gepflegt und sind **vom Gericht formulierte** abstrakte Aussagen.
- Sechsstellige Nummer: `RS0000001` bis aktuell sechsstellig fortlaufend.

## Arbeitsweg

### Was ist ein RS-Satz?

- Eine vom OGH (bzw. VfGH/VwGH) selbst formulierte, abstrakt-generelle Rechtsaussage.
- Wird aus einer oder mehreren Entscheidungen destilliert.
- Pro RS-Satz gibt es eine Liste der Trägerentscheidungen (in RIS sichtbar).
- RS-Sätze werden gelegentlich geändert oder gestrichen, wenn die Judikatur sich entwickelt.

### Form

- Minimal: `RIS-Justiz RS0123456`.
- Mit Trägerentscheidung: `OGH 12.3.2024, 1 Ob 42/24x; RIS-Justiz RS0123456`.
- Pinpoint (bei mehrgliedrigen RS-Sätzen): `RIS-Justiz RS0123456 [T5]` (Teilziffer 5).
- T-Marker (`T1`, `T2`, …) kennzeichnen Erweiterungen oder Differenzierungen im RS-Satz.

### Wann RS-Satz allein, wann mit Entscheidung?

- **Allein:** Wenn die Linie unstreitig ist und keine konkrete Trägerentscheidung im Vordergrund steht.
- **Mit Entscheidung:** Wenn auf eine bestimmte Entscheidung Bezug genommen wird (zB jüngste, einschlägige Fortbildung).
- **Pinpoint Pflicht:** Bei vielen Trägerentscheidungen die markante mitführen.

### Plausibilitätsprüfung

1. **Nummer existiert?** RIS-Justiz öffnen → Suche nach `RS0123456`.
2. **Wortlaut passt?** Der RS-Satz im RIS muss zur behaupteten Aussage passen.
3. **Aktuell?** RS-Sätze tragen einen Geltungsbereich; geänderte Sätze sind in RIS gekennzeichnet.
4. **T-Marker bewusst verwenden.** `[T5]` heißt: die fünfte Teilziffer des Satzes — nur zitieren, wenn diese die Aussage stützt.

## Beispielcluster (kein konkreter Inhalt)

Wenn im Sachverhalt steht: »Der OGH judiziert in stRsp, dass …« — dann **muss** ein konkreter RS-Satz oder eine konkrete Trägerentscheidung folgen. Generische Hinweise auf »ständige Rechtsprechung« ohne Beleg sind nicht zitierfähig.

| Aussage des Sachverhalts | Mindestbeleg |
| --- | --- |
| »OGH-stRsp zur Sittenwidrigkeit nach § 879 ABGB« | RS-Satz **oder** Leitentscheidung mit Az |
| »OGH bejaht Schutzpflichten aus dem Vertrag« | RS-Satz mit Trägerentscheidung |
| »OGH hat dies abgelehnt« | konkrete Entscheidung mit Az + Datum |

## Qualitätsanker

- **Niemals eine RS-Nummer erfinden.** Eine erfundene `RS0XXXXXX` führt sofort zum Auffinden des Fehlers in RIS.
- **Wortlaut nicht paraphrasieren ohne Hinweis.** Wenn der RS-Satz wörtlich zitiert wird, in Anführungszeichen; wenn paraphrasiert, ohne Anführungszeichen, aber mit Verweis.
- **T-Marker nicht erfinden.** Wenn die Teilziffer nicht zur Aussage passt, lieber den Hauptsatz zitieren.

## Wenn kein RS-Satz existiert

- Manche jüngere Linien sind noch nicht in einen RS-Satz übersetzt.
- Dann: konkrete Trägerentscheidung mit Pinpoint zitieren; **kein** »RS-äquivalent« erfinden.

## Anschluss-Skills

- Trägerentscheidung des OGH: `ogh-judikatur`.
- Trägerentscheidung VfGH/VwGH: `vfgh-vwgh-judikatur`.
- Vor Versand: `pflichtcheckliste-vor-ausgabe`.
