# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **1969**
- Today's entries: **5**
- Today's note: `notes/2026-07-09.md`

### Latest Entry

- Timestamp: `2026-07-09T16:54:19+08:00`
- Title: **Name intent, not mechanics**
- Category: `Code Quality`
- Source: https://martinfowler.com/books/clean-code.html
- Summary: Readable names should communicate business intent so maintainers understand why code exists before how it works.

### Top Categories

- `APIs`: 99
- `Architecture`: 99
- `Backend`: 99
- `Code Quality`: 99
- `Databases`: 99

### Recent Timeline

- `2026-07-09T16:54:19+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-09T13:31:01+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-09T09:18:26+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-09T07:45:03+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-09T06:42:18+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-08T21:44:56+08:00` | **Log with stable keys** (Observability)
- `2026-07-08T19:49:27+08:00` | **Design for idempotency** (APIs)
- `2026-07-08T17:59:37+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-08T15:44:23+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-08T13:17:44+08:00` | **Write one behavior per test** (Testing)
