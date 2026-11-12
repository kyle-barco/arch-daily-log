# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2831**
- Today's entries: **1**
- Today's note: `notes/2026-11-13.md`

### Latest Entry

- Timestamp: `2026-11-13T07:33:14+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 142
- `Architecture`: 142
- `Backend`: 142
- `Code Quality`: 142
- `Databases`: 142

### Recent Timeline

- `2026-11-13T07:33:14+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-11-12T18:00:00+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-11-12T10:21:10+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-11-11T22:12:21+08:00` | **Automate rollback paths** (DevOps)
- `2026-11-11T14:06:03+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-11-11T08:01:17+08:00` | **Optimize first contentful view** (Frontend)
- `2026-11-10T19:46:01+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-11-10T11:31:20+08:00` | **Log with stable keys** (Observability)
- `2026-11-09T18:41:42+08:00` | **Design for idempotency** (APIs)
- `2026-11-09T10:50:24+08:00` | **Add indexes for real query patterns** (Databases)
