# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2131**
- Today's entries: **1**
- Today's note: `notes/2026-07-31.md`

### Latest Entry

- Timestamp: `2026-07-31T06:08:07+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 107
- `Architecture`: 107
- `Backend`: 107
- `Code Quality`: 107
- `Databases`: 107

### Recent Timeline

- `2026-07-31T06:08:07+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-30T20:47:37+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-30T18:59:36+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-30T16:46:32+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-30T14:04:01+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-30T11:24:40+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-30T08:08:34+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-30T07:01:16+08:00` | **Log with stable keys** (Observability)
- `2026-07-29T22:38:24+08:00` | **Design for idempotency** (APIs)
- `2026-07-29T20:17:54+08:00` | **Add indexes for real query patterns** (Databases)
