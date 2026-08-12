# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2262**
- Today's entries: **11**
- Today's note: `notes/2026-08-12.md`

### Latest Entry

- Timestamp: `2026-08-12T19:28:40+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 114
- `Security`: 114
- `Testing`: 114
- `APIs`: 113
- `Accessibility`: 113

### Recent Timeline

- `2026-08-12T19:28:40+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-12T18:41:07+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-12T17:30:25+08:00` | **Write one behavior per test** (Testing)
- `2026-08-12T16:09:57+08:00` | **Use virtual environments by default** (Python)
- `2026-08-12T14:51:13+08:00` | **Prefer small focused commits** (Git)
- `2026-08-12T13:25:10+08:00` | **Write decisions down** (Leadership)
- `2026-08-12T11:50:26+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-12T09:42:19+08:00` | **Measure before tuning** (Performance)
- `2026-08-12T07:56:59+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-12T07:00:14+08:00` | **Retry only safe operations** (Networking)
