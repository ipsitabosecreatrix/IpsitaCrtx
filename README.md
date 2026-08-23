# Ipsita Portfolio v2 — first build

This first milestone includes:
- Astro static site shell
- responsive homepage
- avatar-led hero
- clickable Medusa project card
- `/work/medusa` case-study page
- local font hooks for Galocca + Nexa
- placeholders for remaining work

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL Astro prints in the terminal.

## Fonts

The CSS expects your own licensed/local web font files at:

- `public/fonts/galocca.woff2`
- `public/fonts/nexa.woff2`

Until you add those, the site uses serif/sans fallbacks.

## Replace before publishing

In `src/pages/index.astro`, replace:
- `YOUR_EMAIL_HERE`
- `YOUR_LINKEDIN_URL_HERE`

## Next build step

1. Replace the Medusa hero asset with a purpose-rendered landscape image.
2. Add 4–5 real Medusa process images.
3. Add a compressed Medusa preview video.
4. Only then add the optional interactive GLB viewer.
