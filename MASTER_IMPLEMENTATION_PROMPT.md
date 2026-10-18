# Master Implementation Prompt — Google AI Studio

Implement a private, unofficial website concept for VEYRO Studio to demonstrate to prospective client Duggu Renovation & Interior Contractor Greater Noida.

## Before editing
1. Inspect the existing repository, package manager, framework, styling, routing, and assets.
2. Read `PRD.md`, `BUSINESS_FACTS.md`, `CONTENT_BLUEPRINT.md`, `DESIGN_SYSTEM.md`, `ASSET_MANIFEST.md`, `TASKS.md`, and `QA_CHECKLIST.md`.
3. Preserve working code and dependencies where practical. Do not rewrite from scratch unless necessary.
4. If a conflict exists, choose the smallest safe change and explain it.

## Objective
Implement the complete agreed prototype, not just a plan. Prioritize visual quality, clarity, responsive behavior, working navigation, factual content, accessibility, and maintainability.

## Design
Modern Renovation Studio: warm ivory, charcoal, restrained bronze, soft sage, editorial serif headings, legible sans-serif body, architectural imagery, spacious layouts, restrained motion, clear CTAs. Avoid generic template styling, excessive gradients, and unnecessary animation.

## Accuracy and assets
- `BUSINESS_FACTS.md` is the source of truth.
- Do not invent services, areas, founder details, credentials, years of experience, warranties, prices, timelines, or guarantees.
- Do not invent testimonials or project histories.
- Never present stock/generated photos as Duggu's actual projects.
- Use licensed/illustrative local assets and label concept imagery.
- Do not scrape/reuse Google Maps photos or reviews without permission.
- Never imply official status or endorsement.

## Technical constraints
- Prefer existing React + TypeScript + Vite if present.
- No backend, database, authentication, payments, or remote form submission.
- Do not persist form data in localStorage/sessionStorage.
- Avoid unnecessary dependencies.
- Implement homepage and supporting pages/sections appropriate to existing architecture.
- All buttons/links must have meaningful behavior.
- Use semantic HTML, accessible labels, visible focus, keyboard navigation, and reduced-motion support.
- Add page metadata.
- Keep private prototype out of public indexing where supported.

## Form
Validate locally only. On submit show: “This is a concept demo. Your details have not been sent. Contact the business directly to discuss your project.”
No network requests, no persistence, no false success state.

## Work sequence
1. Inspect and plan briefly.
2. Implement design foundation and complete homepage.
3. Implement supporting pages or anchor sections.
4. Add interactions and metadata.
5. Run available build/lint/type checks and inspect likely responsive/accessibility issues.
6. Fix found issues.
7. Provide a concise report.

## Done means
Meet the QA checklist as far as testable. Do not claim a test passed unless actually run.

Report:
- Files changed.
- Pages/interactions implemented.
- Commands/tests run and actual outcomes.
- Remaining limitations and business facts requiring confirmation.
- How to run/preview locally.

Do not stop after planning; implement and QA within the available project context.
