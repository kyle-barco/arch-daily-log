# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2111**
- Today's entries: **4**
- Today's note: `notes/2026-07-28.md`

### Latest Entry

- Timestamp: `2026-07-28T12:25:34+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 106
- `Architecture`: 106
- `Backend`: 106
- `Code Quality`: 106
- `Databases`: 106

### Recent Timeline

- `2026-07-28T12:25:34+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-28T09:04:02+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-28T07:42:50+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-28T06:32:18+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-27T20:13:31+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-27T16:45:36+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-27T13:04:08+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-27T09:17:05+08:00` | **Log with stable keys** (Observability)
- `2026-07-27T07:39:38+08:00` | **Design for idempotency** (APIs)
- `2026-07-27T06:39:38+08:00` | **Add indexes for real query patterns** (Databases)
