# Dipity Farms — dipityfarms.com

Static one-page site for Dipity Farms (Greenville, SC): kitchen garden
consulting, design and workshops with Sarrin Warfield.

## What's here

- `index.html` — the whole site. No build step, no framework.
- `photos/` — every image in AVIF, WebP and JPEG, at three display widths.
  The browser picks the smallest format and size it can use.
- `vercel.json` — cache and security headers.

## Deploying

Vercel builds this straight from the repo root — no build command, no
install step. Push to `main` and it deploys.

## Editing

Text, photos and the farmstand menu were edited in a Claude preview and
baked into `index.html` as static markup. Editing now means editing the
HTML directly.
