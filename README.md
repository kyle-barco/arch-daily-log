# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2601**
- Today's entries: **4**
- Today's note: `notes/2026-09-04.md`

### Latest Entry

- Timestamp: `2026-09-04T16:57:43+08:00`
- Title: **Rotate credentials on schedule**
- Category: `Security`
- Source: https://owasp.org/www-project-top-ten/
- Summary: Regular credential rotation limits blast radius if a secret leaks and encourages teams to maintain key management hygiene.

### Top Categories

- `Security`: 131
- `Testing`: 131
- `APIs`: 130
- `Accessibility`: 130
- `Architecture`: 130

### Recent Timeline

- `2026-09-04T16:57:43+08:00` | **Rotate credentials on schedule** (Security)
- `2026-09-04T12:26:47+08:00` | **Write one behavior per test** (Testing)
- `2026-09-04T08:03:16+08:00` | **Use virtual environments by default** (Python)
- `2026-09-04T06:03:44+08:00` | **Prefer small focused commits** (Git)
- `2026-09-03T21:41:43+08:00` | **Write decisions down** (Leadership)
- `2026-09-03T17:19:51+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-09-03T12:48:21+08:00` | **Measure before tuning** (Performance)
- `2026-09-03T08:24:58+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-09-03T06:16:20+08:00` | **Retry only safe operations** (Networking)
- `2026-09-02T21:39:25+08:00` | **Batch similar tasks** (Productivity)
