# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2321**
- Today's entries: **3**
- Today's note: `notes/2026-08-16.md`

### Latest Entry

- Timestamp: `2026-08-16T07:41:42+08:00`
- Title: **Rotate credentials on schedule**
- Category: `Security`
- Source: https://owasp.org/www-project-top-ten/
- Summary: Regular credential rotation limits blast radius if a secret leaks and encourages teams to maintain key management hygiene.

### Top Categories

- `Security`: 117
- `Testing`: 117
- `APIs`: 116
- `Accessibility`: 116
- `Architecture`: 116

### Recent Timeline

- `2026-08-16T07:41:42+08:00` | **Rotate credentials on schedule** (Security)
- `2026-08-16T06:59:25+08:00` | **Write one behavior per test** (Testing)
- `2026-08-16T06:15:09+08:00` | **Use virtual environments by default** (Python)
- `2026-08-15T22:45:32+08:00` | **Prefer small focused commits** (Git)
- `2026-08-15T22:24:03+08:00` | **Write decisions down** (Leadership)
- `2026-08-15T21:41:58+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-15T21:06:00+08:00` | **Measure before tuning** (Performance)
- `2026-08-15T19:55:50+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-15T19:42:10+08:00` | **Retry only safe operations** (Networking)
- `2026-08-15T18:56:51+08:00` | **Batch similar tasks** (Productivity)
