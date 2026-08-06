# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2182**
- Today's entries: **4**
- Today's note: `notes/2026-08-06.md`

### Latest Entry

- Timestamp: `2026-08-06T11:59:00+08:00`
- Title: **Add indexes for real query patterns**
- Category: `Databases`
- Source: https://use-the-index-luke.com/
- Summary: Measure slow queries first, then index based on predicates and sort order. Over-indexing harms write performance.

### Top Categories

- `Databases`: 110
- `Security`: 110
- `Testing`: 110
- `APIs`: 109
- `Accessibility`: 109

### Recent Timeline

- `2026-08-06T11:59:00+08:00` | **Add indexes for real query patterns** (Databases)
- `2026-08-06T08:49:32+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-06T07:17:51+08:00` | **Write one behavior per test** (Testing)
- `2026-08-06T06:13:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-05T22:53:07+08:00` | **Prefer small focused commits** (Git)
- `2026-08-05T20:26:22+08:00` | **Write decisions down** (Leadership)
- `2026-08-05T18:40:50+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-05T15:59:44+08:00` | **Measure before tuning** (Performance)
- `2026-08-05T13:23:44+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-05T10:09:33+08:00` | **Retry only safe operations** (Networking)
