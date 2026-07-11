# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **1985**
- Today's entries: **7**
- Today's note: `notes/2026-07-11.md`

### Latest Entry

- Timestamp: `2026-07-11T22:23:44+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 100
- `Architecture`: 100
- `Databases`: 100
- `Observability`: 100
- `Security`: 100

### Recent Timeline

- `2026-07-11T22:23:44+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-11T21:00:03+08:00` | **Log with stable keys** (Observability)
- `2026-07-11T19:50:22+08:00` | **Design for idempotency** (APIs)
- `2026-07-11T18:56:39+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-11T16:13:21+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-11T08:09:54+08:00` | **Write one behavior per test** (Testing)
- `2026-07-11T06:14:15+08:00` | **Use virtual environments by default** (Python)
- `2026-07-10T21:45:18+08:00` | **Prefer small focused commits** (Git)
- `2026-07-10T19:44:03+08:00` | **Write decisions down** (Leadership)
- `2026-07-10T16:48:49+08:00` | **Keyboard support is a baseline** (Accessibility)
