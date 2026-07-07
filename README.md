# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **1953**
- Today's entries: **4**
- Today's note: `notes/2026-07-07.md`

### Latest Entry

- Timestamp: `2026-07-07T13:08:06+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 98
- `Architecture`: 98
- `Backend`: 98
- `Code Quality`: 98
- `Databases`: 98

### Recent Timeline

- `2026-07-07T13:08:06+08:00` | **Retry only safe operations** (Networking)
- `2026-07-07T09:14:11+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-07T07:22:01+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-07T06:02:31+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-06T21:29:01+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-06T17:41:22+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-06T13:36:43+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-06T09:13:52+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-06T07:18:17+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-06T06:12:13+08:00` | **Log with stable keys** (Observability)
