# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2017**
- Today's entries: **9**
- Today's note: `notes/2026-07-15.md`

### Latest Entry

- Timestamp: `2026-07-15T21:46:16+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 101
- `Accessibility`: 101
- `Architecture`: 101
- `Backend`: 101
- `CI/CD`: 101

### Recent Timeline

- `2026-07-15T21:46:16+08:00` | **Write decisions down** (Leadership)
- `2026-07-15T19:58:35+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-15T18:27:51+08:00` | **Measure before tuning** (Performance)
- `2026-07-15T16:41:10+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-15T14:26:09+08:00` | **Retry only safe operations** (Networking)
- `2026-07-15T12:06:15+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-15T08:58:53+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-15T07:31:46+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-15T06:38:17+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-14T22:10:28+08:00` | **Automate rollback paths** (DevOps)
