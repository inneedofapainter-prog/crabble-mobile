# Crabble Profile, Leaderboard Cleanup, and 3+ Player Lobby Update

## Added
- Saved player profile name for Solo and Online play.
- Cleaner lobby leaderboard labelled Top Players.
- Top 5 leaderboard display to reduce clutter.
- Leaderboard rows now show W-L, games, best streak, and current streak.
- Online players section renamed Find Match.
- Host room screen now includes Add Players From Lobby.
- Hosts can directly invite available or solo players into an existing lobby before starting.
- Accepted room invites add the player to the existing room instead of creating a new 2-player room.
- Server registers room creators/joiners in the public lobby so 3+ player room inviting is more reliable.

## Kept
- Postgres persistent wins/losses/streaks.
- Rematch winner fix.
- GI word validation fix.
- Share App button.
- Direct challenges.
- Electric blue theme.

## Usage
Players should enter their player profile name before choosing Solo or Online. For 3+ player online matches, the host creates a room, then uses Add Players From Lobby or the share invite link before pressing Start Game.
