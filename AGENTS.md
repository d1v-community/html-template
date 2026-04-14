# Agent Guide (AGENTS.md)

Use this file as the execution contract for work in this template.

## Planning First

- Every non-trivial task must start by pruning stale or already-compressed completed noise from `PLAN.md`, then writing the current goal, background, selected validators, and todo list before editing.
- `PLAN.md` is the source of truth for scope, order, verification, evidence, and residual risk.
- Keep at most one todo `in_progress` per execution thread unless work was intentionally delegated in parallel.

## Checkoff Rule

- Do not check off a todo until its assigned validators have passed and the evidence is written into `PLAN.md`.
- If verification fails, keep the todo open, record the failure, and add the corrective next step.
- Never mark work done based on implementation alone.

## Minimum Verification Before Checkoff

- `@frontend-ui-qa`: before checking off a UI or interaction todo, the touched surface must have intentional loading, empty, and error messaging where relevant, and the visual quality must fit the target audience.
- `@cro-copy-qa`: before checking off a copy todo, rewrite against the CRO-copy standard: ICP + pain + desire, feature-to-benefit framing, and Promise / Proof / Push with short, scannable CTAs.

## Validator Registry

- `@frontend-ui-qa`: page structure, CTA hierarchy, interaction quality, visual states
- `@cro-copy-qa`: headline, proof, CTA, risk-reversal, benefit-first copy
- `@interaction-state-qa`: static interactions, anchor jumps, lightweight forms, empty/error messaging
- `@responsive-accessibility-qa`: desktop/mobile layout, readability, contrast, keyboard reachability
- `@performance-seo-qa`: metadata, above-the-fold clarity, asset discipline, scanability
- `@asset-integrity-qa`: safe public assets, no broken links, no accidental local-only files

## Working Rules

- Keep diffs focused. Avoid turning this template into a framework-heavy starter unless explicitly requested.
- Prefer plain HTML, CSS, and minimal JavaScript.
- Do not add dependencies or build tooling unless explicitly requested.
- Do not hardcode secrets or commit `.env`, caches, build output, or deployment metadata.
- Prefer `rg` for search and read files in small chunks.

## Handoff Format

- Each validator handoff must include `Result`, `Checked`, `Passed`, `Failed`, `Not checked`, `Risk`, and `Plan update`.
