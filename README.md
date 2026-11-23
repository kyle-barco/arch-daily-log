# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2853**
- Today's entries: **1**
- Today's note: `notes/2026-11-24.md`

### Latest Entry

- Timestamp: `2026-11-24T06:00:51+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 143
- `Architecture`: 143
- `Backend`: 143
- `Code Quality`: 143
- `Databases`: 143

### Recent Timeline

- `2026-11-24T06:00:51+08:00` | **Retry only safe operations** (Networking)
- `2026-11-23T18:02:07+08:00` | **Batch similar tasks** (Productivity)
- `2026-11-23T09:52:25+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-11-21T21:57:00+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-11-21T07:57:52+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-11-20T17:43:29+08:00` | **Automate rollback paths** (DevOps)
- `2026-11-20T09:57:56+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-11-19T20:21:07+08:00` | **Optimize first contentful view** (Frontend)
- `2026-11-19T11:51:07+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-11-19T06:41:33+08:00` | **Log with stable keys** (Observability)
