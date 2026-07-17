# Regalita Home Health — Website PRD
**Client:** Regalita Home Health Service LLC
**Location served:** Chandler, AZ & the East Valley
**Status:** Design & build complete — pending client content sign-off before launch

---

## 1. Project Overview

A single-page marketing website for Regalita Home Health Service LLC. The site speaks
to two audiences at once, from the first screen onward:

- **Families** seeking in-home care for a loved one
- **Referral partners** — hospitals, discharge planners, and care agencies evaluating
  Regalita as a coordination partner

The goal: feel warm, trustworthy, and premium — closer to a boutique hospitality brand
than a clinical medical template — while making it effortless for either audience to take
the next step (call, request an assessment, or refer a patient).

---

## 2. Brand & Visual Design

### Color Palette
| Role | Color | Usage |
|---|---|---|
| Background | Cream / ivory (`#F6F1E7`, `#FCF9F2`) | Page base — warm, not clinical white |
| Primary | Warm sage-olive green (`#56603B`, `#5A6440`) | Hero gradient, Partners section, links |
| Accent | Warm gold (`#C29A4B`) | CTAs, stat numbers, brand mark, dividers |
| Dramatic | Deep charcoal (`#26241F`) | Reserved for exactly one section (24/7 band) + footer |
| Text | Warm charcoal (`#2A2824`, `#3A382F`) | Body copy — never pure black |

### Typography
- **Headlines:** Newsreader (serif) — editorial, premium, trustworthy
- **Body / UI:** Hanken Grotesk (sans-serif) — clean and humanist

### Brand Mark
A fleur-de-lis inside a dotted gold circle (⚜), used as Regalita's logo mark, a recurring
section watermark, and a divider accent throughout the page — elegant rather than clinical,
deliberately avoiding medical iconography like a cross or plus sign.

---

## 3. Site Structure (as built)

1. **Header / Nav** — logo mark, sticky on scroll, nav links (Home / About / Services /
   For Partners / Contact), gold "Request Care" button
2. **Hero** — full-bleed background video, headline + subhead, two CTAs side by side
   ("Find Care for a Loved One" / "Refer a Patient"), "scroll to discover" cue
3. **Trust Bar** — four stats (years of service, families supported, recommend rate, 24/7)
4. **About** — founder/care-team photo + mission narrative
5. **Core Services** — 4-card grid: Comprehensive Care Coordination, In-Home Health
   Assessments, Personalized Care Plans, Life Skills & Companion Support
6. **Beyond Medical Care** — differentiator section with photography + 4-icon grid
   (Wellness Activities, Companionship, Movement & Recreation, Community Connection)
7. **Editorial image band** — full-width lifestyle photo with a short emotive line
8. **How It Works** — 3-step timeline (Reach Out → Care Plan → Ongoing Support) with a
   connector line that draws itself in as you scroll
9. **24/7 CTA Band** — the one charcoal + gold dramatic section; phone number + assessment CTA
10. **For Referral Partners** — coordination-focused messaging + photo, distinct sage-green
    section
11. **Testimonials** — three family/partner quotes
12. **Contact** — phone / email / address, a "loved one vs. referral" toggle, and a request form
13. **Footer** — logo, nav repeat, contact details, copyright

---

## 4. Motion & Interaction

Built to feel alive without feeling flashy — every animation is subtle, and the page
remains fully readable with motion disabled (`prefers-reduced-motion` respected throughout):

- Hero content fades and rises in on load, staggered line by line
- Every section reveals on scroll (fade + slide, staggered across card groups)
- Stat numbers animate as a count-up once real figures are confirmed
- Gentle parallax on the hero video while scrolling
- The "How It Works" connector line draws itself left-to-right on scroll
- Service cards lift with a soft shadow on hover
- CTA buttons nudge their arrow forward on hover
- Sticky header reacts to scroll position (condenses + gains a shadow)

---

## 5. Technical Summary

- **Stack:** plain HTML, CSS, and vanilla JavaScript — no framework, no build step,
  no external runtime dependency. Deploys as a static site to any host.
- **Hosting plan:** GitHub (source of truth) → Vercel (hosting), so future edits can be
  pushed live in seconds.
- **Performance:** images and video are the only heavy assets; a compression pass is
  planned before public launch (see open items below).
- **Accessibility:** semantic structure, descriptive alt text on all photography, full
  functionality with animations turned off.
- **Responsive:** mobile, tablet, and desktop breakpoints; navigation collapses to a
  simplified mobile header.

---

## 6. Assets Currently In Place

- Hero background video
- Founder / care-team photo (About section)
- Caregiver + client companionship photo (Beyond Medical Care section)
- Outdoor caregiver walk photo (editorial band)
- Care-coordinator photo (For Partners section)
- Brand mark favicon

---

## 7. Open Items — Needs Client Input Before Launch

- [ ] **Trust-bar statistics** — years of service, families supported, and satisfaction
      rate are currently placeholders. Please confirm real numbers.
- [ ] **Testimonials** — the three quotes shown are sample copy. Please provide real
      client/partner testimonials (with permission to publish names).
- [ ] **Contact form routing** — the form currently confirms submission on-screen but is
      not yet connected to an inbox. Needs a destination email or CRM before launch.
- [ ] **Contact email** — confirm the final public-facing email address for the site.
- [ ] **Map** — the contact section currently links out to Google Maps; let us know if
      an embedded map view is preferred instead.
- [ ] **Legal/licensure details** — any certifications, license numbers, or insurance
      information you'd like displayed (e.g., in the footer or About section).

---

## 8. Next Steps

1. Client review of the current build
2. Confirm or revise copy, stats, testimonials, and contact details above
3. Connect the contact form to a live inbox
4. Image/video compression pass for faster load times
5. Push to GitHub → deploy live on Vercel
6. Final client walkthrough on the live URL before public launch

---

*Questions or requested changes can be sent back against this document — happy to
iterate on any section, copy, or interaction before we lock the final build.*
