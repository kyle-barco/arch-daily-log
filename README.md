# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2325**
- Today's entries: **7**
- Today's note: `notes/2026-08-16.md`

### Latest Entry

- Timestamp: `2026-08-16T16:44:47+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 117
- `Architecture`: 117
- `Databases`: 117
- `Observability`: 117
- `Security`: 117

### Recent Timeline

- `2026-08-16T16:44:47+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-16T13:51:54+08:00` | **Log with stable keys** (Observability)
- `2026-08-16T12:19:34+08:00` | **Design for idempotency** (APIs)
- `2026-08-16T09:01:14+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-16T07:41:42+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-16T06:59:25+08:00` | **Write one behavior per test** (Testing)
- `2026-08-16T06:15:09+08:00` | **Use virtual environments by default** (Python)
- `2026-08-15T22:45:32+08:00` | **Prefer small focused commits** (Git)
- `2026-08-15T22:24:03+08:00` | **Write decisions down** (Leadership)
- `2026-08-15T21:41:58+08:00` | **Keyboard support is a baseline** (Accessibility)
