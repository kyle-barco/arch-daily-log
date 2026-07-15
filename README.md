# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2015**
- Today's entries: **7**
- Today's note: `notes/2026-07-15.md`

### Latest Entry

- Timestamp: `2026-07-15T18:27:51+08:00`
- Title: **Measure before tuning**
- Category: `Performance`
- Source: https://perf.wiki/
- Summary: Profiling first prevents optimization of cold paths and helps teams target changes with measurable user impact.

### Top Categories

- `APIs`: 101
- `Architecture`: 101
- `Backend`: 101
- `CI/CD`: 101
- `Code Quality`: 101

### Recent Timeline

- `2026-07-15T18:27:51+08:00` | **Measure before tuning** (Performance)
- `2026-07-15T16:41:10+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-15T14:26:09+08:00` | **Retry only safe operations** (Networking)
- `2026-07-15T12:06:15+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-15T08:58:53+08:00` | **Keep runbooks close to code** (Documentation)
- `2026-07-15T07:31:46+08:00` | **Use exponential backoff with jitter** (Reliability)
- `2026-07-15T06:38:17+08:00` | **Name intent, not mechanics** (Code Quality)
- `2026-07-14T22:10:28+08:00` | **Automate rollback paths** (DevOps)
- `2026-07-14T20:00:59+08:00` | **Set realistic timeouts everywhere** (Backend)
- `2026-07-14T18:38:56+08:00` | **Optimize first contentful view** (Frontend)
