# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2822**
- Today's entries: **2**
- Today's note: `notes/2026-11-09.md`

### Latest Entry

- Timestamp: `2026-11-09T10:50:24+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 142
- `Security`: 142
- `Testing`: 142
- `APIs`: 141
- `Accessibility`: 141

### Recent Timeline

- `2026-11-09T10:50:24+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-11-09T07:24:48+08:00` | **Rotate credentials on schedule** (Security)
- `2026-11-07T16:43:01+08:00` | **Write one behavior per test** (Testing)
- `2026-11-07T10:07:00+08:00` | **Use virtual environments by default** (Python)
- `2026-11-06T18:35:21+08:00` | **Prefer small focused commits** (Git)
- `2026-11-06T10:59:31+08:00` | **Write decisions down** (Leadership)
- `2026-11-06T06:50:43+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-11-05T17:42:48+08:00` | **Measure before tuning** (Performance)
- `2026-11-05T10:26:43+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-11-05T06:12:11+08:00` | **Retry only safe operations** (Networking)
