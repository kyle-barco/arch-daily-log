# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2391**
- Today's entries: **1**
- Today's note: `notes/2026-08-19.md`

### Latest Entry

- Timestamp: `2026-08-19T06:26:40+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 120
- `Architecture`: 120
- `Backend`: 120
- `Code Quality`: 120
- `Databases`: 120

### Recent Timeline

- `2026-08-19T06:26:40+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-18T22:50:10+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-18T22:03:35+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-18T21:23:10+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-18T20:28:09+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-18T19:47:56+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-18T19:17:24+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-18T18:53:26+08:00` | **Log with stable keys** (Observability)
- `2026-08-18T18:19:14+08:00` | **Design for idempotency** (APIs)
- `2026-08-18T17:46:54+08:00` | **Add indexes for real query patterns** (Databases)
