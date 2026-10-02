# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2707**
- Today's entries: **3**
- Today's note: `notes/2026-10-02.md`

### Latest Entry

- Timestamp: `2026-10-02T20:56:12+08:00`
- Title: **Set realistic timeouts everywhere**
- Category: `Backend`
- Source: https://sre.google/sre-book/addressing-cascading-failures/
- Summary: Explicit timeouts on outbound calls prevent thread exhaustion and keep cascading failures contained.

### Top Categories

- `APIs`: 136
- `Architecture`: 136
- `Backend`: 136
- `Databases`: 136
- `Frontend`: 136

### Recent Timeline

- `2026-10-02T20:56:12+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-10-02T14:15:48+08:00` | **Optimize first contentful view** (Frontend)
- `2026-10-02T08:44:50+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-10-01T17:11:22+08:00` | **Log with stable keys** (Observability)
- `2026-10-01T10:24:43+08:00` | **Design for idempotency** (APIs)
- `2026-10-01T07:33:37+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-09-30T16:29:08+08:00` | **Rotate credentials on schedule** (Security)
- `2026-09-30T10:05:02+08:00` | **Write one behavior per test** (Testing)
- `2026-09-30T07:03:51+08:00` | **Use virtual environments by default** (Python)
- `2026-09-29T22:02:09+08:00` | **Prefer small focused commits** (Git)
