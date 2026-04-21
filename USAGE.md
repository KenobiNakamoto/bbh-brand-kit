# USAGE.md

A quick-start guide for producing BBH material. Read this before designing a poster, building a landing page, or publishing a social post.

---

## Philosophy in one paragraph

BBH is **Financial Times × Bitcoin Magazine**. It's an editorial brand — parchment paper, midnight ink, an accent of Bitcoin Orange. It is not a tech brand, not a crypto brand, not a startup brand. The visual language borrows from newspapers and serious journals: mastheads, editorial rules, pull quotes, numbered editions, grayscale photography. The rule of thumb: *if it would look at home in a 1970s financial weekly, it is on-brand.*

## Designer checklist

Before shipping any BBH material, confirm every item below is true:

- [ ] The background is **Parchment Cream (#F0E8D5)** or **Parchment Cream Light (#F7F3EA)** — not white, not off-white.
- [ ] The background carries the three-layer paper grain texture (or, for print, a visible paper texture).
- [ ] Bitcoin Orange appears **at most once or twice per viewport**, and never as body text.
- [ ] All photography is **grayscale** with a **1px ink border**.
- [ ] Headlines use **The Seasons**. Body copy uses **Inter** (or a system sans).
- [ ] The BBH logo has at least **one mark-height of clear space** around it.
- [ ] No reference to price, trading, altcoins, or returns.
- [ ] Every title includes the meetup number where applicable: **№ XVI** (roman) for marketing, **№ 16** (arabic) for tables.

## Developer quick-start

```bash
# 1. Add the brand kit as a git submodule (or clone it next to your project)
git submodule add https://github.com/<owner>/bbh-brand-kit.git brand

# 2. Import the tokens in your main stylesheet
@import url("./brand/design-tokens/tokens.css");

# 3. Reference the variables
body {
  background: var(--bbh-paper);
  color: var(--bbh-charcoal);
  font-family: var(--bbh-sans);
}
h1, h2, h3 {
  font-family: var(--bbh-display);
  color: var(--bbh-ink);
}
```

For the paper texture, copy the `.paper` class from `design-tokens/paper-texture.css` into your stylesheet (it's a three-layer SVG turbulence).

## Poster / deck cheat sheet

- **Cover slide or poster head**: masthead strip at the very top (uppercase sans, 12px, 0.22em letter-spacing, bordered above and below), then a large serif headline, then a 3px × 56px Bitcoin Orange rule, then a 64ch-max deck.
- **Body slides**: Parchment Cream background, ink-ruled section dividers, 64ch columns max. Photography grayscale, bordered, captioned in eyebrow style below.
- **Closing slide**: Solo Bitcoin declaration, centered, large. Orange italics on the words "Solo Bitcoin".

## Social post cheat sheet

- **Square 1080×1080**: Parchment background. Masthead at top. Headline in The Seasons. One grayscale photo. BBH square logo bottom-right with mark-height of clear space. Meetup number top-left.
- **Story 1080×1920**: Vertical editorial. Masthead top. Pull-quote style headline, italic emphasis in orange on the key phrase. Logo bottom.
- **Twitter/X header 1500×500**: Paper texture base. Grayscale photo with ink border, right-aligned. Wordmark left. "Solo Bitcoin. Since 2025." in eyebrow style.

## What NOT to do

The following are off-brand and should never ship:

1. **Purple, gradient, or neon.** BBH does not use gradients. Colors are flat.
2. **Sans-serif headlines.** The Seasons only, for anything display-sized.
3. **Colour photography.** Every photo is grayscaled.
4. **"To the moon" / rocket emojis / price charts.** These violate Solo Bitcoin.
5. **Logo on coloured backgrounds.** Black logo on Parchment or Paper Light only; white logo on Midnight Ink only. No colour-on-colour combinations.
6. **Modified logo.** Do not skew, rotate, recolour, or inset the marks.
7. **Full-bleed photography in hero sections.** Photos are always contained, bordered, captioned — not backgrounds.
8. **Pure white (#FFFFFF) as a page background.** Cards are white; pages are Parchment.
9. **Bitcoin Orange as body copy.** Accents only.
10. **"The Seasons" at body-copy sizes.** Display type only (18px+).

## Attribution

If you use BBH material publicly:

- **Photography**: "Photograph: Barcelona Bitcoin Hub" (visible near the image).
- **Logos**: "Logo © Barcelona Bitcoin Hub. Used with permission." in a colophon, if the use is adjacent to a third-party brand.
- **Writing from `design-tokens/voice-and-motifs.json` signature phrases**: No attribution required, but the phrase "Bitcoin. Sin ruido." is the brand slogan — use it editorially, not promotionally.

## Questions

Email `barcelona_btc_hub@proton.me` before producing anything at scale. We'll reply.
