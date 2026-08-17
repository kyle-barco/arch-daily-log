# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2363**
- Today's entries: **25**
- Today's note: `notes/2026-08-17.md`

### Latest Entry

- Timestamp: `2026-08-17T22:19:32+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 119
- `Databases`: 119
- `Security`: 119
- `Testing`: 119
- `Accessibility`: 118

### Recent Timeline

- `2026-08-17T22:19:32+08:00` | **Design for idempotency** (APIs)
- `2026-08-17T21:53:41+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-17T21:14:49+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-17T20:26:08+08:00` | **Write one behavior per test** (Testing)
- `2026-08-17T19:47:52+08:00` | **Use virtual environments by default** (Python)
- `2026-08-17T19:17:52+08:00` | **Prefer small focused commits** (Git)
- `2026-08-17T18:48:36+08:00` | **Write decisions down** (Leadership)
- `2026-08-17T18:14:30+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-17T17:41:26+08:00` | **Measure before tuning** (Performance)
- `2026-08-17T16:58:20+08:00` | **Fail fast on lint and tests** (CI/CD)
