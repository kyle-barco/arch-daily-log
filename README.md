# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2117**
- Today's entries: **2**
- Today's note: `notes/2026-07-29.md`

### Latest Entry

- Timestamp: `2026-07-29T07:37:45+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 106
- `Accessibility`: 106
- `Architecture`: 106
- `Backend`: 106
- `CI/CD`: 106

### Recent Timeline

- `2026-07-29T07:37:45+08:00` | **Write decisions down** (Leadership)
- `2026-07-29T06:31:58+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-28T21:44:56+08:00` | **Measure before tuning** (Performance)
- `2026-07-28T19:51:22+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-28T17:45:35+08:00` | **Retry only safe operations** (Networking)
- `2026-07-28T15:09:09+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-28T12:25:34+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-28T09:04:02+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-28T07:42:50+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-28T06:32:18+08:00` | **Automate rollback paths** (DevOps)
