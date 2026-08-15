# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2313**
- Today's entries: **20**
- Today's note: `notes/2026-08-15.md`

### Latest Entry

- Timestamp: `2026-08-15T19:42:10+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 116
- `Architecture`: 116
- `Backend`: 116
- `Code Quality`: 116
- `Databases`: 116

### Recent Timeline

- `2026-08-15T19:42:10+08:00` | **Retry only safe operations** (Networking)
- `2026-08-15T18:56:51+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-15T18:40:24+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-15T18:14:15+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-15T17:47:30+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-15T17:18:03+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-15T16:51:56+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-15T16:17:37+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-15T15:50:08+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-15T13:58:56+08:00` | **Log with stable keys** (Observability)
