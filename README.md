# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2713**
- Today's entries: **2**
- Today's note: `notes/2026-10-05.md`

### Latest Entry

- Timestamp: `2026-10-05T09:16:18+08:00`
- Title: **Retry only safe operations**
- Category: `Networking`
- Source: https://www.rfc-editor.org/rfc/rfc9110
- Summary: Not all requests should be retried blindly; non-idempotent calls need safeguards or idempotency keys.

### Top Categories

- `APIs`: 136
- `Architecture`: 136
- `Backend`: 136
- `Code Quality`: 136
- `Databases`: 136

### Recent Timeline

- `2026-10-05T09:16:18+08:00` | **Retry only safe operations** (Networking)
- `2026-10-05T06:38:10+08:00` | **Batch similar tasks** (Productivity)
- `2026-10-04T20:16:49+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-10-03T14:29:19+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-10-03T09:10:26+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-10-03T06:10:23+08:00` | **Automate rollback paths** (DevOps)
- `2026-10-02T20:56:12+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-10-02T14:15:48+08:00` | **Optimize first contentful view** (Frontend)
- `2026-10-02T08:44:50+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-10-01T17:11:22+08:00` | **Log with stable keys** (Observability)
