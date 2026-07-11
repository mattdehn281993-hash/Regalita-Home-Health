# Regalita Home Health — Website

Marketing site for **Regalita Home Health Service LLC** (Chandler, AZ & the East Valley).
A single-page, static site — warm sage / gold / cream palette, serif headlines, gentle
scroll animations. Built to serve two audiences at once: **families** seeking in-home care
and **referral partners** (hospitals, discharge planners, agencies).

Design brief: [`docs/PRD.md`](docs/PRD.md).

## Stack

Plain **HTML + CSS + vanilla JS** — no framework, no build step. It deploys to any static
host as-is. (Originally exported from a design tool that depended on a React runtime; that
dependency has been removed so the site runs standalone.)

```
index.html        ← the whole site
public/
  hero.mp4        ← hero background video  ← REPLACE with the final animation
  favicon.svg     ← fleur-de-lis brand mark favicon
vercel.json       ← caching + clean URLs for Vercel
docs/PRD.md       ← product requirements
```

## Run locally

No tooling needed — just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to Vercel

1. Push this folder to a GitHub repo.
2. In Vercel → **Add New → Project** → import the repo.
3. Framework preset: **Other** (it's a static site — no build command, no output dir).
4. Deploy. `vercel.json` handles clean URLs and video caching.

Or from the CLI: `npm i -g vercel && vercel` (then `vercel --prod`).

## Before launch — checklist

Placeholders intentionally left in (per the PRD, real figures/photos come from the client):

- [ ] **Hero video** — drop the final animation in as `public/hero.mp4`.
- [ ] **Photos** — replace the two hatched placeholder blocks (About founder/team photo,
      Partners coordination photo) with real natural-light photography.
- [ ] **Trust-bar stats** — confirm real numbers, then set `STATS_LIVE = true` in the
      `<script>` at the bottom of `index.html` to enable the count-up animation.
- [ ] **Testimonials** — swap the three sample quotes for real client voices.
- [ ] **Contact form** — currently shows a front-end "thank you" only; it does **not** send
      anywhere yet. Wire it to a real endpoint (e.g. [Formspree](https://formspree.io),
      Netlify Forms, or a small serverless function) before launch.
- [ ] **Map** — the contact "map" block links out to Google Maps; embed a real map iframe
      if a richer view is wanted.

## Notes

- Fully responsive (mobile breakpoints at 820px / 560px); nav collapses on small screens.
- Respects `prefers-reduced-motion` — all content is readable with animations disabled.
- Contact: (480) 590-0357 · zionpalace01@gmail.com · 3306 E Bluejay Drive, Chandler, AZ 85286
