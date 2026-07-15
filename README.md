# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2011**
- Today's entries: **3**
- Today's note: `notes/2026-07-15.md`

### Latest Entry

- Timestamp: `2026-07-15T08:58:53+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 101
- `Architecture`: 101
- `Backend`: 101
- `Code Quality`: 101
- `Databases`: 101

### Recent Timeline

- `2026-07-15T08:58:53+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-15T07:31:46+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-15T06:38:17+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-14T22:10:28+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-14T20:00:59+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-14T18:38:56+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-14T16:53:50+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-14T14:33:00+08:00` | **Log with stable keys** (Observability)
- `2026-07-14T12:15:58+08:00` | **Design for idempotency** (APIs)
- `2026-07-14T09:02:48+08:00` | **Add indexes for real query patterns** (Databases)
