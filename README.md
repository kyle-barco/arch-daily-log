# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2387**
- Today's entries: **23**
- Today's note: `notes/2026-08-18.md`

### Latest Entry

- Timestamp: `2026-08-18T20:28:09+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 120
- `Architecture`: 120
- `Backend`: 120
- `Databases`: 120
- `Frontend`: 120

### Recent Timeline

- `2026-08-18T20:28:09+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-18T19:47:56+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-18T19:17:24+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-18T18:53:26+08:00` | **Log with stable keys** (Observability)
- `2026-08-18T18:19:14+08:00` | **Design for idempotency** (APIs)
- `2026-08-18T17:46:54+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-18T17:01:42+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-18T16:25:59+08:00` | **Write one behavior per test** (Testing)
- `2026-08-18T15:51:13+08:00` | **Use virtual environments by default** (Python)
- `2026-08-18T15:01:19+08:00` | **Prefer small focused commits** (Git)
