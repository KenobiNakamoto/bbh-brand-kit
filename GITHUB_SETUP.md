# Publishing `bbh-brand-kit` to GitHub

This is a one-time setup. After this, pushing updates is just `git add . && git commit -m "..." && git push`.

Total time: about 3 minutes.

## Step 1 — Create the empty repository on GitHub

1. Go to <https://github.com/new>.
2. Repository name: **`bbh-brand-kit`**.
3. Description: *Brand kit and design tokens for Barcelona Bitcoin Hub.*
4. Visibility: **Public**.
5. **Do not** initialize with a README, `.gitignore`, or license — this kit already ships with all three.
6. Click **Create repository**.

GitHub will show you a page with instructions. Ignore it; use the script below — it's tailored to this repo.

## Step 2 — Push from your Mac

Open Terminal, then paste the whole block below. Replace `<your-github-username>` once at the top (it appears only in the `REMOTE_URL` variable).

```bash
# ---- edit only this line ----
REMOTE_URL="https://github.com/<your-github-username>/bbh-brand-kit.git"
# -----------------------------

cd "/Users/<you>/Documents/01_Private/Bitcoin Projects/Communities/Barcelona Bitcoin Hub/bbh-brand-kit"

# Remove the partial .git folder created during prep (it's empty-staged only)
rm -rf .git

# Initialize fresh, on main
git init -b main
git config user.email "barcelona_btc_hub@proton.me"
git config user.name  "Barcelona Bitcoin Hub"

# Stage everything, commit, link remote, push
git add .
git commit -m "feat: initial brand kit v1.0.0

- Logos (round, square, wordmark in SVG and PNG, black + white)
- Fonts: The Seasons (TTF) + Inter documented as dependency
- Photography: founders + 5 meetup reportage shots
- Design tokens: colors.json, typography.json, tokens.css, voice-and-motifs.json
- Docs: README, USAGE, LICENSE (multi-section), CHANGELOG
- AI pack: brand-prompt.md + AI_README for LLM consumption
- Partner brands: BFH reference marks"

git remote add origin "$REMOTE_URL"
git push -u origin main
```

If `git push` asks for a password, modern GitHub requires a personal access token (not your account password). Create one at <https://github.com/settings/tokens?type=beta>, scope it to this repo with *Contents: read/write*, and paste it when prompted. Or set up SSH: [GitHub's SSH guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

## Step 3 — Verify

Visit `https://github.com/<your-github-username>/bbh-brand-kit`. You should see the full tree, and the README should render cleanly on the landing page. Click through to `/ai-pack/brand-prompt.md` — that's the fastest way to test that AI tools can pull a brief.

## After that — day-to-day updates

```bash
cd "/Users/<you>/Documents/01_Private/Bitcoin Projects/Communities/Barcelona Bitcoin Hub/bbh-brand-kit"
git add .
git commit -m "feat(photos): add meetup № XVII reportage"   # or whatever
git push
```

## Optional — turn on GitHub Pages for a preview

If you want a simple public URL to share the tokens demo or the brand prompt:

1. Repo → **Settings** → **Pages**.
2. Source: **Deploy from a branch**, branch **main**, folder **/** (root).
3. Save. After a minute your kit is browsable at `https://<your-github-username>.github.io/bbh-brand-kit/`.

## Optional — tag the first release

```bash
git tag -a v1.0.0 -m "Barcelona Bitcoin Hub brand kit — v1.0.0"
git push --tags
```

Then on GitHub: **Releases** → **Draft a new release** → pick tag `v1.0.0` → paste the `## [1.0.0]` section from `CHANGELOG.md` as the release notes.

---

Questions: `barcelona_btc_hub@proton.me`.
