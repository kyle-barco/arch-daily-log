# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2603**
- Today's entries: **1**
- Today's note: `notes/2026-09-05.md`

### Latest Entry

- Timestamp: `2026-09-05T07:19:05+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 131
- `Databases`: 131
- `Security`: 131
- `Testing`: 131
- `Accessibility`: 130

### Recent Timeline

- `2026-09-05T07:19:05+08:00` | **Design for idempotency** (APIs)
- `2026-09-04T21:10:12+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-09-04T16:57:43+08:00` | **Rotate credentials on schedule** (Security)
- `2026-09-04T12:26:47+08:00` | **Write one behavior per test** (Testing)
- `2026-09-04T08:03:16+08:00` | **Use virtual environments by default** (Python)
- `2026-09-04T06:03:44+08:00` | **Prefer small focused commits** (Git)
- `2026-09-03T21:41:43+08:00` | **Write decisions down** (Leadership)
- `2026-09-03T17:19:51+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-09-03T12:48:21+08:00` | **Measure before tuning** (Performance)
- `2026-09-03T08:24:58+08:00` | **Fail fast on lint and tests** (CI/CD)
