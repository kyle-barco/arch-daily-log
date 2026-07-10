# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **1979**
- Today's entries: **1**
- Today's note: `notes/2026-07-11.md`

### Latest Entry

- Timestamp: `2026-07-11T06:14:15+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 99
- `Accessibility`: 99
- `Architecture`: 99
- `Backend`: 99
- `CI/CD`: 99

### Recent Timeline

- `2026-07-11T06:14:15+08:00` | **Use virtual environments by default** (Python)
- `2026-07-10T21:45:18+08:00` | **Prefer small focused commits** (Git)
- `2026-07-10T19:44:03+08:00` | **Write decisions down** (Leadership)
- `2026-07-10T16:48:49+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-10T13:29:16+08:00` | **Measure before tuning** (Performance)
- `2026-07-10T09:16:11+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-10T07:43:36+08:00` | **Retry only safe operations** (Networking)
- `2026-07-10T06:15:11+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-09T22:36:39+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-09T19:53:15+08:00` | **Use exponential backoff with jitter** (Reliability)
