# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2217**
- Today's entries: **10**
- Today's note: `notes/2026-08-09.md`

### Latest Entry

- Timestamp: `2026-08-09T16:21:26+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 111
- `Accessibility`: 111
- `Architecture`: 111
- `Backend`: 111
- `CI/CD`: 111

### Recent Timeline

- `2026-08-09T16:21:26+08:00` | **Write decisions down** (Leadership)
- `2026-08-09T15:31:13+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-09T14:27:20+08:00` | **Measure before tuning** (Performance)
- `2026-08-09T13:32:47+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-09T11:06:31+08:00` | **Retry only safe operations** (Networking)
- `2026-08-09T09:04:53+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-09T07:52:17+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-09T07:20:02+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-09T06:54:41+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-09T06:19:29+08:00` | **Automate rollback paths** (DevOps)
