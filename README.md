# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2465**
- Today's entries: **24**
- Today's note: `notes/2026-08-21.md`

### Latest Entry

- Timestamp: `2026-08-21T22:17:32+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 124
- `Architecture`: 124
- `Databases`: 124
- `Observability`: 124
- `Security`: 124

### Recent Timeline

- `2026-08-21T22:17:32+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-21T21:38:38+08:00` | **Log with stable keys** (Observability)
- `2026-08-21T20:55:02+08:00` | **Design for idempotency** (APIs)
- `2026-08-21T19:59:37+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-21T19:38:32+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-21T19:03:46+08:00` | **Write one behavior per test** (Testing)
- `2026-08-21T18:44:46+08:00` | **Use virtual environments by default** (Python)
- `2026-08-21T18:00:49+08:00` | **Prefer small focused commits** (Git)
- `2026-08-21T17:28:57+08:00` | **Write decisions down** (Leadership)
- `2026-08-21T16:55:33+08:00` | **Keyboard support is a baseline** (Accessibility)
