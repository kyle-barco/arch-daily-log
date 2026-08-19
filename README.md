# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2419**
- Today's entries: **3**
- Today's note: `notes/2026-08-20.md`

### Latest Entry

- Timestamp: `2026-08-20T07:15:42+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 121
- `Accessibility`: 121
- `Architecture`: 121
- `Backend`: 121
- `CI/CD`: 121

### Recent Timeline

- `2026-08-20T07:15:42+08:00` | **Use virtual environments by default** (Python)
- `2026-08-20T06:48:09+08:00` | **Prefer small focused commits** (Git)
- `2026-08-20T06:15:57+08:00` | **Write decisions down** (Leadership)
- `2026-08-19T22:51:06+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-19T22:04:36+08:00` | **Measure before tuning** (Performance)
- `2026-08-19T21:25:12+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-19T20:28:49+08:00` | **Retry only safe operations** (Networking)
- `2026-08-19T19:47:55+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-19T19:17:42+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-19T18:52:56+08:00` | **Use exponential backoff with jitter** (Reliability)
