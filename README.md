# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2767**
- Today's entries: **2**
- Today's note: `notes/2026-10-22.md`

### Latest Entry

- Timestamp: `2026-10-22T12:43:04+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 139
- `Architecture`: 139
- `Backend`: 139
- `Databases`: 139
- `Frontend`: 139

### Recent Timeline

- `2026-10-22T12:43:04+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-10-22T08:12:19+08:00` | **Optimize first contentful view** (Frontend)
- `2026-10-21T21:13:02+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-10-21T15:33:08+08:00` | **Log with stable keys** (Observability)
- `2026-10-21T10:00:27+08:00` | **Design for idempotency** (APIs)
- `2026-10-21T07:33:00+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-10-20T20:27:20+08:00` | **Rotate credentials on schedule** (Security)
- `2026-10-20T14:55:25+08:00` | **Write one behavior per test** (Testing)
- `2026-10-20T09:50:41+08:00` | **Use virtual environments by default** (Python)
- `2026-10-20T07:13:53+08:00` | **Prefer small focused commits** (Git)
