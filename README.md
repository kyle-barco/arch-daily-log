# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2273**
- Today's entries: **8**
- Today's note: `notes/2026-08-13.md`

### Latest Entry

- Timestamp: `2026-08-13T16:04:52+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 114
- `Architecture`: 114
- `Backend`: 114
- `Code Quality`: 114
- `Databases`: 114

### Recent Timeline

- `2026-08-13T16:04:52+08:00` | **Retry only safe operations** (Networking)
- `2026-08-13T14:42:34+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-13T13:06:04+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-13T11:14:11+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-13T08:43:16+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-13T07:42:23+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-13T06:58:36+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-13T06:09:13+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-12T22:44:05+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-12T21:43:37+08:00` | **Log with stable keys** (Observability)
