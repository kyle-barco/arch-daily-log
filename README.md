# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2697**
- Today's entries: **2**
- Today's note: `notes/2026-09-29.md`

### Latest Entry

- Timestamp: `2026-09-29T15:08:06+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 135
- `Accessibility`: 135
- `Architecture`: 135
- `Backend`: 135
- `CI/CD`: 135

### Recent Timeline

- `2026-09-29T15:08:06+08:00` | **Write decisions down** (Leadership)
- `2026-09-29T09:15:22+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-09-28T15:37:27+08:00` | **Measure before tuning** (Performance)
- `2026-09-28T09:38:16+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-09-28T07:11:32+08:00` | **Retry only safe operations** (Networking)
- `2026-09-27T21:10:53+08:00` | **Batch similar tasks** (Productivity)
- `2026-09-27T09:47:00+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-09-26T13:31:50+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-09-26T08:43:49+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-09-26T06:17:01+08:00` | **Automate rollback paths** (DevOps)
