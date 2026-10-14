# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2737**
- Today's entries: **3**
- Today's note: `notes/2026-10-14.md`

### Latest Entry

- Timestamp: `2026-10-14T18:08:51+08:00`
- Title: **Write decisions down**
- Category: `Leadership`
- Source: https://adr.github.io/
- Summary: Lightweight decision records preserve context, reduce repeated debates, and accelerate onboarding for new contributors.

### Top Categories

- `APIs`: 137
- `Accessibility`: 137
- `Architecture`: 137
- `Backend`: 137
- `CI/CD`: 137

### Recent Timeline

- `2026-10-14T18:08:51+08:00` | **Write decisions down** (Leadership)
- `2026-10-14T13:08:17+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-10-14T08:18:20+08:00` | **Measure before tuning** (Performance)
- `2026-10-13T16:16:56+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-10-13T09:30:01+08:00` | **Retry only safe operations** (Networking)
- `2026-10-12T17:31:01+08:00` | **Batch similar tasks** (Productivity)
- `2026-10-12T10:21:12+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-10-12T07:09:03+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-10-11T10:10:42+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-10-11T07:33:07+08:00` | **Automate rollback paths** (DevOps)
