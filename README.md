# Heart Crew Guides — data feed

Generated JSON feed of weekly Heart Crew / Live It Out guides for the
HeartCrew app. Published automatically by a sync workflow — **do not edit
by hand**; changes will be overwritten on the next sync.

- `manifest.json` — list of available guides (campus, link type, sermon
  metadata, thumbnail URL)
- `guides/<id>.json` — one structured CrewGuide document per guide

Consumed by the app via
`https://raw.githubusercontent.com/arsonull/heartcrew-guides/main/manifest.json`.
