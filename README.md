# United Way of Harvey and Marion Counties — Strategic Plan FY2026–2029

A single-page website that hosts the United Way of Harvey and Marion Counties (UWHMC)
**FY2026–2029 Strategic Plan**. The page opens with our Board-adopted framework, then
showcases the priority-area activities we'll advance over the next three years.

**Live page:** `index.html` (open in any browser, or host on GitHub Pages).

## What's on the page

1. **About This Plan** — a short overview plus the community context that drives the work.
2. **Our Adopted Framework** *(shown first, by design)* — vision, mission, the four focus
   areas, "United Way as the Community Hub," the "Advance Upward Mobility" core goal, and
   the three vehicles for impact.
3. **What We'll Work On, 2026–2029** — the three coalition-driven priority areas
   (Housing; Health & Well-Being; Early Childhood & Child Care), cross-cutting
   organizational strategies, and the VOAD / VITA / Volunteer United community programs.
4. **How We Stay Accountable** — our review and reporting cadence.
5. **Be the Way** — a Give / Volunteer / Partner / Advocate call to action.

## Project structure

```
uwhmc-strategic-plan/
├── index.html            # The complete page (HTML + CSS, no build step)
├── assets/
│   ├── logo-white.png    # United Way logo — used on dark backgrounds
│   └── logo-color.png    # United Way full-color logo
└── README.md
```

## Running it locally

No build tools or dependencies. Either:

- Double-click `index.html` to open it in a browser, **or**
- Serve the folder: `python3 -m http.server` then visit `http://localhost:8000`.

## Publishing with GitHub Pages

1. Push this repository to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick your
   default branch (e.g. `main`) and the `/ (root)` folder, and save.
4. Your page will be live at `https://<your-org>.github.io/<repo-name>/` in a few minutes.

## Editing content

All content and styling live in `index.html`. Common edits:

- **Contact / CTA links** — search for `tel:` and `mailto:` near the bottom of the file.
- **Goals and targets** — each priority area is a `<div class="priority ...">` block.
- **Colors** — brand colors are defined once as CSS variables in the `:root { ... }` block
  at the top of the `<style>` section.

## Brand

Built to the United Way brand system: **Antonio** for headlines (all caps) and
**Palanquin** for body text (loaded from Google Fonts), the official United Way color
palette (primary blue, navy, red, and gold, with green and orange as accents), and the
signature concentric-arc graphic motif — using solid palette colors only, with no
gradients or transparency, per the brand guidelines.

## Fonts

Fonts are loaded from Google Fonts via a `<link>` in the page `<head>`, so an internet
connection is required for the exact brand typography. Without it, the page falls back to
Arial (the brand's approved default system font).

---

© United Way of Harvey and Marion Counties · (316) 283-7101 · 204 W 6th St, Newton, KS 67114
