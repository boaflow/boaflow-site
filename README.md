# Boaflow — marketing site

Static site for manufacturers. No build step, no dependencies.
Live at **https://boaflow.ai** (boaflow.co redirects here).

## Files
- `index.html` — homepage
- `sops.html` — SOP creation page, served at `/sops`
- `og.png` — link-preview image (1200×630)
- `favicon.ico`, `icon-32.png`, `icon-180.png`, `icon-512.png` — favicons
- `sitemap.xml`, `robots.txt`

## Booking link
Fit-call CTAs point at the Google Calendar appointment:
https://calendar.app.google/vn369DieRsAXJTx46

## Deploy
Every push to `main` auto-deploys via Vercel.
Project settings: Framework preset **Other**, no build command, no output directory.
