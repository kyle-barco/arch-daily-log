# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2487**
- Today's entries: **3**
- Today's note: `notes/2026-08-23.md`

### Latest Entry

- Timestamp: `2026-08-23T07:42:31+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 125
- `Architecture`: 125
- `Backend`: 125
- `Databases`: 125
- `Frontend`: 125

### Recent Timeline

- `2026-08-23T07:42:31+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-23T06:40:27+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-23T06:15:06+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-22T22:56:40+08:00` | **Log with stable keys** (Observability)
- `2026-08-22T22:37:43+08:00` | **Design for idempotency** (APIs)
- `2026-08-22T21:17:31+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-22T20:34:55+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-22T19:42:43+08:00` | **Write one behavior per test** (Testing)
- `2026-08-22T18:41:11+08:00` | **Use virtual environments by default** (Python)
- `2026-08-22T18:14:30+08:00` | **Prefer small focused commits** (Git)
