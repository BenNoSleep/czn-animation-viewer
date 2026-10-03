# CZN Animation Viewer

A **fan-made** web viewer for previewing animations from **Chaos Zero Nightmare (CZN)**.

**Live: https://bennosleep.github.io/czn-animation-viewer/**

## What it's for

- **Animation preview** — character models, portraits, battle animations and animated
  cut-ins (FHD / collapse / UX) in one grid, with a seekable timeline for the cut-ins.
  Filter by character, kind (portrait / model / battle / cutin / gacha) and role
  (Playable / Support / Other).
- **Content creators** — find the exact animation, pose or effect you need before
  recording or editing: video edits, thumbnails, guides, fan art, references.

## Disclaimer

- Unofficial **fan project** — not affiliated with, sponsored or endorsed by the game's
  developer or publisher.
- All game assets (art, animations, names) are © their respective owners; they appear
  here for preview / reference purposes only.
- Assets are data-mined from the game client. No accounts, no tracking, no ads.

## Technical

- Static site hosted on GitHub Pages; Spine 3.8 WebGL runtime.
- Viewer shell: `index.html` / `viewer.html`; assets under `rigs/`, `cutins/`, `thumbs/`;
  catalog in `index.json`.
- Built from the game pack with the UncleDecodeCZN toolkit.
