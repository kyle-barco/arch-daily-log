# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2041**
- Today's entries: **6**
- Today's note: `notes/2026-07-18.md`

### Latest Entry

- Timestamp: `2026-07-18T18:39:47+08:00`
- Title: **Rotate credentials on schedule**
- Category: `Security`
- Source: https://owasp.org/www-project-top-ten/
- Summary: Regular credential rotation limits blast radius if a secret leaks and encourages teams to maintain key management hygiene.

### Top Categories

- `Security`: 103
- `Testing`: 103
- `APIs`: 102
- `Accessibility`: 102
- `Architecture`: 102

### Recent Timeline

- `2026-07-18T18:39:47+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-18T17:07:38+08:00` | **Write one behavior per test** (Testing)
- `2026-07-18T15:19:10+08:00` | **Use virtual environments by default** (Python)
- `2026-07-18T13:42:47+08:00` | **Prefer small focused commits** (Git)
- `2026-07-18T11:28:42+08:00` | **Write decisions down** (Leadership)
- `2026-07-18T06:05:13+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-17T22:10:54+08:00` | **Measure before tuning** (Performance)
- `2026-07-17T20:20:14+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-17T19:05:32+08:00` | **Retry only safe operations** (Networking)
- `2026-07-17T17:27:22+08:00` | **Batch similar tasks** (Productivity)
