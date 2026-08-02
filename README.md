# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2151**
- Today's entries: **5**
- Today's note: `notes/2026-08-02.md`

### Latest Entry

- Timestamp: `2026-08-02T17:29:58+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 108
- `Architecture`: 108
- `Backend`: 108
- `Code Quality`: 108
- `Databases`: 108

### Recent Timeline

- `2026-08-02T17:29:58+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-02T15:16:19+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-02T12:38:31+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-02T09:13:46+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-02T06:36:14+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-01T22:10:39+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-01T20:38:14+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-01T19:38:56+08:00` | **Log with stable keys** (Observability)
- `2026-08-01T18:21:34+08:00` | **Design for idempotency** (APIs)
- `2026-08-01T16:37:51+08:00` | **Add indexes for real query patterns** (Databases)
