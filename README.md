# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2565**
- Today's entries: **13**
- Today's note: `notes/2026-08-26.md`

### Latest Entry

- Timestamp: `2026-08-26T16:22:21+08:00`
- Title: **Keep boundaries explicit**
- Category: `Architecture`
- Source: https://12factor.net/
- Summary: Defining module boundaries early reduces accidental coupling and keeps refactors local instead of system-wide.

### Top Categories

- `APIs`: 129
- `Architecture`: 129
- `Databases`: 129
- `Observability`: 129
- `Security`: 129

### Recent Timeline

- `2026-08-26T16:22:21+08:00` | **Keep boundaries explicit** (Architecture)
- `2026-08-26T15:30:18+08:00` | **Log with stable keys** (Observability)
- `2026-08-26T14:33:45+08:00` | **Design for idempotency** (APIs)
- `2026-08-26T13:47:50+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-26T13:02:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-26T12:22:08+08:00` | **Write one behavior per test** (Testing)
- `2026-08-26T11:30:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-26T10:20:19+08:00` | **Prefer small focused commits** (Git)
- `2026-08-26T08:48:46+08:00` | **Write decisions down** (Leadership)
- `2026-08-26T07:46:27+08:00` | **Keyboard support is a baseline** (Accessibility)
