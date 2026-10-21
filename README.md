# Elastic AI Day Tokyo — Day 1 タイムテーブル

Day 1 timetable, embedded in the Splash event page via an iframe.

- Live page: https://gonzalopollandt-lgtm.github.io/elastic-ai-day-tokyo-timetable/
- `index.html` — the page (plain HTML + CSS, no scripts)
- `img/` — speaker photos (small WebP images wrapped in SVG)

## Updating sessions

Edit the text in `index.html` (pencil icon on GitHub) and commit. Each breakout session is an `<article class="ect-card">`; each keynote is an `<li class="ect-block ect-block--key">`. The Splash iframe picks up changes automatically once GitHub Pages redeploys (usually 1–2 minutes).

- To grey out a pending item, add `is-tbd` to the card or to the speaker name.
- To change a photo, replace the matching file in `img/` and keep the same filename.
