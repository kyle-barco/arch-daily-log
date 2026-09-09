# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2619**
- Today's entries: **2**
- Today's note: `notes/2026-09-09.md`

### Latest Entry

- Timestamp: `2026-09-09T08:54:51+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 131
- `Accessibility`: 131
- `Architecture`: 131
- `Backend`: 131
- `CI/CD`: 131

### Recent Timeline

- `2026-09-09T08:54:51+08:00` | **Use virtual environments by default** (Python)
- `2026-09-09T06:49:26+08:00` | **Prefer small focused commits** (Git)
- `2026-09-08T21:44:17+08:00` | **Write decisions down** (Leadership)
- `2026-09-08T17:18:32+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-09-08T12:56:16+08:00` | **Measure before tuning** (Performance)
- `2026-09-08T08:22:32+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-09-08T06:09:20+08:00` | **Retry only safe operations** (Networking)
- `2026-09-07T17:43:19+08:00` | **Batch similar tasks** (Productivity)
- `2026-09-07T12:34:26+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-09-07T08:07:26+08:00` | **Use exponential backoff with jitter** (Reliability)
