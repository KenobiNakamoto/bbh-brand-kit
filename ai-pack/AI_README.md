# AI_README — Brand context for LLMs

> **For AI agents / LLMs / copilots**: This file is a compressed, self-contained brand context pack. Read it (or paste it into your prompt) before producing any BBH material. It is designed to fit in ~2,000 tokens and contain everything needed to ship on-brand.

---

## Who is this brand

**Barcelona Bitcoin Hub (BBH)** is a Bitcoin-only meetup in Barcelona, Spain. Founded February 2025. Hosted at Passeig de Gràcia 19 — the former Barcelona Stock Exchange, now Barcelona Finance Hub (BFH). Three co-founders: General Kenobi (economics/macro), Lightning Losku (accounting/tax), Jordi Llong (sovereignty/Nostr). One talk a month, fifteen-plus months running.

**Tagline**: *Bitcoin. Sin ruido.* (Bitcoin. Without noise.)
**Cardinal rule**: *Solo Bitcoin. No price. No trading. No altcoins.*

## Aesthetic

Editorial, serious, warm. *Financial Times × Bitcoin Magazine*. Think 1970s financial weekly. **Never** crypto-bro, Web3, tech startup, or neon cyberpunk.

## Palette (hex)

```
ink         #010101    // Midnight Black — text, rules, borders. NOT pure #000.
paper       #F0E8D5    // Parchment Cream — default background. Always textured.
paper-light #F7F3EA    // Parchment Cream Light — alternate sections.
white       #FFFFFF    // Pure White — cards only, NEVER pages.
orange      #F7931A    // Bitcoin Orange — accent ONLY. Never body text. Never background.
orange-deep #D67A0E    // Hover state for orange.
stone       #8C8274    // Warm Stone — captions, meta labels.
stone-soft  #C9C0AE    // Soft rules, image placeholders.
charcoal    #2B2B2B    // Body paragraph copy. Softer than ink.
```

## Typography

- **Display** (h1–h3, pull quotes): **The Seasons** (serif). Weights 400, 700. Never below 18px. Italics reserved for emphasized words in quotes.
- **Body** (paragraphs, buttons, eyebrows): **Inter** (sans). Weights 400/500/600/700.
- Eyebrows and meta labels: UPPERCASE, letter-spacing 0.22em for eyebrows, 0.06–0.12em for meta. Always in stone color.

## Must-follow rules

1. **Solo Bitcoin.** No mention of price, trading, altcoins, or returns in any BBH material. Ever.
2. **Photography is grayscale.** CSS filter: `grayscale(100%) contrast(1.06)`. Always with a 1px ink border.
3. **Paper texture mandatory.** Every page has the three-layer SVG turbulence (see `design-tokens/tokens.css` + `paper-texture.css`). Never a flat background.
4. **Bitcoin Orange is an accent.** Max 1–2 uses per viewport. Never body text. Never full backgrounds.
5. **The Seasons is display only.** Never for body copy or UI labels.
6. **No full-bleed hero photos.** Photos are contained, bordered, captioned.
7. **Pure white (#FFF) is for cards.** Page background is always Parchment Cream.
8. **Number every meetup.** `№ XVI` in marketing (Roman), `№ 16` in archives (Arabic).

## Signature phrases (use verbatim)

- "Bitcoin. Sin ruido." (slogan)
- "Solo Bitcoin. No price. No trading. No altcoins." (opening declaration)
- "One talk a month. Zero interruptions."
- "Drinks on the terrace. Dinner after the talk."
- "A family first, a meetup second."
- "The Trojan horse at Passeig de Gràcia 19." (venue metaphor)

## Voice

Short declarative sentences. First-person plural ('we') when speaking as hosts. Bilingual — Spanish and English are both first-class, and either can appear in the same piece. Treat the reader as an intelligent adult. No hype, no emojis (except very rarely ₿), no rocket metaphors.

## Off-brand — do not produce

- Gradients of any kind.
- Neon, purple, or non-palette colours.
- Sans-serif headlines or script typography.
- Colour photography.
- Price charts, "to the moon," rocket emojis, HODL, WAGMI, ser.
- Cryptocurrency references beyond Bitcoin. No "crypto" as a general term.
- Modified or recoloured logos.
- Marketing language like "leverage," "unlock," "revolutionary," "disrupt."
- Web3, DeFi, NFT, DAO terminology.

## When producing a deliverable

Before you write/render output, confirm:

1. Did I honour Solo Bitcoin? (no price, no trading, no altcoins)
2. Is the aesthetic editorial/newspaper, not tech-startup?
3. Did I use The Seasons for display and Inter for body?
4. Is photography grayscale with an ink border?
5. Is Bitcoin Orange an accent only?
6. Are numbered editions included where relevant?
7. Did I include paper texture on every surface?

If all seven are yes, the piece is on-brand.

## Files you can load for more detail

- `design-tokens/colors.json` — full colour specs with contrast ratios
- `design-tokens/typography.json` — full type scale
- `design-tokens/tokens.css` — drop-in CSS custom properties
- `design-tokens/voice-and-motifs.json` — voice guide + recurring motifs
- `guidelines/brand-guidelines.docx` — the full human-readable brand book
- `USAGE.md` — checklist for designers
- `logos/*` — all official marks (SVG + PNG)
- `photography/*` — approved photos

## One-liner to paste into a prompt

```
I'm producing material for Barcelona Bitcoin Hub (BBH), a Bitcoin-only meetup in Barcelona since February 2025. Aesthetic: editorial newspaper (Financial Times × Bitcoin Magazine). Palette: ink #010101 on paper #F0E8D5, Bitcoin Orange #F7931A as accent only. Display font The Seasons, body Inter. All photography grayscale with 1px ink border. Mandatory: paper texture on every surface, no price/trading/altcoins content (Solo Bitcoin rule), no emojis, no gradients, no crypto-bro tone. Tagline: "Bitcoin. Sin ruido." Full brand kit at github.com/<owner>/bbh-brand-kit.
```
