# Product Requirements Document
## Regalita Home Health Service LLC — Website

**Prepared for:** Claude Design build
**Document owner:** David Isaac / VMSA
**Status:** Ready for design & build

---

## 1. Project Overview

Regalita Home Health Service LLC needs a modern, warm, and animated marketing website that builds trust with two audiences simultaneously: families seeking in-home care for a loved one, and referral partners (hospitals, discharge planners, care agencies) evaluating Regalita as a coordination partner.

The site should feel more alive and memorable than typical home-health templates — through motion, editorial photography, and a distinctive brand mark — while staying calm and trustworthy rather than flashy.

**Design references provided:**
- Serenova (senior care) — hero structure, whitespace, serif/sans pairing, "scroll to discover" interaction
- Heritage Home Health LLC — service card clarity, contact/CTA density
- Zion Classique Care & Human Services LLC brochure (sister brand under the same operator) — brand mark (fleur-de-lis in dotted circle), tone of voice, service language, gold/charcoal accent palette

**Explicit instruction:** Do not replicate either reference site exactly. Use them as structural/tonal inspiration only. Output should be cleaner, more restrained, and more animated than both.

---

## 2. Audience & Goals

| Audience | Primary goal on site |
|---|---|
| Families | Feel reassured within seconds; understand services quickly; easy path to request care/assessment |
| Referral partners | Perceive credibility, coordination capability, responsiveness; easy path to initiate a referral |

Both audiences should be addressed from the hero onward via a dual-CTA approach — not a hard split into separate site experiences.

---

## 3. Brand Identity

**Name:** Regalita Home Health Service LLC
**Tone of voice:** Warm, personal, slightly elevated — not clinical or corporate. Reference phrases from the Zion Classique brochure to adapt: "Care Like No Other," "We care about you," "Best care and respect for everyone," "Help is only one call away."

**Brand mark:** Adapt the fleur-de-lis-in-dotted-circle mark from the Zion Classique brochure as a refined/simplified version for Regalita — use as logo mark, section watermark, and divider accent. Should read as elegant, not medical/clinical (avoid literal cross or plus-sign iconography).

---

## 4. Visual Design System

### 4.1 Color Palette

| Role | Color | Notes |
|---|---|---|
| Primary | Warm sage/olive green | Softer and warmer than a corporate forest green |
| Background | Cream / ivory | Not pure white — keeps the "home," not "hospital," feel |
| Accent | Warm gold | Pulled directly from the Zion Classique brochure; used for CTAs, stat numbers, dividers, brand mark |
| Dramatic section background | Deep charcoal (from brochure) | Reserved for ONE section only (24/7 CTA band) — not used site-wide |
| Text | Charcoal, not pure black | Keeps warmth consistent across light sections |

### 4.2 Typography
- **Headlines:** Serif — editorial, trustworthy, slightly premium (in the spirit of the Serenova reference)
- **Body/UI:** Clean humanist sans-serif
- Optional: one section may use a slightly warmer/quirkier display treatment for a headline (not applied site-wide) to avoid a generic template feel

### 4.3 Imagery
- Real, natural-light photography of caregivers and clients — avoid overly glossy/staged stock imagery
- Benchmark: the Serenova hero photo (outdoor, natural, dignified) — not the more staged shots in the Heritage reference
- Family-facing sections: warm, intimate, in-home imagery
- Partner-facing section: can lean slightly more professional/coordination-oriented imagery

### 4.4 Motion & Interaction Principles
Motion should feel **gentle and reassuring**, never flashy or distracting. Guidelines:
- Hero content fades and rises in slowly on load
- Scroll-triggered reveals on every section (fade + slight upward slide, staggered on card groups)
- Stats animate as count-up numbers when scrolled into view
- Subtle parallax on the hero photo while scrolling
- "How It Works" timeline: connecting line draws itself left-to-right as the user scrolls into the section
- Service cards: gentle scale/shadow lift on hover
- Optional ambient background: slow-drifting soft organic shapes behind the hero for a subtle "alive" feel without noise
- A "Scroll to Discover" micro-cue in the hero (borrowed concept from Serenova)

---

## 5. Site Structure & Section-by-Section Content Direction

### 5.1 Header/Nav
Logo mark + wordmark, simple nav (Home, About, Services, For Partners, Contact), one primary CTA button in gold (e.g., "Request Care").

### 5.2 Hero
- Full-bleed warm, real photograph
- Headline: warm, human, reassuring (adapt "Care Like No Other" energy for home health — draft options during copywriting phase)
- Subheadline: one sentence on what Regalita does and for whom
- **Dual CTA, side by side:** "Find Care for a Loved One" / "Refer a Patient" — addresses both audiences immediately without fragmenting the nav
- Scroll-to-discover micro-interaction at bottom of hero

### 5.3 Trust Bar
Animated count-up stats (e.g., years of experience, families served, satisfaction rate — final numbers TBD/confirmed by client). Styled like Serenova's stat row but with gold numerals.

### 5.4 About Us
Adapted from the Zion Classique brochure's About paragraph, rewritten for home health context — mission-driven, patient-centered, community-integrated language. Pair with a warm founder/team photo.

### 5.5 Core Services
Card grid, 3–4 core services, icon + short line each, hover reveals more detail. Adapt from brochure language:
- Comprehensive Care Coordination (between providers, physicians, local care resources)
- In-Home Health Assessments
- Personalized Care Plans (adapted from "Progressive Phase Program" concept)
- Life Skills & Companion Support

### 5.6 Beyond Medical Care *(differentiator section)*
New section not present in either reference site — this is the memorable/distinctive moment. Animated icon grid pulling from the brochure's holistic therapy list, reframed for home health: wellness activities, companionship/social engagement, movement & recreation, cultural/community connection. Positions Regalita as whole-person care, not just clinical tasks.

### 5.7 How It Works
Simple 3-step horizontal timeline (e.g., Reach Out → Care Plan → Ongoing Support), with the self-drawing connector line animation described in Section 4.4.

### 5.8 24/7 CTA Band *(dramatic section)*
Deep charcoal + gold section, brochure-inspired copy: "We're here 24/7 — help is only one call away." Includes phone number prominently and a "Request a Free, Confidential Assessment" CTA button.

### 5.9 For Referral Partners
Distinct section addressing hospitals/discharge planners/agencies directly — coordination process, responsiveness, compliance/trust signals. Can reuse the sage-green section background but with a slightly more professional visual tone than the family-facing sections.

### 5.10 Testimonials
Family voices — photo + short quote, subtle carousel or staggered card layout.

### 5.11 Contact / Closing CTA
Warm closing section: phone, address, simple form (name, email, message, reason for contact — family vs. partner toggle optional), map or location visual. Reuse direct brochure phrasing style ("Call us today," "We care about you").

### 5.12 Footer
Logo mark, nav repeat, contact details, social links if applicable, copyright.

---

## 6. Content/Copy Notes for Claude Design
- Do not invent specific stats, credentials, or claims (years in business, number of families served, licensure details) — these must come from the client before final copy is locked. Use placeholder brackets in first draft.
- Do not reuse Zion Classique's exact stat numbers or copy verbatim — adapt tone and structure only, since it's a different entity/service line.
- Keep all CTA copy short and action-oriented (2–4 words).

---

## 7. Technical/Build Notes
- Build in Claude Design as a modern responsive site (mobile-first breakpoints required — assume a meaningful share of family-audience traffic is mobile).
- Motion should degrade gracefully — no motion-dependent content (i.e., content must still be accessible/readable if animations are disabled or reduced-motion is set).
- Keep the charcoal/gold section visually distinct but not jarring against the sage/cream sections — use it once, deliberately, for maximum impact (Section 5.8).
- Reserve final brand mark refinement (simplified fleur-de-lis) as an early design step before full section build-out, since it recurs across the site as a watermark/divider element.

---

## 8. Out of Scope (for this phase)
- Booking/scheduling system integration
- Client portal or login
- Blog/CMS functionality
- Multi-language support

*(Flag if any of the above should be added to scope before build begins.)*
