# Signal — Earnings Common Ground

A responsive research site comparing ten earnings releases each from NVIDIA, Microsoft and Apple. It is a dependency-free static site and can be hosted directly on GitHub Pages.

## Deploy to GitHub Pages

1. Create an empty GitHub repository.
2. Upload everything in this folder to the repository root. Keep the hidden `.github` folder.
3. Name the default branch `main` and commit the files.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, set **Source** to **GitHub Actions**.
6. Open the **Actions** tab and wait for “Deploy site to GitHub Pages” to finish.

The live URL will appear in the completed workflow and in **Settings → Pages**. Future pushes to `main` deploy automatically.

## Local preview

Open `index.html` directly in a browser. No installation or build command is needed.

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
