# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2787**
- Today's entries: **2**
- Today's note: `notes/2026-10-27.md`

### Latest Entry

- Timestamp: `2026-10-27T10:14:06+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 140
- `Architecture`: 140
- `Backend`: 140
- `Databases`: 140
- `Frontend`: 140

### Recent Timeline

- `2026-10-27T10:14:06+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-10-27T07:22:08+08:00` | **Optimize first contentful view** (Frontend)
- `2026-10-26T21:57:33+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-10-26T14:58:27+08:00` | **Log with stable keys** (Observability)
- `2026-10-26T09:41:51+08:00` | **Design for idempotency** (APIs)
- `2026-10-26T07:33:53+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-10-25T14:50:36+08:00` | **Rotate credentials on schedule** (Security)
- `2026-10-25T09:39:20+08:00` | **Write one behavior per test** (Testing)
- `2026-10-25T07:42:05+08:00` | **Use virtual environments by default** (Python)
- `2026-10-24T21:34:36+08:00` | **Prefer small focused commits** (Git)
