# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2251**
- Today's entries: **16**
- Today's note: `notes/2026-08-11.md`

### Latest Entry

- Timestamp: `2026-08-11T22:42:04+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 113
- `Architecture`: 113
- `Backend`: 113
- `Code Quality`: 113
- `Databases`: 113

### Recent Timeline

- `2026-08-11T22:42:04+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-11T21:39:21+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-11T20:08:47+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-11T19:28:05+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-11T18:34:31+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-11T17:43:21+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-11T16:44:42+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-11T15:52:05+08:00` | **Log with stable keys** (Observability)
- `2026-08-11T14:34:32+08:00` | **Design for idempotency** (APIs)
- `2026-08-11T13:40:29+08:00` | **Add indexes for real query patterns** (Databases)
