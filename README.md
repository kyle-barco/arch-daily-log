# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **1947**
- Today's entries: **4**
- Today's note: `notes/2026-07-06.md`

### Latest Entry

- Timestamp: `2026-07-06T13:36:43+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 98
- `Architecture`: 98
- `Backend`: 98
- `Databases`: 98
- `Frontend`: 98

### Recent Timeline

- `2026-07-06T13:36:43+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-06T09:13:52+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-06T07:18:17+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-06T06:12:13+08:00` | **Log with stable keys** (Observability)
- `2026-07-05T22:53:22+08:00` | **Design for idempotency** (APIs)
- `2026-07-05T21:13:53+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-05T18:28:17+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-05T17:45:00+08:00` | **Write one behavior per test** (Testing)
- `2026-07-05T17:30:01+08:00` | **Use virtual environments by default** (Python)
- `2026-07-05T17:15:00+08:00` | **Prefer small focused commits** (Git)
