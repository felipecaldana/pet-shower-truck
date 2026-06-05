# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Static website for **Pet Shower Truck** — a mobile dog grooming business (banho e tosa) serving Monte Mor - SP, Brazil.

No build step, no dependencies, no package manager. Open `index.html` directly in a browser to preview.

```bash
xdg-open index.html   # Linux
open index.html        # macOS
```

## Architecture

Single-page site, three files:

- `index.html` — all content and structure. Sections in order: navbar, hero, sobre, serviços, galeria, contato, footer, floating WhatsApp button.
- `style.css` — mobile-first CSS using custom properties (`:root` variables). Breakpoints at 900px and 640px.
- `script.js` — minimal JS: hamburger menu toggle and navbar shadow on scroll.

## Key details

- **WhatsApp number:** `5519994174917` — used in `wa.me/` links and `tel:` href throughout `index.html`.
- **Instagram:** `https://www.instagram.com/petshowertruck/`
- **Photos:** placed in `images/` and referenced as `<img src="images/filename.jpg">` inside the `.galeria-grid` div. Current placeholders are `.foto-placeholder` divs — replace them with `<img>` tags when real photos are available.
- **Color palette** (defined as CSS variables in `style.css`): `--turquesa: #00B4D8`, `--amarelo: #FFD60A`, `--laranja: #FF6B35`, `--texto: #1A1A2E`.
- **Font:** Poppins via Google Fonts (loaded in `<head>`).
