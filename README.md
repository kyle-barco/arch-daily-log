# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2197**
- Today's entries: **11**
- Today's note: `notes/2026-08-07.md`

### Latest Entry

- Timestamp: `2026-08-07T21:59:03+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 110
- `Accessibility`: 110
- `Architecture`: 110
- `Backend`: 110
- `CI/CD`: 110

### Recent Timeline

- `2026-08-07T21:59:03+08:00` | **Write decisions down** (Leadership)
- `2026-08-07T20:43:12+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-07T19:54:54+08:00` | **Measure before tuning** (Performance)
- `2026-08-07T19:05:40+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-07T18:08:49+08:00` | **Retry only safe operations** (Networking)
- `2026-08-07T17:03:03+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-07T15:59:25+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-07T14:42:28+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-07T13:22:11+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-07T11:37:48+08:00` | **Automate rollback paths** (DevOps)
