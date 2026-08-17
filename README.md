# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2351**
- Today's entries: **13**
- Today's note: `notes/2026-08-17.md`

### Latest Entry

- Timestamp: `2026-08-17T14:00:15+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 118
- `Architecture`: 118
- `Backend`: 118
- `Code Quality`: 118
- `Databases`: 118

### Recent Timeline

- `2026-08-17T14:00:15+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-17T13:28:41+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-17T12:55:28+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-17T12:09:37+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-17T11:25:35+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-17T10:15:26+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-17T08:46:45+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-17T07:54:29+08:00` | **Log with stable keys** (Observability)
- `2026-08-17T07:34:00+08:00` | **Design for idempotency** (APIs)
- `2026-08-17T07:13:58+08:00` | **Add indexes for real query patterns** (Databases)
