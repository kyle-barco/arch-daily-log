# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2690**
- Today's entries: **3**
- Today's note: `notes/2026-09-26.md`

### Latest Entry

- Timestamp: `2026-09-26T13:31:50+08:00`
- Title: **Use exponential backoff with jitter**
- Category: `Reliability`
- Source: https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/
- Summary: Backoff plus jitter avoids retry storms and improves recovery behavior when downstream systems are degraded.

### Top Categories

- `APIs`: 135
- `Architecture`: 135
- `Backend`: 135
- `Code Quality`: 135
- `Databases`: 135

### Recent Timeline

- `2026-09-26T13:31:50+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-09-26T08:43:49+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-09-26T06:17:01+08:00` | **Automate rollback paths** (DevOps)
- `2026-09-25T22:55:48+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-09-25T17:56:07+08:00` | **Optimize first contentful view** (Frontend)
- `2026-09-25T12:54:25+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-09-25T08:11:00+08:00` | **Log with stable keys** (Observability)
- `2026-09-24T22:26:15+08:00` | **Design for idempotency** (APIs)
- `2026-09-24T17:33:35+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-09-24T12:44:11+08:00` | **Rotate credentials on schedule** (Security)
