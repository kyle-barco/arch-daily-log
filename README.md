# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2525**
- Today's entries: **20**
- Today's note: `notes/2026-08-24.md`

### Latest Entry

- Timestamp: `2026-08-24T19:50:53+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 127
- `Architecture`: 127
- `Databases`: 127
- `Observability`: 127
- `Security`: 127

### Recent Timeline

- `2026-08-24T19:50:53+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-24T19:19:30+08:00` | **Log with stable keys** (Observability)
- `2026-08-24T18:51:19+08:00` | **Design for idempotency** (APIs)
- `2026-08-24T18:02:57+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-24T17:12:00+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-24T16:26:19+08:00` | **Write one behavior per test** (Testing)
- `2026-08-24T15:43:13+08:00` | **Use virtual environments by default** (Python)
- `2026-08-24T14:39:15+08:00` | **Prefer small focused commits** (Git)
- `2026-08-24T13:51:08+08:00` | **Write decisions down** (Leadership)
- `2026-08-24T13:10:23+08:00` | **Keyboard support is a baseline** (Accessibility)
