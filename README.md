# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2797**
- Today's entries: **1**
- Today's note: `notes/2026-10-30.md`

### Latest Entry

- Timestamp: `2026-10-30T09:29:42+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 140
- `Accessibility`: 140
- `Architecture`: 140
- `Backend`: 140
- `CI/CD`: 140

### Recent Timeline

- `2026-10-30T09:29:42+08:00` | **Write decisions down** (Leadership)
- `2026-10-29T19:22:47+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-10-29T13:00:00+08:00` | **Measure before tuning** (Performance)
- `2026-10-29T07:59:23+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-10-28T22:58:22+08:00` | **Retry only safe operations** (Networking)
- `2026-10-28T15:59:58+08:00` | **Batch similar tasks** (Productivity)
- `2026-10-28T09:58:43+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-10-28T06:56:03+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-10-27T21:49:07+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-10-27T15:53:51+08:00` | **Automate rollback paths** (DevOps)
