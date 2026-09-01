# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2587**
- Today's entries: **4**
- Today's note: `notes/2026-09-01.md`

### Latest Entry

- Timestamp: `2026-09-01T20:54:41+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 130
- `Architecture`: 130
- `Backend`: 130
- `Databases`: 130
- `Frontend`: 130

### Recent Timeline

- `2026-09-01T20:54:41+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-09-01T15:46:21+08:00` | **Optimize first contentful view** (Frontend)
- `2026-09-01T10:02:17+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-09-01T07:31:03+08:00` | **Log with stable keys** (Observability)
- `2026-08-31T21:46:54+08:00` | **Design for idempotency** (APIs)
- `2026-08-31T14:11:49+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-31T08:41:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-31T06:15:46+08:00` | **Write one behavior per test** (Testing)
- `2026-08-30T20:50:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-30T07:28:31+08:00` | **Prefer small focused commits** (Git)
