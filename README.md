# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2650**
- Today's entries: **3**
- Today's note: `notes/2026-09-16.md`

### Latest Entry

- Timestamp: `2026-09-16T15:54:09+08:00`
- Title: **Use exponential backoff with jitter**
- Category: `Reliability`
- Source: https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/
- Summary: Backoff plus jitter avoids retry storms and improves recovery behavior when downstream systems are degraded.

### Top Categories

- `APIs`: 133
- `Architecture`: 133
- `Backend`: 133
- `Code Quality`: 133
- `Databases`: 133

### Recent Timeline

- `2026-09-16T15:54:09+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-09-16T10:37:07+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-09-16T07:52:02+08:00` | **Automate rollback paths** (DevOps)
- `2026-09-15T18:14:38+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-09-15T13:20:56+08:00` | **Optimize first contentful view** (Frontend)
- `2026-09-15T08:38:16+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-09-15T06:12:56+08:00` | **Log with stable keys** (Observability)
- `2026-09-14T21:21:08+08:00` | **Design for idempotency** (APIs)
- `2026-09-14T14:41:01+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-09-14T09:26:39+08:00` | **Rotate credentials on schedule** (Security)
