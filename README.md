# Product Dashboard — Preview

Static preview of an internal product-quality dashboard. All data shown is **mocked** — numbers, dataset names, issue titles, sprint stats are placeholders meant only to demonstrate layout and interactions.

The real dashboard lives in a separate private repository and connects to live data sources at deploy time.

## How to use this preview

- Open `index.html` directly, or visit the GitHub Pages URL
- Click any tile to see the drill-down modal (search, column toggle, underlying rows)
- Toggle between Build KPIs and GTM KPIs at the top
- Sprint badge shows the auto-computed current sprint

## Feedback wanted

Open an issue on this repo or reply on the original tracking issue with:
- Anything you'd add, remove, reorder, or rename
- Tiles where the drill-down doesn't show the data you'd want
- Anything that reads as broken vs intentionally placeholder

## What's NOT in this preview

- The full sidebar table browser (crawling / extraction / retrieval / etc.) — exists in production with real data and filter controls
- Week-over-week deltas — flagged as v2 work
- Real backend with live data
