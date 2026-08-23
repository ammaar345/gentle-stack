# Combined Dark Site - Gentle Stack

## What is this?
A single-page, dark-themed website that combines research on:
- Steal a Brainrot (marshmallow aesthetic, girl-run-hq inspiration)
- Roblox (specifically Murder Mystery 2 trading and leveling)
- Selling digital products on online stores (Eldorado.gg, G2G.com, and general storefront playbook)

## Tabs & Content Source
The site uses a tabbed SPA interface (hash routing) with the following tabs:

1. **Home** – Introduction and quick navigation cards to each section.
2. **Brainrot & MM2 Trading** – Content from:
   - `problem-research/websites/girlrunhq-site/index.html` (marshmallow skin, adapted to dark)
   - `problem-research/websites/eldorado-brainrot-mm2-guide/index.html` (fully integrated 23 Aug 2026: under-$2 table, MM2 trading resources, security practices, trading workflow, sources; scaling card enriched with account sourcing, boosting do's/don'ts, fee arbitrage table)
   - `problem-research/research/eldorado-seller-brief/eldorado-seller-brief.md` (seller brief, trading tips)
3. **Rebirths & Secrets** – Steal a Brainrot leveling guide, content from:
   - `problem-research/websites/eldorado-brainrot-mm2-guide/index.html` (all 18 rebirth levels with requirements + rewards, full secret brainrot income table sorted low-to-high, rank-up-fast route; adapted to dark palette)
4. **MM2 Leveling** – Content from:
   - `problem-research/websites/mm2-leveling-guide/index.html` (fast leveling guide, XP tips, map recommendations)
5. **Eldorado Seller Brief** – Content from:
   - `problem-research/research/eldorado-seller-brief/eldorado-seller-brief.md` (live market, ROI, fees & payouts)
6. **Seller Fee Guide** – Content from:
   - `problem-research/research/eldorado-vs-g2g/eldorado-vs-g2g-seller-research.md` (detailed fee comparison: commission, withdrawal, hold, KYC)
7. **Selling Online** – Content from:
   - `problem-research/websites/quick-halal-kitchen/index.html` (digital products playbook: pricing, packaging, channels)
   - `problem-research/websites/ember-grill-dark/index.html` (storefront example, dark theme inspiration)

## Design Notes
- Dark gentle palette: deep blues/purples with muted pastel accents (rose, lavender, mint, peach, butter).
- Marshmallow-inspired softness: blob animations, rounded cards, subtle gradients.
- Fonts: Fredoka (headings), Nunito/Quicksand (body) via Google Fonts.
- Mobile-friendly: sticky pill tab bar, stacked tables with `data-label` pseudo-elements.
- All SVG figures from the research have been reviewed and fixed for overlap (see `fig/` in the KDP book projects).

## Maintenance
- If you update any source markdown or HTML, re-copy the relevant sections into the appropriate tab panel in `index.html`.
- After changes, test locally and push to GitHub to trigger GitHub Pages rebuild.
- The site is hosted at: https://ammaar345.github.io/gentle-stack/

## Related Files
- `problem-research/websites/combined-dark/index.html` – The main site.
- `problem-research/websites/combined-dark/_fix.py` (historical) – Bulk repair script for truncated tags (deleted after use).