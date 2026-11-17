# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2842**
- Today's entries: **1**
- Today's note: `notes/2026-11-18.md`

### Latest Entry

- Timestamp: `2026-11-18T07:57:51+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 143
- `Security`: 143
- `Testing`: 143
- `APIs`: 142
- `Accessibility`: 142

### Recent Timeline

- `2026-11-18T07:57:51+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-11-17T16:21:22+08:00` | **Rotate credentials on schedule** (Security)
- `2026-11-17T08:30:06+08:00` | **Write one behavior per test** (Testing)
- `2026-11-16T14:57:35+08:00` | **Use virtual environments by default** (Python)
- `2026-11-16T08:21:50+08:00` | **Prefer small focused commits** (Git)
- `2026-11-15T16:02:56+08:00` | **Write decisions down** (Leadership)
- `2026-11-14T19:39:10+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-11-14T12:17:45+08:00` | **Measure before tuning** (Performance)
- `2026-11-14T07:54:43+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-11-13T19:31:53+08:00` | **Retry only safe operations** (Networking)
