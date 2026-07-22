# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2070**
- Today's entries: **3**
- Today's note: `notes/2026-07-22.md`

### Latest Entry

- Timestamp: `2026-07-22T09:05:12+08:00`
- Title: **Use exponential backoff with jitter**
- Category: `Reliability`
- Source: https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/
- Summary: Backoff plus jitter avoids retry storms and improves recovery behavior when downstream systems are degraded.

### Top Categories

- `APIs`: 104
- `Architecture`: 104
- `Backend`: 104
- `Code Quality`: 104
- `Databases`: 104

### Recent Timeline

- `2026-07-22T09:05:12+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-22T07:39:31+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-22T06:37:08+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-21T22:57:48+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-21T20:53:52+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-21T19:28:24+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-21T17:38:06+08:00` | **Log with stable keys** (Observability)
- `2026-07-21T15:10:32+08:00` | **Design for idempotency** (APIs)
- `2026-07-21T12:29:30+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-21T09:06:20+08:00` | **Rotate credentials on schedule** (Security)
