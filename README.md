# Kasper Studio

A fully refactored single-page creative studio website — built with semantic HTML and modern CSS. No frameworks, no JavaScript dependencies, no build tools.

---

## What's Inside

### HTML

- Correct landmark structure — `<main>`, `<header>`, `<footer>`, `<section>`, `<article>`
- Single `<h1>` with a clean heading hierarchy throughout
- Accessible forms — every input has a visible or `sr-only` label
- ARIA roles on interactive elements — slider dots, progress bars, nav toggle
- `loading="lazy"` on all below-fold images
- `<dl>/<dt>/<dd>` for statistics, `<blockquote>/<cite>` for testimonials and quotes
- Real written content — no lorem ipsum

### CSS

- Full design token system via CSS custom properties — colors, spacing, typography, transitions
- BEM-namespaced selectors — zero class collisions
- Single consistent breakpoint scale — `768px / 992px / 1200px`, mobile-first throughout
- DRY overlays — one reusable pattern replacing seven duplicated `::before` blocks
- `rem`-based typography — respects browser font size preferences
- `:focus-visible` styles on every interactive element
- Custom scrollbar styled to match brand identity
- No `outline: none` without a replacement focus indicator

### Sections

- Header — fixed with glassmorphism scroll state, animated underline nav
- Hero — full-viewport, parallax background, animated entrance, dual CTA
- Services — icon cards with hover lift
- Features — full-bleed background, 2×2 feature grid
- Portfolio — filterable grid, caption slide-up on hover
- Video — cinematic full-bleed autoplay showreel
- About — section header + three content cards
- Statistics — parallax background, branded overlay grid
- Testimonials + Skills — side-by-side, gradient skill bars
- Quote Banner — parallax, large decorative quote mark
- Pricing — four cards with featured state and badge
- Subscribe — two-column layout, glowing input focus
- Contact — visible labels, four info blocks, side panel
- Footer — three-column with social icons, split bottom bar

---

## File Structure

```text
KASPER/
├── assets/          — images and video
├── css/
│   ├── all.min.css  — Font Awesome
│   ├── normalize.css
│   └── kasper.css   — main stylesheet
├── webfonts/        — Font Awesome webfonts
└── index.html
```

---

## Fonts & Icons

- **Open Sans** via Google Fonts — weights 300 / 400 / 500 / 700 / 800
- **Font Awesome 6** (self-hosted) — solid, regular, brands

---

## Deployment

Static site — no build step required. Drop the folder into [Vercel](https://vercel.com), [Netlify](https://netlify.com), or any static host.

```bash
git init
git add .
git commit -m "initial: kasper studio"
# push to GitHub → connect to Vercel
```
