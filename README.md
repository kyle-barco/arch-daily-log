# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2365**
- Today's entries: **1**
- Today's note: `notes/2026-08-18.md`

### Latest Entry

- Timestamp: `2026-08-18T06:15:38+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 119
- `Architecture`: 119
- `Databases`: 119
- `Observability`: 119
- `Security`: 119

### Recent Timeline

- `2026-08-18T06:15:38+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-17T22:51:55+08:00` | **Log with stable keys** (Observability)
- `2026-08-17T22:19:32+08:00` | **Design for idempotency** (APIs)
- `2026-08-17T21:53:41+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-17T21:14:49+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-17T20:26:08+08:00` | **Write one behavior per test** (Testing)
- `2026-08-17T19:47:52+08:00` | **Use virtual environments by default** (Python)
- `2026-08-17T19:17:52+08:00` | **Prefer small focused commits** (Git)
- `2026-08-17T18:48:36+08:00` | **Write decisions down** (Leadership)
- `2026-08-17T18:14:30+08:00` | **Keyboard support is a baseline** (Accessibility)
