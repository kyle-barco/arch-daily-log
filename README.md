# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2861**
- Today's entries: **1**
- Today's note: `notes/2026-11-28.md`

### Latest Entry

- Timestamp: `2026-11-28T19:19:26+08:00`
- Title: **Rotate credentials on schedule**
- Category: `Security`
- Source: https://owasp.org/www-project-top-ten/
- Summary: Regular credential rotation limits blast radius if a secret leaks and encourages teams to maintain key management hygiene.

### Top Categories

- `Security`: 144
- `Testing`: 144
- `APIs`: 143
- `Accessibility`: 143
- `Architecture`: 143

### Recent Timeline

- `2026-11-28T19:19:26+08:00` | **Rotate credentials on schedule** (Security)
- `2026-11-27T19:55:40+08:00` | **Write one behavior per test** (Testing)
- `2026-11-27T10:59:52+08:00` | **Use virtual environments by default** (Python)
- `2026-11-26T19:28:34+08:00` | **Prefer small focused commits** (Git)
- `2026-11-26T10:33:53+08:00` | **Write decisions down** (Leadership)
- `2026-11-25T18:01:31+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-11-25T09:24:29+08:00` | **Measure before tuning** (Performance)
- `2026-11-24T13:58:04+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-11-24T06:00:51+08:00` | **Retry only safe operations** (Networking)
- `2026-11-23T18:02:07+08:00` | **Batch similar tasks** (Productivity)
