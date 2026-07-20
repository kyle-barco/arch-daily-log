# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2053**
- Today's entries: **3**
- Today's note: `notes/2026-07-20.md`

### Latest Entry

- Timestamp: `2026-07-20T08:09:45+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 103
- `Architecture`: 103
- `Backend`: 103
- `Code Quality`: 103
- `Databases`: 103

### Recent Timeline

- `2026-07-20T08:09:45+08:00` | **Retry only safe operations** (Networking)
- `2026-07-20T07:08:29+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-20T06:09:00+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-19T20:34:40+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-19T18:14:34+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-19T16:41:26+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-19T14:24:17+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-19T11:50:32+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-19T08:07:27+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-19T07:07:54+08:00` | **Log with stable keys** (Observability)
