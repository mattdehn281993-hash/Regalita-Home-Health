# Regalita Home Health — Website

Marketing site for **Regalita Home Health Services LLC** (Gilbert, AZ & the East Valley).
A single-page, static site — navy / champagne-gold / warm-teal palette, Playfair Display
headlines, gentle scroll animations. Built to serve two audiences at once: **families**
seeking in-home care and **referral partners** (hospitals, discharge planners, agencies).

## Stack

Plain **HTML + CSS + vanilla JS** — no framework, no build step. It deploys to any static
host as-is.

```
index.html        ← the whole site
media/
  hero.mp4        ← hero background video (desktop)
  hero-family.jpg ← hero photo (mobile, replaces the video below 820px)
  logo.png        ← transparent brand mark
  arizona-map.gif ← Coverage section reference map
  favicon.svg
vercel.json       ← caching + clean URLs for Vercel
```

> **Note:** the assets folder is named `media/`, not `public/`. Several static-site presets
> (Vercel included) auto-detect a folder literally named `public` as the build **Output
> Directory** — since this project has no build step and `index.html` lives at the repo
> root, that misdetection causes a 404 on deploy. Keep it as `media/` (or update Vercel's
> Project Settings → Output Directory to blank/root if you ever rename it back).

## Run locally

No tooling needed — just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to Vercel

1. Push this folder to a GitHub repo.
2. In Vercel → **Add New → Project** → import the repo.
3. Framework preset: **Other** (static site — no build command). Leave **Output Directory**
   blank/root — don't let it auto-select `media/` or anything else.
4. Deploy. `vercel.json` handles clean URLs and media caching.

Or from the CLI: `npm i -g vercel && vercel` (then `vercel --prod`).

## Before launch — checklist

- [ ] **Trust-bar / stats** — the badges under the header ("Licensing in Progress,"
      "Pursuing Joint Commission Accreditation," "We Accept All Insurances") auto-hide a
      few seconds after load; confirm this is still accurate once real licensure status
      changes.
- [ ] **Testimonials** — swap the three sample quotes for real client voices.
- [ ] **Contact form** — currently shows a front-end "thank you" only; it does **not** send
      anywhere yet. Wire it to a real endpoint (e.g. [Formspree](https://formspree.io),
      Netlify Forms, or a small serverless function) before launch.
- [ ] **Logo source file** — confirm `media/logo.png` (background removed via script) is an
      acceptable stand-in, or swap in an original transparent export if the client has one.

## Notes

- Fully responsive; mobile hero switches from video to a static photo (video crops badly on
  tall phone screens) and restructures to an image-above/text-below stacked layout.
- Respects `prefers-reduced-motion` — all content is readable with animations disabled.
- Contact: (602) 686-7878 · admissions@regalitahomehealth.com · 1805 E Mia Ln, Gilbert, AZ 85298
