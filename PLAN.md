# Goal: Turn HTML Template Into a Faster-Converting Static Starter

## Design Thinking And Demand Background

- ICP: founders, consultants, and indie makers who need a clean landing page without app-level complexity.
- Core pain: many static starters explain sections but do not create desire, proof, or decision momentum.
- Desired outcome: a fast, reusable template that sells a clear promise in seconds and stays easy to customize.
- Product standard for this cycle: stronger conversion copy, tighter CTA flow, and safe public-ready static assets.

## Validators For This Cycle

- Reuse the validator registry from `AGENTS.md`.
- Selected validators: `@cro-copy-qa`, `@frontend-ui-qa`, `@interaction-state-qa`, `@responsive-accessibility-qa`, `@performance-seo-qa`, `@asset-integrity-qa`.

## Todo List

- [ ] Ideate a short, creative product name and replace `D1V DEMO` globally.
  - Owner: main agent
  - Verification: choose a final name, run `rg -n "D1V DEMO" .`, and confirm only intentional planning references remain
  - Status: pending
  - Evidence: pending
  - Notes: update header, metadata, pricing/product labels, and any other user-visible brand references together.

- [ ] Rewrite the original landing-page copy so it sells outcomes instead of sections. `@cro-copy-qa` `@frontend-ui-qa` `@responsive-accessibility-qa`
  - Owner: main agent
  - Verification: manual review of hero, proof, CTA, FAQ, and risk-reversal copy against the CRO-copy standard
  - Status: pending
  - Evidence: pending
  - Notes: use ICP + pain + desire, feature-to-benefit framing, and Promise / Proof / Push with short scannable CTA blocks.

- [ ] Verify static interactions and trust surfaces after the copy pass. `@interaction-state-qa` `@frontend-ui-qa` `@responsive-accessibility-qa`
  - Owner: main agent
  - Verification: local browser smoke review of CTA jumps, navigation, empty/error wording where relevant, and visible trust cues
  - Status: pending
  - Evidence: pending
  - Notes: there is no backend migration task in this template; focus on static interaction quality instead.

- [ ] Review metadata, performance discipline, and publication safety. `@performance-seo-qa` `@asset-integrity-qa`
  - Owner: main agent
  - Verification: metadata sanity review plus a check that no local-only files, broken links, or oversized hero assets are introduced
  - Status: pending
  - Evidence: pending
  - Notes: the template should remain lightweight and public-safe after this pass.
