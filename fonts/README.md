# Fonts

## The Seasons (display)

The BBH display typeface. Used for all h1–h3, pull quotes, and other editorial display type. Never at body-copy sizes (minimum 18px).

Files:
- `the-seasons/TheSeasons-Regular.ttf`
- `the-seasons/TheSeasons-Bold.ttf`
- `the-seasons/LICENSE.txt` — license text from OnlineWebFonts (CC BY 4.0)

**Attribution required.** When shipping The Seasons in a live website or product, include somewhere visible (footer is ideal):

> "Typeface: The Seasons via OnlineWebFonts (CC BY 4.0)"

### Loading it in a website

```css
@font-face {
  font-family: "The Seasons";
  src: url("./fonts/the-seasons/TheSeasons-Regular.ttf") format("truetype");
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: "The Seasons";
  src: url("./fonts/the-seasons/TheSeasons-Bold.ttf") format("truetype");
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}
```

For production sites, consider converting the TTFs to WOFF2 to reduce file size by ~70%.

## Inter (body)

BBH's body typeface. **Not included in this repo** — use the system copy on macOS/Windows/iOS/Android (it's a system font on modern OSes), or load from [rsms.me/inter](https://rsms.me/inter/) or Google Fonts.

Stack:
```
"Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Arial, sans-serif
```

Weights used: 400, 500, 600, 700.

Inter is licensed under the SIL Open Font License 1.1 — free for any use.

## Fallback stacks

If neither The Seasons nor Inter load:

- Display: Fraunces, Cormorant Garamond, Georgia, serif
- Sans: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Arial, sans-serif
