# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2579**
- Today's entries: **2**
- Today's note: `notes/2026-08-30.md`

### Latest Entry

- Timestamp: `2026-08-30T20:50:55+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 129
- `Accessibility`: 129
- `Architecture`: 129
- `Backend`: 129
- `CI/CD`: 129

### Recent Timeline

- `2026-08-30T20:50:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-30T07:28:31+08:00` | **Prefer small focused commits** (Git)
- `2026-08-28T21:36:54+08:00` | **Write decisions down** (Leadership)
- `2026-08-28T09:46:22+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-27T14:20:42+08:00` | **Measure before tuning** (Performance)
- `2026-08-27T07:53:28+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-26T22:04:03+08:00` | **Retry only safe operations** (Networking)
- `2026-08-26T21:13:46+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-26T20:01:37+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-26T19:33:24+08:00` | **Use exponential backoff with jitter** (Reliability)
