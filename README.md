# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2105**
- Today's entries: **4**
- Today's note: `notes/2026-07-27.md`

### Latest Entry

- Timestamp: `2026-07-27T13:04:08+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 106
- `Architecture`: 106
- `Databases`: 106
- `Observability`: 106
- `Security`: 106

### Recent Timeline

- `2026-07-27T13:04:08+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-27T09:17:05+08:00` | **Log with stable keys** (Observability)
- `2026-07-27T07:39:38+08:00` | **Design for idempotency** (APIs)
- `2026-07-27T06:39:38+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-26T20:14:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-26T12:42:50+08:00` | **Write one behavior per test** (Testing)
- `2026-07-26T09:14:00+08:00` | **Use virtual environments by default** (Python)
- `2026-07-25T19:40:28+08:00` | **Prefer small focused commits** (Git)
- `2026-07-25T18:15:25+08:00` | **Write decisions down** (Leadership)
- `2026-07-25T16:36:47+08:00` | **Keyboard support is a baseline** (Accessibility)
