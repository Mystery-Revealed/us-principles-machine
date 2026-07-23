# The Principles Machine

A single-page interactive app that turns the seven constitutional principles into a gear machine — click a gear, learn the principle, then practice matching real-life scenarios to the right gear.

Built for 8th Grade U.S. History · TEKS 8.15D, 8.19A, 8.29B.

## What it does

- **Explore the Machine** — seven meshed, slowly turning gears (Popular Sovereignty at the hub; Limited Government, Republicanism, Separation of Powers, Checks and Balances, Federalism, and Individual Rights around it). Click a gear to open its card: plain-words definition, picture example, a "spot it in real life" scenario, and a "don't confuse it with" tip for the classic mix-ups (republicanism vs. popular sovereignty; separation of powers vs. checks and balances).
- **Federalism power sorter** — a mini ungraded activity inside the Federalism card: sort six powers into Delegated, Reserved, or Concurrent.
- **Match It** — a toggled practice mode. A scenario appears, students tap the gear that matches, and get instant feedback plus the confusion tip. Streak counter only; nothing is graded or recorded.
- **Money moment** — open all seven cards and the gears sync up and spin together while "…a more perfect Union" rolls across the screen.
- Tap-to-define bubbles for *sovereignty*, *veto*, and *federal* on first use in each card.

## Tech

One self-contained `index.html` (inline CSS/JS, no build step, no framework, no tracking, no browser storage). Gears are coded SVG, generated at load time from gear geometry (not hand-drawn paths). Images live in `assets/`. Responsive down to 360px — the gear machine becomes a 2×4 button grid and cards go full-screen. Works by opening the file directly or hosting on any static server / GitHub Pages.

## Hosting

Deployed via GitHub Pages (Settings → Pages → deploy from `main`) and embedded in Wix by iframe.
