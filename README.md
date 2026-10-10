# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2727**
- Today's entries: **1**
- Today's note: `notes/2026-10-10.md`

### Latest Entry

- Timestamp: `2026-10-10T08:08:49+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 137
- `Architecture`: 137
- `Backend`: 137
- `Databases`: 137
- `Frontend`: 137

### Recent Timeline

- `2026-10-10T08:08:49+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-10-09T16:58:12+08:00` | **Optimize first contentful view** (Frontend)
- `2026-10-09T10:06:32+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-10-09T06:02:52+08:00` | **Log with stable keys** (Observability)
- `2026-10-08T17:46:10+08:00` | **Design for idempotency** (APIs)
- `2026-10-08T10:55:13+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-10-08T07:39:45+08:00` | **Rotate credentials on schedule** (Security)
- `2026-10-07T21:27:49+08:00` | **Write one behavior per test** (Testing)
- `2026-10-07T14:14:40+08:00` | **Use virtual environments by default** (Python)
- `2026-10-07T08:21:54+08:00` | **Prefer small focused commits** (Git)
