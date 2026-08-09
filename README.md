# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2222**
- Today's entries: **1**
- Today's note: `notes/2026-08-10.md`

### Latest Entry

- Timestamp: `2026-08-10T06:02:39+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 112
- `Security`: 112
- `Testing`: 112
- `APIs`: 111
- `Accessibility`: 111

### Recent Timeline

- `2026-08-10T06:02:39+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-09T21:12:48+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-09T19:00:06+08:00` | **Write one behavior per test** (Testing)
- `2026-08-09T17:54:14+08:00` | **Use virtual environments by default** (Python)
- `2026-08-09T17:09:04+08:00` | **Prefer small focused commits** (Git)
- `2026-08-09T16:21:26+08:00` | **Write decisions down** (Leadership)
- `2026-08-09T15:31:13+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-09T14:27:20+08:00` | **Measure before tuning** (Performance)
- `2026-08-09T13:32:47+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-09T11:06:31+08:00` | **Retry only safe operations** (Networking)
