# Leaderboard v2 update

- Stores online multiplayer results in Postgres table `crabble_player_stats`.
- Tracks wins, losses, games played, current win streak, and best streak.
- Solo games do not count.
- Lobby leaderboard shows top players with win/loss and streak data.
- Winner screen labels online replay as Rematch.

Render note: keep the existing `DATABASE_URL` environment variable set to your Render Postgres internal database URL. The app creates the leaderboard table automatically on startup.
