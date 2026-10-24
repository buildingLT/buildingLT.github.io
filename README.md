# lakshyatiwari.com

Personal website, built with [Astro](https://astro.build) and deployed to GitHub Pages via GitHub Actions.

## Develop

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs to dist/
```

## Structure

- `src/pages/` — one file per page: `index`, `career`, `180dc`, `travel`
- `src/layouts/Layout.astro` — shared header, footer, fonts, contact links
- `src/styles/global.css` — colors, typography, spacing
- `public/` — static files served as-is (`CNAME`, favicon)

Pushing to `main` deploys automatically (`.github/workflows/deploy.yml`).
