# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **1961**
- Today's entries: **5**
- Today's note: `notes/2026-07-08.md`

### Latest Entry

- Timestamp: `2026-07-08T15:44:23+08:00`
- Title: **Rotate credentials on schedule**
- Category: `Security`
- Source: https://owasp.org/www-project-top-ten/
- Summary: Regular credential rotation limits blast radius if a secret leaks and encourages teams to maintain key management hygiene.

### Top Categories

- `Security`: 99
- `Testing`: 99
- `APIs`: 98
- `Accessibility`: 98
- `Architecture`: 98

### Recent Timeline

- `2026-07-08T15:44:23+08:00` | **Rotate credentials on schedule** (Security)
- `2026-07-08T13:17:44+08:00` | **Write one behavior per test** (Testing)
- `2026-07-08T09:56:17+08:00` | **Use virtual environments by default** (Python)
- `2026-07-08T07:51:18+08:00` | **Prefer small focused commits** (Git)
- `2026-07-08T06:53:25+08:00` | **Write decisions down** (Leadership)
- `2026-07-07T21:35:52+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-07T19:29:27+08:00` | **Measure before tuning** (Performance)
- `2026-07-07T16:39:34+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-07T13:08:06+08:00` | **Retry only safe operations** (Networking)
- `2026-07-07T09:14:11+08:00` | **Batch similar tasks** (Productivity)
