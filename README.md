# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2627**
- Today's entries: **5**
- Today's note: `notes/2026-09-10.md`

### Latest Entry

- Timestamp: `2026-09-10T21:58:38+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 132
- `Architecture`: 132
- `Backend`: 132
- `Databases`: 132
- `Frontend`: 132

### Recent Timeline

- `2026-09-10T21:58:38+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-09-10T17:54:39+08:00` | **Optimize first contentful view** (Frontend)
- `2026-09-10T13:19:47+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-09-10T08:44:15+08:00` | **Log with stable keys** (Observability)
- `2026-09-10T06:45:18+08:00` | **Design for idempotency** (APIs)
- `2026-09-09T22:33:16+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-09-09T18:06:33+08:00` | **Rotate credentials on schedule** (Security)
- `2026-09-09T13:36:48+08:00` | **Write one behavior per test** (Testing)
- `2026-09-09T08:54:51+08:00` | **Use virtual environments by default** (Python)
- `2026-09-09T06:49:26+08:00` | **Prefer small focused commits** (Git)
