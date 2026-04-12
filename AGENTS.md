# Agent Guide (AGENTS.md)

These instructions apply to the entire `html-template` repository.

This template is intentionally minimal. Keep changes small, obvious, and safe for public distribution.

## Workflow

- For any non-trivial task, create or update a short written plan before editing.
- Track verification, current status, and residual risk in that plan.
- Do not mark work complete until the required verification has passed.

## Editing Rules

- Keep diffs focused. Avoid turning this template into a framework-specific starter unless explicitly requested.
- Prefer simple HTML, CSS, and minimal JavaScript.
- Do not add dependencies or build tooling unless explicitly requested.
- Prefer `rg` for search and read files in small chunks.

## Verification

- After code changes, verify the page renders and basic interactions still work.
- If no automated check exists, record the manual verification you performed.

## Security

- Do not commit `.env`, local caches, build output, or deployment metadata.
- Keep any demo content safe for public publication.

## Operational

- Do not run `git commit` or create branches unless explicitly asked.
- When unclear whether a change should stay generic or become business-specific, default to the more reusable template form.

---

中文提示（简要）：

- 这个模板应保持轻量，修改要小而明确。
- 非简单任务先写计划。
- 没有自动化测试时，要记录你做了什么手动验证。
