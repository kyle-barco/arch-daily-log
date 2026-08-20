# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2422**
- Today's entries: **6**
- Today's note: `notes/2026-08-20.md`

### Latest Entry

- Timestamp: `2026-08-20T09:21:12+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 122
- `Security`: 122
- `Testing`: 122
- `APIs`: 121
- `Accessibility`: 121

### Recent Timeline

- `2026-08-20T09:21:12+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-20T07:59:02+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-20T07:43:56+08:00` | **Write one behavior per test** (Testing)
- `2026-08-20T07:15:42+08:00` | **Use virtual environments by default** (Python)
- `2026-08-20T06:48:09+08:00` | **Prefer small focused commits** (Git)
- `2026-08-20T06:15:57+08:00` | **Write decisions down** (Leadership)
- `2026-08-19T22:51:06+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-19T22:04:36+08:00` | **Measure before tuning** (Performance)
- `2026-08-19T21:25:12+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-19T20:28:49+08:00` | **Retry only safe operations** (Networking)
