# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2065**
- Today's entries: **7**
- Today's note: `notes/2026-07-21.md`

### Latest Entry

- Timestamp: `2026-07-21T19:28:24+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 104
- `Architecture`: 104
- `Databases`: 104
- `Observability`: 104
- `Security`: 104

### Recent Timeline

- `2026-07-21T19:28:24+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-21T17:38:06+08:00` | **Log with stable keys** (Observability)
- `2026-07-21T15:10:32+08:00` | **Design for idempotency** (APIs)
- `2026-07-21T12:29:30+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-21T09:06:20+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-21T07:38:04+08:00` | **Write one behavior per test** (Testing)
- `2026-07-21T06:31:27+08:00` | **Use virtual environments by default** (Python)
- `2026-07-20T22:39:43+08:00` | **Prefer small focused commits** (Git)
- `2026-07-20T20:29:36+08:00` | **Write decisions down** (Leadership)
- `2026-07-20T18:24:25+08:00` | **Keyboard support is a baseline** (Accessibility)
