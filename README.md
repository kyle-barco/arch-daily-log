# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2571**
- Today's entries: **19**
- Today's note: `notes/2026-08-26.md`

### Latest Entry

- Timestamp: `2026-08-26T20:01:37+08:00`
- Title: **Keep runbooks close to code**
- Category: `Documentation`
- Source: https://sre.google/workbook/
- Summary: Version-controlled operational runbooks age better than external docs and stay aligned with implementation changes.

### Top Categories

- `APIs`: 129
- `Architecture`: 129
- `Backend`: 129
- `Code Quality`: 129
- `Databases`: 129

### Recent Timeline

- `2026-08-26T20:01:37+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-26T19:33:24+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-26T18:59:25+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-26T18:26:04+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-26T17:54:52+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-26T17:08:44+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-26T16:22:21+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-26T15:30:18+08:00` | **Log with stable keys** (Observability)
- `2026-08-26T14:33:45+08:00` | **Design for idempotency** (APIs)
- `2026-08-26T13:47:50+08:00` | **Add indexes for real query patterns** (Databases)
