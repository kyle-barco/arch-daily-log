# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2497**
- Today's entries: **13**
- Today's note: `notes/2026-08-23.md`

### Latest Entry

- Timestamp: `2026-08-23T16:34:14+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 125
- `Accessibility`: 125
- `Architecture`: 125
- `Backend`: 125
- `CI/CD`: 125

### Recent Timeline

- `2026-08-23T16:34:14+08:00` | **Write decisions down** (Leadership)
- `2026-08-23T15:59:29+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-23T15:33:14+08:00` | **Measure before tuning** (Performance)
- `2026-08-23T14:58:18+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-23T13:32:32+08:00` | **Retry only safe operations** (Networking)
- `2026-08-23T12:59:29+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-23T12:21:10+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-23T10:36:25+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-23T09:08:52+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-23T07:57:00+08:00` | **Automate rollback paths** (DevOps)
