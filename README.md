# Nepal Trekking Guide — Tour Guide In Nepal

A free, comprehensive Nepal trekking resource built as a static site for GitHub Pages. Covers Everest Base Camp, Annapurna, Langtang, Manaslu, and Upper Mustang — with permits, seasons, licensed guide advice, safety/altitude sickness tips, packing checklists, and a trekking FAQ.

**Live site:** _add your GitHub Pages URL here after deploying_
**Related brand:** [tourguideinnepal.com](https://tourguideinnepal.com)

## About

This page is designed to be a genuinely useful, bookmark-worthy planning resource for international trekkers — not a plain promotional landing page. It's built to rank well on Google and to be cited accurately by AI answer engines (ChatGPT, Perplexity, AI Overviews).

## Tech Stack

- Pure HTML5 + CSS (no frameworks, no build step)
- Single `index.html` file — fast, lightweight, easy to host
- Semantic markup, mobile-responsive, Lighthouse-friendly
- Schema.org JSON-LD: `TravelAgency`, `BreadcrumbList`, `Article`

## What's Included

- Overview of why Nepal is a top trekking destination
- Deep-dive on 5 major trekking regions
- Trek difficulty comparison table
- Best season / month-by-month trekking chart
- Trekking permit summary by region
- Guidance on hiring licensed guides
- Altitude sickness (AMS) recognition & prevention
- Full packing checklist
- Trip planning & budgeting advice
- FAQ section (accessible `<details>` accordion)

## Deploying on GitHub Pages

1. Push this repo to GitHub with `index.html` in the **root directory**.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then **Save**.
5. Your live URL will appear at the top of the Pages settings page within a minute or two.

## Local Preview

No build tools required — just open the file directly:

```bash
open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Editing Content

All content lives in the single `index.html` file, organized into clearly labeled `<section>` blocks (`#why-nepal`, `#regions`, `#seasons`, `#permits`, `#guides`, `#safety`, `#packing`, `#planning`, `#faq`). Update text directly inside the relevant section — no templating system to worry about.

## License

Content © Tour Guide In Nepal. Update this section with your preferred license (e.g., MIT for code, All Rights Reserved for content) before making the repo public.
