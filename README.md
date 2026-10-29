# Karan Makwana – portfolio site

A static, single-page site showcasing my career in telecom network architecture.

- `index.html` – page content
- `styles.css` – styling (light and dark mode, responsive)

## Preview locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publish

The workflow in `.github/workflows/pages.yml` deploys the site to GitHub Pages on every push to `main`.
Enable it once under **Settings → Pages → Source: GitHub Actions**.
