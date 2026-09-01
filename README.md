# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2585**
- Today's entries: **2**
- Today's note: `notes/2026-09-01.md`

### Latest Entry

- Timestamp: `2026-09-01T10:02:17+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 130
- `Architecture`: 130
- `Databases`: 130
- `Observability`: 130
- `Security`: 130

### Recent Timeline

- `2026-09-01T10:02:17+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-09-01T07:31:03+08:00` | **Log with stable keys** (Observability)
- `2026-08-31T21:46:54+08:00` | **Design for idempotency** (APIs)
- `2026-08-31T14:11:49+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-31T08:41:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-31T06:15:46+08:00` | **Write one behavior per test** (Testing)
- `2026-08-30T20:50:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-30T07:28:31+08:00` | **Prefer small focused commits** (Git)
- `2026-08-28T21:36:54+08:00` | **Write decisions down** (Leadership)
- `2026-08-28T09:46:22+08:00` | **Keyboard support is a baseline** (Accessibility)
