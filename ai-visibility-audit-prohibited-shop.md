# AI Visibility Audit – Prohibited (prohibited.shop)

**Stand:** 07.10.2026 · **Marke:** Prohibited (Berlin-Mitte, gegr. 2021, Philip Krause & Patrick Reimann) · **Kategorie:** Premium-Streetwear / „Old Money“- bzw. „Modern Yuppie“-Streetwear · **Shop:** Shopify, Preisniveau ca. 65–265 €

**Wettbewerber-Set (Annahme, bitte bestätigen):**
- DE: Pegador, LFDY, PESO, 6PM
- EU: Represent, Daily Paper, Cole Buxton

**Zielgruppe (Annahme):** Männer von 18 bis 35 in DACH und Benelux, stilbewusst, kaufen bei Zalando und ASOS oder direkt im Shop. Sie suchen hochwertige Basics, Strick und Bundfaltenhosen statt Logo-Hype.

> **Methodik-Hinweis:** In dieser Umgebung konnte ich ChatGPT, Gemini und Perplexity nicht direkt abfragen. Die Baseline unten beruht auf **10 Panel-Prompts, die über eine Websuche mit KI-Zusammenfassung gelaufen sind**. Das kommt dem Retrieval von Perplexity, AI Overviews und ChatGPT Search recht nahe, ist aber nur ein Proxy. Für die echte Baseline das Prompt-Panel (Abschnitt 5) in jedem Assistenten ausführen, die Antworten einfügen und neu scoren lassen.

---

## 1. Executive Summary

| Kennzahl | Wert |
|---|---|
| Mention-Rate in **unbranded** Kategorie-Prompts | **1 / 7 (14 %)** |
| Mention-Rate in **branded** Prompts mit „Berlin“ | 2 / 2 (100 %), Tonalität **positiv** |
| Branded Prompts **ohne** Zusatz „Berlin“ (Marke/Domain allein) | **0 / 2 erkannt**: Die KI liest „prohibited“ als Wort („verboten“) |
| Durchschnittliche Position, wenn genannt | 1 (bei Bundfaltenhosen/Old Money, über ASOS-Produktseiten) |
| Wichtigste Quellen über die Marke | FashionUnited, ASOS, Zalando, Pitti Uomo, Trusted Shops |
| Wichtigste Quellen der Wettbewerber | Highsnobiety, TextilWirtschaft, nss magazine, ZDF/funk, Ape to Gentleman, Reddit, iHeartBerlin |

**Kernaussagen:**
1. **Das größte Risiko ist der Markenname, nicht der Content.** „Prohibited“ ist ein gängiges englisches Wort. Ohne Kontext („Berlin“, „Streetwear“) erkennen LLMs die Marke nicht. Ein Vergleich wie „Prohibited vs Pegador vs Represent“ lieferte nur Wörterbuch- und Jura-Treffer. Die Marke muss als **Entität** eindeutig werden.
2. **Wer die Marke kennt, bekommt gute Antworten:** Gründung, Positionierung („Anti-Hype“, „Modern Yuppie“), Händler und Trusted-Shops-Feedback sind gut belegt. Das Wissen ist also da, wird aber **nicht in Kategorie-Antworten übertragen**.
3. **In den Listen, aus denen KI-Antworten entstehen, fehlt Prohibited komplett.** Dazu gehören „Beste deutsche Streetwear-Marken“, „Berlin streetwear brands“, „Best heavyweight hoodies“ und „Marken wie Pegador“. Genau dort holen sich die Wettbewerber ihre Nennungen.
4. **Die eigenen Seiten liefern der KI kaum zitierfähige Fakten.** Produkttexte bestehen aus 4 Stichpunkten, GSM/Grammatur fehlt im Shop (ASOS nennt sie), Organization-Schema auf der Startseite fehlt, und es gibt keinen Ratgeber-Content.

---

## 2. Visibility-Scorecard (Proxy-Lauf)

| # | Prompt (Typ) | Prohibited genannt? | Position | Sentiment | Stattdessen genannt | Zitierte Quellen |
|---|---|---|---|---|---|---|
| 1 | best streetwear brands from Berlin (Kategorie, EN) | ❌ | – | – | 032c, Frank Leder, Arys, Vain, Anonymous Club (und fälschlich Casablanca) | thesolesupplier, nss magazine, iHeartBerlin, discobrands |
| 2 | beste deutsche Streetwear Marken 2026 (Kategorie, DE) | ❌ | – | – | LFDY, PESO, 6PM, Gerrit Jacob, William Fan, Colors, Huni | TextilWirtschaft, Highsnobiety, ZDF/funk, nss magazine |
| 3 | old money streetwear brands Germany pleated pants (Best X für Y) | ✅ | 1 | neutral | GmbH, Frank Leder | **ASOS-Produktseiten** (Soho Pleated Pants) |
| 4 | Marken wie Pegador / Alternativen (Vergleich) | ❌ | – | – | nur Pegador selbst | FashionUnited, TextilWirtschaft, Zalando |
| 5 | premium heavyweight hoodie brand Europe (Best X für Y) | ❌ | – | – | Represent, CDLP, ASKET, Service Works, Sunspel | Ape to Gentleman, Mensflair, Reddit, parse.gl |
| 6 | hochwertige Streetwear Strick Quarter Zip Herren (Produkt) | ❌ | – | – | Ralph Lauren, Tiger of Sweden, Levi's, Suitsupply | Zalando-Kategorieseiten |
| 7 | brands like Represent / Cole Buxton / Daily Paper (Vergleich) | ❌ | – | – | Daily Paper, Represent, Cole Buxton | END., GOAT, FashionUnited |
| 8 | Prohibited vs Pegador vs Represent (Branded-Vergleich) | ❌ **nicht erkannt** | – | – | Wörterbuch, Jura-Texte | Wiktionary u. a. |
| 9 | prohibited.shop (Navigational) | ❌ **nicht erkannt** | – | – | „Shopify Prohibited Products“ | help.shopify.com u. a. |
| 10 | Prohibited Berlin streetwear review / Erfahrungen (Branded) | ✅ | 1 | **positiv** (Qualität, Service, Preis-Leistung; Kritik: Black-Friday-Lieferzeit, einzelne Schnitte) | – | FashionUnited (2×), Trusted Shops, Pitti Uomo, ASOS, Zalando |

**Sentiment-Treiber (positiv):** „Anti-Hype“-Positionierung, hohe Qualität, faire Preise, schneller Service, über 100 Händler, Pitti Uomo.
**Sentiment-Risiken:** Lieferverzug zu Peak-Zeiten und der Hinweis „Produktbilder teilweise KI-generiert“ auf den Produktseiten. Der Hinweis kann in künftigen Reviews oder Reddit-Threads als Vertrauensthema auftauchen.

---

## 3. Competitor-Citation-Map

Diese Quellen bringen den Wettbewerbern ihre Nennungen. Sie sind die Hebel, in die Prohibited hinein muss:

| Quelle | Typ | Wer dort genannt wird | Realistisch für Prohibited? |
|---|---|---|---|
| Highsnobiety – „Best German clothing brands“ | Listicle, hohe Autorität | dt. Designer- und Streetwear-Labels | **Mittel**: PR-Pitch mit Pitti-Uomo- und Händler-Story |
| TextilWirtschaft – „Streetwear aus Deutschland: Labels mit Hype-Potenzial“ | Fachpresse | Gerrit Jacob, Colors, Huni | **Hoch**: Business-Story (Wachstum, Store-Pläne) ist schon bei FashionUnited gelaufen |
| nss magazine (Berlin Fashion Week) | Mode-Magazin | Berliner Labels, Street Style | **Mittel**: Präsenz zur Berlin Fashion Week und BCCO-Kollab |
| iHeartBerlin, discobrands („Berlin streetwear brands“) | Blog / Listicle | Berliner Labels | **Hoch**: kleine Redaktionen, leicht anzusprechen |
| thesolesupplier („Best streetwear shops in Berlin“) | Listicle | Shops (Voo, Overkill, Solebox) | Mittel: erst relevant mit eigenem Store |
| Ape to Gentleman, Mensflair („Best heavyweight hoodies“) | Kauf-Ratgeber EN | Represent, CDLP, ASKET | **Hoch**: Produkt-Seeding oder Affiliate, braucht GSM-Fakten |
| Reddit (r/streetwear, r/malefashionadvice, r/de) | Community | Represent, Sunspel | **Mittel**: echte Erwähnungen anstoßen, nicht spammen |
| ZDF/funk, TikTok-Kultur („LFDY, PESO, 6PM“) | Video / Youth | LFDY, PESO, 6PM | Mittel: Herkunft TikTok ist eine Stärke, sollte aber als Text (Transkripte, Artikel) auffindbar werden |
| Zalando / ASOS-Kategorieseiten | Marktplatz | Ralph Lauren, Levi's | **Hoch**: Prohibited ist schon gelistet. Produkttitel dort mit Kategorie-Keywords anreichern („Cable Knit Quarter Zip“, „Old Money“) |

---

## 4. Priorisierte Maßnahmenliste

### P1 – Sofort (Wochen 1–4): Entität eindeutig machen
1. **Organization-Schema auf der Startseite** (JSON-LD, fehlt aktuell): `name: "Prohibited"`, `alternateName: ["Prohibited Berlin", "PROHIBITED Berlin"]`, `foundingDate: 2021`, `founder` (Philip Krause, Patrick Reimann), `address` (Berlin-Mitte), `sameAs` (Instagram, TikTok, LinkedIn, Zalando- und ASOS-Brandpage, FashionUnited, Pitti-Uomo-Profil, Trusted Shops).
2. **Wikidata-Eintrag** für „Prohibited (Modemarke)“ mit Branche, Sitz, Gründern und Website anlegen. Das ist der stärkste einzelne Hebel gegen die Wort-Verwechslung.
3. **Konsequent „Prohibited Berlin“** als Markenbezeichnung nutzen, in Title-Tags, Meta-Descriptions, Social-Bios, Marktplatz-Brandnamen und PR-Texten. Der aktuelle Title „Prohibited – High Quality Streetwear from Berlin“ ist gut; diese Formel überall verwenden.
4. **„Über uns“-Seite als Faktenblatt:** Gründung, Gründer, Herkunft (Design Berlin, Produktion Türkei), Stoffe/GSM, Händlerzahl, Pitti Uomo, Presse-Zitate. LLMs zitieren gerne solche klar strukturierten Fakten.

### P2 – Produkt- & Shop-Daten (Wochen 2–6)
5. **Produkttexte ausbauen.** Statt 4 Stichpunkten: Material, **Grammatur (GSM)**, Passform mit Modellmaßen, Pflege, Style-Kontext („Old Money“, „Quiet Luxury“, „College“). Die GSM-Angabe ist entscheidend für „heavyweight hoodie“-Prompts.
6. **Product-Schema erweitern:** `gtin13` ergänzen (die EANs stehen schon in den Bild-Dateinamen, z. B. 4255746572861), dazu `material`, `aggregateRating` und `review` aus Trusted Shops sowie `brand` mit Verweis auf die Organization.
7. **Lokalisierung prüfen:** Die `/de/`-Produktseite zeigte im Test USD-Preise und eine gemischt englisch-deutsche Oberfläche. Ursache kann der Abruf aus den USA sein; trotzdem hreflang, Währung und Übersetzung kontrollieren. KI-Crawler kommen meist aus den USA.
8. **Feeds für KI-Shopping:** robots.txt, agents.md und UCP/MCP-Endpunkt von Shopify sind schon aktiv (gut). Merchant-Center- und Shop-Feeds mit vollständigen Attributen (GTIN, Material, Farbe, Fit) pflegen. Daraus speisen sich ChatGPT Shopping und Google AI Mode.

### P3 – Citations gewinnen (Monate 1–3)
9. **PR-Pitch an TextilWirtschaft und Highsnobiety:** Wachstumsstory (TikTok/Amazon → 150+ Händler → Pitti Uomo → Store-Pläne) und BCCO-x-Prohibited-„Berlincore“-Kollab.
10. **Berlin-Blogs und -Listicles** (iHeartBerlin, discobrands u. a.) ansprechen und um Aufnahme in „Berlin streetwear brands“ bitten.
11. **Produkt-Seeding** bei englischen Kauf-Ratgebern (Ape to Gentleman, Mensflair) für Hoodie und Strick, mit GSM-Daten.
12. **Reddit- und Community-Präsenz:** Echte Kundenstimmen anregen (z. B. Fit-Pics, Reviews in r/streetwear). Kein Astroturfing.

### P4 – Eigener GEO-Content (laufend)
13. **Ratgeber-Hub** im Shop-Blog:
    - „Old Money Streetwear: Der Guide (Bundfaltenhose, Strick, Quarter Zip)“
    - „Berliner Streetwear-Marken im Überblick“ (fair, mit Prohibited)
    - „Hoodie-Grammatur erklärt: Was bedeuten 360 GSM?“
    - „Bundfaltenhose kombinieren“
    Jeweils mit kurzer Direktantwort am Anfang, FAQ-Block und Tabellen.
14. **KI-Bild-Hinweis:** Für Bestseller echte Produktfotos nachziehen. Das stärkt das Vertrauen in Reviews und Marktplatz-Bewertungen, die LLMs zur Sentiment-Bildung heranziehen.

---

## 5. Prompt-Panel (40 Prompts, zur Ausführung in ChatGPT, Claude, Gemini, Perplexity und AI Overviews)

**Kategorie (DE)**
1. Was sind die besten deutschen Streetwear-Marken?
2. Welche Streetwear-Marken kommen aus Berlin?
3. Welche neuen deutschen Modelabels sollte man 2026 kennen?
4. Hochwertige Streetwear aus Deutschland – welche Marken lohnen sich?
5. Welche Streetwear-Marken sind gerade bei jungen Männern angesagt?
6. Welche Marken stehen für Old-Money-Style für Männer, aber bezahlbar?
7. Welche Streetwear-Marken setzen auf Qualität statt Hype?
8. Gute Marken für Bundfaltenhosen für Herren?

**Kategorie (EN)**
9. What are the best streetwear brands from Berlin?
10. Best European premium streetwear brands right now?
11. Best old money / quiet luxury menswear brands under €150?
12. Best heavyweight hoodie brands in Europe?
13. Up-and-coming German fashion brands to watch?
14. Best brands for pleated trousers with a streetwear look?

**Best X für Y**
15. Bester Hoodie unter 100 € mit guter Qualität?
16. Bester Strick-Quarter-Zip für Herren?
17. Welche Marke für Collegejacke / Letterman-Jacke?
18. Best knit sweater brand for a preppy / college look?
19. Best relaxed denim from a European streetwear brand?
20. Gute Geschenkidee Kleidung für 20-jährigen Mann – welche Marke?

**Vergleich / Alternativen**
21. Marken wie Pegador?
22. Alternativen zu Represent, aber günstiger?
23. Brands like Daily Paper or Cole Buxton?
24. LFDY vs PESO vs 6PM – was gibt es Hochwertigeres?
25. Prohibited Berlin vs Pegador – welche Marke ist besser?
26. Prohibited vs Represent – quality comparison?
27. Brands similar to Ralph Lauren but more streetwear?

**Marken-/Vertrauensfragen**
28. Was ist Prohibited Berlin für eine Marke?
29. Ist Prohibited Berlin seriös / gute Qualität?
30. Prohibited Hoodie Erfahrungen?
31. Wo wird Prohibited produziert?
32. Prohibited Größe – fällt die Marke groß oder klein aus?
33. Who founded Prohibited streetwear?
34. Is prohibited.shop legit?

**Problem / Use Case**
35. Ich will weg von Logo-Streetwear und mich erwachsener kleiden – welche Marken?
36. Wie kombiniere ich Bundfaltenhose mit Hoodie?
37. Welche Kleidung für den „Old Money“-Look im Herbst?
38. Where to buy quality basics that don't shrink after washing?
39. Wo kann ich in Berlin hochwertige Streetwear kaufen?
40. Welche Streetwear-Marken haben faire Preise und gute Qualität?

**Scoring je Antwort:** genannt (j/n) · Position in der Liste · Sentiment (+ / 0 / –) · zitierte Quellen-URLs · genannte Wettbewerber. Ziel nach 90 Tagen: unbranded Mention-Rate von 14 % auf **≥ 30 %**, Prompts 25, 26 und 34 werden korrekt als Marke erkannt.

---

## Quellen (Proxy-Lauf)
- [FashionUnited – Label to Watch: Prohibited](https://fashionunited.de/nachrichten/mode/label-to-watch-berliner-streetwear-von-prohibited-die-neue-massstabe-setzt/2024052956677)
- [FashionUnited – Die Pläne von Prohibited](https://fashionunited.de/nachrichten/business/die-plane-von-prohibited-expansion-marketing-aktionen-und-eigener-store/2026040866177)
- [Pitti Uomo – Brand Profile Prohibited](https://uomo.pittimmagine.com/107/exhibitors/P/prohibited)
- [Trusted Shops – Bewertungen](https://www.trustedshops.de/bewertung/info_X08A5D7BA99CD37DAF0316881E5CD17CA.html)
- [ASOS – Prohibited](https://www.asos.com/men/fashion-feed/2024_11_08-fri/prohibited) · [Zalando – Prohibited](https://www.zalando.de/damenbekleidung/prohibited)
- [TextilWirtschaft – Streetwear aus Deutschland](https://www.textilwirtschaft.de/fashion/news/junge-kreative-diese-brands-praegen-die-deutsche-streetwear-240033)
- [Highsnobiety – Best German clothing brands](https://www.highsnobiety.com/p/best-german-clothing-brands/)
- [ZDF/funk – Deutsche Streetwear: LFDY, PESO, 6PM](https://www.zdf.de/video/kommentare/funk-collection-funk-12281-112/funk-deutsche-streetwear---hype-um-lfdy-peso-und-6pm-mit-sami-rhoma-emily-furz-ned-sadikajvincent-102)
- [thesolesupplier – Best streetwear shops in Berlin](https://thesolesupplier.co.uk/news/here-are-the-12-best-sneaker-streetwear-shops-in-berlin/)
- [discobrands – Berlin streetwear brands](https://discobrands.co/blogs/10-brands-like-berlin-streetwear-brands)
- [Ape to Gentleman – Best heavyweight hoodies](https://www.apetogentleman.com/the-best-heavyweight-hoodie-brands-for-men/)
- [Wiktionary – prohibited](https://en.wiktionary.org/wiki/prohibited) (Beleg für die Entitäts-Verwechslung)
