# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2583**
- Today's entries: **4**
- Today's note: `notes/2026-08-31.md`

### Latest Entry

- Timestamp: `2026-08-31T21:46:54+08:00`
- Title: **Design for idempotency**
- Category: `APIs`
- Source: https://www.rfc-editor.org/rfc/rfc7231
- Summary: Idempotent create/update endpoints make retries safe under network failures and reduce accidental duplicate operations.

### Top Categories

- `APIs`: 130
- `Databases`: 130
- `Security`: 130
- `Testing`: 130
- `Accessibility`: 129

### Recent Timeline

- `2026-08-31T21:46:54+08:00` | **Design for idempotency** (APIs)
- `2026-08-31T14:11:49+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-31T08:41:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-31T06:15:46+08:00` | **Write one behavior per test** (Testing)
- `2026-08-30T20:50:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-30T07:28:31+08:00` | **Prefer small focused commits** (Git)
- `2026-08-28T21:36:54+08:00` | **Write decisions down** (Leadership)
- `2026-08-28T09:46:22+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-27T14:20:42+08:00` | **Measure before tuning** (Performance)
- `2026-08-27T07:53:28+08:00` | **Fail fast on lint and tests** (CI/CD)
