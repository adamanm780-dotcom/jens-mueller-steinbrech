# Inspo — Friseur Müller-Steinbrech (Branche: Friseur, Beauty-Editorial)

## Übergeordnete Richtung
Editorial Beauty mit warmem, ruhigem Ton: cremiges Beige + Off-White als Grundfläche, Roségold/Kupfer als feiner Akzent, Cormorant-Serif für Statements, Inter für Sans-Body. Kein lautes Pink-Trend-Beauty — eher die "Haute Coiffure"-Linie: Atelier-Würde, Familienhandwerk, leise Eleganz. Tradition seit 50 Jahren ist das Anchor-Motiv, nicht "trendy salon".

## Referenzen

### 1. Haute Coiffure (Editorial Atelier)
- URL: dribbble.com/search/hair-salon-website-luxury — Shot „Haute Coiffure"
- Stil: editorial cream serif circular-portrait
- Übernehmen:
  - Asymmetrischer Hero: Riesen-Serif-Headline links („Haute Coiffure"-Style), Kreis-Portrait rechts mit Inset-Border
  - 3-Spalten-Bento darunter: „2025 Award" / „Studio Services" / „Specialty"
  - Buttons rounded-pill mit subtiler Outline
- Screenshot: inspo/grid.png + inspo/grid-salon.png

### 2. All About Hair Fashion (Sand/Beige Warm)
- URL: dribbble.com/search/hair-salon-website-luxury — Shot „All About Hair Fashion"
- Stil: warm sand serif soft-glow
- Übernehmen:
  - Sehr warmer Beige-Hintergrund mit weichem Hair-Hero rechts
  - Headline-Mix: bold serif + cursive serif („Hair Fashion") für Spannung
  - Such-/Filter-Bar als kleiner Booking-Anker
- Screenshot: inspo/grid-salon.png

### 3. Luxury Boutique Salon Experience (Dark Atelier)
- URL: dribbble.com/search/hair-salon-website-luxury — Shot „Luxury Boutique Salon"
- Stil: dark atelier cinematic
- Übernehmen:
  - Volle Atelier-Innenraum-Aufnahme (Stuhl, Spiegel, Werkstatt-Detail)
  - Section-Heading „WHY [Salon]?" — 3 USPs in Bento
  - Sehr ruhige Typografie, viel Whitespace
- Screenshot: inspo/grid-salon.png

### 4. Elegance, Refined (Editorial Masonry Pink-Cream)
- URL: dribbble.com/search/hair-salon-website-luxury — Shot „Elegance Refined"
- Stil: pink-cream masonry magazine
- Übernehmen:
  - Detail-Grid mit ungleichen Höhen (Masonry-Feel) für Insta-/Maps-Material
  - „Our Masterpieces" als Section-Heading mit Mix aus Innenraum + Resultat-Shots
  - Team-Sektion als kleines 4er-Grid
- Screenshot: inspo/grid-salon.png

### 5. Editorial Perfume Layout (PARIS-Style)
- URL: dribbble.com/search/editorial-beauty-website — „PARIS" perfume
- Stil: cream serif editorial product
- Übernehmen:
  - Über-uns-Section als Magazin-Doppelseite (Image links + Body rechts mit großer Initiale)
  - Marquee-Tags-Leiste mit Leistungen („Damenhaarschnitt · Coloration · Strähnen · Dauerwelle")
- Screenshot: inspo/grid-2.png

### 6. FaceTheory (Clean Editorial Portrait)
- URL: dribbble.com/search/editorial-beauty-website — „FaceTheory"
- Stil: clean cream big-portrait
- Übernehmen:
  - Eine ganz große ruhige Hero-Aufnahme als Anker (Frau mit Kurzhaar — passt zu Spezialität!)
  - Ruhig gesetzter Tagline „Ihr Look, beraten" o.ä.
- Screenshot: inspo/grid-2.png

## Konkrete Anpassungen für Phase 6
- **Font-Pair**: `Cormorant Garamond` (Display/Headlines) + `Inter` (Body/UI). Begründung: Cormorant trägt das „Atelier/Tradition"-Gefühl ohne in Beauty-Cliché zu rutschen, Inter hält die Lese-Ergonomie clean.
- **Hero-Treatment**: Asymmetrisch wie „Haute Coiffure" — links Display-Serif-Headline „Friseur seit 1972" o.ä., rechts ruhiges Hero-Portrait/Detail-Foto mit Inset-Border (kein Kreis, weil Brand klassisch ist — eher Rechteck mit Inset 18px Border in Akzentfarbe). Tags-Leiste unten am Hero („Schnitt · Coloration · Termin").
- **Section-Flourishes**:
  - Marquee-Leiste mit Service-Tags zwischen Hero und Intro
  - Categories als 3er-Bento (Damenhaarschnitt / Coloration & Strähnen / Behandlungen) mit Image+Title+Body
  - „Atelier-Section" Magazin-Style: portrait-Bild + Body mit Drop-Cap, „3. Generation" Subheadline
  - Detail-Grid 6-Bilder (Masonry-feel via unterschiedliche Höhen, Ken-Burns subtil)
- **Mikro-Interaktionen**:
  - Hover-Scale 1.04 auf alle Bilder (sanft, 800ms ease)
  - Underline-Reveal auf Nav
  - Fade-in-on-Scroll via IntersectionObserver
  - Sehr subtile Ken-Burns auf Hero (22s Loop)
- **Farb-Mood-Hinweis**: Hero-Palette wird **warm-creme + roségold/kupfer-Akzent** statt klassisch dunkel — kein „luxury low-key dark", sondern „editorial bright cream". `--bg` ist hellbeige (nicht schwarz!), `--text` ist warm-anthrazit, `--accent` roségold/kupfer.

## Limited inspo
Cloudflare hat Shot-Detail-Pages teils blockiert — wir arbeiten mit den Such-Grid-Screenshots als Pattern-Referenz. Reicht für die Synthese-Entscheidungen oben.
