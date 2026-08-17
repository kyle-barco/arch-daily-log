# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2357**
- Today's entries: **19**
- Today's note: `notes/2026-08-17.md`

### Latest Entry

- Timestamp: `2026-08-17T18:48:36+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 118
- `Accessibility`: 118
- `Architecture`: 118
- `Backend`: 118
- `CI/CD`: 118

### Recent Timeline

- `2026-08-17T18:48:36+08:00` | **Write decisions down** (Leadership)
- `2026-08-17T18:14:30+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-08-17T17:41:26+08:00` | **Measure before tuning** (Performance)
- `2026-08-17T16:58:20+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-08-17T16:00:25+08:00` | **Retry only safe operations** (Networking)
- `2026-08-17T15:13:39+08:00` | **Batch similar tasks** (Productivity)
- `2026-08-17T14:00:15+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-08-17T13:28:41+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-08-17T12:55:28+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-08-17T12:09:37+08:00` | **Automate rollback paths** (DevOps)
