# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2839**
- Today's entries: **2**
- Today's note: `notes/2026-11-16.md`

### Latest Entry

- Timestamp: `2026-11-16T14:57:35+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 142
- `Accessibility`: 142
- `Architecture`: 142
- `Backend`: 142
- `CI/CD`: 142

### Recent Timeline

- `2026-11-16T14:57:35+08:00` | **Use virtual environments by default** (Python)
- `2026-11-16T08:21:50+08:00` | **Prefer small focused commits** (Git)
- `2026-11-15T16:02:56+08:00` | **Write decisions down** (Leadership)
- `2026-11-14T19:39:10+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-11-14T12:17:45+08:00` | **Measure before tuning** (Performance)
- `2026-11-14T07:54:43+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-11-13T19:31:53+08:00` | **Retry only safe operations** (Networking)
- `2026-11-13T11:34:58+08:00` | **Batch similar tasks** (Productivity)
- `2026-11-13T07:33:14+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-11-12T18:00:00+08:00` | **Use exponential backoff with jitter** (Reliability)
