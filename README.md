# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2562**
- Today's entries: **10**
- Today's note: `notes/2026-08-26.md`

### Latest Entry

- Timestamp: `2026-08-26T13:47:50+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 129
- `Security`: 129
- `Testing`: 129
- `APIs`: 128
- `Accessibility`: 128

### Recent Timeline

- `2026-08-26T13:47:50+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-26T13:02:39+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-26T12:22:08+08:00` | **Write one behavior per test** (Testing)
- `2026-08-26T11:30:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-26T10:20:19+08:00` | **Prefer small focused commits** (Git)
- `2026-08-26T08:48:46+08:00` | **Write decisions down** (Leadership)
- `2026-08-26T07:46:27+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-26T07:21:22+08:00` | **Measure before tuning** (Performance)
- `2026-08-26T06:56:35+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-26T06:29:43+08:00` | **Retry only safe operations** (Networking)
