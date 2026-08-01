# Signal — Earnings Common Ground

A responsive research site comparing ten earnings releases each from NVIDIA, Microsoft and Apple. It is a dependency-free static site and can be hosted directly on GitHub Pages.

The site is dependency-free. Made by Shardul in July 2026 with ❤️.

## Project files

- `index.html` — page structure and content
- `styles.css` — responsive visual system
- `app.js` — report data, query behavior and interactive charts
- `.github/workflows/deploy-pages.yml` — automatic GitHub Pages deployment
- `.nojekyll` — disables Jekyll processing

## Data notes

- Quarterly revenue and source excerpts link to official company releases.
- Market capitalization and trailing P/E values are rounded post-earnings research snapshots for directional comparison.
- The query interface runs locally in the browser using keyword expansion and report tagging; no external AI service or API key is required.
