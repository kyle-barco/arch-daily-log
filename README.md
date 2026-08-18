# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2377**
- Today's entries: **13**
- Today's note: `notes/2026-08-18.md`

### Latest Entry

- Timestamp: `2026-08-18T14:01:51+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 119
- `Accessibility`: 119
- `Architecture`: 119
- `Backend`: 119
- `CI/CD`: 119

### Recent Timeline

- `2026-08-18T14:01:51+08:00` | **Write decisions down** (Leadership)
- `2026-08-18T13:43:22+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-18T13:06:30+08:00` | **Measure before tuning** (Performance)
- `2026-08-18T12:36:10+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-18T11:58:36+08:00` | **Retry only safe operations** (Networking)
- `2026-08-18T11:14:19+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-18T10:20:13+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-18T09:00:13+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-18T07:56:42+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-18T07:39:28+08:00` | **Automate rollback paths** (DevOps)
