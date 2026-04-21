# Changelog

All notable changes to the Barcelona Bitcoin Hub brand kit are documented in this file.

The format is loosely based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html) — major versions signal a deliberate brand change, minor versions add assets, patches fix typos or metadata.

## [1.0.0] — 2026-04-21

First public release of the BBH brand kit.

### Added

- **Logos** — round, square, wordmark, and mark-only variants in SVG and PNG (black and white).
- **Fonts** — The Seasons (display, CC BY 4.0 via OnlineWebFonts) with drop-in `@font-face` declarations. Inter documented as a system/rsms.me dependency.
- **Photography** — founder portraits (group wide, group portrait, group square, Kenobi, Losku, Jordi) plus two original full-resolution files; five meetup reportage photos (`meetup-01` through `meetup-05`). All web-optimised JPEGs.
- **Design tokens** — `colors.json`, `typography.json`, `voice-and-motifs.json`, and a drop-in `tokens.css` with CSS custom properties for the full palette, type scale, spacing, and motifs.
- **Guidelines** — `guidelines/brand-guidelines.docx`, the canonical brand document.
- **AI pack** — `ai-pack/AI_README.md` (compressed ~2k-token context pack for LLMs) and `ai-pack/brand-prompt.md` (paste-in prompts for ChatGPT / Claude / Gemini / Cursor / v0).
- **Partner brands** — BFH logo reference files (`partner-brands/bfh/`).
- **Documentation** — `README.md`, `USAGE.md`, `LICENSE` (multi-section: MIT for docs/tokens, CC BY-NC 4.0 for photography, all-rights-reserved for logos, CC BY 4.0 for The Seasons), plus section-level READMEs for `logos/`, `fonts/`, `photography/`, and `partner-brands/`.

### Known limitations

- Tokens are CSS + JSON only. No Figma library or Tailwind theme export yet.
- The Seasons is shipped as TTF only. WOFF2 conversion is left to consumers.
- Logo AI source files are not in this repo. Contact `barcelona_btc_hub@proton.me`.

---

_For older history (the pre-kit era — meetups № I through № XV), see the commit history of the website repository and the meetup archive on Meetup.com and Nostr._
