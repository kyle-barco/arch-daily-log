# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2723**
- Today's entries: **3**
- Today's note: `notes/2026-10-08.md`

### Latest Entry

- Timestamp: `2026-10-08T17:46:10+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 137
- `Databases`: 137
- `Security`: 137
- `Testing`: 137
- `Accessibility`: 136

### Recent Timeline

- `2026-10-08T17:46:10+08:00` | **Design for idempotency** (APIs)
- `2026-10-08T10:55:13+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-10-08T07:39:45+08:00` | **Rotate credentials on schedule** (Security)
- `2026-10-07T21:27:49+08:00` | **Write one behavior per test** (Testing)
- `2026-10-07T14:14:40+08:00` | **Use virtual environments by default** (Python)
- `2026-10-07T08:21:54+08:00` | **Prefer small focused commits** (Git)
- `2026-10-06T17:24:25+08:00` | **Write decisions down** (Leadership)
- `2026-10-06T10:30:16+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-10-06T06:40:12+08:00` | **Measure before tuning** (Performance)
- `2026-10-05T15:19:13+08:00` | **Fail fast on lint and tests** (CI/CD)
