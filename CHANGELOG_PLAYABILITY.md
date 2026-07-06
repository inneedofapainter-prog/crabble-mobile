# Crabble Playability Update

This Render-ready build adds the first playability fixes requested after live testing.

## Added

- **Dump Tile button** during gameplay.
  - Select a rack tile, then tap **Dump Tile**.
  - The selected tile goes back into the pool and the player draws up to 2 new tiles.
  - Works in solo and online multiplayer.
- **How to Play popup** in the in-game menu.
  - Tap the ☰ menu, then **How to Play**.
  - Explains tap-to-place, valid words, Dump Tile, and GO.
- **Clear GO locked message**.
  - The footer now explains why GO is unavailable and tells the player how to continue.
- **Better selected-tile hint**.
  - When a tile is selected, the hint now says the player can place it or dump it.

## Render settings

Use the same Render settings as the last working package:

- Build command: `npm install`
- Start command: `npm start`
- Health check path: `/api/healthz`
- Environment variables:
  - `NODE_ENV=production`
  - `DATABASE_URL=<your Render Postgres internal URL>`


## Dump Tile rule update

- Dump Tile is now restricted to genuine stuck states only.
- The button unlocks only when no valid word can be formed using at least one tile from the player's rack plus letters already on that player's board.
- The multiplayer server enforces the same rule, so the browser cannot bypass it.
