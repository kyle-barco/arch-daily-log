# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2042**
- Today's entries: **7**
- Today's note: `notes/2026-07-18.md`

### Latest Entry

- Timestamp: `2026-07-18T20:36:59+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 103
- `Security`: 103
- `Testing`: 103
- `APIs`: 102
- `Accessibility`: 102

### Recent Timeline

- `2026-07-18T20:36:59+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-18T18:39:47+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-18T17:07:38+08:00` | **Write one behavior per test** (Testing)
- `2026-07-18T15:19:10+08:00` | **Use virtual environments by default** (Python)
- `2026-07-18T13:42:47+08:00` | **Prefer small focused commits** (Git)
- `2026-07-18T11:28:42+08:00` | **Write decisions down** (Leadership)
- `2026-07-18T06:05:13+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-17T22:10:54+08:00` | **Measure before tuning** (Performance)
- `2026-07-17T20:20:14+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-17T19:05:32+08:00` | **Retry only safe operations** (Networking)
