# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2009**
- Today's entries: **1**
- Today's note: `notes/2026-07-15.md`

### Latest Entry

- Timestamp: `2026-07-15T06:38:17+08:00`
- Title: **Name intent, not mechanics**
- Category: `Code Quality`
- Source: https://martinfowler.com/books/clean-code.html
- Summary: Readable names should communicate business intent so maintainers understand why code exists before how it works.

### Top Categories

- `APIs`: 101
- `Architecture`: 101
- `Backend`: 101
- `Code Quality`: 101
- `Databases`: 101

### Recent Timeline

- `2026-07-15T06:38:17+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-14T22:10:28+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-14T20:00:59+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-14T18:38:56+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-14T16:53:50+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-14T14:33:00+08:00` | **Log with stable keys** (Observability)
- `2026-07-14T12:15:58+08:00` | **Design for idempotency** (APIs)
- `2026-07-14T09:02:48+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-14T07:33:40+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-14T06:36:05+08:00` | **Write one behavior per test** (Testing)
