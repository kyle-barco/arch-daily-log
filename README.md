# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2425**
- Today's entries: **9**
- Today's note: `notes/2026-08-20.md`

### Latest Entry

- Timestamp: `2026-08-20T12:07:37+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 122
- `Architecture`: 122
- `Databases`: 122
- `Observability`: 122
- `Security`: 122

### Recent Timeline

- `2026-08-20T12:07:37+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-20T11:28:07+08:00` | **Log with stable keys** (Observability)
- `2026-08-20T10:33:49+08:00` | **Design for idempotency** (APIs)
- `2026-08-20T09:21:12+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-20T07:59:02+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-20T07:43:56+08:00` | **Write one behavior per test** (Testing)
- `2026-08-20T07:15:42+08:00` | **Use virtual environments by default** (Python)
- `2026-08-20T06:48:09+08:00` | **Prefer small focused commits** (Git)
- `2026-08-20T06:15:57+08:00` | **Write decisions down** (Leadership)
- `2026-08-19T22:51:06+08:00` | **Keyboard support is a baseline** (Accessibility)
