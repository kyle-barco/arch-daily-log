# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2090**
- Today's entries: **7**
- Today's note: `notes/2026-07-24.md`

### Latest Entry

- Timestamp: `2026-07-24T19:10:01+08:00`
- Title: **Use exponential backoff with jitter**
- Category: `Reliability`
- Source: https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/
- Summary: Backoff plus jitter avoids retry storms and improves recovery behavior when downstream systems are degraded.

### Top Categories

- `APIs`: 105
- `Architecture`: 105
- `Backend`: 105
- `Code Quality`: 105
- `Databases`: 105

### Recent Timeline

- `2026-07-24T19:10:01+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-24T17:08:37+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-24T14:38:02+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-24T12:10:31+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-24T08:56:00+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-24T07:28:55+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-24T06:29:23+08:00` | **Log with stable keys** (Observability)
- `2026-07-23T22:28:44+08:00` | **Design for idempotency** (APIs)
- `2026-07-23T20:10:26+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-23T18:28:35+08:00` | **Rotate credentials on schedule** (Security)
