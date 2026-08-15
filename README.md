# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2305**
- Today's entries: **12**
- Today's note: `notes/2026-08-15.md`

### Latest Entry

- Timestamp: `2026-08-15T15:50:08+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 116
- `Architecture`: 116
- `Databases`: 116
- `Observability`: 116
- `Security`: 116

### Recent Timeline

- `2026-08-15T15:50:08+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-15T13:58:56+08:00` | **Log with stable keys** (Observability)
- `2026-08-15T12:44:47+08:00` | **Design for idempotency** (APIs)
- `2026-08-15T12:01:29+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-15T11:22:00+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-15T10:37:35+08:00` | **Write one behavior per test** (Testing)
- `2026-08-15T07:59:57+08:00` | **Use virtual environments by default** (Python)
- `2026-08-15T07:44:15+08:00` | **Prefer small focused commits** (Git)
- `2026-08-15T07:21:59+08:00` | **Write decisions down** (Leadership)
- `2026-08-15T06:58:27+08:00` | **Keyboard support is a baseline** (Accessibility)
