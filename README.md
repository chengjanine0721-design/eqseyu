# eqseyu.com

Static website for eqseyu.com — free online web tools. Hosted on Cloudflare Pages.

## Structure

- `index.html` — homepage / tool hub
- `character-counter/` — character counter tool page
- `robots.txt`, `sitemap.xml` — SEO basics

## Deployment

Cloudflare Pages → connect this repo → **no build command**, output directory = `/` (root).

Push to `main` triggers automatic redeploy.
