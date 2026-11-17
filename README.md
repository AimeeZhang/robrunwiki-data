# ROB RUN Wiki — Open Data

Live, source-verified data for **ROB RUN** (Kefir's free-to-play crime sandbox on Steam, Early Access since Nov 4, 2026), maintained by the team behind [robrunwiki.site](https://robrunwiki.site).

## What's in here

- [`data/rob-run-snapshot.json`](data/rob-run-snapshot.json) — current verified snapshot: live server & player counts, weekly wipe schedule anchors, platform support, system requirements, official links. Every entity carries `checkedAt` and its `sources` — no unsourced numbers, ever.
- Refreshed daily by the robrunwiki.site data pipeline. Sources are limited to **Steam official API endpoints and Kefir official announcements** — no third-party wikis.

## Wipe schedule quick reference

- New servers open daily per region: **EU at 17:00 UTC**, **East US at 20:00 ET** (per official Nov 3–4 announcements).
- Each server wipes **7 days after it opened**. Interactive timer with region picker and per-server calculation: [robrunwiki.site/wipe](https://robrunwiki.site/wipe/).

## Using the data

- License: [CC BY 4.0](LICENSE.md) — attribute with a link to https://robrunwiki.site
- The wiki itself: [robrunwiki.site](https://robrunwiki.site) — server status, player count, wipe timer, map & districts (English + Русский).

## Why open

Player counts and wipe times get re-reported everywhere without sources. We verify every reading against official endpoints and date-stamp it — build on top of it freely.
