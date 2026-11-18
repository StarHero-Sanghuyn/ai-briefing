# AI daily briefing

This is the personal AI briefing page. Shared agent rules and common skills are
maintained in `~/my-harness`; keep project-specific guidance in this file.

- `index.html` contains the page UI and client-side loading logic.
- `data/index.json` lists briefing dates, newest first.
- `data/<date>.json` contains the briefing loaded for that date.
- Preserve existing briefing files and the JSON shape consumed by the page.
- Before changing loading logic, inspect both the fetch code and a matching data
  file. Verify that dates in the index still resolve to valid JSON files.
- New project plans and task records belong in this project's `.agents/`, using
  the shared PM skills. Do not create a separate copy of the common PM engine.

`CLAUDE.md` links to this file so Claude and Codex use the same project guidance.
