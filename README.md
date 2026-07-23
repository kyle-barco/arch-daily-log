# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2083**
- Today's entries: **8**
- Today's note: `notes/2026-07-23.md`

### Latest Entry

- Timestamp: `2026-07-23T22:28:44+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 105
- `Databases`: 105
- `Security`: 105
- `Testing`: 105
- `Accessibility`: 104

### Recent Timeline

- `2026-07-23T22:28:44+08:00` | **Design for idempotency** (APIs)
- `2026-07-23T20:10:26+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-23T18:28:35+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-23T16:00:03+08:00` | **Write one behavior per test** (Testing)
- `2026-07-23T13:33:40+08:00` | **Use virtual environments by default** (Python)
- `2026-07-23T10:10:25+08:00` | **Prefer small focused commits** (Git)
- `2026-07-23T07:55:48+08:00` | **Write decisions down** (Leadership)
- `2026-07-23T06:54:41+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-22T21:10:16+08:00` | **Measure before tuning** (Performance)
- `2026-07-22T19:42:58+08:00` | **Fail fast on lint and tests** (CI/CD)
