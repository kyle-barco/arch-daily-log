# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2781**
- Today's entries: **3**
- Today's note: `notes/2026-10-25.md`

### Latest Entry

- Timestamp: `2026-10-25T14:50:36+08:00`
- Title: **Rotate credentials on schedule**
- Category: `Security`
- Source: https://owasp.org/www-project-top-ten/
- Summary: Regular credential rotation limits blast radius if a secret leaks and encourages teams to maintain key management hygiene.

### Top Categories

- `Security`: 140
- `Testing`: 140
- `APIs`: 139
- `Accessibility`: 139
- `Architecture`: 139

### Recent Timeline

- `2026-10-25T14:50:36+08:00` | **Rotate credentials on schedule** (Security)
- `2026-10-25T09:39:20+08:00` | **Write one behavior per test** (Testing)
- `2026-10-25T07:42:05+08:00` | **Use virtual environments by default** (Python)
- `2026-10-24T21:34:36+08:00` | **Prefer small focused commits** (Git)
- `2026-10-24T17:40:22+08:00` | **Write decisions down** (Leadership)
- `2026-10-24T13:15:17+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-10-24T08:54:19+08:00` | **Measure before tuning** (Performance)
- `2026-10-24T06:26:30+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-10-23T18:18:31+08:00` | **Retry only safe operations** (Networking)
- `2026-10-23T13:21:04+08:00` | **Batch similar tasks** (Productivity)
