# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2193**
- Today's entries: **7**
- Today's note: `notes/2026-08-07.md`

### Latest Entry

- Timestamp: `2026-08-07T18:08:49+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 110
- `Architecture`: 110
- `Backend`: 110
- `Code Quality`: 110
- `Databases`: 110

### Recent Timeline

- `2026-08-07T18:08:49+08:00` | **Retry only safe operations** (Networking)
- `2026-08-07T17:03:03+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-07T15:59:25+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-07T14:42:28+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-07T13:22:11+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-07T11:37:48+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-07T08:36:23+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-06T21:19:05+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-06T19:41:20+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-06T17:29:08+08:00` | **Log with stable keys** (Observability)
