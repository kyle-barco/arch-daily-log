# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2247**
- Today's entries: **12**
- Today's note: `notes/2026-08-11.md`

### Latest Entry

- Timestamp: `2026-08-11T18:34:31+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 113
- `Architecture`: 113
- `Backend`: 113
- `Databases`: 113
- `Frontend`: 113

### Recent Timeline

- `2026-08-11T18:34:31+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-11T17:43:21+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-11T16:44:42+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-11T15:52:05+08:00` | **Log with stable keys** (Observability)
- `2026-08-11T14:34:32+08:00` | **Design for idempotency** (APIs)
- `2026-08-11T13:40:29+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-11T12:37:14+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-11T11:10:08+08:00` | **Write one behavior per test** (Testing)
- `2026-08-11T09:05:54+08:00` | **Use virtual environments by default** (Python)
- `2026-08-11T07:49:04+08:00` | **Prefer small focused commits** (Git)
