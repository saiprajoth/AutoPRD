# SST Packet — Task 00: Repo Foundation

## S — Spec
Initialize Turborepo with apps and packages needed for Phase 1. Provide infra (Postgres/Redis) and green checks.

Acceptance Criteria:
- `pnpm lint` passes
- `pnpm typecheck` passes
- `pnpm test` passes
- `docker compose up -d` starts Postgres + Redis

## C — Constraints
- Must run on macOS/Linux with Node + pnpm + Docker.
- Green checks should be fast.

## A — Architecture
- apps/web: Next.js app
- apps/worker: TS worker skeleton
- packages/core: shared TS + tests
- packages/db: prisma scaffold placeholder

## L — Load & Limits
N/A (setup task).

## E — Evaluation
N/A (setup task).

## D — Defense
- No secrets committed.
- `.env.example` provided.

## T — Testing
- At least one real unit test exists (`packages/core`) so test runner is real.

## Sh — Shipping
- README contains setup and green-check commands.
