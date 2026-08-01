# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2145**
- Today's entries: **7**
- Today's note: `notes/2026-08-01.md`

### Latest Entry

- Timestamp: `2026-08-01T20:38:14+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 108
- `Architecture`: 108
- `Databases`: 108
- `Observability`: 108
- `Security`: 108

### Recent Timeline

- `2026-08-01T20:38:14+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-01T19:38:56+08:00` | **Log with stable keys** (Observability)
- `2026-08-01T18:21:34+08:00` | **Design for idempotency** (APIs)
- `2026-08-01T16:37:51+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-01T14:21:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-01T11:46:50+08:00` | **Write one behavior per test** (Testing)
- `2026-08-01T08:10:01+08:00` | **Use virtual environments by default** (Python)
- `2026-07-31T22:54:59+08:00` | **Prefer small focused commits** (Git)
- `2026-07-31T20:17:44+08:00` | **Write decisions down** (Leadership)
- `2026-07-31T18:14:23+08:00` | **Keyboard support is a baseline** (Accessibility)
