# AI Search Readiness Report – prohibited.shop

**Seiten geprüft:** Startseite, `/en/pages/about`, `/de/pages/about`, `/de/blogs/news`, `/de/collections/pleated-pants`, Produktseite `/de/products/cable-knit-quarter-zip-cream`
**Zielfragen (Annahme):** „hochwertige Streetwear aus Berlin“, „Old-Money-Streetwear-Marken“, „gute Bundfaltenhosen für Herren“, „Ist Prohibited gut / seriös?“
**Branche:** Mode-E-Commerce / Premium-Streetwear
**Datum:** 07.10.2026

```
GESAMT-SCORE: 26/70 (37 %)

1. Direkte Antworten:              3/10
2. Struktur / Überschriften:       4/10
3. Entitäts-Klarheit:              5/10
4. Faktendichte:                   3/10
5. E-E-A-T-Signale:                4/10
6. Fragen-Abdeckung:               1/10
7. Aktualität & Pflege:            6/10

READINESS-LEVEL: Needs Work
```

**Kurz gesagt:** Die Seiten lassen sich technisch gut lesen: KI-Crawler sind erlaubt, Shopify liefert ein Product-Schema mit, die Seiten sind sauber gerendert. Es gibt auf ihnen aber kaum etwas, das eine KI **zitieren möchte**. Die Startseite besteht nur aus Kollektionsnamen und Preisen. Kategorieseiten haben keinen Einleitungstext, Produktseiten nur 4 Stichpunkte. Ratgeber und FAQ fehlen ganz. Die beste Quelle ist die englische About-Seite, und ihr deutsches Gegenstück liefert im Test einen 404-Fehler.

---

## Top 3 Quick Wins

1. **Die deutsche „Über uns“-Seite reparieren.** `/de/pages/about` liefert „404 Seite nicht gefunden“. Vermutlich hat die Seite auf Deutsch einen übersetzten Handle, oder die Übersetzung fehlt. Dazu eine Meta-Description setzen (aktuell leer) und oben einen Satz einbauen, den eine KI wörtlich übernehmen kann: *„Prohibited ist ein Streetwear-Label aus Berlin-Mitte, 2021 gegründet von Philip Krause und Patrick Reimann. Die Marke verbindet Streetwear mit sportlicher Old-Money-Ästhetik („Modern Yuppie“). Sie ist in über 150 Stores sowie bei Zalando, About You und ASOS erhältlich.“*
2. **Einleitungstexte für die 5 wichtigsten Kategorien schreiben** (Pleated Pants, Knit, Hoodies, Quarter/Half Zips, Jeans). Je 80–150 Wörter mit Direktantwort, Materialien, Passform und Preisspanne. Beispiel siehe unten.
3. **Organization-Schema auf die Startseite setzen** (es fehlt komplett), mit `sameAs` auf Instagram (@prohibitedclo), TikTok, YouTube, Zalando, ASOS und Trusted Shops. Das hilft der KI, „Prohibited“ als Marke und nicht als Wort zu verstehen.

---

## Detaillierte Ergebnisse

### 1. Direkte Antworten – 3/10
- **Was funktioniert:** Title und Meta-Description der Startseite sagen klar, worum es geht („High Quality Streetwear from Berlin … designed in Berlin, produced in Turkey“).
- **Was fehlt:** Im sichtbaren Text der Startseite steht kein einziger erklärender Satz. Kategorieseiten (z. B. „Pleated Pants“, 25 Produkte) haben nur H1 und Produktraster. Damit gibt es nichts, was eine KI auf „Was ist eine gute Bundfaltenhose?“ übernehmen könnte.
- **Vorschlag (Startseite, unter dem Hero):** *„Prohibited ist Premium-Streetwear aus Berlin: Bundfaltenhosen, Strick, Hoodies und Jacken im Old-Money-Look, entworfen in Berlin-Mitte, gefertigt in der Türkei, ab ca. 65 €.“*

### 2. Struktur / Überschriften – 4/10
- **Was funktioniert:** Produktseiten haben eine saubere H1 (Produktname) und H2 („Product details“, „Shipping & Returns“).
- **Was fehlt:**
  - Die H2 der Startseite heißen „BACK IN THE DAYS“ und „BESTSELLER“, die der About-Seite „THE VIBE“ und „SO FAR“. Das sind Kampagnen-Slogans, keine beschreibenden Überschriften.
  - Die Oberfläche auf `/de/` ist überwiegend englisch („Skip to content“, „Product details“), und `lang` steht auf `en`.
  - Die interne Verlinkung zeigt von `/de` auf `/en`-URLs.
- **Vorschlag:** Beschreibende H2 wie „Bundfaltenhosen für Herren“, „Strick & Quarter Zips“, „Über Prohibited“. Außerdem deutsche Übersetzung und hreflang prüfen. Der Test lief aus den USA, das Verhalten in DE bitte gegenchecken.

### 3. Entitäts-Klarheit – 5/10
- **Was funktioniert:** Die About-Seite nennt Gründer (Philip & Patrick), Gründungsjahr 2021, Sitz Berlin-Mitte, 20 Mitarbeitende, über 150 Stores, Zalando, About You und ASOS, eigenes Lager und keine Investoren. Die Social-Profile sind im Footer verlinkt.
- **Was fehlt:**
  - Kein Organization- oder WebSite-Schema.
  - Die Nachnamen der Gründer fehlen.
  - Die Marke heißt nur „Prohibited“, ein Allerweltswort.
  - Das Help-Center liegt auf `checkmatecommerce.zendesk.com`. KI ordnet diese Inhalte nicht der Marke zu.
- **Vorschlag:** Konsequent „Prohibited Berlin“ als Markenbezeichnung verwenden. Schema mit `alternateName`, `founder`, `foundingDate` und `address` ergänzen und einen Wikidata-Eintrag anlegen.

### 4. Faktendichte – 3/10
- **Was funktioniert:** Material wird genannt („100 % Baumwolle“), dazu Passform („Oversized Fit“), Lieferzeit (3–5 Werktage DHL) und Retoure (30 Tage).
- **Was fehlt:** Grammatur (GSM), Stoffart (z. B. Cable Knit, Garnstärke), Modellgröße und -maße, Maßtabelle als Text, Pflegehinweise, Produktionsland je Produkt.
- **Vorschlag (Cable Knit Quarter Zip):** *„Schwerer Zopfstrick-Troyer aus 100 % Baumwolle (ca. XXX g/m²), Oversized Fit. Das Model ist 1,86 m groß und trägt M. Gefertigt in der Türkei, bei 30 °C waschbar.“* (Werte ergänzen.)

### 5. E-E-A-T-Signale – 4/10
- **Was funktioniert:**
  - Die Gründer-Story stammt aus erster Hand.
  - Impressum und Policies sind vorhanden.
  - Die Lookbooks sind datiert.
  - Kooperationen mit Strellson und BCCO belegen Relevanz in der Branche.
- **Was fehlt:**
  - Auf Shop-Seiten sind keine Kundenbewertungen sichtbar, und im Schema fehlt `aggregateRating`, obwohl es Trusted-Shops-Bewertungen gibt.
  - Presse-Erwähnungen fehlen auf der Seite (FashionUnited, Pitti Uomo).
  - Der Hinweis, dass Produktbilder teils KI-generiert sind, schwächt das Vertrauen, wenn er bei Bestsellern steht.
- **Vorschlag:** Einen Block „Bekannt aus / Vertreten bei“ einbauen (FashionUnited, Pitti Uomo, Zalando, ASOS). Trusted-Shops-Sterne auf Produkt- und Startseite zeigen. Für Bestseller echte Fotos verwenden.

### 6. Fragen-Abdeckung – 1/10
- **Was funktioniert:** Versand und Retoure sind auf der Produktseite beschrieben.
- **Was fehlt:**
  - Es gibt keine FAQ im Shop.
  - Der Blog enthält nur Lookbooks (Bilder ohne Text).
  - Größen-, Material- und Styling-Fragen werden nirgends beantwortet. Genau das fragen Nutzer ChatGPT: „Fällt Prohibited groß aus?“, „Wie kombiniere ich eine Bundfaltenhose?“
- **Vorschlag:**
  - Eine FAQ-Seite plus ein FAQ-Block je Kategorie, jeweils mit FAQPage-Schema.
  - Den Blog um Ratgeber erweitern, statt nur Lookbooks zu zeigen.

### 7. Aktualität & Pflege – 6/10
- **Was funktioniert:** Aktuelle Kollektion („Fall 26“), Lookbooks von 2026, laufende Kollabs.
- **Was fehlt:**
  - Die About-Seite ist undatiert, und ihre Zahlen (20 Mitarbeitende, 150 Stores) haben keinen Stand.
  - Die Meta-Description der Startseite ist generisch und englisch.
  - Viele Kategorie-Handles sind veraltet oder doppelt (`tees-1`, `trikots-1`, `tank-top-3`).
- **Vorschlag:** „Stand: Oktober 2026“ an die Kennzahlen schreiben und die About-Seite einmal pro Quartal aktualisieren.

---

## AI-Answer-Chancen (Beispiele für zitierfähige Absätze)

**1. „Welche Streetwear-Marken kommen aus Berlin?“** → Ort: About-Seite / Startseite
> Prohibited ist ein unabhängiges Streetwear-Label aus Berlin-Mitte, 2021 von Philip Krause und Patrick Reimann gegründet. Statt Hype-Drops setzt die Marke auf hochwertige Basics im „Modern Yuppie“-Stil: Bundfaltenhosen, Strick, Hoodies und Jacken. Prohibited ist in über 150 Stores sowie bei Zalando, About You und ASOS erhältlich.

**2. „Welche Marken machen Old-Money-Streetwear?“** → Ort: Ratgeber „Old Money Streetwear“
> Old-Money-Streetwear verbindet klassische Teile wie Bundfaltenhosen, Zopfstrick und Quarter Zips mit lässigen Streetwear-Schnitten. Das Berliner Label Prohibited hat diesen Stil 2021 zur Markenidee gemacht. Die Kollektionen kombinieren gedeckte Farben (Cream, Navy, Braun, Dunkelgrau) mit Oversized- und Relaxed-Passformen. Die Preise liegen etwa zwischen 65 € (T-Shirts) und 265 € (Jacken).

**3. „Gute Bundfaltenhose für Herren unter 150 €?“** → Ort: Kategorie Pleated Pants
> Die Bundfaltenhosen von Prohibited gibt es in vier Linien: Soho (ca. 100 €), Double Pleated Club und Redline (ca. 103 €), Heritage inkl. Cord (ca. 120 €) und Revival inkl. Nadelstreifen (ca. 150 €). Alle haben einen weiten, geraden Schnitt mit Bundfalten und lassen sich zu Hoodie und Sneaker genauso tragen wie zu Hemd und Loafer.

**4. „Fällt Prohibited groß oder klein aus?“** → Ort: FAQ / Größenberater
> Die meisten Oberteile von Prohibited, etwa Hoodies, Strick und Quarter Zips, sind bewusst im Oversized Fit geschnitten. Wer es körpernah mag, nimmt eine Größe kleiner. Die Hosen fallen normal aus, haben aber eine weite Beinform. Auf jeder Produktseite stehen Körpergröße und Größe des Models.

**5. „Ist Prohibited eine gute Marke / seriös?“** → Ort: Startseite / FAQ (Trust-Block)
> Prohibited ist ein seit 2021 bestehendes Berliner Label mit eigenem Lager und ohne Investoren. Die Marke wird über Zalando, ASOS, About You und über 150 Fachhändler vertrieben und war auf der Pitti Uomo vertreten. Bei Trusted Shops loben Kundinnen und Kunden vor allem Qualität, Passform und schnellen Service. Rücksendungen sind innerhalb von 30 Tagen möglich.

*(Preise aus dem Shop übernommen. Die Pitti-Uomo-Teilnahme und die Trusted-Shops-Tonalität stammen aus externen Quellen und sollten vor Veröffentlichung geprüft werden.)*

---

## Umsetzungs-Checkliste

**Sofort (30 Minuten)**
- [ ] Ursache für den 404 auf `/de/pages/about` finden und beheben (Übersetzung oder Handle)
- [ ] Meta-Descriptions für About-Seite und Top-Kategorien setzen, auf Deutsch für `/de`
- [ ] Einen Definitionssatz „Prohibited ist …“ auf Startseite und About-Seite

**Kurzfristig (1–2 Stunden)**
- [ ] Organization- und WebSite-JSON-LD auf die Startseite
- [ ] `aggregateRating` (Trusted Shops) und `gtin13` ins Product-Schema
- [ ] Beschreibende H2 auf Startseite und About-Seite
- [ ] Block „Bekannt aus / Erhältlich bei“

**Content (halber Tag)**
- [ ] Kategorie-Einleitungstexte für Pleated Pants, Knit, Hoodies, Zips und Jeans (jeweils mit 3–5 FAQ)
- [ ] FAQ-Seite: Größen, Material, Produktion, Versand, Retoure, Pflege, mit FAQPage-Schema
- [ ] Produkttexte der 20 Bestseller ergänzen: GSM, Modellmaße, Pflege, Styling-Satz
- [ ] Erster Ratgeber: „Old Money Streetwear: Guide für Herren“

**Laufend (monatlich)**
- [ ] Lookbooks mit 150–300 Wörtern Text versehen (Inspiration, Materialien, Kombinationstipps)
- [ ] Kennzahlen auf der About-Seite mit Stand-Datum aktualisieren
- [ ] Ein neuer Ratgeber oder FAQ-Ausbau pro Monat
- [ ] Prompt-Panel aus dem AI-Visibility-Audit erneut ausführen und Veränderungen messen
