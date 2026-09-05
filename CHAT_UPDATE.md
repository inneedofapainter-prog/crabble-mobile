# Chat Update

Adds room chat for online multiplayer.

## Included
- Chat button in the in-game header for online rooms.
- Room Chat button in the game dropdown menu.
- Real-time messages through Socket.io.
- Server-side message validation and 160-character limit.
- Last 50 room messages are kept while the room exists.
- Chat history is sent to players who join or reconnect to a room.

## Notes
- Chat is per online room only.
- Chat is not stored permanently in Postgres.
- Messages are cleared when the room disappears/restarts on deploy.
