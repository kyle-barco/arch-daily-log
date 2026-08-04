# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2171**
- Today's entries: **1**
- Today's note: `notes/2026-08-05.md`

### Latest Entry

- Timestamp: `2026-08-05T06:54:25+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 109
- `Architecture`: 109
- `Backend`: 109
- `Code Quality`: 109
- `Databases`: 109

### Recent Timeline

- `2026-08-05T06:54:25+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-04T21:22:17+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-04T19:38:37+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-04T17:27:36+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-04T14:40:17+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-04T12:12:36+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-04T08:57:34+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-04T07:17:48+08:00` | **Log with stable keys** (Observability)
- `2026-08-04T06:05:47+08:00` | **Design for idempotency** (APIs)
- `2026-08-03T21:30:01+08:00` | **Add indexes for real query patterns** (Databases)
