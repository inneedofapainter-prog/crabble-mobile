# GO Rule Update

This update fixes the issue where GO could be pressed when the rack was empty but the board was split into disconnected word groups.

## Changed

- GO now requires every placed tile to be in one connected group.
- GO now requires every extracted word to be valid.
- Disconnected tiles/words are highlighted as invalid.
- The server rejects forced GO calls when the board is disconnected or invalid.

## Deploy

Copy the contents of this folder to your GitHub repo root, commit to `main`, then let Render redeploy.
