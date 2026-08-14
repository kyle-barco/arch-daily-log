# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2285**
- Today's entries: **6**
- Today's note: `notes/2026-08-14.md`

### Latest Entry

- Timestamp: `2026-08-14T13:18:28+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 115
- `Architecture`: 115
- `Databases`: 115
- `Observability`: 115
- `Security`: 115

### Recent Timeline

- `2026-08-14T13:18:28+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-14T11:30:18+08:00` | **Log with stable keys** (Observability)
- `2026-08-14T09:13:45+08:00` | **Design for idempotency** (APIs)
- `2026-08-14T07:45:58+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-14T06:59:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-14T06:01:56+08:00` | **Write one behavior per test** (Testing)
- `2026-08-13T22:44:36+08:00` | **Use virtual environments by default** (Python)
- `2026-08-13T21:43:28+08:00` | **Prefer small focused commits** (Git)
- `2026-08-13T20:09:19+08:00` | **Write decisions down** (Leadership)
- `2026-08-13T19:28:09+08:00` | **Keyboard support is a baseline** (Accessibility)
