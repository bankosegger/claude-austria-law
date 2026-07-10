---
name: einstieg-routing
description: "Einstieg in die Methodenlehre nach §§ 6, 7 ABGB: erkennt, ob eine Auslegungs-, Lücken-, Präzedenz- oder Normhierarchiefrage vorliegt; leitet zum passenden Spezial-Skill."
---

# Einstieg und Routing — Methodenlehre

## Einsatzlage

Dieser Skill ist der Einstieg in jede methodisch geprägte Falllösung. Er ordnet die Methodenfrage und leitet zum passenden Spezial-Skill.

## Fachlandkarte dieses Plugins

- `auslegungsmethoden` — § 6 ABGB-Kanon: wörtlich, systematisch, teleologisch, historisch.
- `analogie-und-umkehrschluss` — § 7 ABGB: Einzel- und Gesamtanalogie, Umkehrschluss, teleologische Reduktion.
- `anspruchsaufbau` — Standardstruktur: Anspruchsgrundlage → Tatbestand → Rechtsfolge → Einreden.
- `ogh-judikatur-und-praezedenz` — faktische Bindungswirkung, verstärkter Senat, RS-Sätze.
- `stufenbau-und-unionsrecht` — Normhierarchie, Vorrang des Unionsrechts.

## Regelungs- und Quellenanker

- §§ 6, 7 ABGB — Auslegung und Lückenfüllung.
- B-VG — Stufenbau und Verfassungsgerichtsbarkeit.
- Art 267 AEUV — Vorabentscheidungsverfahren.
- § 8 OGHG — verstärkter Senat des OGH.

Vertiefung in [`references/methodik-abgb.md`](../../references/methodik-abgb.md) und [`references/stufenbau-rechtsordnung.md`](../../references/stufenbau-rechtsordnung.md).

## Arbeitsweg

### Schritt 1 — Typus der Methodenfrage erkennen

| Symptom im Sachverhalt | Methodenfrage |
| --- | --- |
| Wortlaut mehrdeutig | Auslegung → `auslegungsmethoden` |
| Sachverhalt nicht direkt erfasst | Lücke → `analogie-und-umkehrschluss` |
| Norm würde absurdes Ergebnis liefern | Teleologische Reduktion → `analogie-und-umkehrschluss` |
| Vorhandene Judikatur, Bindung? | Präjudiz → `ogh-judikatur-und-praezedenz` |
| Norm könnte verfassungs-/unionsrechtswidrig sein | Hierarchie → `stufenbau-und-unionsrecht` |
| Falllösung im Mandat | Anspruchsaufbau → `anspruchsaufbau` |

### Schritt 2 — Methodenreihenfolge respektieren

- Auslegung **vor** Lückenfüllung.
- Verfassungs- und unionsrechtskonforme Auslegung **vor** Verfassungs- oder Vorabentscheidungsfrage.
- Konkrete Norm **vor** Generalklausel.

### Schritt 3 — Belegdisziplin

- Methodenargumente sind transparent zu machen: »Die teleologische Auslegung des § X spricht für …«.
- Bei Berufung auf historisches Material: konkrete ErläutRV (BlgNR, GP, Seite) angeben.
- Bei Berufung auf Judikatur: Aktenzeichen + Datum (siehe `zitierweise-oesterreichisches-recht`).
- Bei methodischen Aussagen aus Lehrbüchern: Autor, Werk, Auflage, Stelle.

### Schritt 4 — Spezial-Skill aufrufen

Nach Identifikation der Methodenfrage den passenden Skill aus der Fachlandkarte aufrufen und kurz begründen, warum (»Hier liegt eine planwidrige Lücke vor; deshalb `analogie-und-umkehrschluss`.«).

## Qualitätsanker

- **Keine Methodenkurzschlüsse.** Eine teleologische Reduktion braucht Begründung, warum der Wortlaut zu weit greift.
- **Keine erfundenen Materialien.** ErläutRV-Verweise nur, wenn die Stelle in der jeweiligen BlgNR konkret existiert (über RIS oder Parlaments-Website prüfbar).
- **Keine »Methodenstapel« ohne Auswahl.** Wenn mehrere Methoden in dieselbe Richtung weisen: kurz benennen; wenn sie divergieren: begründen, welche überwiegt.

## Anschluss-Skills

- Bei Quellenfragen: `zitierweise-oesterreichisches-recht/skills/einstieg-routing`.
- Bei spezifischen Rechtsgebieten: jeweiliges Fachplugin (z. B. `arbeitsrecht-at`, `datenschutzrecht-at`).
