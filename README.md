# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2779**
- Today's entries: **1**
- Today's note: `notes/2026-10-25.md`

### Latest Entry

- Timestamp: `2026-10-25T07:42:05+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 139
- `Accessibility`: 139
- `Architecture`: 139
- `Backend`: 139
- `CI/CD`: 139

### Recent Timeline

- `2026-10-25T07:42:05+08:00` | **Use virtual environments by default** (Python)
- `2026-10-24T21:34:36+08:00` | **Prefer small focused commits** (Git)
- `2026-10-24T17:40:22+08:00` | **Write decisions down** (Leadership)
- `2026-10-24T13:15:17+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-10-24T08:54:19+08:00` | **Measure before tuning** (Performance)
- `2026-10-24T06:26:30+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-10-23T18:18:31+08:00` | **Retry only safe operations** (Networking)
- `2026-10-23T13:21:04+08:00` | **Batch similar tasks** (Productivity)
- `2026-10-23T08:37:54+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-10-23T06:00:27+08:00` | **Use exponential backoff with jitter** (Reliability)
