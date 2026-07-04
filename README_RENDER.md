# Crabble Render deploy

Upload the contents of this folder to the root of your GitHub repository.

Render settings:
- Runtime: Node
- Build Command: npm install
- Start Command: npm start
- Health Check Path: /api/healthz
- Environment variables:
  - NODE_ENV=production
  - DATABASE_URL=<Render Postgres internal database URL>

Do not add PORT manually; Render provides it.
