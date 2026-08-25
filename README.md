# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2543**
- Today's entries: **15**
- Today's note: `notes/2026-08-25.md`

### Latest Entry

- Timestamp: `2026-08-25T16:07:32+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 128
- `Databases`: 128
- `Security`: 128
- `Testing`: 128
- `Accessibility`: 127

### Recent Timeline

- `2026-08-25T16:07:32+08:00` | **Design for idempotency** (APIs)
- `2026-08-25T15:28:47+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-25T14:33:18+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-25T13:55:27+08:00` | **Write one behavior per test** (Testing)
- `2026-08-25T13:24:08+08:00` | **Use virtual environments by default** (Python)
- `2026-08-25T12:51:22+08:00` | **Prefer small focused commits** (Git)
- `2026-08-25T12:08:48+08:00` | **Write decisions down** (Leadership)
- `2026-08-25T11:29:20+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-25T10:35:02+08:00` | **Measure before tuning** (Performance)
- `2026-08-25T09:17:03+08:00` | **Fail fast on lint and tests** (CI/CD)
