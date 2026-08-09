# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2213**
- Today's entries: **6**
- Today's note: `notes/2026-08-09.md`

### Latest Entry

- Timestamp: `2026-08-09T11:06:31+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 111
- `Architecture`: 111
- `Backend`: 111
- `Code Quality`: 111
- `Databases`: 111

### Recent Timeline

- `2026-08-09T11:06:31+08:00` | **Retry only safe operations** (Networking)
- `2026-08-09T09:04:53+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-09T07:52:17+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-09T07:20:02+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-09T06:54:41+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-09T06:19:29+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-08T21:27:48+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-08T19:28:39+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-08T18:22:35+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-08T17:52:01+08:00` | **Log with stable keys** (Observability)
