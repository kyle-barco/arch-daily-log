# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2410**
- Today's entries: **20**
- Today's note: `notes/2026-08-19.md`

### Latest Entry

- Timestamp: `2026-08-19T18:52:56+08:00`
- Title: **Use exponential backoff with jitter**
- Category: `Reliability`
- Source: https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/
- Summary: Backoff plus jitter avoids retry storms and improves recovery behavior when downstream systems are degraded.

### Top Categories

- `APIs`: 121
- `Architecture`: 121
- `Backend`: 121
- `Code Quality`: 121
- `Databases`: 121

### Recent Timeline

- `2026-08-19T18:52:56+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-19T18:22:12+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-19T17:56:11+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-19T17:16:03+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-19T16:43:08+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-19T15:59:59+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-19T15:21:13+08:00` | **Log with stable keys** (Observability)
- `2026-08-19T14:29:37+08:00` | **Design for idempotency** (APIs)
- `2026-08-19T13:53:07+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-19T13:21:44+08:00` | **Rotate credentials on schedule** (Security)
