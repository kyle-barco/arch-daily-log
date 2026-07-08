# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **1965**
- Today's entries: **1**
- Today's note: `notes/2026-07-09.md`

### Latest Entry

- Timestamp: `2026-07-09T06:42:18+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 99
- `Architecture`: 99
- `Databases`: 99
- `Observability`: 99
- `Security`: 99

### Recent Timeline

- `2026-07-09T06:42:18+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-08T21:44:56+08:00` | **Log with stable keys** (Observability)
- `2026-07-08T19:49:27+08:00` | **Design for idempotency** (APIs)
- `2026-07-08T17:59:37+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-08T15:44:23+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-08T13:17:44+08:00` | **Write one behavior per test** (Testing)
- `2026-07-08T09:56:17+08:00` | **Use virtual environments by default** (Python)
- `2026-07-08T07:51:18+08:00` | **Prefer small focused commits** (Git)
- `2026-07-08T06:53:25+08:00` | **Write decisions down** (Leadership)
- `2026-07-07T21:35:52+08:00` | **Keyboard support is a baseline** (Accessibility)
