# Style Presets Reference

Curated visual styles for Frontend Slides. Each preset is inspired by real design references — no generic "AI slop" aesthetics. **Abstract shapes only — no illustrations.**

**Viewport CSS:** For mandatory base styles, see [viewport-base.css](viewport-base.css). Include in every presentation.

---

## Dark Themes

### 1. Bold Signal

**Vibe:** Confident, bold, modern, high-impact

**Layout:** Colored card on dark gradient. Number top-left, navigation top-right, title bottom-left.

**Typography:**
- Display: `Archivo Black` (900)
- Body: `Space Grotesk` (400/500)

**Colors:**
```css
:root {
    --bg-primary: #1a1a1a;
    --bg-gradient: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 50%, #1a1a1a 100%);
    --card-bg: #FF5722;
    --text-primary: #ffffff;
    --text-on-card: #1a1a1a;
}
```

**Signature Elements:**
- Bold colored card as focal point (orange, coral, or vibrant accent)
- Large section numbers (01, 02, etc.)
- Navigation breadcrumbs with active/inactive opacity states
- Grid-based layout for precise alignment

---

### 2. Electric Studio

**Vibe:** Bold, clean, professional, high contrast

**Layout:** Split panel—white top, blue bottom. Brand marks in corners.

**Typography:**
- Display: `Manrope` (800)
- Body: `Manrope` (400/500)

**Colors:**
```css
:root {
    --bg-dark: #0a0a0a;
    --bg-white: #ffffff;
    --accent-blue: #4361ee;
    --text-dark: #0a0a0a;
    --text-light: #ffffff;
}
```

**Signature Elements:**
- Two-panel vertical split
- Accent bar on panel edge
- Quote typography as hero element
- Minimal, confident spacing

---

### 3. Creative Voltage

**Vibe:** Bold, creative, energetic, retro-modern

**Layout:** Split panels—electric blue left, dark right. Script accents.

**Typography:**
- Display: `Syne` (700/800)
- Mono: `Space Mono` (400/700)

**Colors:**
```css
:root {
    --bg-primary: #0066ff;
    --bg-dark: #1a1a2e;
    --accent-neon: #d4ff00;
    --text-light: #ffffff;
}
```

**Signature Elements:**
- Electric blue + neon yellow contrast
- Halftone texture patterns
- Neon badges/callouts
- Script typography for creative flair

---

### 4. Dark Botanical

**Vibe:** Elegant, sophisticated, artistic, premium

**Layout:** Centered content on dark. Abstract soft shapes in corner.

**Typography:**
- Display: `Cormorant` (400/600) — elegant serif
- Body: `IBM Plex Sans` (300/400)

**Colors:**
```css
:root {
    --bg-primary: #0f0f0f;
    --text-primary: #e8e4df;
    --text-secondary: #9a9590;
    --accent-warm: #d4a574;
    --accent-pink: #e8b4b8;
    --accent-gold: #c9b896;
}
```

**Signature Elements:**
- Abstract soft gradient circles (blurred, overlapping)
- Warm color accents (pink, gold, terracotta)
- Thin vertical accent lines
- Italic signature typography
- **No illustrations—only abstract CSS shapes**

---

## Light Themes

### 5. Notebook Tabs

**Vibe:** Editorial, organized, elegant, tactile

**Layout:** Cream paper card on dark background. Colorful tabs on right edge.

**Typography:**
- Display: `Bodoni Moda` (400/700) — classic editorial
- Body: `DM Sans` (400/500)

**Colors:**
```css
:root {
    --bg-outer: #2d2d2d;
    --bg-page: #f8f6f1;
    --text-primary: #1a1a1a;
    --tab-1: #98d4bb; /* Mint */
    --tab-2: #c7b8ea; /* Lavender */
    --tab-3: #f4b8c5; /* Pink */
    --tab-4: #a8d8ea; /* Sky */
    --tab-5: #ffe6a7; /* Cream */
}
```

**Signature Elements:**
- Paper container with subtle shadow
- Colorful section tabs on right edge (vertical text)
- Binder hole decorations on left
- Tab text must scale with viewport: `font-size: clamp(0.5rem, 1vh, 0.7rem)`

---

### 6. Pastel Geometry

**Vibe:** Friendly, organized, modern, approachable

**Layout:** White card on pastel background. Vertical pills on right edge.

**Typography:**
- Display: `Plus Jakarta Sans` (700/800)
- Body: `Plus Jakarta Sans` (400/500)

**Colors:**
```css
:root {
    --bg-primary: #c8d9e6;
    --card-bg: #faf9f7;
    --pill-pink: #f0b4d4;
    --pill-mint: #a8d4c4;
    --pill-sage: #5a7c6a;
    --pill-lavender: #9b8dc4;
    --pill-violet: #7c6aad;
}
```

**Signature Elements:**
- Rounded card with soft shadow
- **Vertical pills on right edge** with varying heights (like tabs)
- Consistent pill width, heights: short → medium → tall → medium → short
- Download/action icon in corner

---

### 7. Split Pastel

**Vibe:** Playful, modern, friendly, creative

**Layout:** Two-color vertical split (peach left, lavender right).

**Typography:**
- Display: `Outfit` (700/800)
- Body: `Outfit` (400/500)

**Colors:**
```css
:root {
    --bg-peach: #f5e6dc;
    --bg-lavender: #e4dff0;
    --text-dark: #1a1a1a;
    --badge-mint: #c8f0d8;
    --badge-yellow: #f0f0c8;
    --badge-pink: #f0d4e0;
}
```

**Signature Elements:**
- Split background colors
- Playful badge pills with icons
- Grid pattern overlay on right panel
- Rounded CTA buttons

---

### 8. Vintage Editorial

**Vibe:** Witty, confident, editorial, personality-driven

**Layout:** Centered content on cream. Abstract geometric shapes as accent.

**Typography:**
- Display: `Fraunces` (700/900) — distinctive serif
- Body: `Work Sans` (400/500)

**Colors:**
```css
:root {
    --bg-cream: #f5f3ee;
    --text-primary: #1a1a1a;
    --text-secondary: #555;
    --accent-warm: #e8d4c0;
}
```

**Signature Elements:**
- Abstract geometric shapes (circle outline + line + dot)
- Bold bordered CTA boxes
- Witty, conversational copy style
- **No illustrations—only geometric CSS shapes**

---

## Specialty Themes

### 9. Neon Cyber

**Vibe:** Futuristic, techy, confident

**Typography:** `Clash Display` + `Satoshi` (Fontshare)

**Colors:** Deep navy (#0a0f1c), cyan accent (#00ffcc), magenta (#ff00aa)

**Signature:** Particle backgrounds, neon glow, grid patterns

---

### 10. Terminal Green

**Vibe:** Developer-focused, hacker aesthetic

**Typography:** `JetBrains Mono` (monospace only)

**Colors:** GitHub dark (#0d1117), terminal green (#39d353)

**Signature:** Scan lines, blinking cursor, code syntax styling

---

### 11. Swiss Modern

**Vibe:** Clean, precise, Bauhaus-inspired

**Typography:** `Archivo` (800) + `Nunito` (400)

**Colors:** Pure white, pure black, red accent (#ff3300)

**Signature:** Visible grid, asymmetric layouts, geometric shapes

---

### 12. Paper & Ink

**Vibe:** Editorial, literary, thoughtful

**Typography:** `Cormorant Garamond` + `Source Serif 4`

**Colors:** Warm cream (#faf9f7), charcoal (#1a1a1a), crimson accent (#c41e3a)

**Signature:** Drop caps, pull quotes, elegant horizontal rules

---

### 13. CMU Dark

**Vibe:** Authoritative, research-driven, bold, confident — for talks, defenses, keynotes

**Title Slide Layout (TWO-COLUMN — mandatory for CMU presets):**
Left column (60%) has title, subtitle, author, affiliation. Right column (40%) displays a featured image — default to the CMU tartan pattern from `assets/cmu-tartan.svg` if no user image is provided. The image fills the right column with `object-fit: cover` and a subtle rounded corner. A thin Carnegie Red vertical divider separates the columns.

```html
<!-- Title slide structure -->
<section class="slide title-slide">
  <div class="title-left">
    <img src="cmu-logo.png" alt="CMU" class="title-logo">
    <div class="title-eyebrow">venue · event</div>
    <h1 class="title-main">Talk Title</h1>
    <p class="title-sub">Subtitle</p>
    <div class="title-meta">name · affiliation · date</div>
  </div>
  <div class="title-right">
    <div class="title-image" style="background-image: url('assets/cmu-tartan.svg')"></div>
  </div>
</section>
```

**Layout:** Dark background with Carnegie Red accent bars. Slide numbers top-left, content centered or two-column.

**Typography:**
- Display: `Source Serif 4` (600/700/900) — official CMU serif
- Body: `Open Sans` (300/400/500/600) — official CMU sans-serif

**Colors:**
```css
:root {
    --bg-primary: #0C0C0C;
    --bg-slide: #111111;
    --bg-card: #1A1A1A;
    --text-primary: #F2F0ED;
    --text-secondary: #9A9A9A;
    --carnegie-red: #C41230;
    --iron-gray: #6D6E71;
    --steel-gray: #E0E0E0;
    --blue-thread: #043673;
    --highlands-blue: #007BC0;
    --gold-thread: #FDB515;
    --green-thread: #009647;
    --teal-thread: #008F91;
    --weaver-blue: #182C4B;
}
```

**Signature Elements:**
- **Two-column title slide** with tartan image on the right (see layout above)
- Top accent bar on every slide: `linear-gradient(90deg, Carnegie Red 0% 30%, Blue Thread 100%)`
- Carnegie Red slide numbers in Source Serif 4
- Paper cards with left red border for citing works
- Stat callouts with large Source Serif 4 numbers in Carnegie Red
- Highlight boxes with red-tinted background (`rgba(196,18,48,0.08)`) and red border
- Subtle radial gradients using Carnegie Red and Blue Thread for depth on title/closing slides
- **Fragment animations**: bullet points and key elements appear one-by-one on keypress (see SKILL.md fragment rules)

---

### 14. CMU Light

**Vibe:** Clean, academic, traditional, approachable — for seminars, tutorials, classroom talks

**Title Slide Layout (TWO-COLUMN — mandatory for CMU presets):**
Same two-column structure as CMU Dark: left column (60%) has title content, right column (40%) displays a featured image. Default to the CMU tartan pattern from `assets/cmu-tartan.svg`. On light theme the image panel has a subtle warm shadow and 12px rounded corners.

```html
<!-- Same structure as CMU Dark — only colors differ -->
<section class="slide title-slide">
  <div class="title-left">...</div>
  <div class="title-right">
    <div class="title-image" style="background-image: url('assets/cmu-tartan.svg')"></div>
  </div>
</section>
```

**Layout:** Light cream background with Carnegie Red accents. Clean, generous whitespace. Slide numbers in Iron Gray.

**Typography:**
- Display: `Source Serif 4` (600/700/900) — official CMU serif
- Body: `Open Sans` (300/400/500/600) — official CMU sans-serif

**Colors:**
```css
:root {
    --bg-primary: #FAFAF8;
    --bg-slide: #FFFFFF;
    --bg-card: #F5F3EE;
    --text-primary: #1A1A1A;
    --text-secondary: #555555;
    --carnegie-red: #C41230;
    --iron-gray: #6D6E71;
    --steel-gray: #E0E0E0;
    --blue-thread: #043673;
    --highlands-blue: #007BC0;
    --gold-thread: #FDB515;
    --green-thread: #009647;
    --teal-thread: #008F91;
    --kittanning-beige: #E4DAC4;
    --machinery-tan: #BCB49E;
}
```

**Signature Elements:**
- **Two-column title slide** with tartan image on the right (see layout above)
- Thin Carnegie Red top accent bar on every slide (3px solid, no gradient)
- Slide numbers in Iron Gray (#6D6E71)
- Content cards with cream background (`#F5F3EE`), subtle shadow, and left red border
- Stat callouts in Carnegie Red with light warm background
- Highlight boxes with warm beige background (`#E4DAC4` at 30% opacity) and red left border
- Generous padding and whitespace — the "academic paper" feel
- **Fragment animations**: bullet points and key elements appear one-by-one on keypress (see SKILL.md fragment rules)

**Brand Reference (both CMU presets):** https://brand.cmu.edu/visual-identity — four core colors (Carnegie Red #C41230, Black, Iron Gray #6D6E71, Steel Gray #E0E0E0) plus Tartan and Campus secondary palettes. Only use Open Sans and Source Serif 4 (substitute: Helvetica / Times). Default tartan image: [assets/cmu-tartan.svg](assets/cmu-tartan.svg).

---

## Font Pairing Quick Reference

| Preset | Display Font | Body Font | Source |
|--------|--------------|-----------|--------|
| Bold Signal | Archivo Black | Space Grotesk | Google |
| Electric Studio | Manrope | Manrope | Google |
| Creative Voltage | Syne | Space Mono | Google |
| Dark Botanical | Cormorant | IBM Plex Sans | Google |
| Notebook Tabs | Bodoni Moda | DM Sans | Google |
| Pastel Geometry | Plus Jakarta Sans | Plus Jakarta Sans | Google |
| Split Pastel | Outfit | Outfit | Google |
| Vintage Editorial | Fraunces | Work Sans | Google |
| Neon Cyber | Clash Display | Satoshi | Fontshare |
| Terminal Green | JetBrains Mono | JetBrains Mono | JetBrains |
| CMU Dark | Source Serif 4 | Open Sans | Google |
| CMU Light | Source Serif 4 | Open Sans | Google |

---

## DO NOT USE (Generic AI Patterns)

**Fonts:** Inter, Roboto, Arial, system fonts as display

**Colors:** `#6366f1` (generic indigo), purple gradients on white

**Layouts:** Everything centered, generic hero sections, identical card grids

**Decorations:** Realistic illustrations, gratuitous glassmorphism, drop shadows without purpose

---

## CSS Gotchas

### Negating CSS Functions

**WRONG — silently ignored by browsers (no console error):**
```css
right: -clamp(28px, 3.5vw, 44px);   /* Browser ignores this */
margin-left: -min(10vw, 100px);      /* Browser ignores this */
```

**CORRECT — wrap in `calc()`:**
```css
right: calc(-1 * clamp(28px, 3.5vw, 44px));  /* Works */
margin-left: calc(-1 * min(10vw, 100px));     /* Works */
```

CSS does not allow a leading `-` before function names. The browser silently discards the entire declaration — no error, the element just appears in the wrong position. **Always use `calc(-1 * ...)` to negate CSS function values.**

