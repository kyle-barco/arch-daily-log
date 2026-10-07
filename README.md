# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2719**
- Today's entries: **2**
- Today's note: `notes/2026-10-07.md`

### Latest Entry

- Timestamp: `2026-10-07T14:14:40+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 136
- `Accessibility`: 136
- `Architecture`: 136
- `Backend`: 136
- `CI/CD`: 136

### Recent Timeline

- `2026-10-07T14:14:40+08:00` | **Use virtual environments by default** (Python)
- `2026-10-07T08:21:54+08:00` | **Prefer small focused commits** (Git)
- `2026-10-06T17:24:25+08:00` | **Write decisions down** (Leadership)
- `2026-10-06T10:30:16+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-10-06T06:40:12+08:00` | **Measure before tuning** (Performance)
- `2026-10-05T15:19:13+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-10-05T09:16:18+08:00` | **Retry only safe operations** (Networking)
- `2026-10-05T06:38:10+08:00` | **Batch similar tasks** (Productivity)
- `2026-10-04T20:16:49+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-10-03T14:29:19+08:00` | **Use exponential backoff with jitter** (Reliability)
