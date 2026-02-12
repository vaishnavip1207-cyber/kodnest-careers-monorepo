# KodNestCareers

Local-first job tracking and career readiness monorepo.

## Quick local setup

1. Install pnpm: `npm i -g pnpm`
2. Install deps: `pnpm install`
3. Start infra: `docker compose -f docker-compose.local.yml up -d`
4. Copy env: `cp .env.example .env`
5. Run migrations: `pnpm db:migrate`
6. Start apps: `pnpm dev`

See `docs/runbooks/local-setup.md` for details.
