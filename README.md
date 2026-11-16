# Research Department Staff Forecast 2026–2027

Interactive dashboard transcribed from a user-provided research department forecast screenshot.

## Files
- [index.html](index.html) — standalone, browser-based dashboard: sortable/searchable table, category filtering, comparable interactive bar charts, July revisions and filtered CSV download.
- [forecast-data.csv](forecast-data.csv) — 15 source indicators, with missing values left empty.

## Publishing with GitHub Pages
1. Open the repository's [Pages settings](https://github.com/Ribeiro2026/BoI-forecasts/settings/pages).
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select branch **main** and directory **/(root)**. Click **Save**.
4. When deployed, the site address is: **https://ribeiro2026.github.io/BoI-forecasts/**.

Because this is a static HTML app without build dependencies, it can be served directly from the repository root. Later pushes to `main` automatically redeploy after branch-based publishing is enabled.

## Data notes
- Values are percentage growth rates or percentage levels, depending on the indicator.
- July forecast differences are reported in percentage points.
- Blank cells were preserved as missing values, not zero.
- Footnote definitions c, d and e were not visible in the source screenshot.
- This is a transcription and not an independently verified forecast.
