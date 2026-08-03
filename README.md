# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2163**
- Today's entries: **1**
- Today's note: `notes/2026-08-04.md`

### Latest Entry

- Timestamp: `2026-08-04T06:05:47+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 109
- `Databases`: 109
- `Security`: 109
- `Testing`: 109
- `Accessibility`: 108

### Recent Timeline

- `2026-08-04T06:05:47+08:00` | **Design for idempotency** (APIs)
- `2026-08-03T21:30:01+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-03T18:33:57+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-03T14:52:47+08:00` | **Write one behavior per test** (Testing)
- `2026-08-03T11:51:44+08:00` | **Use virtual environments by default** (Python)
- `2026-08-03T08:10:22+08:00` | **Prefer small focused commits** (Git)
- `2026-08-03T07:08:50+08:00` | **Write decisions down** (Leadership)
- `2026-08-03T06:08:20+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-02T22:55:35+08:00` | **Measure before tuning** (Performance)
- `2026-08-02T21:55:16+08:00` | **Fail fast on lint and tests** (CI/CD)
