# Boaflow — marketing site

Single-page static site. No build step, no dependencies.

## Files
- `index.html` — the entire site (CSS + JS inlined)
- `og.png` — link-preview image (1200×630)
- `favicon.ico`, `icon-32.png`, `icon-180.png`, `icon-512.png` — favicons

## Before going live
1. In `index.html`, replace every `SITE_URL_HERE` with your real domain, e.g. `https://boaflow.co` (no trailing slash).
2. Find the comment `<!-- BOOKING LINK -->` and replace the `mailto:` href with your GoHighLevel calendar link.

## Deploy
Push to GitHub, import the repo in Vercel. Framework preset: **Other**. No build command, no output directory.
