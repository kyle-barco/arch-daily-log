# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2542**
- Today's entries: **14**
- Today's note: `notes/2026-08-25.md`

### Latest Entry

- Timestamp: `2026-08-25T15:28:47+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 128
- `Security`: 128
- `Testing`: 128
- `APIs`: 127
- `Accessibility`: 127

### Recent Timeline

- `2026-08-25T15:28:47+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-25T14:33:18+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-25T13:55:27+08:00` | **Write one behavior per test** (Testing)
- `2026-08-25T13:24:08+08:00` | **Use virtual environments by default** (Python)
- `2026-08-25T12:51:22+08:00` | **Prefer small focused commits** (Git)
- `2026-08-25T12:08:48+08:00` | **Write decisions down** (Leadership)
- `2026-08-25T11:29:20+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-25T10:35:02+08:00` | **Measure before tuning** (Performance)
- `2026-08-25T09:17:03+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-25T07:58:23+08:00` | **Retry only safe operations** (Networking)
