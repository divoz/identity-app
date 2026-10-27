# identity-app
![WIP](https://img.shields.io/badge/status-in--progress-yellow)

RBAC identity service: users, roles, permissions, and an audit log with
 AI-assisted investigation of suspicious events.

**Status:** in progress. Week 1 of 4.

## Stack
Next.js (TypeScript) · PostgreSQL · Prisma · Argon2 · JWT

## Running locally
```bash
docker compose up -d
npm install
npx prisma migrate dev
npm run dev
```

## Progress
- [x] Postgres + Prisma
- [ ] Schema: users, roles, permissions
- [ ] Register and login
- [ ] Permission checks
- [ ] Audit log
- [ ] LLM investigation summaries
- [ ] AWS deployment
