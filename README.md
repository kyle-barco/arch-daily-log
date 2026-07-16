# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2022**
- Today's entries: **5**
- Today's note: `notes/2026-07-16.md`

### Latest Entry

- Timestamp: `2026-07-16T14:40:00+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 102
- `Security`: 102
- `Testing`: 102
- `APIs`: 101
- `Accessibility`: 101

### Recent Timeline

- `2026-07-16T14:40:00+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-07-16T12:23:45+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-16T09:06:17+08:00` | **Write one behavior per test** (Testing)
- `2026-07-16T07:39:06+08:00` | **Use virtual environments by default** (Python)
- `2026-07-16T06:38:33+08:00` | **Prefer small focused commits** (Git)
- `2026-07-15T21:46:16+08:00` | **Write decisions down** (Leadership)
- `2026-07-15T19:58:35+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-15T18:27:51+08:00` | **Measure before tuning** (Performance)
- `2026-07-15T16:41:10+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-15T14:26:09+08:00` | **Retry only safe operations** (Networking)
