# Design — Emad Ghasemi

A locked design system for the portfolio and About pages.

## Genre

Editorial atelier: material-led, restrained, and image-first.

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

Quiet image lift and colour shifts only. Reduced motion collapses to a short opacity crossfade.

## CTA voice

Rectangular terracotta action with a one-pixel rule and direct, single-line copy.

## What pages must share

Masthead, warm-paper palette, font pairing, terracotta accent restraint, rules, footer treatment, and 4-point spacing scale.

## Exports

Use [`tokens.css`](tokens.css) as the drop-in CSS export. Its semantic custom properties are the source of truth for any future page.
