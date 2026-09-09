# westland-issues

Public **issues-only** tracker for Westland Construction skills, MCP tools, and workflows.

Code lives in other repos (`westland-mcps`, `construction-skills`, etc.). This repo is the shared backlog so reports are visible, linkable, and easy to triage.

## How to report

Most people report from Claude via the Westland bug-report skill / MCP (no GitHub account required). A bot opens the issue and the chat gets the issue URL back.

You can also open an issue here in the GitHub UI if you have a GitHub account.

## Labels (type)

Every issue should get **one type label**:

| Label | Use for |
|---|---|
| `bug` | Something broken / wrong output / error |
| `feat` | Feature request / capability gap |
| `friction` | Confusing UX, missing docs, awkward flow |
| `docs` | Documentation-only fix |
| optional severity | `severity:low` · `severity:medium` · `severity:high` · `severity:critical` |

## Body conventions

Bot-filed issues include:

```text
Reporter: <local-part>
```

(local-part of `@westlandconstruction.com` only — public repo.)

**Do not** put proprietary customer data, pricing, or unnecessary PII in titles or bodies.

## Status

MCP + skill rewrite and Supabase migration are tracked in the design issue on this repo.
