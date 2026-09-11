# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2630**
- Today's entries: **3**
- Today's note: `notes/2026-09-11.md`

### Latest Entry

- Timestamp: `2026-09-11T13:14:33+08:00`
- Title: **Use exponential backoff with jitter**
- Category: `Reliability`
- Source: https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/
- Summary: Backoff plus jitter avoids retry storms and improves recovery behavior when downstream systems are degraded.

### Top Categories

- `APIs`: 132
- `Architecture`: 132
- `Backend`: 132
- `Code Quality`: 132
- `Databases`: 132

### Recent Timeline

- `2026-09-11T13:14:33+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-09-11T08:32:26+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-09-11T06:33:19+08:00` | **Automate rollback paths** (DevOps)
- `2026-09-10T21:58:38+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-09-10T17:54:39+08:00` | **Optimize first contentful view** (Frontend)
- `2026-09-10T13:19:47+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-09-10T08:44:15+08:00` | **Log with stable keys** (Observability)
- `2026-09-10T06:45:18+08:00` | **Design for idempotency** (APIs)
- `2026-09-09T22:33:16+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-09-09T18:06:33+08:00` | **Rotate credentials on schedule** (Security)
