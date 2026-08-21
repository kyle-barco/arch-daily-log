# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2463**
- Today's entries: **22**
- Today's note: `notes/2026-08-21.md`

### Latest Entry

- Timestamp: `2026-08-21T20:55:02+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 124
- `Databases`: 124
- `Security`: 124
- `Testing`: 124
- `Accessibility`: 123

### Recent Timeline

- `2026-08-21T20:55:02+08:00` | **Design for idempotency** (APIs)
- `2026-08-21T19:59:37+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-21T19:38:32+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-21T19:03:46+08:00` | **Write one behavior per test** (Testing)
- `2026-08-21T18:44:46+08:00` | **Use virtual environments by default** (Python)
- `2026-08-21T18:00:49+08:00` | **Prefer small focused commits** (Git)
- `2026-08-21T17:28:57+08:00` | **Write decisions down** (Leadership)
- `2026-08-21T16:55:33+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-21T16:04:43+08:00` | **Measure before tuning** (Performance)
- `2026-08-21T15:27:12+08:00` | **Fail fast on lint and tests** (CI/CD)
