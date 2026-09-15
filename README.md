# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2645**
- Today's entries: **2**
- Today's note: `notes/2026-09-15.md`

### Latest Entry

- Timestamp: `2026-09-15T08:38:16+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 133
- `Architecture`: 133
- `Databases`: 133
- `Observability`: 133
- `Security`: 133

### Recent Timeline

- `2026-09-15T08:38:16+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-09-15T06:12:56+08:00` | **Log with stable keys** (Observability)
- `2026-09-14T21:21:08+08:00` | **Design for idempotency** (APIs)
- `2026-09-14T14:41:01+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-09-14T09:26:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-09-14T07:29:52+08:00` | **Write one behavior per test** (Testing)
- `2026-09-13T17:44:04+08:00` | **Use virtual environments by default** (Python)
- `2026-09-13T12:41:57+08:00` | **Prefer small focused commits** (Git)
- `2026-09-13T08:05:20+08:00` | **Write decisions down** (Leadership)
- `2026-09-13T06:25:26+08:00` | **Keyboard support is a baseline** (Accessibility)
