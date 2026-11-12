# Record Waterfalls

An animated page of twelve waterfalls that each hold a record: the tallest, the widest, the largest by flow, one under the sea, and one that no longer exists. Each waterfall has its own animation, drawn to show what makes it the record holder, plus a ranked comparison by height, width and flow. Educational only.

**Live:** https://sneakysquidz.github.io/record-waterfalls/

## Run locally

Open `index.html`, no build step. It is one self-contained file; only the fonts load from Google Fonts, and the page falls back to system fonts without them.

## Sources

Every figure on the page links to its source under the waterfall it belongs to:

- UNESCO World Heritage Centre
- NOAA (US National Ocean Service)
- US National Park Service
- Vatnajökull National Park
- Britannica
- World Waterfall Database
- Wikipedia

Where sources disagree, the page says so. "No sourced figure" means none was found, not zero. Each "In the animation" note says what is drawn to scale and what is drawn by eye.

Figures checked November 2026.

## Deploy

A push to `main` publishes the site to GitHub Pages through `.github/workflows/deploy-pages.yml`.
