# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2671**
- Today's entries: **1**
- Today's note: `notes/2026-09-22.md`

### Latest Entry

- Timestamp: `2026-09-22T06:40:51+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 134
- `Architecture`: 134
- `Backend`: 134
- `Code Quality`: 134
- `Databases`: 134

### Recent Timeline

- `2026-09-22T06:40:51+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-09-21T22:06:56+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-09-21T15:11:47+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-09-21T09:42:35+08:00` | **Automate rollback paths** (DevOps)
- `2026-09-21T07:44:24+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-09-20T22:12:41+08:00` | **Optimize first contentful view** (Frontend)
- `2026-09-20T13:34:13+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-09-19T17:05:38+08:00` | **Log with stable keys** (Observability)
- `2026-09-19T12:49:04+08:00` | **Design for idempotency** (APIs)
- `2026-09-19T08:17:48+08:00` | **Add indexes for real query patterns** (Databases)
