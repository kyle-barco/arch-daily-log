# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2489**
- Today's entries: **5**
- Today's note: `notes/2026-08-23.md`

### Latest Entry

- Timestamp: `2026-08-23T09:08:52+08:00`
- Title: **Name intent, not mechanics**
- Category: `Code Quality`
- Source: https://martinfowler.com/books/clean-code.html
- Summary: Readable names should communicate business intent so maintainers understand why code exists before how it works.

### Top Categories

- `APIs`: 125
- `Architecture`: 125
- `Backend`: 125
- `Code Quality`: 125
- `Databases`: 125

### Recent Timeline

- `2026-08-23T09:08:52+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-23T07:57:00+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-23T07:42:31+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-23T06:40:27+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-23T06:15:06+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-22T22:56:40+08:00` | **Log with stable keys** (Observability)
- `2026-08-22T22:37:43+08:00` | **Design for idempotency** (APIs)
- `2026-08-22T21:17:31+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-22T20:34:55+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-22T19:42:43+08:00` | **Write one behavior per test** (Testing)
