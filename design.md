# Design — Emad Ghasemi

A locked design system for the portfolio and About pages.

## Genre

Editorial atelier with an atmospheric layer: material-led, restrained, and image-first.

## Macrostructure family

- Portfolio: Photographic Archive — irregular work grid with a masthead and colophon close.
- Profile: Letter — portrait and considered studio note, followed by a direct contact band.

## Theme

Dark ceramic paper, warm off-white ink, and a sparse terracotta accent. The exact OKLCH values, type, spacing, and motion tokens are in `tokens.css`.

## Typography

- Display: Signika 700, roman.
- Body: IBM Plex Sans 400.
- Outlier: IBM Plex Mono 400 for metadata only.

## Motion

GSAP and ScrollTrigger coordinate three motion primitives: staged content reveals, sequenced media reveals and a two-layer warm aura scrub. Motion changes transform and opacity only, uses restrained `power2.out` easing and runs once for content; reduced motion keeps the full experience static and readable.

## CTA voice

Rectangular terracotta action with a one-pixel rule and direct, single-line copy.

## What pages must share

Masthead, dark ceramic palette, font pairing, terracotta accent restraint, rules, footer treatment, and 4-point spacing scale.

## Exports

Use [`tokens.css`](tokens.css) as the drop-in CSS export. Its semantic custom properties are the source of truth for any future page.
