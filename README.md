# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2019**
- Today's entries: **2**
- Today's note: `notes/2026-07-16.md`

### Latest Entry

- Timestamp: `2026-07-16T07:39:06+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 101
- `Accessibility`: 101
- `Architecture`: 101
- `Backend`: 101
- `CI/CD`: 101

### Recent Timeline

- `2026-07-16T07:39:06+08:00` | **Use virtual environments by default** (Python)
- `2026-07-16T06:38:33+08:00` | **Prefer small focused commits** (Git)
- `2026-07-15T21:46:16+08:00` | **Write decisions down** (Leadership)
- `2026-07-15T19:58:35+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-15T18:27:51+08:00` | **Measure before tuning** (Performance)
- `2026-07-15T16:41:10+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-15T14:26:09+08:00` | **Retry only safe operations** (Networking)
- `2026-07-15T12:06:15+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-15T08:58:53+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-15T07:31:46+08:00` | **Use exponential backoff with jitter** (Reliability)
