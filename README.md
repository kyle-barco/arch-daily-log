# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2231**
- Today's entries: **10**
- Today's note: `notes/2026-08-10.md`

### Latest Entry

- Timestamp: `2026-08-10T17:47:23+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 112
- `Architecture`: 112
- `Backend`: 112
- `Code Quality`: 112
- `Databases`: 112

### Recent Timeline

- `2026-08-10T17:47:23+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-10T16:12:03+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-10T14:21:17+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-10T13:02:48+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-10T11:22:48+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-10T09:18:40+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-10T07:56:09+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-10T07:22:44+08:00` | **Log with stable keys** (Observability)
- `2026-08-10T06:47:57+08:00` | **Design for idempotency** (APIs)
- `2026-08-10T06:02:39+08:00` | **Add indexes for real query patterns** (Databases)
