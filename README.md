# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2287**
- Today's entries: **8**
- Today's note: `notes/2026-08-14.md`

### Latest Entry

- Timestamp: `2026-08-14T16:07:51+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 115
- `Architecture`: 115
- `Backend`: 115
- `Databases`: 115
- `Frontend`: 115

### Recent Timeline

- `2026-08-14T16:07:51+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-14T14:50:58+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-14T13:18:28+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-14T11:30:18+08:00` | **Log with stable keys** (Observability)
- `2026-08-14T09:13:45+08:00` | **Design for idempotency** (APIs)
- `2026-08-14T07:45:58+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-14T06:59:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-14T06:01:56+08:00` | **Write one behavior per test** (Testing)
- `2026-08-13T22:44:36+08:00` | **Use virtual environments by default** (Python)
- `2026-08-13T21:43:28+08:00` | **Prefer small focused commits** (Git)
