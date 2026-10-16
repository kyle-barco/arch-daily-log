# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2747**
- Today's entries: **1**
- Today's note: `notes/2026-10-17.md`

### Latest Entry

- Timestamp: `2026-10-17T06:48:38+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 138
- `Architecture`: 138
- `Backend`: 138
- `Databases`: 138
- `Frontend`: 138

### Recent Timeline

- `2026-10-17T06:48:38+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-10-16T21:31:16+08:00` | **Optimize first contentful view** (Frontend)
- `2026-10-16T16:30:26+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-10-16T11:43:16+08:00` | **Log with stable keys** (Observability)
- `2026-10-16T07:59:05+08:00` | **Design for idempotency** (APIs)
- `2026-10-15T22:36:11+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-10-15T17:55:52+08:00` | **Rotate credentials on schedule** (Security)
- `2026-10-15T13:13:49+08:00` | **Write one behavior per test** (Testing)
- `2026-10-15T08:42:24+08:00` | **Use virtual environments by default** (Python)
- `2026-10-15T06:26:33+08:00` | **Prefer small focused commits** (Git)
