# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2467**
- Today's entries: **2**
- Today's note: `notes/2026-08-22.md`

### Latest Entry

- Timestamp: `2026-08-22T06:43:01+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 124
- `Architecture`: 124
- `Backend`: 124
- `Databases`: 124
- `Frontend`: 124

### Recent Timeline

- `2026-08-22T06:43:01+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-22T06:14:52+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-21T22:17:32+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-21T21:38:38+08:00` | **Log with stable keys** (Observability)
- `2026-08-21T20:55:02+08:00` | **Design for idempotency** (APIs)
- `2026-08-21T19:59:37+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-21T19:38:32+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-21T19:03:46+08:00` | **Write one behavior per test** (Testing)
- `2026-08-21T18:44:46+08:00` | **Use virtual environments by default** (Python)
- `2026-08-21T18:00:49+08:00` | **Prefer small focused commits** (Git)
