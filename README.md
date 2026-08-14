# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2283**
- Today's entries: **4**
- Today's note: `notes/2026-08-14.md`

### Latest Entry

- Timestamp: `2026-08-14T09:13:45+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 115
- `Databases`: 115
- `Security`: 115
- `Testing`: 115
- `Accessibility`: 114

### Recent Timeline

- `2026-08-14T09:13:45+08:00` | **Design for idempotency** (APIs)
- `2026-08-14T07:45:58+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-14T06:59:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-14T06:01:56+08:00` | **Write one behavior per test** (Testing)
- `2026-08-13T22:44:36+08:00` | **Use virtual environments by default** (Python)
- `2026-08-13T21:43:28+08:00` | **Prefer small focused commits** (Git)
- `2026-08-13T20:09:19+08:00` | **Write decisions down** (Leadership)
- `2026-08-13T19:28:09+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-13T18:43:05+08:00` | **Measure before tuning** (Performance)
- `2026-08-13T17:31:32+08:00` | **Fail fast on lint and tests** (CI/CD)
