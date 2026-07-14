# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2005**
- Today's entries: **6**
- Today's note: `notes/2026-07-14.md`

### Latest Entry

- Timestamp: `2026-07-14T16:53:50+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 101
- `Architecture`: 101
- `Databases`: 101
- `Observability`: 101
- `Security`: 101

### Recent Timeline

- `2026-07-14T16:53:50+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-14T14:33:00+08:00` | **Log with stable keys** (Observability)
- `2026-07-14T12:15:58+08:00` | **Design for idempotency** (APIs)
- `2026-07-14T09:02:48+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-14T07:33:40+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-14T06:36:05+08:00` | **Write one behavior per test** (Testing)
- `2026-07-13T21:13:49+08:00` | **Use virtual environments by default** (Python)
- `2026-07-13T18:51:52+08:00` | **Prefer small focused commits** (Git)
- `2026-07-13T15:54:43+08:00` | **Write decisions down** (Leadership)
- `2026-07-13T12:44:14+08:00` | **Keyboard support is a baseline** (Accessibility)
