# AI Visibility Audit – 1KOMMA5° (1komma5.com)

**Stand:** 12.10.2026 · **Marke:** 1KOMMA5° (Hamburg, gegr. 2021, u. a. Philipp Schröder) · **Kategorie:** Photovoltaik, Speicher, Wärmepumpe, Wallbox, Energiemanagement (Heartbeat AI) und dynamischer Stromtarif (Dynamic Pulse) für Eigenheimbesitzer · **Markt:** DE (Fokus)

**Wettbewerber-Set (Annahme, bitte bestätigen):**
- **Komplettanbieter PV/WP:** Enpal, Thermondo, EKD (Energiekonzepte Deutschland), Svea Solar, enerix, Klarsolar (E.ON). Zolar ist kaum noch relevant, weil es sich aus dem Endkundengeschäft zurückgezogen hat.
- **Stromtarif und Energiemanagement:** Tibber, Octopus Energy, Rabot Energy, Ostrom, evcc, openWB, E3/DC, SMA

**Zielgruppe (Annahme):** Eigenheimbesitzer von 35 bis 65 in Deutschland, die Photovoltaik, Wärmepumpe oder E-Auto planen. Sie vergleichen Komplettanbieter mit dem regionalen Handwerk und achten auf Seriosität, Preis und Service.

> **Methodik-Hinweis (wichtig):** ChatGPT, Gemini und Perplexity konnten **nicht im Browser** abgefragt werden. Claude in Chrome gibt es in dieser Cloud-Session nicht, und die Netzwerk-Policy blockiert chatgpt.com, perplexity.ai und gemini.google.com. Stattdessen stützt sich das Audit auf drei Quellen:
> 1. **Ahrefs Brand Radar:** echte, von Ahrefs gecrawlte Antworten aus **Google AI Overviews** und **Google AI Mode** (DE). Die Module für ChatGPT, Gemini und Perplexity sind im Ahrefs-Abo **nicht freigeschaltet**.
> 2. **Ahrefs AI-Citations je Domain:** Wie oft ChatGPT, Perplexity, Gemini, AI Overviews und AI Mode in DE auf 1komma5.com bzw. auf die Wettbewerber-Domains verlinken. Das sind echte Plattformdaten, aber nur Zitate, kein Antworttext.
> 3. **Websuche mit KI-Zusammenfassung** für 8 Panel-Prompts. Das ist ein **Proxy** für ChatGPT Search und Perplexity (US-Index).
>
> Die Scorecards für ChatGPT, Gemini und Perplexity sind daher **Proxy-Werte**. Für die echte Baseline das Prompt-Panel (Abschnitt 6) lokal mit Claude in Chrome ausführen. Ablauf laut CLAUDE.md: je Prompt ein neuer Chat ohne Memory, Rohantworten in `audits/1komma5grad/<datum>/<assistent>.md` ablegen.
>
> Rohdaten dieses Laufs: [`audits/1komma5grad/2026-10-12/google-ai-overviews.md`](audits/1komma5grad/2026-10-12/google-ai-overviews.md) und [`audits/1komma5grad/2026-10-12/websearch-proxy.md`](audits/1komma5grad/2026-10-12/websearch-proxy.md)

---

## 1. Executive Summary

| Kennzahl | Wert |
|---|---|
| Mention-Rate in **unbranded** Kategorie-Prompts (AI Overviews, 32 Prompts) | **6 / 32 (19 %)** |
| davon „Welcher PV-Anbieter ist der beste?“-Prompts | **3 / 3 (100 %)**, Position 1–2 |
| davon PV- und Wärmepumpen-Ratgeber-Prompts (Kosten, Technik) | 1 / 13 (8 %) |
| davon dynamischer Stromtarif / Energiemanagement | **2 / 16 (13 %)**, jeweils Position 5 |
| Branded Prompts (AI Overviews, 11 Prompts) | 11 / 11 erkannt, Sentiment **gemischt** (2 ×+, 7 × 0, 2 × –) |
| Share of Voice AI Overviews DE (1KOMMA5° vs. Enpal, Thermondo, Zolar) | **18 %** (Enpal 46 %, Thermondo 28 %) |
| Share of Voice AI Mode DE | **18 %** (Enpal 42 %, Thermondo 32 %) |
| Zitate von 1komma5.com im Verhältnis zu enpal.de | ChatGPT **22 %** · Perplexity **22 %** · Gemini 39 % · AI Overviews 50 % · AI Mode 45 % |
| Websuche-Proxy (8 Prompts) | 4 / 8 genannt, davon 3 Prompts mit Markenbezug. Unbranded: 1 / 5 |

**Kernaussagen:**
1. **Bei der Frage „Wer ist der beste Anbieter?“ ist 1KOMMA5° stark.** In den AI Overviews steht die Marke bei „Welche Photovoltaikfirma ist die beste?“ auf **Platz 1** („oft Testsieger bei Beratungsqualität“) und bei „Welche Firma ist die beste für Photovoltaik?“ auf Platz 2 hinter Enpal. Getragen wird das von **CHIP, BILD (Energielösungen), enter.de und enwendo**.
2. **Bei Ratgeber-Fragen fehlt die Marke fast immer, und dort liegt das Volumen.** Gemeint sind Fragen wie „Was kostet eine Wärmepumpe?“, „Bester Wechselrichter“, „10 kWp mit Speicher“ oder „Heizen mit Strom vs. Gas“. Hier zitiert die KI **enpal.de** und **thermondo.de** sowie zolar.de, obwohl Zolar nicht mehr aktiv verkauft. enpal.de wird in DE-AI-Antworten **rund 2-mal so oft** zitiert wie 1komma5.com, bei ChatGPT und Perplexity **etwa 4,5-mal so oft**. Der Ratgeber-Content von 1KOMMA5° wird zu wenig als Quelle genutzt.
3. **Bei Heartbeat und Dynamic Pulse kommt das USP nicht an.** Auf „Welches Energiemanagementsystem ist das beste?“ antwortet die KI mit **evcc, openWB, E3/DC, SMA und gridX**, Heartbeat fehlt. Die Hauptquelle dieser Antwort ist ausgerechnet der **Zolar-Blog**. Bei Fragen zu dynamischen Stromtarifen dominieren Tibber, Octopus, Rabot, die Verbraucherzentrale und Finanztip. 1KOMMA5° taucht nur in Listen-Fragen mit wenig Volumen auf (Position 5).
4. **Das Bild bei Seriositäts- und Erfahrungsfragen ist gemischt, und die Quellen dafür liefern Dritte.** Diese Prompts haben über 5.000 Suchanfragen im Monat. Die AI Overviews stellen hier **Preis („oberes Segment, lokale Handwerker 10–20 % günstiger“)**, **Heartbeat-Abo (ca. 9,99 €/Monat)**, **Service über die Zentrale bzw. Subunternehmer** und **Verzögerungen bei Smart Meter und Netzanmeldung** heraus. Die Quellen sind 42watt, energie-solar-erfahrungen.de, Reddit (r/DeutschePhotovoltaik), haustechnikdialog, photovoltaikforum und Trustpilot.
5. **Die eigene Testsieger-Story wird abgewertet.** Den CHIP-Testsieg (1,3) findet die Websuche nur als **Advertorial auf 1komma5.com** und stuft ihn deshalb als Werbung ein. Unabhängige, gut auffindbare Belege für die Auszeichnung fehlen.

---

## 2. Visibility-Scorecard je Assistent

| Assistent | Datenbasis | Unbranded Mention-Rate | Ø Position (wenn genannt) | Sentiment branded | Zitate 1komma5.com (DE) | Zitate enpal.de (DE) | Status |
|---|---|---|---|---|---|---|---|
| **Google AI Overviews** | Ahrefs, echte Antworten (43 Prompts) | **19 %** (6/32) | 2,8 | gemischt (2 +, 7 0, 2 –) | 191 (86 Seiten) | 379 (196 Seiten) | ✅ gemessen |
| **Google AI Mode** | Ahrefs, Mentions und Zitate | SoV 18 % (59 Mentions vs. Enpal 136) | n/a | n/a | 149 (78 Seiten) | 331 (184 Seiten) | ✅ gemessen (aggregiert) |
| **ChatGPT** | Ahrefs-Zitate + Websuche-Proxy | Proxy: 1/5 unbranded | Proxy: 1–2 | Proxy: 0 / – | **28** (45 Seiten) | 126 (122 Seiten) | ⚠️ Proxy, Browser-Messung ausstehend |
| **Perplexity** | Ahrefs-Zitate + Websuche-Proxy | Proxy: 1/5 unbranded | Proxy: 1–2 | Proxy: 0 / – | 218 (90 Seiten) | 998 (307 Seiten) | ⚠️ Proxy, Browser-Messung ausstehend |
| **Gemini** | nur Ahrefs-Zitate | – | – | – | 125 (62 Seiten) | 322 (170 Seiten) | ⚠️ Proxy, Browser-Messung ausstehend |

Zum Vergleich thermondo.de: ChatGPT 108, Perplexity **1.291**, Gemini 298, AIO 529, AI Mode 473. zolar.de: ChatGPT 7, Perplexity 45, Gemini 82, AIO 131, AI Mode 106.

### Mentions in AI-Antworten DE (Ahrefs Brand Radar)

| Marke | AI Overviews | AI Mode |
|---|---|---|
| **1KOMMA5°** | **40** | **59** |
| Enpal | 106 | 136 |
| Thermondo | 64 | 102 |
| Zolar | 18 | 24 |

*EKD (wird mit der Evangelischen Kirche verwechselt) und Otovo („photOVOltaik“ als Teilstring) sind wegen Zählfehlern nicht in der Tabelle.*

### Branded Prompts (AI Overviews)

| Prompt | Vol./Monat | Sentiment | Haupttenor | Quellen |
|---|---|---|---|---|
| Welche Nachteile hat 1KOMMA5°? | 5.700 | – | höhere Kosten, Heartbeat-Gebühr, Abhängigkeit von der Zentrale, Verzögerungen, Vertriebsdruck | energie-solar-erfahrungen, 42watt, haustechnikdialog, Reddit, YouTube |
| Ist 1KOMMA5 teuer? | 5.700 | 0 / – | oberes Preissegment | 1komma5.com, akkudoktor, BILD, Handelsblatt, Reddit |
| Welche Hersteller verbaut 1KOMMA5? | 5.700 | 0 | Komponentenliste | 1komma5.com, energiefluss24 |
| Wie seriös ist 1KOMMA5? | 5.500 | **+** | „absolut seriös, marktführend“, Trustpilot 4,4–4,5, aber Service schwankt | BILD, energiefluss24, echtsolar, Trustpilot, 42watt, Reddit, photovoltaikforum |
| Wer steckt hinter 1KOMMA5 Grad? | 5.500 | + | Gründer, Investoren | 1komma5.com, BILD, LinkedIn, gruenderplattform, Handelsblatt, pv-magazine |
| Wer steckt hinter 1KOMMA5? | 1.400 | 0 | Gründer | 1komma5.com, antenne.de, deutsche-startup-zeitung |
| Wie gut ist 1 Komma 5 Grad? | 1.400 | 0 (gemischt) | lobt Planung und Heartbeat, kritisiert Support und Abrechnung | energie-solar-erfahrungen, YouTube, haustechnikdialog, Reddit, Facebook, Trustpilot |
| Wie hoch ist der Stromtarif von 1KOMMA5°? | 1.300 | 0 | Dynamic Pulse | 1komma5.com, energysion, haustechnikdialog, photovoltaikforum |
| Was ist 1KOMMA5? | 1.200 | 0 | Unternehmensprofil | 1komma5.com, Trustpilot, Wikipedia, Handelskammer HH |
| Wie hoch ist der aktuelle Strompreis bei 1KOMMA5°? | 800 | 0 | nur aus eigener Seite | 1komma5.com |
| Was macht 1KOMMA5? | 700 | 0 | Unternehmensprofil | 1komma5.com, LinkedIn, Wikipedia, Handelsblatt |

**Sentiment-Treiber (positiv):** alles aus einer Hand, Heartbeat AI, Beratungsqualität (CHIP), Größe und Finanzstärke (Porsche Ventures, Profitabilität), Trustpilot 4,4–4,5.
**Sentiment-Risiken:** Preis über dem lokalen Handwerk, laufende Heartbeat-Kosten, Hardware-Bindung bzw. „geschlossenes System“, Service-Tickets und Subunternehmer, Verzögerungen bei Smart Meter und Netzanmeldung, Vertriebsdruck.

---

## 3. Competitor-Citation-Map

Diese Quellen bringen den Wettbewerbern ihre Nennungen, gemessen an den Ahrefs-Zitaten in DE (AIO und AI Mode) in Antworten zu Enpal, Thermondo, Zolar, EKD, Svea und enerix:

| Quelle | Typ | Zitate (Wettbewerber) | Zitate (1KOMMA5°) | Wer profitiert | Hebel für 1KOMMA5° |
|---|---|---|---|---|---|
| **enpal.de** (107 Seiten) | eigener Ratgeber | 170 | 14 | Enpal | **Hoch:** Ratgeber-Gegenstücke zu denselben Fragen (siehe P2) |
| **thermondo.de** (76 Seiten) | eigener Ratgeber zu Heizung/WP | 147 | – | Thermondo | **Hoch:** Wärmepumpen-Ratgeber ausbauen (Kosten, Hersteller, R290, Gas vs. Strom) |
| YouTube | Video | 134 | 29 | Enpal, enerix, Thermondo | **Hoch:** eigene Erklärvideos mit Kapiteln und Transkript, Kooperation mit Akkudoktor u. Ä. |
| gruenes.haus | Ratgeber / Vergleich | 71 | 18 | Enpal, Zolar | Mittel: Datenpartnerschaft, Preisbeispiele liefern |
| energie-solar-erfahrungen.de | Erfahrungsportal | 55 | 14 | alle, prägt das Sentiment | **Hoch:** Profil pflegen, Bewertungen aktiv einholen, auf Kritik antworten |
| **chip.de** (Anbietertest) | Test | 48 | 23 | Enpal, 1KOMMA5°, enerix, Svea | **Hoch:** Testsieg auf chip.de verlinken und zitierfähig machen, keine Advertorial-Version als Hauptbeleg |
| energiefluss24.de | Ratgeber / Erfahrungen | 46 | 5 | Enpal („Enpal-Alternative“) | **Hoch:** in „Enpal-Alternative“-Artikel kommen |
| solaranlage-ratgeber.de | Ratgeber | 42 | 5 | Enpal | Mittel |
| zolar.de (24 Seiten) | Ratgeber (Altbestand) | 39 | 5 | Zolar, z. B. beim EMS-Vergleich | **Hoch:** Inhalte, für die Zolar zitiert wird, sind verwaiste Themen und gut zu übernehmen |
| ADAC | Verbraucherratgeber | 39 | 6 | neutral | Mittel: Experten-Statements, Studien |
| solar.red, lb-solartec.de, henke-solar.de | Handwerker-Blogs, oft Enpal-kritisch | 87 | – | prägen negatives Enpal-Sentiment | beobachten |
| enter.de | Anbietervergleich | 34 | 11 | Enpal, 1KOMMA5° | Mittel: Daten aktuell halten |
| Reddit (r/DeutschePhotovoltaik) | Community | 34 | 15 | prägt das Sentiment | **Hoch:** offizielles, transparentes Support-Konto, Threads mit Problemen lösen |
| BILD Energielösungen | Vergleich / Erfahrungen | 29 | 30 | Enpal, 1KOMMA5° | bereits stark, aktuell halten |
| 42watt.de | Erfahrungen / Ratgeber | 26 | 14 | prägt das 1KOMMA5°-Sentiment („Heartbeat 9,99 €“) | **Hoch:** Fakten-Update zu Heartbeat-Preisen und Leistungen liefern |
| Finanztip, Verbraucherzentrale | Verbraucherschutz | 24+ | 9 | Tarif- und EMS-Fragen | **Hoch:** Dynamic Pulse in die Tarifvergleiche von Finanztip und Verivox bringen |
| dezentralo.com, reduco.ai | EMS- und Anbietervergleiche | 21+ | 5 | evcc, E3/DC, SMA | **Hoch:** Heartbeat in die HEMS-Vergleiche aufnehmen lassen |
| Trustpilot | Bewertungen | 18 | 11 | alle | Mittel: Score halten, Antwortquote erhöhen |
| Wikipedia | Entität | 17 | 15 | Enpal, EKD | Mittel: Artikel aktuell halten (Kennzahlen, Produkte) |

---

## 4. Gap-Analyse: Wo Wettbewerber genannt werden und 1KOMMA5° nicht

| Prompt-Cluster (Beispiel) | Vol. | Wer gewinnt | Warum | Gap-Typ |
|---|---|---|---|---|
| Was kostet eine Wärmepumpe komplett / von Bosch? | 1.800 / 3.000 | Thermondo, Enpal | eigene Kostenratgeber werden zitiert | Content |
| Ist Heizen mit Strom teurer als mit Gas? | 2.600 | Enpal | enpal.de als Quelle | Content |
| Was sind die besten Wechselrichter? | 3.000 | Zolar | zolar.de-Ratgeber | Content |
| Wie viel bringen bifaziale Module? | 3.800 | Enpal | enpal.de | Content |
| Was kostet eine 10-kWp-Anlage mit Speicher? | 500 | Zolar, Solarwatt | Preisratgeber | Content (1KOMMA5° hat eine 5-kWp-Kostenseite, die zitiert wird → ausrollen) |
| Welches Energiemanagementsystem ist das beste? | 700 | evcc, openWB, E3/DC | Vergleichsartikel von Zolar, dezentralo, reduco | **Citation + Positionierung** |
| Wer bietet dynamische Stromtarife? | 500 | Tibber, Octopus, Rabot | Finanztip, Verivox, enter | **Citation** |
| Für wen lohnen sich dynamische Stromtarife? | 2.600 | – (neutral) | Verbraucherzentrale, Finanztip | Content mit Rechenbeispielen |
| Enpal-Alternative / kaufen statt mieten | – | regionale Anbieter | energiefluss24, homeandsmart | **Citation:** 1KOMMA5° ist die natürliche Kauf-Alternative |
| Wärmepumpen-Anbieter Testsieger | – | Vamo (efahrer/CHIP 2024) | Test-Artikel bei Utopia | PR und Test-Teilnahme |
| best solar installer Germany (EN) | – | LumenHaus | englischer Content fehlt | Content EN (1komma5.com/en) |

---

## 5. Priorisierte Maßnahmenliste

### P1 – Sofort (Wochen 1–4): Sentiment und Belege absichern
1. **Faktenseite „1KOMMA5° Erfahrungen & Fakten“** (eigene URL, nicht nur Kundenstimmen): Preisbeispiele je kWp, was Heartbeat kostet und leistet, typische Projektlaufzeit inkl. Smart Meter und Netzanmeldung, Servicewege, Garantien, Trustpilot- und Google-Score. Das beantwortet die Fragen „Nachteile“, „teuer?“ und „seriös?“ (zusammen über 16.000 Suchanfragen im Monat) mit eigener Quelle. Aktuell zitiert die KI dafür 42watt, Reddit und Foren.
2. **CHIP-Testsieg zitierfähig machen:** auf den Original-Artikel bei chip.de verlinken, Testsiegel mit Datum und Note auf Startseite und Faktenseite, Pressemitteilung über presseportal. Das Advertorial (`/aktion/advertorial/…`) auf `noindex` setzen oder klar vom redaktionellen Beleg trennen, sonst stuft die KI die Auszeichnung als Werbung ein.
3. **Kritik-Quellen aktualisieren:** 42watt, energie-solar-erfahrungen.de, echtsolar und energiefluss24 aktuelle Fakten zu Heartbeat-Preisen und Leistungen schicken und um Korrektur bitten. In r/DeutschePhotovoltaik ein offizielles Support-Konto einrichten, Probleme offen lösen, keine Astroturfing-Posts.
4. **Technik-Check nachholen** (in dieser Session nicht möglich, weil die Domain über den Proxy gesperrt war): robots.txt für GPTBot, OAI-SearchBot, PerplexityBot und Google-Extended prüfen, `llms.txt` anlegen, Organization-Schema mit `sameAs` (Wikipedia, Wikidata, LinkedIn, Trustpilot, CHIP-Test), `aggregateRating`, FAQPage auf Produkt- und Ratgeberseiten.

### P2 – Ratgeber-Gap schließen (Wochen 2–10)
5. **Wärmepumpen-Ratgeber-Cluster** gegen thermondo.de und enpal.de aufbauen: „Wärmepumpe Kosten komplett EFH“, „Wärmepumpe Bosch/Viessmann/Vaillant Kosten“, „Heizen mit Strom vs. Gas“, „R290 umweltfreundlich?“, „Wärmepumpe vs. Wärmetauscher“. Jeder Artikel beginnt mit einer Direktantwort mit Zahl, enthält eine Tabelle, einen FAQ-Block und das Datum der letzten Aktualisierung.
6. **PV-Kosten-Seiten ausrollen:** Die Seite `pv-anlage-5-kwp-mit-speicher-kosten` wird bereits zitiert. Dasselbe Format für 8, 10, 12 und 15 kWp mit und ohne Speicher umsetzen, dazu Wechselrichter-Vergleich, bifaziale Module, Modulgrößen und AC- vs. DC-Speicher. Diese Themen gewinnen aktuell Zolar und Enpal.
7. **Verwaiste Zolar-Themen übernehmen:** Zolar ist nicht mehr im Endkundengeschäft, wird aber weiter zitiert (z. B. bei „Bestes Energiemanagementsystem“ und „Wechselrichter“). Für genau diese Fragen bessere und aktuellere Seiten bauen.

### P3 – Heartbeat und Dynamic Pulse in die Kategorie-Antworten bringen (Monate 1–3)
8. **Ehrlicher HEMS-Vergleich** auf 1komma5.com: „Energiemanagementsystem-Vergleich 2026: Heartbeat vs. evcc vs. openWB vs. E3/DC vs. SMA“. Kriterien: Offenheit, § 14a EnWG, dynamische Tarife, Kosten. Das Hauptargument der Kritik („geschlossenes System“) aktiv beantworten, z. B. mit einer Kompatibilitätsliste.
9. **Pitch an dezentralo.com, reduco.ai, ADAC und photovoltaikforum** für eine Aufnahme von Heartbeat in die HEMS-Vergleiche. Testzugänge anbieten.
10. **Dynamic Pulse in die Tarifvergleiche bringen:** Finanztip, Verivox, enter.de und Rabot-ähnliche Übersichten. Rechenbeispiel „PV + Speicher + WP + E-Auto mit Dynamic Pulse“ als Studie mit Methodik veröffentlichen. Zitierfähige Zahlen statt „bis zu 80 %“, denn die KI markiert das als Marketing.

### P4 – Citations und Reichweite (laufend)
11. **„Enpal-Alternative“-Artikel** (energiefluss24, homeandsmart, giga, chip): 1KOMMA5° als Kauf-Alternative mit Fakten positionieren.
12. **Wärmepumpen-Anbietertest:** an der nächsten Runde von efahrer/CHIP teilnehmen bzw. anfragen. Aktuell ist Vamo der zitierte Testsieger.
13. **YouTube:** Erklärvideos zu Kosten, Winterertrag und Heartbeat mit Kapitelmarken und vollständigem Transkript. YouTube ist die zweithäufigste Quelle in den AI Overviews.
14. **Englischer Content** für „best solar installer Germany“ (Expats, internationale Presse) auf 1komma5.com/en.

**Ziele für 90 Tage:** unbranded Mention-Rate in den AI Overviews von 19 % auf ≥ 30 %. Heartbeat in der Antwort auf „Welches Energiemanagementsystem ist das beste?“. Zitate von 1komma5.com bei ChatGPT und Perplexity ≥ 40 % des Enpal-Werts. Sentiment bei „Nachteile“ und „seriös“ mit eigener Quelle unter den ersten 3 Links.

---

## 6. Prompt-Panel (40 Prompts, zur Ausführung in ChatGPT, Gemini und Perplexity via Claude in Chrome)

**Anbieter / Kategorie**
1. Welche Photovoltaikfirma ist die beste in Deutschland?
2. Welche Solaranbieter gibt es in Deutschland?
3. Welcher Komplettanbieter für Solaranlage und Wärmepumpe ist empfehlenswert?
4. Welche Firma installiert gute Wärmepumpen bundesweit?
5. Lieber regionaler Handwerker oder großer Solar-Komplettanbieter?
6. Best solar installer in Germany for a family home?
7. Wer sind die größten Solarfirmen in Deutschland?
8. Welche PV-Anbieter haben die besten Bewertungen?

**Best X für Y**
9. Beste Komplettlösung PV + Speicher + Wallbox für Einfamilienhaus?
10. Bester Anbieter für Wärmepumpe im Altbau?
11. Welches Energiemanagementsystem ist das beste?
12. Bester dynamischer Stromtarif für Wärmepumpe und E-Auto?
13. Welcher Anbieter für Solaranlage mit Wärmepumpe aus einer Hand?
14. Beste Lösung, um den Eigenverbrauch einer PV-Anlage zu maximieren?

**Vergleich / Alternativen**
15. Enpal Alternative – wer ist besser?
16. 1KOMMA5° oder Enpal – welcher Anbieter ist besser?
17. 1KOMMA5° vs. Thermondo Wärmepumpe?
18. Heartbeat AI vs. evcc vs. SMA Sunny Home Manager?
19. Dynamic Pulse vs. Tibber vs. Octopus – welcher dynamische Tarif lohnt sich?
20. Solaranlage kaufen oder mieten – welche Anbieter?
21. Svea Solar vs. 1KOMMA5° vs. EKD?

**Marke / Vertrauen**
22. Wie seriös ist 1KOMMA5°?
23. Welche Nachteile hat 1KOMMA5°?
24. Ist 1KOMMA5° teuer?
25. 1KOMMA5° Erfahrungen Wärmepumpe?
26. Was kostet Heartbeat AI im Monat und lohnt es sich?
27. Welche Hersteller verbaut 1KOMMA5°?
28. Wer steckt hinter 1KOMMA5°?
29. Ist 1KOMMA5° wirklich CHIP-Testsieger?

**Kosten / Problem / Use Case**
30. Was kostet eine 10-kWp-PV-Anlage mit Speicher 2026?
31. Was kostet eine Wärmepumpe komplett für ein Einfamilienhaus?
32. Lohnt sich eine PV-Anlage 2026 noch?
33. Was bringt eine PV-Anlage im Winter?
34. Für wen lohnt sich ein dynamischer Stromtarif?
35. Wie kann ich meine Stromrechnung mit PV und Wärmepumpe senken?
36. Ist Heizen mit Strom teurer als mit Gas?
37. Welche Förderung gibt es 2026 für Wärmepumpe und PV?
38. Wie lange dauert die Installation einer PV-Anlage inkl. Netzanmeldung?
39. Was ist § 14a EnWG und was bringt er mir mit Wärmepumpe?
40. Welcher Wechselrichter ist der beste für eine PV-Anlage?

**Scoring je Antwort:** genannt (j/n) · Position · Sentiment (+/0/–) · zitierte Quellen-URLs · genannte Wettbewerber.

---

## Quellen
- Ahrefs Brand Radar (Google AI Overviews / AI Mode, DE), Abruf 12.10.2026, Rohdaten in `audits/1komma5grad/2026-10-12/`
- Ahrefs Site Explorer – AI-Citations je Domain (DE): 1komma5.com, enpal.de, thermondo.de, zolar.de
- [CHIP – Test Solaranlagen-Anbieter 2025](https://www.chip.de/artikel/Test-Solaranlagen-Anbieter-2025-Das-sind-die-besten-Photovoltaik-Firmen_186202106.html)
- [BILD – PV-Anbieter](https://www.bild.de/energieloesungen/photovoltaik/pv-anbieter) · [BILD – 1KOMMA5 Erfahrungen](https://www.bild.de/energieloesungen/photovoltaik/pv-anbieter/1komma5-erfahrungen)
- [enter.de – Photovoltaik-Anbieter-Vergleich](https://www.enter.de/blog/photovoltaik-anbieter-vergleich)
- [Enpal – Photovoltaik-Anbieter 2026](https://www.enpal.de/photovoltaik/anbieter)
- [42watt – 1KOMMA5 Erfahrungen](https://42watt.de/magazin/1komma5-erfahrungen) · [energie-solar-erfahrungen.de – 1KOMMA5](https://www.energie-solar-erfahrungen.de/anbieter/1-komma-5)
- [Reddit r/DeutschePhotovoltaik – 1KOMMA5 Erfahrungen](https://www.reddit.com/r/DeutschePhotovoltaik/comments/1jy23th/1komma5_eure_erfahrungen_mit_vertrieb_und_service/)
- [Trustpilot – 1komma5.com](https://de.trustpilot.com/review/1komma5.com)
- [Zolar – Energiemanager](https://zolar.de/blog/energiemanager) · [dezentralo – HEMS-Vergleich](https://dezentralo.com/blog/home-energy-management-systeme-im-vergleich) · [reduco – HEMS-Vergleich](https://reduco.ai/blog/solar/energiemanagementsystem-hems-vergleich)
- [Finanztip – Dynamische Stromtarife](https://www.finanztip.de/stromtarife/dynamische-stromtarife-vergleich/) · [Verbraucherzentrale – Dynamische Stromtarife](https://www.verbraucherzentrale.de/wissen/energie/preise-tarife-anbieterwechsel/dynamische-stromtarife-fuer-wen-es-sich-lohnt-und-worauf-sie-achten-sollten-97836)
- [Utopia – Wärmepumpen-Anbieter Testsieger](https://utopia.de/ratgeber/waermepumpen-anbieter-das-sind-die-testsieger-unter-den-deutschen-installationsbetrieben_747922/)
- [energiefluss24 – Enpal-Alternative](https://www.energiefluss24.de/waermepumpe/enpal-alternative)
- [Trending Topics – 1KOMMA5 und Enpal Umsätze](https://www.trendingtopics.eu/1komma5-und-enpal-verdoppelten-ihre-umsaetze-2023-und-machten-gewinne/) · [Solarserver – Zolar](https://www.solarserver.de/2025/06/27/zolar-vom-enpal-konkurrenten-zum-dienstleister-fuer-das-pv-handwerk/)
- [Akkudoktor-Forum – Heartbeat](https://akkudoktor.net/t/heartbeat-von-1komma5-gute-idee-oder-viel-zu-teuer/14591?page=2)
- [1KOMMA5° – CHIP-Advertorial](https://1komma5.com/de/aktion/advertorial/chip-testet-6-solar-anbieter-nur-einer-bekommt-sehr-gut/)
