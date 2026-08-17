# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2347**
- Today's entries: **9**
- Today's note: `notes/2026-08-17.md`

### Latest Entry

- Timestamp: `2026-08-17T11:25:35+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 118
- `Architecture`: 118
- `Backend`: 118
- `Databases`: 118
- `Frontend`: 118

### Recent Timeline

- `2026-08-17T11:25:35+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-17T10:15:26+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-17T08:46:45+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-17T07:54:29+08:00` | **Log with stable keys** (Observability)
- `2026-08-17T07:34:00+08:00` | **Design for idempotency** (APIs)
- `2026-08-17T07:13:58+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-17T06:55:53+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-17T06:36:37+08:00` | **Write one behavior per test** (Testing)
- `2026-08-17T06:12:58+08:00` | **Use virtual environments by default** (Python)
- `2026-08-16T22:46:40+08:00` | **Prefer small focused commits** (Git)
