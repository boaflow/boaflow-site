# Boaflow — marketing site

Single-page static site. No build step, no dependencies.
Live at **https://boaflow.co**

## Files
- `index.html` — the entire site (CSS + JS inlined)
- `og.png` — link-preview image (1200×630)
- `favicon.ico`, `icon-32.png`, `icon-180.png`, `icon-512.png` — favicons

## Booking link
The "Book a Discovery Call" CTA points at the GoHighLevel calendar:
https://api.leadconnectorhq.com/widget/bookings/boaflow-discovery

## Deploy
Every push to `main` auto-deploys via Vercel.
Project settings: Framework preset **Other**, no build command, no output directory.
