# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2179**
- Today's entries: **1**
- Today's note: `notes/2026-08-06.md`

### Latest Entry

- Timestamp: `2026-08-06T06:13:55+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 109
- `Accessibility`: 109
- `Architecture`: 109
- `Backend`: 109
- `CI/CD`: 109

### Recent Timeline

- `2026-08-06T06:13:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-05T22:53:07+08:00` | **Prefer small focused commits** (Git)
- `2026-08-05T20:26:22+08:00` | **Write decisions down** (Leadership)
- `2026-08-05T18:40:50+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-05T15:59:44+08:00` | **Measure before tuning** (Performance)
- `2026-08-05T13:23:44+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-05T10:09:33+08:00` | **Retry only safe operations** (Networking)
- `2026-08-05T07:56:47+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-05T06:54:25+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-04T21:22:17+08:00` | **Use exponential backoff with jitter** (Reliability)
