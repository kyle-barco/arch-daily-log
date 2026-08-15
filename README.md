# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2311**
- Today's entries: **18**
- Today's note: `notes/2026-08-15.md`

### Latest Entry

- Timestamp: `2026-08-15T18:40:24+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 116
- `Architecture`: 116
- `Backend`: 116
- `Code Quality`: 116
- `Databases`: 116

### Recent Timeline

- `2026-08-15T18:40:24+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-15T18:14:15+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-15T17:47:30+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-15T17:18:03+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-15T16:51:56+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-15T16:17:37+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-15T15:50:08+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-15T13:58:56+08:00` | **Log with stable keys** (Observability)
- `2026-08-15T12:44:47+08:00` | **Design for idempotency** (APIs)
- `2026-08-15T12:01:29+08:00` | **Add indexes for real query patterns** (Databases)
