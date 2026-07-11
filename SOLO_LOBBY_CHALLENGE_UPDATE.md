# Solo Lobby Challenge Update

- Keeps the online Socket.io lobby mounted across the whole app, including Solo mode.
- Solo setup registers the player as available in the public lobby once a name is entered.
- Starting a solo game changes the player lobby status to `Playing solo`.
- Lobby lists `Available`, `Playing solo`, `In room`, and `In online game` players.
- Available and solo players can be challenged directly.
- Solo players receive a challenge prompt and can accept to switch into a private online room.
- Server-side challenge checks now allow `available` and `solo` statuses, while still blocking players already in rooms or online games.
