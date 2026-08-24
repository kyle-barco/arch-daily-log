# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2533**
- Today's entries: **5**
- Today's note: `notes/2026-08-25.md`

### Latest Entry

- Timestamp: `2026-08-25T07:58:23+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 127
- `Architecture`: 127
- `Backend`: 127
- `Code Quality`: 127
- `Databases`: 127

### Recent Timeline

- `2026-08-25T07:58:23+08:00` | **Retry only safe operations** (Networking)
- `2026-08-25T07:43:20+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-25T07:15:25+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-25T06:50:49+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-25T06:17:06+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-24T22:24:13+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-24T21:34:56+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-24T20:31:27+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-24T19:50:53+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-24T19:19:30+08:00` | **Log with stable keys** (Observability)
