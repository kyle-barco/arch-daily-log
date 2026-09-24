# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2682**
- Today's entries: **3**
- Today's note: `notes/2026-09-24.md`

### Latest Entry

- Timestamp: `2026-09-24T17:33:35+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 135
- `Security`: 135
- `Testing`: 135
- `APIs`: 134
- `Accessibility`: 134

### Recent Timeline

- `2026-09-24T17:33:35+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-09-24T12:44:11+08:00` | **Rotate credentials on schedule** (Security)
- `2026-09-24T08:08:38+08:00` | **Write one behavior per test** (Testing)
- `2026-09-23T22:37:36+08:00` | **Use virtual environments by default** (Python)
- `2026-09-23T17:56:30+08:00` | **Prefer small focused commits** (Git)
- `2026-09-23T13:00:46+08:00` | **Write decisions down** (Leadership)
- `2026-09-23T08:28:51+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-09-23T06:05:38+08:00` | **Measure before tuning** (Performance)
- `2026-09-22T19:34:44+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-09-22T14:11:03+08:00` | **Retry only safe operations** (Networking)
