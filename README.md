# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2327**
- Today's entries: **9**
- Today's note: `notes/2026-08-16.md`

### Latest Entry

- Timestamp: `2026-08-16T17:38:35+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 117
- `Architecture`: 117
- `Backend`: 117
- `Databases`: 117
- `Frontend`: 117

### Recent Timeline

- `2026-08-16T17:38:35+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-16T17:04:19+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-16T16:44:47+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-16T13:51:54+08:00` | **Log with stable keys** (Observability)
- `2026-08-16T12:19:34+08:00` | **Design for idempotency** (APIs)
- `2026-08-16T09:01:14+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-16T07:41:42+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-16T06:59:25+08:00` | **Write one behavior per test** (Testing)
- `2026-08-16T06:15:09+08:00` | **Use virtual environments by default** (Python)
- `2026-08-15T22:45:32+08:00` | **Prefer small focused commits** (Git)
