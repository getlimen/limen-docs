# CLAUDE.md — limen-docs (documentation site)

> **Project**: limen-docs — component of [Limen](https://github.com/getlimen/limen)
> **Role**: Public documentation site. **Skeleton only in v1 — full content in v1.1+.**

**For full project context, read [`limen/docs/HANDOFF.md`](https://github.com/getlimen/limen/blob/main/docs/HANDOFF.md) and [`limen/docs/CONVENTIONS.md`](https://github.com/getlimen/limen/blob/main/docs/CONVENTIONS.md).**

## Workflow rules (enforced, apply to every repo in `getlimen`)

- **Never work on `main`.** Create issue (labeled) → branch `<type>/<issue>_<PascalCaseName>` → PR (labeled) with `Closes #<issue>` → squash-merge + delete branch.
- **Use CLI generators whenever one exists** (`gh`, site-builder scaffolders, etc.). If you don't know the command, search online before hand-writing boilerplate.
- **No AI / Claude attribution** in commits or PRs.

## Planned

- **Stack**: Astro Starlight
- **Hosted at**: GitHub Pages under `limen.dev` or `getlimen.github.io`
- **Content**:
  - Quickstart (install via docker compose, enroll first node, add first service)
  - Architecture overview (repurposed from design spec)
  - Per-component reference (limen, ostiarius, forculus, limentinus)
  - Operations (backup/restore, upgrades, troubleshooting)
  - API reference (OpenAPI generated from Limen.API)

## Conventions

Same as `limen`: English-only, Apache 2.0, conventional commits, **no AI attribution in commits**.
