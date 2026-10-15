# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2743**
- Today's entries: **1**
- Today's note: `notes/2026-10-16.md`

### Latest Entry

- Timestamp: `2026-10-16T07:59:05+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 138
- `Databases`: 138
- `Security`: 138
- `Testing`: 138
- `Accessibility`: 137

### Recent Timeline

- `2026-10-16T07:59:05+08:00` | **Design for idempotency** (APIs)
- `2026-10-15T22:36:11+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-10-15T17:55:52+08:00` | **Rotate credentials on schedule** (Security)
- `2026-10-15T13:13:49+08:00` | **Write one behavior per test** (Testing)
- `2026-10-15T08:42:24+08:00` | **Use virtual environments by default** (Python)
- `2026-10-15T06:26:33+08:00` | **Prefer small focused commits** (Git)
- `2026-10-14T18:08:51+08:00` | **Write decisions down** (Leadership)
- `2026-10-14T13:08:17+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-10-14T08:18:20+08:00` | **Measure before tuning** (Performance)
- `2026-10-13T16:16:56+08:00` | **Fail fast on lint and tests** (CI/CD)
