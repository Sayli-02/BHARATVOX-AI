# BharatVox AI

Multilingual customer support for the demo shop Mogra. The assistant answers from an approved knowledge base and escalates everything else to staff, with a ticket the customer can track.

The short source of truth is [PROJECT_INIT.md](PROJECT_INIT.md). Working docs live in [docs/](docs/). Agent instructions are in [docs/AGENT.md](docs/AGENT.md).

## Scripts

```bash
pnpm install
pnpm dev
pnpm lint
pnpm typecheck
pnpm test
```

Copy `.env.example` to `.env.local` when a later phase needs keys. Leave the values empty until then.

## Status

Phase 0 (foundation and docs) is in place. Design, database, chat, and AI are not built yet. The full setup guide, architecture diagram, and demo script arrive in Phase 9.
