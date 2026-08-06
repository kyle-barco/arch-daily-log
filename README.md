# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2185**
- Today's entries: **7**
- Today's note: `notes/2026-08-06.md`

### Latest Entry

- Timestamp: `2026-08-06T19:41:20+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 110
- `Architecture`: 110
- `Databases`: 110
- `Observability`: 110
- `Security`: 110

### Recent Timeline

- `2026-08-06T19:41:20+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-06T17:29:08+08:00` | **Log with stable keys** (Observability)
- `2026-08-06T14:33:17+08:00` | **Design for idempotency** (APIs)
- `2026-08-06T11:59:00+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-06T08:49:32+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-06T07:17:51+08:00` | **Write one behavior per test** (Testing)
- `2026-08-06T06:13:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-05T22:53:07+08:00` | **Prefer small focused commits** (Git)
- `2026-08-05T20:26:22+08:00` | **Write decisions down** (Leadership)
- `2026-08-05T18:40:50+08:00` | **Keyboard support is a baseline** (Accessibility)
