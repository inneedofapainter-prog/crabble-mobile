# Share App Update

Added a general Share App action to the in-game dropdown menu.

## Behaviour

- Adds `📤 Share App` to the Game Menu dropdown.
- Shares the public app link only; no room code is included.
- Uses the message: `Play Crabble with me. Tap to play.`
- Uses the current live site origin on Render so the shared link points to the deployed app.
- Falls back to copying the link/message on browsers that do not support the native share sheet.

## Previous updates still included

- Lobby and direct challenge flow.
- Solo players visible/challengeable in the lobby.
- Electric blue theme.
- Dump Tile rule protection.
- GO connected-board rule protection.
