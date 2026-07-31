# Urban Geo-Innovation Lab

Website for the Urban Geo-Innovation Lab, directed by Dr. Achituv Cohen in the
Department of Civil Engineering at Ariel University. The lab researches GeoAI,
urban mobility, active transportation, and spatial equity.

Live site: https://achic19.github.io/Urban-Geo-Innovation-Lab/

## Structure

- `index.html` — page content
- `style.css` — styling
- `favicon.svg` — browser tab icon
- `assets/` — images (logo, team photos) — add `assets/logo.png` to show the lab logo in the header
- `google27736415b7102fa6.html` — Google Search Console site-verification file, do not remove

## Deployment

Static site served directly by GitHub Pages from the `main` branch root — no
build step. Push to `main` and GitHub Pages redeploys automatically. Repo
Settings → Pages → Source is set to "Deploy from a branch" (`main`, `/root`).

## Local preview

Open `index.html` directly in a browser, or serve the folder with any static
file server, e.g.:

```bash
python -m http.server 8000
```
