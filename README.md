# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2527**
- Today's entries: **22**
- Today's note: `notes/2026-08-24.md`

### Latest Entry

- Timestamp: `2026-08-24T21:34:56+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 127
- `Architecture`: 127
- `Backend`: 127
- `Databases`: 127
- `Frontend`: 127

### Recent Timeline

- `2026-08-24T21:34:56+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-24T20:31:27+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-24T19:50:53+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-24T19:19:30+08:00` | **Log with stable keys** (Observability)
- `2026-08-24T18:51:19+08:00` | **Design for idempotency** (APIs)
- `2026-08-24T18:02:57+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-24T17:12:00+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-24T16:26:19+08:00` | **Write one behavior per test** (Testing)
- `2026-08-24T15:43:13+08:00` | **Use virtual environments by default** (Python)
- `2026-08-24T14:39:15+08:00` | **Prefer small focused commits** (Git)
