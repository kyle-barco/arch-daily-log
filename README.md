# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2067**
- Today's entries: **9**
- Today's note: `notes/2026-07-21.md`

### Latest Entry

- Timestamp: `2026-07-21T22:57:48+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 104
- `Architecture`: 104
- `Backend`: 104
- `Databases`: 104
- `Frontend`: 104

### Recent Timeline

- `2026-07-21T22:57:48+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-21T20:53:52+08:00` | **Optimize first contentful view** (Frontend)
- `2026-07-21T19:28:24+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-07-21T17:38:06+08:00` | **Log with stable keys** (Observability)
- `2026-07-21T15:10:32+08:00` | **Design for idempotency** (APIs)
- `2026-07-21T12:29:30+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-21T09:06:20+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-21T07:38:04+08:00` | **Write one behavior per test** (Testing)
- `2026-07-21T06:31:27+08:00` | **Use virtual environments by default** (Python)
- `2026-07-20T22:39:43+08:00` | **Prefer small focused commits** (Git)
