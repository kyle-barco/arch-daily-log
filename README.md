# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2559**
- Today's entries: **7**
- Today's note: `notes/2026-08-26.md`

### Latest Entry

- Timestamp: `2026-08-26T11:30:55+08:00`
- Title: **Use virtual environments by default**
- Category: `Python`
- Source: https://docs.python.org/3/library/venv.html
- Summary: Project-specific virtual environments prevent dependency leaks across projects and make builds more reproducible on CI.

### Top Categories

- `APIs`: 128
- `Accessibility`: 128
- `Architecture`: 128
- `Backend`: 128
- `CI/CD`: 128

### Recent Timeline

- `2026-08-26T11:30:55+08:00` | **Use virtual environments by default** (Python)
- `2026-08-26T10:20:19+08:00` | **Prefer small focused commits** (Git)
- `2026-08-26T08:48:46+08:00` | **Write decisions down** (Leadership)
- `2026-08-26T07:46:27+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-26T07:21:22+08:00` | **Measure before tuning** (Performance)
- `2026-08-26T06:56:35+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-26T06:29:43+08:00` | **Retry only safe operations** (Networking)
- `2026-08-25T22:26:11+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-25T21:32:46+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-25T20:31:32+08:00` | **Use exponential backoff with jitter** (Reliability)
