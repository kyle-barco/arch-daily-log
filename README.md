# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2051**
- Today's entries: **1**
- Today's note: `notes/2026-07-20.md`

### Latest Entry

- Timestamp: `2026-07-20T06:09:00+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 103
- `Architecture`: 103
- `Backend`: 103
- `Code Quality`: 103
- `Databases`: 103

### Recent Timeline

- `2026-07-20T06:09:00+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-19T20:34:40+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-19T18:14:34+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-19T16:41:26+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-19T14:24:17+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-19T11:50:32+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-19T08:07:27+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-19T07:07:54+08:00` | **Log with stable keys** (Observability)
- `2026-07-19T06:05:22+08:00` | **Design for idempotency** (APIs)
- `2026-07-18T20:36:59+08:00` | **Add indexes for real query patterns** (Databases)
