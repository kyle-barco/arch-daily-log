# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2639**
- Today's entries: **4**
- Today's note: `notes/2026-09-13.md`

### Latest Entry

- Timestamp: `2026-09-13T17:44:04+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 132
- `Accessibility`: 132
- `Architecture`: 132
- `Backend`: 132
- `CI/CD`: 132

### Recent Timeline

- `2026-09-13T17:44:04+08:00` | **Use virtual environments by default** (Python)
- `2026-09-13T12:41:57+08:00` | **Prefer small focused commits** (Git)
- `2026-09-13T08:05:20+08:00` | **Write decisions down** (Leadership)
- `2026-09-13T06:25:26+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-09-12T20:36:28+08:00` | **Measure before tuning** (Performance)
- `2026-09-12T08:15:14+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-09-12T06:07:07+08:00` | **Retry only safe operations** (Networking)
- `2026-09-11T21:49:43+08:00` | **Batch similar tasks** (Productivity)
- `2026-09-11T17:43:11+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-09-11T13:14:33+08:00` | **Use exponential backoff with jitter** (Reliability)
