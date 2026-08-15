# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2302**
- Today's entries: **9**
- Today's note: `notes/2026-08-15.md`

### Latest Entry

- Timestamp: `2026-08-15T12:01:29+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 116
- `Security`: 116
- `Testing`: 116
- `APIs`: 115
- `Accessibility`: 115

### Recent Timeline

- `2026-08-15T12:01:29+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-15T11:22:00+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-15T10:37:35+08:00` | **Write one behavior per test** (Testing)
- `2026-08-15T07:59:57+08:00` | **Use virtual environments by default** (Python)
- `2026-08-15T07:44:15+08:00` | **Prefer small focused commits** (Git)
- `2026-08-15T07:21:59+08:00` | **Write decisions down** (Leadership)
- `2026-08-15T06:58:27+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-15T06:41:09+08:00` | **Measure before tuning** (Performance)
- `2026-08-15T06:13:53+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-14T22:37:18+08:00` | **Retry only safe operations** (Networking)
