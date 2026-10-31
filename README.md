# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2802**
- Today's entries: **3**
- Today's note: `notes/2026-10-31.md`

### Latest Entry

- Timestamp: `2026-10-31T16:37:10+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 141
- `Security`: 141
- `Testing`: 141
- `APIs`: 140
- `Accessibility`: 140

### Recent Timeline

- `2026-10-31T16:37:10+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-10-31T10:23:52+08:00` | **Rotate credentials on schedule** (Security)
- `2026-10-31T07:14:07+08:00` | **Write one behavior per test** (Testing)
- `2026-10-30T22:30:46+08:00` | **Use virtual environments by default** (Python)
- `2026-10-30T15:38:20+08:00` | **Prefer small focused commits** (Git)
- `2026-10-30T09:29:42+08:00` | **Write decisions down** (Leadership)
- `2026-10-29T19:22:47+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-10-29T13:00:00+08:00` | **Measure before tuning** (Performance)
- `2026-10-29T07:59:23+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-10-28T22:58:22+08:00` | **Retry only safe operations** (Networking)
