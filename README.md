# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2299**
- Today's entries: **6**
- Today's note: `notes/2026-08-15.md`

### Latest Entry

- Timestamp: `2026-08-15T07:59:57+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 115
- `Accessibility`: 115
- `Architecture`: 115
- `Backend`: 115
- `CI/CD`: 115

### Recent Timeline

- `2026-08-15T07:59:57+08:00` | **Use virtual environments by default** (Python)
- `2026-08-15T07:44:15+08:00` | **Prefer small focused commits** (Git)
- `2026-08-15T07:21:59+08:00` | **Write decisions down** (Leadership)
- `2026-08-15T06:58:27+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-15T06:41:09+08:00` | **Measure before tuning** (Performance)
- `2026-08-15T06:13:53+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-14T22:37:18+08:00` | **Retry only safe operations** (Networking)
- `2026-08-14T21:38:24+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-14T20:05:26+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-14T19:25:53+08:00` | **Use exponential backoff with jitter** (Reliability)
