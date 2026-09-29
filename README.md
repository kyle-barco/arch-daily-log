# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2699**
- Today's entries: **1**
- Today's note: `notes/2026-09-30.md`

### Latest Entry

- Timestamp: `2026-09-30T07:03:51+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 135
- `Accessibility`: 135
- `Architecture`: 135
- `Backend`: 135
- `CI/CD`: 135

### Recent Timeline

- `2026-09-30T07:03:51+08:00` | **Use virtual environments by default** (Python)
- `2026-09-29T22:02:09+08:00` | **Prefer small focused commits** (Git)
- `2026-09-29T15:08:06+08:00` | **Write decisions down** (Leadership)
- `2026-09-29T09:15:22+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-09-28T15:37:27+08:00` | **Measure before tuning** (Performance)
- `2026-09-28T09:38:16+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-09-28T07:11:32+08:00` | **Retry only safe operations** (Networking)
- `2026-09-27T21:10:53+08:00` | **Batch similar tasks** (Productivity)
- `2026-09-27T09:47:00+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-09-26T13:31:50+08:00` | **Use exponential backoff with jitter** (Reliability)
