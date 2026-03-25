# Pi lightning talk slides

Starter slide deck for a GitHub Pages-hosted lightning talk about Pi.

## What's here

- `index.html` — Reveal.js slide deck
- `assets/style.css` — custom styling
- `.github/workflows/pages.yml` — GitHub Pages deploy workflow

## Local preview

From this directory:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish on GitHub Pages

1. Create a GitHub repo and push this directory.
2. In GitHub, enable **Pages** and set **Source** to **GitHub Actions**.
3. Push to `main`.
4. The workflow in `.github/workflows/pages.yml` will publish the static site.

## Editing tips

- Keep the deck short: ~5–7 slides for a lightning talk.
- The current deck is intentionally a roomy starter outline.
- Speaker notes are included in `index.html` via `<aside class="notes">`.
- Reveal.js uses URL hashes, so slides are linkable.

## Suggested trim pass

For a really tight talk, keep just:

1. Title
2. What Pi is
3. Why Pi is different
4. Customization / extensions
5. Philosophy
6. Tiny demo
7. Links
