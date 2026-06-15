# Valuation Workbench

A single-page market-valuation dashboard for ~130 large- and mid-cap names: each multiple
read against the name's **own 5-year history** (cheap or rich vs itself) and its **sector**,
under a live market-regime line. Pure static HTML, inline-SVG charts, no backend, no trackers.

**Tabs:** Top Picks · Valuation · Sectors · Value Map · Market P/E·P/S·P/B · Companies · Fundamentals · Method & Quality.

## Deploy

Static site — `index.html` is served at the root by Vercel. No build step.

## Data

Prices are refreshed from primary exchange data (Nasdaq) with an independent cross-check
(finviz), and re-priced through identity-preserving transforms. This public build contains
**no personal holdings, net worth, or account information** — ownership markers are disabled.

Snapshot date is shown in the page header.

---
*Generated from a private analysis pipeline. This site is informational only and is not investment advice.*
