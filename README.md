# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2225**
- Today's entries: **4**
- Today's note: `notes/2026-08-10.md`

### Latest Entry

- Timestamp: `2026-08-10T07:56:09+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 112
- `Architecture`: 112
- `Databases`: 112
- `Observability`: 112
- `Security`: 112

### Recent Timeline

- `2026-08-10T07:56:09+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-10T07:22:44+08:00` | **Log with stable keys** (Observability)
- `2026-08-10T06:47:57+08:00` | **Design for idempotency** (APIs)
- `2026-08-10T06:02:39+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-09T21:12:48+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-09T19:00:06+08:00` | **Write one behavior per test** (Testing)
- `2026-08-09T17:54:14+08:00` | **Use virtual environments by default** (Python)
- `2026-08-09T17:09:04+08:00` | **Prefer small focused commits** (Git)
- `2026-08-09T16:21:26+08:00` | **Write decisions down** (Leadership)
- `2026-08-09T15:31:13+08:00` | **Keyboard support is a baseline** (Accessibility)
