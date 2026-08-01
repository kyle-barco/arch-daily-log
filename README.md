# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2139**
- Today's entries: **1**
- Today's note: `notes/2026-08-01.md`

### Latest Entry

- Timestamp: `2026-08-01T08:10:01+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 107
- `Accessibility`: 107
- `Architecture`: 107
- `Backend`: 107
- `CI/CD`: 107

### Recent Timeline

- `2026-08-01T08:10:01+08:00` | **Use virtual environments by default** (Python)
- `2026-07-31T22:54:59+08:00` | **Prefer small focused commits** (Git)
- `2026-07-31T20:17:44+08:00` | **Write decisions down** (Leadership)
- `2026-07-31T18:14:23+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-31T15:33:04+08:00` | **Measure before tuning** (Performance)
- `2026-07-31T12:36:32+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-31T09:01:18+08:00` | **Retry only safe operations** (Networking)
- `2026-07-31T07:17:09+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-31T06:08:07+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-30T20:47:37+08:00` | **Use exponential backoff with jitter** (Reliability)
