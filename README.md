# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2510**
- Today's entries: **5**
- Today's note: `notes/2026-08-24.md`

### Latest Entry

- Timestamp: `2026-08-24T07:42:39+08:00`
- Title: **Use exponential backoff with jitter**
- Category: `Reliability`
- Source: https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/
- Summary: Backoff plus jitter avoids retry storms and improves recovery behavior when downstream systems are degraded.

### Top Categories

- `APIs`: 126
- `Architecture`: 126
- `Backend`: 126
- `Code Quality`: 126
- `Databases`: 126

### Recent Timeline

- `2026-08-24T07:42:39+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-24T07:15:50+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-24T06:56:26+08:00` | **Automate rollback paths** (DevOps)
- `2026-08-24T06:38:11+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-24T06:13:52+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-23T22:28:39+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-23T22:00:06+08:00` | **Log with stable keys** (Observability)
- `2026-08-23T21:43:46+08:00` | **Design for idempotency** (APIs)
- `2026-08-23T20:25:33+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-23T19:34:40+08:00` | **Rotate credentials on schedule** (Security)
