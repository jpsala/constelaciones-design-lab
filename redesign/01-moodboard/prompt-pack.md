# Prompt Pack — Moodboard / Images

Use this before Figma/HTML. Goal: find a visual world for Rocío’s public site, not final copy.

## Global negative prompt

```text
no AI landing page, no SaaS gradient blobs, no glassmorphism, no floating abstract shapes, no generic wellness stock, no mystical theater, no tarot, no crystals, no candles, no smoke, no zodiac symbols, no dramatic therapy scene, no exaggerated spirituality, no promises of healing, no luxury spa aesthetic, no clinical medical look, no unreadable busy layout, no desktop form squeezed into mobile, no legible generated text, no fake Spanish copy, no hand grabbing wooden figures by the head
```

## Suggested palette anchor

- warm paper `#fffaf3`
- sand background `#f8f2e8`
- dark ink `#332923`
- olive `#6b8f71`
- clay `#b9824f`
- soft gold `#f0c27b`

Use palette as atmosphere, not as rigid tokens yet.

---

## Lane 1 — Tactile / grounded table

The site feels like a real table where someone arrives with a question: paper, notebook, wooden representatives, morning light, tactile calm.

### Prompt 1 — mobile north-star still life

```text
Mobile-first website visual direction mockup for a warm family constellations booking site, 390px phone composition, tactile warm paper background, large documentary photo area with a calm wooden table, small wooden constellation figures, blank notebook and pen, soft morning window light, olive green and clay accents, clear booking area represented by simple UI blocks, clean placeholder typography with no readable text, human grounded atmosphere, refined but not SaaS, no mystical props
```

Aspect ratio: `9:16`.

### Prompt 2 — desktop split composition

```text
Desktop homepage visual direction for a grounded family constellations facilitator, split composition with a warm tactile table scene on one side and calm booking blocks on the other, wooden figures, blank cream paper, linen cloth, notebook, soft natural light, olive and clay accents, editorial website layout, placeholder typography only, no readable text, no glass cards, no SaaS hero, no mystical wellness aesthetic
```

Aspect ratio: `16:9`.

### Prompt 3 — production hero asset

```text
Warm editorial documentary photo of a calm work table for a family constellations facilitator, natural morning light, linen tablecloth, blank cream paper, simple pencil, ceramic cup, a few small wooden figures placed gently, human and grounded atmosphere, tactile materials, shallow depth of field, Mar del Plata home studio feeling, no text, no logos, no crystals, no candles, no tarot, no mystical symbols, no hands grabbing figures, not wellness stock, 4:5 vertical composition
```

Aspect ratio: `4:5` or `3:4`.

---

## Lane 2 — Calm ritual studio

The site opens on the space before people arrive: a prepared room, chairs, quietness, invitation. More group encounter than product booking.

### Prompt 1 — prepared room mobile

```text
Mobile-first website visual direction for a small group encounter in Mar del Plata, calm room prepared before participants arrive, simple chairs in a gentle circle, warm natural light, side table with a few wooden constellation figures, paper and pen, tactile neutral materials, subtle olive and clay palette, booking elements as understated blocks, placeholder typography only, no readable words, no spiritual clichés, no candles, no crystals, no therapy drama
```

Aspect ratio: `9:16`.

### Prompt 2 — quiet room photo

```text
Quiet prepared room for a small group encounter, simple chairs in a gentle circle, warm natural light, understated Mar del Plata studio atmosphere, tactile floor and neutral walls, a few wooden constellation figures on a side table, calm and human, no spiritual clichés, no candles, no crystals, no dramatic therapy scene, editorial documentary photography, warm paper tones, subtle olive accents
```

Aspect ratio: `16:9` and `4:5`.

### Prompt 3 — room plus booking artifact

```text
Editorial website layout concept where a prepared circle of chairs and a booking card coexist naturally, mobile-first public site, calm group encounter atmosphere, tactile paper card for date and reservation, warm neutral room, olive green and clay details, restrained motion cues implied, no readable text, no generic landing page, no mystical props
```

Aspect ratio: `9:16`.

---

## Lane 3 — Mobile booking clarity, editorial not transactional

The site is a clear mobile booking page but visually differentiated: date/reservation are physical artifacts, not generic cards.

### Prompt 1 — booking as physical pieces

```text
Mobile-first landing page visual direction for booking a family constellations group encounter, 390px phone layout, date, place, payment and testimonials represented as tactile paper pieces arranged on a warm table, primary CTA as a strong but warm object, documentary image fragments, clean accessible placeholder UI, no readable text, no SaaS cards, no glassmorphism, no generic app template, human and calm
```

Aspect ratio: `9:16`.

### Prompt 2 — editorial reservation poster

```text
Editorial mobile web layout inspired by a warm event poster and booking table, family constellations in Mar del Plata, large date module, calm image area with wooden figures, trust/testimonial cue, simple reservation action, tactile paper, olive and clay palette, strong hierarchy, placeholder typography only, no readable text, not commercial SaaS, not spiritual cliché
```

Aspect ratio: `9:16`.

### Prompt 3 — testimonial notes as visual system

```text
Editorial still life of small handwritten testimonial notes on warm paper, wooden family constellation figures nearby, soft natural light, intimate human atmosphere, anonymous and respectful, no dramatic promises, no therapy clichés, no mystical props, warm neutral palette with olive and clay accents, refined mobile-friendly composition, no legible generated text
```

Aspect ratio: `4:5`.

---

## Tool notes

### Krea

- Best first tool for taste/moodboard exploration.
- Create a moodboard in the webapp from accepted images.
- Use moodboard strength around `0.35` initially; raise only if outputs drift.
- Generate many quick `9:16` mobile compositions; choose, do not over-tune.

### Adobe Firefly Boards

- Best for arranging references, remixing and comparing.
- Use selected images as style reference and composition reference.
- Use artboards/mosaic to compare lanes.

### Recraft V4

- Use Exploration Mode when unsure: one prompt returns 8 directions.
- Good for comparing composition and visual taste quickly.
- Keep generated UI text disabled / placeholder only.
