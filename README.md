# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2291**
- Today's entries: **12**
- Today's note: `notes/2026-08-14.md`

### Latest Entry

- Timestamp: `2026-08-14T20:05:26+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 115
- `Architecture`: 115
- `Backend`: 115
- `Code Quality`: 115
- `Databases`: 115

### Recent Timeline

- `2026-08-14T20:05:26+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-14T19:25:53+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-14T18:30:38+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-14T17:18:47+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-14T16:07:51+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-14T14:50:58+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-14T13:18:28+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-14T11:30:18+08:00` | **Log with stable keys** (Observability)
- `2026-08-14T09:13:45+08:00` | **Design for idempotency** (APIs)
- `2026-08-14T07:45:58+08:00` | **Add indexes for real query patterns** (Databases)
