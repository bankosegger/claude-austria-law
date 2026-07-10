# Claude für österreichisches Recht / Austrian Legal Skills

> **Experimentelle Skill-Sammlung für österreichisches Recht** — derzeit Methodenlehre, Zitierweise, Arbeitsrecht und Datenschutzrecht; weitere Rechtsgebiete (Gesellschaftsrecht, Insolvenzrecht, Zivilprozessrecht u. a.) sind als Ausbaustufen geplant. Skills, Sub-Agenten und Workflows als Anregung für die Arbeit in Kanzleien, Rechtsabteilungen und bei Beratern. **Keine Rechtsberatung. Alle Angaben ohne Gewähr.** Mandatsgeheimnis (§ 9 RAO, § 121 StGB), DSGVO/DSG, US-Transfer, KI-VO und sonstige Compliance bleiben in der Eigenverantwortung der Nutzer.

## Über dieses Repository

Dieses Repository ist eine **experimentelle Plugin- und Skill-Sammlung für österreichisches Recht**. Es zeigt, wie sich Plugins und Skills für die in Österreich übliche Methodik strukturieren lassen — am ABGB, an den Methodenregeln der §§ 6, 7 ABGB, an der Judikatur des OGH, VfGH und VwGH, an Bundesgesetzblattzitierung und an der österreichischen Aktenzeichenpraxis.

Die Inhalte dienen ausschließlich als **Anregung für eigene Kanzlei- oder Inhouse-Plugins und -Skills**. Jeder Nutzer passt sie an die eigenen Mandate, Branchen, Tools und Compliance-Vorgaben an. Das Repository ist eigenständig entwickelt und keine Übersetzung einer ausländischen Sammlung — es orientiert sich am Format der freien `claude-for-legal`-Idee, ist aber inhaltlich von Grund auf am österreichischen Recht ausgerichtet.

### Bitte mit-testen und Feedback geben

- Nutzt die Skills im **Testbetrieb** (ohne echte Mandatsdaten) und schaut, wie sie zu eurer Praxis passen.
- Gebt **Rückmeldungen**, eröffnet **Issues**, schickt **Pull Requests** mit Korrekturen, neuen Rechtsgebieten oder eigenen Workflows.
- Passt Zitierweise, Quellenzugänge, interne Vorgaben zu Berufsrecht, Datenschutz, KI-Governance und Verschwiegenheit an euer Setup an.

## KEINE Aussage zu Berufsrecht, Datenschutz, KI-VO oder Beschlagnahmeverboten

**Vor jedem produktiven Einsatz lesen.** Dieses Repository trifft **keine Aussage** darüber, ob der Einsatz dieser Skills in einer konkreten Praxisumgebung berufs-, datenschutz- oder KI-rechtlich zulässig ist. Folgende Fragen muss **jeder Nutzer in Eigenverantwortung** prüfen — das Repository, der Autor und alle Mitwirkenden übernehmen keinerlei Haftung:

- **Anwaltliche Verschwiegenheit — § 9 RAO.** Es wird nicht geprüft, ob ein konkreter Einsatz mit der Verschwiegenheitspflicht des § 9 Abs 2 RAO (Rechtsanwaltsordnung, RGBl 96/1868 idgF) und den Richtlinien der ÖRAK (insbesondere der RL-BA 2015) vereinbar ist. Gleiches gilt für die Sondervorschriften zu IT-Auslagerung und Auftragsverarbeitern, soweit sie sich im jeweils geltenden Berufsrecht finden.
- **Strafrechtliches Berufsgeheimnis — §§ 121, 122 StGB.** Die Skills sagen nichts darüber aus, ob ein konkreter Einsatz mit dem strafbewehrten Schutz nach § 121 StGB (Verletzung von Berufsgeheimnissen) und § 122 StGB (Verletzung eines Geschäfts- oder Betriebsgeheimnisses) vereinbar ist.
- **Aussageverweigerung und Beschlagnahmeverbote — §§ 112, 157 Abs 1 Z 2 StPO.** Es wird **nicht** geprüft, ob der Schutz nach § 157 Abs 1 Z 2 StPO (Aussageverweigerungsrecht der zur Verschwiegenheit verpflichteten Berufsgruppen, ua Rechtsanwälte und Verteidiger) und der Schutz schriftlicher Aufzeichnungen nach § 112 StPO im konkreten Setup tatsächlich gewahrt sind.
- **Berufsrecht freier Berufe.** Gleichermaßen ungeprüft bleiben die jeweiligen berufsrechtlichen Sondervorschriften für Notare (NO), Steuerberater/Wirtschaftsprüfer (WTBG 2017), Patentanwälte (PAG), Ärzte (ÄrzteG 1998, insb § 54 — Verschwiegenheit) und sonstige zur Verschwiegenheit verpflichtete Berufe.
- **Datenschutz — DSGVO + DSG.** Es wird **nicht** beurteilt, ob die Verarbeitung personenbezogener Daten mit der DSGVO (Verordnung (EU) 2016/679) und dem österreichischen DSG (BGBl I 165/1999 idF BGBl I 14/2019) vereinbar ist — insbesondere nicht, ob eine taugliche **Rechtsgrundlage** (Art 6, 9 DSGVO; §§ 7 ff DSG für staatliche Bereiche), ein **Auftragsverarbeitungsvertrag** nach Art 28 DSGVO, eine **Datenschutz-Folgenabschätzung** nach Art 35 DSGVO oder eine ordnungsgemäße **Informationserteilung** nach Art 13, 14 DSGVO vorliegt. Zuständige Aufsichtsbehörde ist die **Datenschutzbehörde (DSB)**; Rechtsmittel gehen ans **Bundesverwaltungsgericht (BVwG)** und in weiterer Folge an VwGH/VfGH.
- **KI-Verordnung (VO (EU) 2024/1689).** Es wird **nicht** entschieden, ob der Einsatz unter eine Hochrisiko-Kategorie nach Art 6 iVm Anhang III KI-VO fällt (etwa Zugang zur Justiz, Strafverfolgung, demokratische Prozesse), ob Transparenzpflichten nach Art 50 KI-VO greifen, ob es sich um ein General-Purpose-AI-Modell nach Art 51 ff KI-VO handelt und welche Pflichten als **Betreiber** nach Art 26 KI-VO zu erfüllen sind.
- **Drittlandtransfer, US-Zugriffe.** Es wird nicht geprüft, ob Eingabedaten und Modellantworten gegen Zugriffe nach US **Cloud Act**, **FISA § 702**, **CLOUD Act warrants**, **PATRIOT Act § 215** oder sonstige extraterritoriale Zugriffsbefugnisse hinreichend geschützt sind. Übermittlung in Drittländer richtet sich nach Kapitel V DSGVO (Angemessenheitsbeschluss, Standardvertragsklauseln, Transfer Impact Assessment).
- **Zugang, Auftragsverarbeitung, Hosting.** Wie der API-Zugang beschafft wird (Anthropic direkt, AWS Bedrock, Google Vertex, ein anderer Anbieter), ob mit dem Anbieter ein wirksamer AVV nach Art 28 DSGVO geschlossen wird, ob ein berufsrechtskonformer Cloud-Vertrag vorliegt und ob die Anforderungen an die Verschwiegenheit (Mandatsgeheimnis-Header, Datenflusskontrolle, Subunternehmer) eingehalten sind, bleibt vollständig in der **Eigenverantwortung des Nutzers**.

> **Die Skills sind generalisierte Beispiele.** Eine Frist kann sich geändert haben, eine zitierte Norm idgF anders lauten, ein Spezialist im Rechtsgebiet einzelne Punkte anders bewerten. Bitte forken, anpassen, Pull Request oder Issue — das Repository soll genau so weiterentwickelt werden.

## Was ist drin?

> **Querschnitts-Plugins zum Mitladen.** Zwei Plugins liefern die methodische Grundlage, die in den anderen Plugins vorausgesetzt wird:
>
> - [`methodenlehre-abgb`](./methodenlehre-abgb) — Methodenlehre nach §§ 6, 7 ABGB, Auslegung (wörtlich, systematisch, teleologisch, historisch), Analogie und Umkehrschluss, Stufenbau der Rechtsordnung (B-VG), Bedeutung der OGH-Judikatur und der RIS-Justiz-RS-Sätze.
> - [`zitierweise-oesterreichisches-recht`](./zitierweise-oesterreichisches-recht) — Hauszitierweise für ABGB, Bundesgesetzblatt (BGBl I/II/III), OGH/VfGH/VwGH-Aktenzeichen, RIS-Justiz-RS-Nummern. Sperre gegen Blindzitate ohne frei prüfbare Quelle.

### Was da ist — Plugin-Übersicht

Alle vier in [`marketplace.json`](./.claude-plugin/marketplace.json) geführten Plugins sind **vollständig**: `plugin.json`, README, Referenzdateien und sämtliche im jeweiligen Plugin-README gelisteten Skills existieren.

| Plugin | Skills | Beschreibung |
| --- | --- | --- |
| [`methodenlehre-abgb`](./methodenlehre-abgb) | 6 | Methodenlehre nach §§ 6, 7 ABGB; Auslegung, Analogie, Anspruchsaufbau, Stufenbau der Rechtsordnung; OGH-Judikatur und RS-Sätze. Querschnitt — wird von den Fachplugins vorausgesetzt. |
| [`zitierweise-oesterreichisches-recht`](./zitierweise-oesterreichisches-recht) | 8 | Österreichische juristische Hauszitierweise: BGBl, OGH/VfGH/VwGH-Aktenzeichen, RIS-Justiz, RS-Nummern, Literatur; Pflichtcheckliste vor Ausgabe. Keine Blindzitate. Querschnitt. |
| [`arbeitsrecht-at`](./arbeitsrecht-at) | 8 | Kernstrecke des Individualarbeitsrechts: Vertragstypen (§ 1151 ABGB), harmonisierte Kündigungsfristen, allgemeiner (§ 105 ArbVG) und besonderer Kündigungs-/Entlassungsschutz, Entlassung/Austritt, Arbeitszeit/Urlaub, Abfertigung alt/neu. |
| [`datenschutzrecht-at`](./datenschutzrecht-at) | 8 | DSGVO + DSG-Kernstrecke: Rechtsgrundlagen (Art 6/9), Betroffenenrechte, Auftragsverarbeitung (Art 26–28), DSFA (Art 35), Data Breach (Art 33/34), Verfahren vor der DSB samt Instanzenzug, Drittlandtransfer (Kapitel V). |

### Was fehlt — Fortschritt und offene Punkte

Das Repository ist eine kuratierte Methoden- und Routing-Schicht für einzelne Beratungssituationen — **kein Abbild des österreichischen Rechts**. Der verbindliche Normtext steht immer im RIS (`ris.bka.gv.at`), nie hier.

Plugins mit Status »Gerüst« existieren als Ordnerstruktur mit README und Skill-Stubs (`[TODO]`-Marker), sind aber **bewusst noch nicht in `marketplace.json`** gelistet — Aufnahme erst, wenn die Skills inhaltlich tragen.

| Bereich | Status | Noch zu tun |
| --- | --- | --- |
| `methodenlehre-abgb` | vollständig (6 Skills, 2 Referenzen) | Pflege bei Rechtsprechungs-/Gesetzesänderungen. |
| `zitierweise-oesterreichisches-recht` | vollständig (8 Skills, 2 Referenzen) | Pflege; ggf Skill für EuGH/EGMR-Zitierweise ergänzen. |
| `arbeitsrecht-at` | Kernthemen fertig (8 Skills, 2 Referenzen) | Eigene Skills für: Gleichbehandlung (GlBG), Betriebsverfassung (§§ 33 ff ArbVG), Betriebsübergang (§ 3 AVRAG), Entgeltfortzahlung (EFZG / § 8 AngG), Arbeitskräfteüberlassung (AÜG), Entsendung (LSD-BG), Insolvenz-Entgelt (IESG), Lehrlingsrecht (BAG), Kollektivvertragsrecht im Detail. |
| `datenschutzrecht-at` | Kernregime fertig (8 Skills, 2 Referenzen) | Eigene Skills für: 3. Hauptstück DSG (Strafverfolgung), Beschäftigtendatenschutz (§ 96 ArbVG-Schnittstelle), TKG 2021 (Cookies, Direktwerbung), Schadenersatz nach Art 82 DSGVO, sektorales Datenschutzrecht (Gesundheit, Finanz). |
| Qualitätssicherung Bestand | teilweise erledigt (Juli 2026) | Erledigt: §§ 1159a–1159c ABGB sind aufgehoben, Fristen stehen konsolidiert in § 1159 ABGB; Inkrafttreten der Harmonisierung auf 1.10.2021 korrigiert. Offen: Wartefristen § 8 BEinstG; Mindesteinzahlungszeiten § 14 BMSVG; BGBl-II-Fundstellen der DSFA-V/DSFA-AV; Stand der Angemessenheitsbeschlüsse (Kapitel V DSGVO). |
| [`gesellschaftsrecht-at`](./gesellschaftsrecht-at) | Gerüst (6 Skill-Stubs) | Skills inhaltlich schreiben (GmbHG, AktG, UGB, FlexKapGG, FBG, EU-UmgrG), Referenz befüllen; danach Aufnahme in `marketplace.json`. |
| [`insolvenzrecht-at`](./insolvenzrecht-at) | Gerüst (6 Skill-Stubs) | Skills inhaltlich schreiben (IO, ReO, IESG, URG), Referenz befüllen; danach Aufnahme in `marketplace.json`. |
| [`zivilprozessrecht-at`](./zivilprozessrecht-at) | Gerüst (6 Skill-Stubs) | Skills inhaltlich schreiben (JN, ZPO, EO, AußStrG), ASGG-Material aus `arbeitsrecht-at` andocken, Referenz befüllen; danach Aufnahme in `marketplace.json`. |
| [`verwaltungsrecht-at`](./verwaltungsrecht-at) | Gerüst (6 Skill-Stubs) | Skills inhaltlich schreiben (AVG, VwGVG, VStG, VwGG, VfGG), Referenz befüllen; danach Aufnahme in `marketplace.json`. |
| Weitere Ausbaustufen | nicht begonnen | Strafrecht, Verfassungsrecht, Steuerrecht, gewerblicher Rechtsschutz, IT-Recht, Sozialversicherungsrecht, Mietrecht (MRG), Konsumentenschutz (KSchG), Familien- und Erbrecht, Landesrecht der neun Bundesländer. |

Pull Requests zu jedem dieser Punkte sind willkommen — vorher bitte [`CLAUDE.md`](./CLAUDE.md) (Hausstil, Quellenhygiene) lesen.

## Quickstart

```text
# Marketplace im Claude-Code-Prompt hinzufügen
/plugin marketplace add bankosegger/claude-austria-law
/plugin install <plugin-name>@austrian-legal-skills
```

Alternativ: einzelne `SKILL.md`-Dateien aus dem jeweiligen `skills/`-Ordner kopieren und in einem beliebigen Chatbot (Claude, ChatGPT, Gemini, Mistral, Le Chat, Perplexity) als Prompt-Baustein verwenden. Die Skills sind so geschrieben, dass sie auch ohne Claude-Code-Installation tragen.

## Eigene API, Gateway oder Zwischenanbieter (Stand 2026)

Berufsgeheimnisträger müssen vor jedem produktiven Einsatz selbst prüfen, ob die konkrete Anbieter-, Hosting- und Datenflusskonstellation mit § 9 RAO, § 121 StGB, Art 28 DSGVO, Kapitel V DSGVO, TOMs, Löschkonzept, Audit-Rechten, Subunternehmern, Datenresidenz und vertraglicher Verschwiegenheit vereinbar ist. Dieses Repository bestätigt keinen Anbieter und ersetzt keine berufsrechtliche oder datenschutzrechtliche Prüfung.

Technisch gibt es zwei saubere Wege:

### Weg A — Claude Code im Terminal

```sh
export ANTHROPIC_BASE_URL="https://api.<anbieter>.at/anthropic"
export ANTHROPIC_AUTH_TOKEN="<dein-schluessel>"
unset ANTHROPIC_API_KEY
```

Base URL, Auth-Schema und Modellname exakt aus der Anbieterdokumentation übernehmen. Mit Dummy-Daten testen; die Provider-Logs müssen den Aufruf zeigen, im falschen Anbieter-/Anthropic-Konto darf er nicht auftauchen.

### Weg B — Claude Desktop / GUI

Wenn die installierte Oberfläche einen eigenen Gateway-Dialog hat: Base URL, Auth-Schema und Modellname aus der Anbieterdokumentation übernehmen, ausgehende Hosts auf die Anbieterdomain beschränken, mit Dummy-Daten testen.

### Kontrollliste vor echtem Mandatsmaterial

- Vertragliche Grundlage: AVV nach Art 28 DSGVO, TOMs, Verschwiegenheit, Unterauftragsverarbeiter, Audit-/Löschrechte.
- Datenfluss: Region, Protokollierung, Trainings-/Retention-Regeln, Support-Zugriffe.
- Technik: Base URL, Auth-Schema, Modellname, erlaubte Hosts, Provider-Logs.
- Kanzlei-Governance: KI-Richtlinie, Mandatsfreigabe, Dokumentation in der Akte.
- Test: nur Dummy-Daten, Provider-Logs geprüft, keine Schlüssel im Repo.

## Mitwirken

Pull Requests willkommen, insbesondere für:

- Korrekturen an Norm- oder Judikaturverweisen (mit RIS-Link oder Aktenzeichen-Beleg).
- Aktualisierung bei Gesetzesänderungen (neue BGBl-Fundstelle angeben).
- Neue Plugins für noch nicht abgedeckte Rechtsgebiete.
- Schärfung der Compliance-Hinweise (Berufsrecht, DSGVO, KI-VO).

Vor PRs bitte die Hinweise in [`CLAUDE.md`](./CLAUDE.md) zur Hausstil-Disziplin und Quellenhygiene lesen.

## Lizenz

Doppelter Lizenzhinweis: [Apache-2.0](./LICENSE-APACHE) **oder** [MIT](./LICENSE-MIT) — auswählen, was zum eigenen Einsatz passt.

## Disclaimer

Dieses Repository ist eine technische Spielwiese. Es ersetzt keine anwaltliche Beratung, keine berufsrechtliche Prüfung und keine Datenschutz-Folgenabschätzung. Wer Mandatsdaten verarbeitet, muss Mandatsgeheimnis, Berufsrecht, DSGVO, DSG, KI-VO und alle einschlägigen Sondervorschriften eigenverantwortlich einhalten.
