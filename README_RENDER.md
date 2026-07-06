# Crabble Render deploy

Upload the contents of this folder to the root of your GitHub repository.

Render settings:
- Runtime: Node
- Build Command: npm install
- Start Command: npm start
- Health Check Path: /api/healthz
- Environment variables:
  - NODE_ENV=production
  - DATABASE_URL=<Render Postgres internal database URL>

Do not add PORT manually; Render provides it.

## Dump Tile rule update

Dump Tile is now a last-resort move. It only unlocks when the player cannot form any valid word using at least one tile from their rack plus the letters already on their own board. The same rule is enforced in the multiplayer server.
