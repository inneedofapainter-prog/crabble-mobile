# Stats Tab and Leaderboard Cleanup Update

This update cleans up the online lobby and moves stats into a dedicated Stats tab.

## Included

- Removed the full leaderboard block from the online lobby so the lobby is focused on finding and challenging players.
- Added a new **Stats** tab beside Lobby / Create / Join.
- Stats tab shows the current player profile's combined stats:
  - Total wins/losses
  - Online wins/losses
  - Solo wins/losses
  - Current/best online streak
  - Longest word overall
  - Longest online word
  - Longest solo word
- Stats tab shows only the **Top 3 Players** leaderboard.
- Online stats stay saved in Postgres.
- Solo game wins/losses/longest word are sent to the server when a solo game ends, so they can appear under that profile name.

## Deploy

Copy this package into the GitHub repo root, overwrite files, commit to `main`, then let Render redeploy.
