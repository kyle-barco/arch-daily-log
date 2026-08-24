# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2513**
- Today's entries: **8**
- Today's note: `notes/2026-08-24.md`

### Latest Entry

- Timestamp: `2026-08-24T10:36:13+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 126
- `Architecture`: 126
- `Backend`: 126
- `Code Quality`: 126
- `Databases`: 126

### Recent Timeline

- `2026-08-24T10:36:13+08:00` | **Retry only safe operations** (Networking)
- `2026-08-24T09:05:35+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-24T07:56:56+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-24T07:42:39+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-24T07:15:50+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-24T06:56:26+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-24T06:38:11+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-24T06:13:52+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-23T22:28:39+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-23T22:00:06+08:00` | **Log with stable keys** (Observability)
