# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2079**
- Today's entries: **4**
- Today's note: `notes/2026-07-23.md`

### Latest Entry

- Timestamp: `2026-07-23T13:33:40+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 104
- `Accessibility`: 104
- `Architecture`: 104
- `Backend`: 104
- `CI/CD`: 104

### Recent Timeline

- `2026-07-23T13:33:40+08:00` | **Use virtual environments by default** (Python)
- `2026-07-23T10:10:25+08:00` | **Prefer small focused commits** (Git)
- `2026-07-23T07:55:48+08:00` | **Write decisions down** (Leadership)
- `2026-07-23T06:54:41+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-22T21:10:16+08:00` | **Measure before tuning** (Performance)
- `2026-07-22T19:42:58+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-22T17:54:46+08:00` | **Retry only safe operations** (Networking)
- `2026-07-22T15:19:44+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-22T12:32:02+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-22T09:05:12+08:00` | **Use exponential backoff with jitter** (Reliability)
