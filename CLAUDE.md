# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **KitchenMax landing page** project — a single-page HTML site for KitchenMax.store, an industrial/commercial kitchen equipment company based in Zapopan, Jalisco, Mexico. Part of Grupo Kingstrong.

## Architecture

- **Single file**: `kitchenmax-landing.html` — self-contained HTML/CSS/JS landing page (no build tools, no frameworks)
- **Assets**: Images stored as flat files in root directory (`.png`, `.webp`)
- **No package manager or build step** — open the HTML file directly in a browser to preview

## Key Files

- `kitchenmax-landing.html` — The complete landing page
- `preview.webp` — Official KitchenMax logo (SKS icon + "KitchenMax.store" text, light bg `#fcfcfc`)
- `preview (1).webp` — Mexico map image (black background) for cobertura section
- `preview (2).webp` — Industrial kitchen photo for hero background
- `Banner shopify KM (9-14).png` — Section images for "Tipos de proyecto" cards
- `document_pdf.pdf` — Company profile PDF ("Quienes somos")

## Brand Guidelines

- **Colors**: Negro `#0d0d0d`, Rojo institucional `#c8102e`, Blanco `#ffffff`, Gris acero `#1a1a1a`
- **Nav background**: `#fcfcfc` (matches logo background exactly)
- **Cobertura section background**: `#000000` (matches map image background)
- **Typography**: Inter (Google Fonts), sans-serif, geometric, professional — never friendly/rounded
- **Tone**: Technical, structured, high-level positioning — NOT a store/ecommerce page
- **No**: promotions, discounts, prices, counters, urgency, multiple CTAs, rounded borders, emojis

## Landing Page Sections (in order)

1. **Nav** — Logo image + links + red CTA button on light `#fcfcfc` background
2. **Hero** — Left-aligned title "PROYECTOS EN TODO MEXICO" with "MEXICO" in red, kitchen bg image with dark overlay, single red CTA
3. **Modelo de trabajo** — White bg, horizontal 4-column cards (01-04) with hover expand showing bullet details + red bar animation
4. **Cobertura** — Black bg, Mexico map image, centered title
5. **Tipos de proyecto** — Dark bg, 3x2 grid cards with images, red left-bar on hover
6. **Metodologia** — White bg, horizontal timeline with black circles (01-05) connected by red line
7. **Perfil del cliente** — Light gray bg, checklist with red checks + Grupo Kingstrong dark card
8. **CTA/Contacto** — Dark bg, centered form in white card, red submit button
9. **Footer** — Logo + contact info

## Development

To preview: open `kitchenmax-landing.html` in any browser. No server needed.

Image references use relative paths with spaces (e.g., `"Banner shopify KM (9).png"`), so the HTML file must remain in the same directory as the images.
