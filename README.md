# BBH Brand Kit

The official brand asset repository for **Barcelona Bitcoin Hub (BBH)** — a Bitcoin-only meetup hosted at the former Barcelona Stock Exchange (Passeig de Gràcia 19) since February 2025.

This repo is the canonical source for logos, fonts, colours, photography, brand guidelines, and editorial voice. It is designed to be consumed by humans (designers, partners, press), by AI tools (via `ai-pack/`), and by code (via `design-tokens/`).

---

## What's inside

```
bbh-brand-kit/
├── logos/               SVG + PNG — round, square, wordmark, both colourways
├── fonts/               The Seasons (display) + license
├── photography/         Founder portraits, meetup reportage
├── design-tokens/       colors.json, typography.json, tokens.css, voice-and-motifs.json
├── guidelines/          Full brand guidelines (.docx)
├── partner-brands/      Third-party marks we appear alongside (BFH). Reference only.
├── ai-pack/             Compressed brand context for LLMs
├── USAGE.md             Quick-start for designers and developers
├── GITHUB_SETUP.md      One-time instructions to publish this repo to GitHub
├── CHANGELOG.md         Release notes
├── LICENSE              MIT for code/docs + asset-usage notes
└── README.md            This file
```

## Who this is for

- **Designers & agencies** producing posters, social posts, decks, or merchandise for BBH. Start with [USAGE.md](./USAGE.md).
- **Partners & press** that need an official logo or a founder photo. See `logos/` and `photography/`.
- **Developers** building a website, app, or newsletter template. Start with `design-tokens/tokens.css` — drop it in, reference `--bbh-*` variables.
- **AI tools (ChatGPT, Claude, Gemini, Cursor, etc.)** building marketing material for BBH. Point them to [`ai-pack/AI_README.md`](./ai-pack/AI_README.md) — it's a single-file context pack with everything needed in ~2k tokens.

## Quick start

**Logos.** Use `logos/round/bbh-round-black.svg` on light backgrounds, `logos/round/bbh-round-white.svg` on dark. Respect the clear-space rule: leave at least one "B"-height of empty margin around the mark.

**Colours.** Primary palette is Midnight Black (`#010101`) on Parchment Cream (`#F0E8D5`). Bitcoin Orange (`#F7931A`) is an accent only — never body text, never backgrounds. See [`design-tokens/colors.json`](./design-tokens/colors.json) for full specs with contrast ratios.

**Typography.** Headlines use **The Seasons** (included). Body copy uses **Inter** (system-available or from [rsms.me/inter](https://rsms.me/inter/)). Never mix more than two families per page.

**Voice.** Editorial, serious, warm. Never hype. Never price. **Solo Bitcoin.** See [`design-tokens/voice-and-motifs.json`](./design-tokens/voice-and-motifs.json).

## The cardinal rule

This is a **Solo Bitcoin** community. Any material produced with this brand kit must honour the three rules:

1. No price.
2. No trading.
3. No altcoins.

Materials that violate these rules are not permitted to use the BBH name or logo.

## License & usage

- **Code and documentation** in this repo: MIT — free for any use.
- **Design tokens, colour specs, editorial guidelines**: CC BY 4.0 — free to adapt and reuse with attribution.
- **Photography**: CC BY-NC 4.0 — free for non-commercial editorial use with attribution ("Photograph: Barcelona Bitcoin Hub"). Commercial use by permission only.
- **Logos and wordmarks**: All rights reserved. Use permitted only when referring to or collaborating with Barcelona Bitcoin Hub. Modifying the marks is not permitted.
- **The Seasons font**: CC BY 4.0 by OnlineWebFonts. See [`fonts/the-seasons/LICENSE.txt`](./fonts/the-seasons/LICENSE.txt).

See [LICENSE](./LICENSE) for the full text.

## Contact

- Web: [barcelonabitcoinhub.com](https://barcelonabitcoinhub.com) *(placeholder)*
- Email: `barcelona_btc_hub@proton.me`
- Telegram: [t.me/](https://t.me/) *(placeholder — fill in before publishing)*
- YouTube: [@BcnBtcHub](https://www.youtube.com/@BcnBtcHub)
- Twitter/X: [@bcnbtchub](https://twitter.com/bcnbtchub)

For press enquiries or logo-use requests, email `barcelona_btc_hub@proton.me`.

---

*Barcelona Bitcoin Hub — Bitcoin. Sin ruido.*
