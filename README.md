# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2567**
- Today's entries: **15**
- Today's note: `notes/2026-08-26.md`

### Latest Entry

- Timestamp: `2026-08-26T17:54:52+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 129
- `Architecture`: 129
- `Backend`: 129
- `Databases`: 129
- `Frontend`: 129

### Recent Timeline

- `2026-08-26T17:54:52+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-08-26T17:08:44+08:00` | **Optimize first contentful view** (Frontend)
- `2026-08-26T16:22:21+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-26T15:30:18+08:00` | **Log with stable keys** (Observability)
- `2026-08-26T14:33:45+08:00` | **Design for idempotency** (APIs)
- `2026-08-26T13:47:50+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-26T13:02:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-26T12:22:08+08:00` | **Write one behavior per test** (Testing)
- `2026-08-26T11:30:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-26T10:20:19+08:00` | **Prefer small focused commits** (Git)
