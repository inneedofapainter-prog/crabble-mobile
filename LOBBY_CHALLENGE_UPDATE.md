# Crabble Lobby + Direct Challenge Update

This update adds a public online lobby and direct player challenge flow.

## Added

- Public online lobby tab on the Online screen.
- Live online player count.
- Online player list with status:
  - Available
  - In room
  - In game
- Direct Challenge button for available players.
- Incoming challenge prompt with Accept / Decline.
- Challenge accepted flow automatically creates a private room and moves both players into it.
- Server-side Socket.io enforcement so challenges cannot be accepted if either player is already busy.

## Kept from previous versions

- Electric blue header/accent colour.
- GO button connected-board validation.
- Dump Tile rule restriction.
- Render root-ready deployment layout.

## Deploy

Copy the contents of this package into the GitHub repo root, overwrite existing files, commit to `main`, then let Render redeploy.
