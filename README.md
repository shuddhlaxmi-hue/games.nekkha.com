# games.nekkha.com

Standalone landing page for the NEXA gaming platform umbrella.

- `index.html` — single static page, no build step, no dependencies.
- Ludo card links to https://ludo.nekkha.com (live).
- Snake & Ladder and Chess cards are disabled "coming soon" placeholders
  for https://snakeladder.nekkha.com and https://chess.nekkha.com —
  flip them to live links when those games ship.

## Serve

Any static file server / nginx root. e.g. `python3 -m http.server` or an
nginx `server { root .../games.nekkha.com; }` block.
