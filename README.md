# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2330**
- Today's entries: **12**
- Today's note: `notes/2026-08-16.md`

### Latest Entry

- Timestamp: `2026-08-16T18:46:22+08:00`
- Title: **Use exponential backoff with jitter**
- Category: `Reliability`
- Source: https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/
- Summary: Backoff plus jitter avoids retry storms and improves recovery behavior when downstream systems are degraded.

### Top Categories

- `APIs`: 117
- `Architecture`: 117
- `Backend`: 117
- `Code Quality`: 117
- `Databases`: 117

### Recent Timeline

- `2026-08-16T18:46:22+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-16T18:20:39+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-16T17:57:26+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-16T17:38:35+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-16T17:04:19+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-16T16:44:47+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-16T13:51:54+08:00` | **Log with stable keys** (Observability)
- `2026-08-16T12:19:34+08:00` | **Design for idempotency** (APIs)
- `2026-08-16T09:01:14+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-16T07:41:42+08:00` | **Rotate credentials on schedule** (Security)
