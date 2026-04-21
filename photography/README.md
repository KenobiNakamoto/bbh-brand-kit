# Photography

Approved BBH imagery. All photos in this directory have been cleared for use under the CC BY-NC 4.0 license (see repo root `LICENSE`).

## Founders

| File | Subject | Crop | Use |
|------|---------|------|-----|
| `founders/founders-group-wide.jpg`      | All three co-founders, wide framing  | 3:4 landscape | Website hero-support, editorial features |
| `founders/founders-group-portrait.jpg`  | All three co-founders, portrait       | 3:4 portrait  | Social story, magazine column |
| `founders/founders-group-square.jpg`    | All three co-founders, centered       | 1:1           | Instagram, LinkedIn thumbnails |
| `founders/kenobi-portrait.jpg`          | General Kenobi, solo crop             | 3:8 tall      | Speaker card (website), bio badge |
| `founders/losku-portrait.jpg`           | Lightning Losku, solo crop            | 3:8 tall      | Speaker card (website), bio badge |
| `founders/jordi-portrait.jpg`           | Jordi Llong, solo                     | 1:1           | Speaker card, Nostr avatar |
| `founders/founders-group-ORIGINAL.jpg`  | Full-resolution (4MB, 4032×3024)      | 4:3           | Print, editorial full-page |
| `founders/jordi-portrait-ORIGINAL.jpg`  | Full-resolution                        | 1:1           | Print, editorial |

## Meetups

| File | Subject | Use |
|------|---------|-----|
| `meetups/meetup-01.jpg` | Venue — attendees gathering in the main hall | Hero reportage |
| `meetups/meetup-02.jpg` | Audience during a talk | Feature / social |
| `meetups/meetup-03.jpg` | A speaker presenting | Feature / social |
| `meetups/meetup-04.jpg` | Crowd reaction / Q&A | Social |
| `meetups/meetup-05.jpg` | Terrace drinks after the talk | Community / atmosphere |

All files are optimized JPEGs, maximum 1200px on the long edge, quality 75–80, progressive encoding. Suitable for web without further processing. For print, request the original RAW/full-resolution files via `barcelona_btc_hub@proton.me`.

## Brand treatment

When displaying any of these photos in BBH material:

1. Apply grayscale filter: `filter: grayscale(100%) contrast(1.06);`
2. Add a 1px solid ink border: `border: 1px solid #010101;`
3. Caption in eyebrow style below the image (UPPERCASE, 12px, stone color, 0.12em letter-spacing).
4. Never full-bleed. Always contained with visible borders.

## Attribution

Non-commercial use:

> "Photograph: Barcelona Bitcoin Hub"

Place this near the image (caption, margin, or image alt text). No other permission required.

Commercial use requires written permission. Contact `barcelona_btc_hub@proton.me`.

## Adding new photos

1. Export from RAW at quality 85, max 1800px on long edge.
2. Run through `jpegoptim --max=80 --strip-all --progressive` or equivalent to produce the shipping file.
3. Name in kebab-case: `event-YYYY-MM-DD-short-description.jpg` or `founders-<subject>.jpg`.
4. Add a row to the tables above.
5. Commit with a message like `feat(photos): add meetup XVI reportage`.
