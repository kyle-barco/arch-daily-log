# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **1995**
- Today's entries: **3**
- Today's note: `notes/2026-07-13.md`

### Latest Entry

- Timestamp: `2026-07-13T09:04:09+08:00`
- Title: **Measure before tuning**
- Category: `Performance`
- Source: https://perf.wiki/
- Summary: Profiling first prevents optimization of cold paths and helps teams target changes with measurable user impact.

### Top Categories

- `APIs`: 100
- `Architecture`: 100
- `Backend`: 100
- `CI/CD`: 100
- `Code Quality`: 100

### Recent Timeline

- `2026-07-13T09:04:09+08:00` | **Measure before tuning** (Performance)
- `2026-07-13T07:28:12+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-13T06:29:40+08:00` | **Retry only safe operations** (Networking)
- `2026-07-12T22:12:10+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-12T20:35:10+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-12T18:13:05+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-12T16:37:42+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-12T14:26:56+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-12T07:09:08+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-12T06:11:21+08:00` | **Optimize first contentful view** (Frontend)
