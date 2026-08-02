# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2153**
- Today's entries: **7**
- Today's note: `notes/2026-08-02.md`

### Latest Entry

- Timestamp: `2026-08-02T20:13:43+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 108
- `Architecture`: 108
- `Backend`: 108
- `Code Quality`: 108
- `Databases`: 108

### Recent Timeline

- `2026-08-02T20:13:43+08:00` | **Retry only safe operations** (Networking)
- `2026-08-02T19:02:35+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-02T17:29:58+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-02T15:16:19+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-02T12:38:31+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-02T09:13:46+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-02T06:36:14+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-01T22:10:39+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-01T20:38:14+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-01T19:38:56+08:00` | **Log with stable keys** (Observability)
