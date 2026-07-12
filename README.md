# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **1993**
- Today's entries: **1**
- Today's note: `notes/2026-07-13.md`

### Latest Entry

- Timestamp: `2026-07-13T06:29:40+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 100
- `Architecture`: 100
- `Backend`: 100
- `Code Quality`: 100
- `Databases`: 100

### Recent Timeline

- `2026-07-13T06:29:40+08:00` | **Retry only safe operations** (Networking)
- `2026-07-12T22:12:10+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-12T20:35:10+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-12T18:13:05+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-12T16:37:42+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-12T14:26:56+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-12T07:09:08+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-12T06:11:21+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-11T22:23:44+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-11T21:00:03+08:00` | **Log with stable keys** (Observability)
