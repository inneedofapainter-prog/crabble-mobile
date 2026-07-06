# Dump Tile rule update

Implemented rule:

> Dump Tile can only be used when no valid word can be formed from the player's hand plus the letters already on that player's board.

What changed:

- The Dump Tile button is disabled when a valid word is still possible.
- The in-game hints explain why Dump Tile is locked.
- The multiplayer server rejects forced `dumpTile` socket actions if a valid word can still be formed.
- The rule requires the possible word to use at least one tile from the player's current rack.

Checks run:

- Server JavaScript syntax check passed.
- Mobile web bundle syntax check passed.
- Render server `/api/healthz` smoke test passed with a dummy database URL.
