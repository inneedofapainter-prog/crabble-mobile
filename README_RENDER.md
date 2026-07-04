# Crabble Render-ready deploy

This package serves both:
- the built Expo mobile web app from `/`
- the API/socket server from `/api` and `/api/socket.io`

Render settings:
- Service type: Web Service
- Runtime: Node
- Build command: `npm install`
- Start command: `npm start`
- Health check path: `/api/healthz`
- Environment variables:
  - `NODE_ENV=production`
  - `DATABASE_URL=<your Render Postgres External Database URL>`

Render supplies the `PORT` environment variable automatically.
