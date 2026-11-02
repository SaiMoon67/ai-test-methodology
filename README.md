# AI Test Methodology

Status: draft, not yet public.

## What this is
An open methodology for comparing AI models on identical, verifiable tasks. Experiment 001 compares ChatGPT, Claude and Gemini on one task: building a single-file task manager in HTML, CSS and JavaScript.

## Why
Most AI comparisons rely on impressions. Here the prompt, the checklist and the scoring rules are published before any model is run, so the results can be checked by anyone.

## Important limits
- One run per model. This is a preliminary comparison, not proof of repeatable superiority.
- Results depend on the model version, plan and date, which are recorded for every attempt.
- Design is not scored, only functionality.

## Rules
- The methodology is not changed after testing starts. Any change is recorded separately with a date and a reason.
- Fixes are counted separately from checklist scores, and regressions are recorded.
- Full screen recordings and the generated code are kept.
- Every model gets a new chat with no memory and no custom instructions. Conditions for fixes are in PROMPT.md and CHECKLIST.md.
