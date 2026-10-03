# CZN Animation Viewer

A free, **non-commercial fan-made** viewer and reference library for **Chaos Zero Nightmare (CZN)** animations.

**Live: https://bennosleep.github.io/czn-animation-viewer/**

## Why this exists

CZN's animations are scattered inside the game client and hard to look up when you
actually need them. This site is a free reference library built so **content creators,
guide writers and wiki editors** can find and preview the exact animation, pose or
effect before recording or editing — video edits, thumbnails, guides, fan art.

It is a **viewer and index** — nothing here is playable as a game, nothing is sold.

## What's inside

- **Animation preview** — character models, portraits, battle animations and animated
  cut-ins (FHD / collapse / UX) in one grid, with a seekable timeline for the cut-ins.
- Filter by character, kind (portrait / model / battle / cutin / gacha) and role
  (Playable / Support / Other).

## Rights & removal

- Unofficial fan project. **Not affiliated with, sponsored or endorsed by** the
  developers or publishers of Chaos Zero Nightmare.
- All art, animations and names are © their respective owners and appear here for
  **reference purposes only**. No monetization, no ads, no paywalls, no donations.
- **If you are a rights holder and would like content adjusted or removed, please
  open an issue — we comply promptly.**

## Technical

- Static site hosted on GitHub Pages; Spine 3.8 WebGL runtime.
- Viewer shell: `index.html` / `viewer.html`; assets under `rigs/`, `cutins/`, `thumbs/`;
  catalog in `index.json`.
- Built from the game client with the UncleDecodeCZN toolkit.
