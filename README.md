# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2207**
- Today's entries: **9**
- Today's note: `notes/2026-08-08.md`

### Latest Entry

- Timestamp: `2026-08-08T21:27:48+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 111
- `Architecture`: 111
- `Backend`: 111
- `Databases`: 111
- `Frontend`: 111

### Recent Timeline

- `2026-08-08T21:27:48+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-08T19:28:39+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-08T18:22:35+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-08T17:52:01+08:00` | **Log with stable keys** (Observability)
- `2026-08-08T17:08:13+08:00` | **Design for idempotency** (APIs)
- `2026-08-08T13:09:31+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-08T10:59:35+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-08T07:46:12+08:00` | **Write one behavior per test** (Testing)
- `2026-08-08T07:03:03+08:00` | **Use virtual environments by default** (Python)
- `2026-08-07T22:54:36+08:00` | **Prefer small focused commits** (Git)
