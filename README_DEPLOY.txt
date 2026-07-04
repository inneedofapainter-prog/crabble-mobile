Crabble Mobile web export.

Deploy these files to a static host.
For online multiplayer, host the API/socket server too.
If the API is on another domain, rebuild this web export with:

EXPO_PUBLIC_DOMAIN=your-api-domain.com pnpm -C artifacts/crabble-mobile run build

When EXPO_PUBLIC_DOMAIN is unset, the socket client uses same-origin `/api/socket.io`.
