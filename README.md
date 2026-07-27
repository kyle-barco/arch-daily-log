# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2107**
- Today's entries: **6**
- Today's note: `notes/2026-07-27.md`

### Latest Entry

- Timestamp: `2026-07-27T20:13:31+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 106
- `Architecture`: 106
- `Backend`: 106
- `Databases`: 106
- `Frontend`: 106

### Recent Timeline

- `2026-07-27T20:13:31+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-27T16:45:36+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-27T13:04:08+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-27T09:17:05+08:00` | **Log with stable keys** (Observability)
- `2026-07-27T07:39:38+08:00` | **Design for idempotency** (APIs)
- `2026-07-27T06:39:38+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-26T20:14:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-26T12:42:50+08:00` | **Write one behavior per test** (Testing)
- `2026-07-26T09:14:00+08:00` | **Use virtual environments by default** (Python)
- `2026-07-25T19:40:28+08:00` | **Prefer small focused commits** (Git)
