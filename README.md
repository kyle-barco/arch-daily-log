# Daily Knowledge Repo MVP

Automated knowledge maintenance repository. It appends practical daily notes and keeps metadata fresh.

## AI Trend Source

- Optional daily live trend fetch uses Gemini API with Google Search grounding.
- Set `GEMINI_API_KEY` as a GitHub Actions secret to enable one daily `Tech Trends` entry.
- Without API key, the repo falls back to local `data/knowledge_pool.json` entries.

## Dashboard

- Total archive entries: **2701**
- Today's entries: **3**
- Today's note: `notes/2026-09-30.md`

### Latest Entry

- Timestamp: `2026-09-30T16:29:08+08:00`
- Title: **Rotate credentials on schedule**
- Category: `Security`
- Source: https://owasp.org/www-project-top-ten/
- Summary: Regular credential rotation limits blast radius if a secret leaks and encourages teams to maintain key management hygiene.

### Top Categories

- `Security`: 136
- `Testing`: 136
- `APIs`: 135
- `Accessibility`: 135
- `Architecture`: 135

### Recent Timeline

- `2026-09-30T16:29:08+08:00` | **Rotate credentials on schedule** (Security)
- `2026-09-30T10:05:02+08:00` | **Write one behavior per test** (Testing)
- `2026-09-30T07:03:51+08:00` | **Use virtual environments by default** (Python)
- `2026-09-29T22:02:09+08:00` | **Prefer small focused commits** (Git)
- `2026-09-29T15:08:06+08:00` | **Write decisions down** (Leadership)
- `2026-09-29T09:15:22+08:00` | **Keyboard support is a baseline** (Accessibility)
- `2026-09-28T15:37:27+08:00` | **Measure before tuning** (Performance)
- `2026-09-28T09:38:16+08:00` | **Fail fast on lint and tests** (CI/CD)
- `2026-09-28T07:11:32+08:00` | **Retry only safe operations** (Networking)
- `2026-09-27T21:10:53+08:00` | **Batch similar tasks** (Productivity)
