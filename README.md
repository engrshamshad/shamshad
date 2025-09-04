# Shamshad Ali — Academic Portfolio

This repository contains a single-page academic portfolio (`index.html`). It uses public CDNs (TailwindCSS, Font Awesome, Google Fonts) so no build step is required.

## Quick start (GitHub Pages)

1. Create a **public** GitHub repo, e.g. `shamshad-ali-portfolio`.
2. Upload all files from this ZIP (including `index.html`) to the repo root and commit.
3. Go to **Settings → Pages**  
   - **Source**: `Deploy from a branch`  
   - **Branch**: `main` and `/ (root)`  
4. Open: `https://<your-username>.github.io/shamshad-ali-portfolio/`

## Local preview
Just open `index.html` in a browser (double‑click).

## Optional folders
- `images/` — put pictures and figures here; reference as `images/<file>`.
- `docs/` — store PDFs like your CV; link as `docs/<file>`.

## Notes
- The “All Publications” table lives in the bottom of `index.html`. Update the `publicationsData` array in the `<script>` to add more entries (DOI links supported).
- A `.nojekyll` file is included so GitHub Pages serves everything as static files.

