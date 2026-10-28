# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2791**
- Today's entries: **2**
- Today's note: `notes/2026-10-28.md`

### Latest Entry

- Timestamp: `2026-10-28T09:58:43+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 140
- `Architecture`: 140
- `Backend`: 140
- `Code Quality`: 140
- `Databases`: 140

### Recent Timeline

- `2026-10-28T09:58:43+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-10-28T06:56:03+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-10-27T21:49:07+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-10-27T15:53:51+08:00` | **Automate rollback paths** (DevOps)
- `2026-10-27T10:14:06+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-10-27T07:22:08+08:00` | **Optimize first contentful view** (Frontend)
- `2026-10-26T21:57:33+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-10-26T14:58:27+08:00` | **Log with stable keys** (Observability)
- `2026-10-26T09:41:51+08:00` | **Design for idempotency** (APIs)
- `2026-10-26T07:33:53+08:00` | **Add indexes for real query patterns** (Databases)
