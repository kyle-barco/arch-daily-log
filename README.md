# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2081**
- Today's entries: **6**
- Today's note: `notes/2026-07-23.md`

### Latest Entry

- Timestamp: `2026-07-23T18:28:35+08:00`
- Title: **Rotate credentials on schedule**
- Category: `Security`
- Source: https://owasp.org/www-project-top-ten/
- Summary: Regular credential rotation limits blast radius if a secret leaks and encourages teams to maintain key management hygiene.

### Top Categories

- `Security`: 105
- `Testing`: 105
- `APIs`: 104
- `Accessibility`: 104
- `Architecture`: 104

### Recent Timeline

- `2026-07-23T18:28:35+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-23T16:00:03+08:00` | **Write one behavior per test** (Testing)
- `2026-07-23T13:33:40+08:00` | **Use virtual environments by default** (Python)
- `2026-07-23T10:10:25+08:00` | **Prefer small focused commits** (Git)
- `2026-07-23T07:55:48+08:00` | **Write decisions down** (Leadership)
- `2026-07-23T06:54:41+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-22T21:10:16+08:00` | **Measure before tuning** (Performance)
- `2026-07-22T19:42:58+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-22T17:54:46+08:00` | **Retry only safe operations** (Networking)
- `2026-07-22T15:19:44+08:00` | **Batch similar tasks** (Productivity)
