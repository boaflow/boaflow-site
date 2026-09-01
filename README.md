# Boaflow — marketing site

Single-page static site. No build step, no dependencies.
Live at **https://boaflow.co**

## Files
- `index.html` — the entire site (CSS + JS inlined)
- `og.png` — link-preview image (1200×630)
- `favicon.ico`, `icon-32.png`, `icon-180.png`, `icon-512.png` — favicons

## Still to do
Find the comment `<!-- BOOKING LINK -->` in `index.html` and replace the `mailto:`
href with the GoHighLevel Discovery Call calendar link.

## Deploy
Every push to `main` auto-deploys via Vercel.
Project settings: Framework preset **Other**, no build command, no output directory.
