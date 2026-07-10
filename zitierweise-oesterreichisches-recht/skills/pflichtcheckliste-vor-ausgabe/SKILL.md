---
name: pflichtcheckliste-vor-ausgabe
description: "Letzte Kontrolle vor Versand eines Schriftsatzes oder Memos: jede Fußnote belegt? Aktenzeichen plausibel? RS-Satz existiert? Norm in geltender Fassung? Berufsrechts- und Datenschutzhinweise?"
---

# Pflichtcheckliste vor Ausgabe

## Einsatzlage

Aktiv vor jedem Versand eines Schriftsatzes, Memos, Gutachtens, Mandantenbriefs oder einer Stellungnahme — gleich ob die Belegangaben aus Eigenarbeit, Mandantenakte oder KI-gestützter Recherche stammen.

## Regelungs- und Quellenanker

- Berufsrechtliche Sorgfalt: § 9 Abs 1 RAO (gewissenhafte Vertretung); RL-BA 2015 der ÖRAK.
- Bei Schriftsätzen an Gerichte: § 12 RAO (Erfordernis korrekter Bezeichnung); ZPO/StPO/AVG/VwGVG je nach Verfahren.
- Bei Mandantenkommunikation: Verschwiegenheit (§ 9 Abs 2 RAO), § 121 StGB; DSGVO + DSG bei Übermittlung personenbezogener Daten.

## Arbeitsweg

### Block A — Belegcheck

- [ ] Jede behauptete Norm ist nach `normzitierung-bundesgesetze` formatiert (kein Punkt nach Abs/Z/lit).
- [ ] Jede BGBl-Fundstelle ist nach `bgbl-fundstellen` korrekt (richtiger Teil I/II/III/RGBl/StGBl, idF angegeben falls relevant).
- [ ] Jedes OGH-Aktenzeichen ist nach `ogh-judikatur` zitiert (Senat, Datum, Az, Prüfziffer).
- [ ] Jedes VfGH/VwGH-Aktenzeichen ist nach `vfgh-vwgh-judikatur` korrekt (Ra-Format des VwGH bei Daten ab 2014).
- [ ] Jeder RS-Satz ist nach `ris-justiz-rs-saetze` zitiert (sechsstellige Nummer, ggf T-Marker).
- [ ] Jede Literaturstelle hat Autor, Werk, Auflage, Jahr, Pinpoint.

### Block B — Plausibilitätscheck

- [ ] Jedes Aktenzeichen wurde über RIS-Justiz / VfGH-Website / VwGH-Website / EUR-Lex / hudoc geprüft.
- [ ] Jeder RS-Satz existiert und passt im Wortlaut zur behaupteten Aussage.
- [ ] Jede zitierte Norm ist in der angegebenen Fassung in Kraft (RIS: »in Geltung seit«).
- [ ] Bei Kommentarstellen: die Auflage existiert; die Randzahl liegt im angegebenen Paragrafen.
- [ ] Keine vagen Quellenangaben (»vgl OGH«, »stRsp«) ohne Konkretbeleg.

### Block C — Berufsrecht und Datenschutz

- [ ] Wenn personenbezogene Daten zitiert werden: Rechtsgrundlage nach Art 6, 9 DSGVO geprüft.
- [ ] Mandantendaten sind anonymisiert oder pseudonymisiert, wo nicht zwingend erforderlich.
- [ ] Bei KI-gestützter Erstellung: Eintrag in der KI-Nutzungsdokumentation der Kanzlei.
- [ ] Verschwiegenheit nach § 9 Abs 2 RAO durchgängig gewahrt (keine Mandatsgeheimnisse in Beispielen, in Modelltrainingsdaten oder in Logs).

### Block D — Verfahrensrechtliche Form

- [ ] Bezeichnung des Verfahrens, Aktenzeichen, Gericht/Behörde korrekt.
- [ ] Fristen geprüft (Verfahrensfrist, materielle Frist) — nicht aus Modellwissen finalisieren, sondern am konkreten Verfahren prüfen.
- [ ] Schriftform / elektronische Eingabe (ERV) nach den jeweiligen Vorgaben.
- [ ] Unterschrift / qualifizierte elektronische Signatur, wo erforderlich.

### Block E — Anti-Halluzinations-Check

- [ ] Kein einziges Aktenzeichen aus dem Modellwissen ohne Prüfung in RIS.
- [ ] Keine erfundene RS-Nummer.
- [ ] Keine erfundene BGBl-Nummer.
- [ ] Keine Behauptung über stRsp ohne konkreten Beleg.
- [ ] Bei Unsicherheit: lieber generisch (»nach hL/stRsp«) als ein falsches Konkretzitat.

## Qualitätsanker

- Diese Checkliste wird vor jedem Versand durchgegangen. Häkchen ist nicht performativ — es bestätigt eine tatsächlich durchgeführte Prüfung.
- Bei kursorischer KI-Vorbereitung: doppelt prüfen, alle Quellen separat verifizieren.
- Bei Streit über die Quelle: ein Belegfehler kann berufsrechtliche und prozessuale Konsequenzen haben (Wahrheits- und Vollständigkeitspflicht, § 178 ZPO; § 9 RAO).

## Anschluss-Skills

- Bei Korrekturbedarf: zurück in den jeweiligen Form-Skill (`normzitierung-bundesgesetze`, `ogh-judikatur`, etc.).
- Methodische Fragen: `methodenlehre-abgb` (Querschnitts-Plugin).
