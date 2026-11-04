# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2813**
- Today's entries: **1**
- Today's note: `notes/2026-11-05.md`

### Latest Entry

- Timestamp: `2026-11-05T06:12:11+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 141
- `Architecture`: 141
- `Backend`: 141
- `Code Quality`: 141
- `Databases`: 141

### Recent Timeline

- `2026-11-05T06:12:11+08:00` | **Retry only safe operations** (Networking)
- `2026-11-04T16:44:45+08:00` | **Batch similar tasks** (Productivity)
- `2026-11-04T09:58:48+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-11-03T16:34:56+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-11-03T09:42:49+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-11-02T17:01:53+08:00` | **Automate rollback paths** (DevOps)
- `2026-11-02T09:59:11+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-11-02T06:46:11+08:00` | **Optimize first contentful view** (Frontend)
- `2026-11-01T22:25:50+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-11-01T15:29:15+08:00` | **Log with stable keys** (Observability)
