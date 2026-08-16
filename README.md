# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2342**
- Today's entries: **4**
- Today's note: `notes/2026-08-17.md`

### Latest Entry

- Timestamp: `2026-08-17T07:13:58+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 118
- `Security`: 118
- `Testing`: 118
- `APIs`: 117
- `Accessibility`: 117

### Recent Timeline

- `2026-08-17T07:13:58+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-17T06:55:53+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-17T06:36:37+08:00` | **Write one behavior per test** (Testing)
- `2026-08-17T06:12:58+08:00` | **Use virtual environments by default** (Python)
- `2026-08-16T22:46:40+08:00` | **Prefer small focused commits** (Git)
- `2026-08-16T22:25:50+08:00` | **Write decisions down** (Leadership)
- `2026-08-16T21:59:13+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-16T21:42:48+08:00` | **Measure before tuning** (Performance)
- `2026-08-16T20:23:00+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-16T19:55:20+08:00` | **Retry only safe operations** (Networking)
