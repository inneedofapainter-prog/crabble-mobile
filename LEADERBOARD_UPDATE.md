# Crabble Leaderboard Update

Adds an online leaderboard to the public lobby.

## Included

- Online lobby now shows a Leaderboard section.
- Leaderboard displays player name and online win count.
- Online player rows also show each player's wins.
- Server records a win when an online multiplayer game finishes with a winner.
- Solo games do not count as online wins.
- Wins are kept by player name and backed by a small JSON file on the server (`crabble-leaderboard.json` by default).

## Notes

If the Render service is redeployed or rebuilt, the default JSON file may reset unless a persistent disk is attached or `CRABBLE_LEADERBOARD_FILE` points to a persistent path.
