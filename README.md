# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2657**
- Today's entries: **2**
- Today's note: `notes/2026-09-18.md`

### Latest Entry

- Timestamp: `2026-09-18T08:32:16+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 133
- `Accessibility`: 133
- `Architecture`: 133
- `Backend`: 133
- `CI/CD`: 133

### Recent Timeline

- `2026-09-18T08:32:16+08:00` | **Write decisions down** (Leadership)
- `2026-09-18T06:25:05+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-09-17T19:55:06+08:00` | **Measure before tuning** (Performance)
- `2026-09-17T14:19:10+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-09-17T09:22:16+08:00` | **Retry only safe operations** (Networking)
- `2026-09-17T07:05:05+08:00` | **Batch similar tasks** (Productivity)
- `2026-09-16T20:58:14+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-09-16T15:54:09+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-09-16T10:37:07+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-09-16T07:52:02+08:00` | **Automate rollback paths** (DevOps)
