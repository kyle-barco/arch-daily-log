# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2000**
- Today's entries: **1**
- Today's note: `notes/2026-07-14.md`

### Latest Entry

- Timestamp: `2026-07-14T06:36:05+08:00`
- Title: **Write one behavior per test**
- Category: `Testing`
- Source: https://martinfowler.com/bliki/UnitTest.html
- Summary: Single-purpose tests fail with clearer intent and reduce time spent diagnosing what actually regressed.

### Top Categories

- `Testing`: 101
- `APIs`: 100
- `Accessibility`: 100
- `Architecture`: 100
- `Backend`: 100

### Recent Timeline

- `2026-07-14T06:36:05+08:00` | **Write one behavior per test** (Testing)
- `2026-07-13T21:13:49+08:00` | **Use virtual environments by default** (Python)
- `2026-07-13T18:51:52+08:00` | **Prefer small focused commits** (Git)
- `2026-07-13T15:54:43+08:00` | **Write decisions down** (Leadership)
- `2026-07-13T12:44:14+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-07-13T09:04:09+08:00` | **Measure before tuning** (Performance)
- `2026-07-13T07:28:12+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-07-13T06:29:40+08:00` | **Retry only safe operations** (Networking)
- `2026-07-12T22:12:10+08:00` | **Batch similar tasks** (Productivity)
- `2026-07-12T20:35:10+08:00` | **Keep runbooks close to code** (Documentation)
