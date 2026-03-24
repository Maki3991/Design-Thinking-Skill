---
name: dt
description: Route Design Thinking questions to the right packaged lesson summaries and synthesize grounded answers. Use when the user asks about Design Thinking concepts, course structure, lesson routing, applying DT to products, projects, or life decisions, or wants answers based on this DT course pack rather than generic DT knowledge.
---

# DT

Use this skill to answer Design Thinking questions by routing to the right lesson references first, then synthesizing an answer from the packaged course materials.

## Core Workflow

1. Read `references/router.md` first.
   Use it as the top-level map of the course and the default routing table.

2. Classify the request into one or more DT stages.
   Use these buckets:
   - `intro/life-design`
   - `define`
   - `hmw/ideate`
   - `prototype`
   - `test/mvp`

3. Read the minimum relevant lesson files.
   Default mapping:
   - `intro/life-design` -> `references/lesson1-awakening.md`
   - `define` -> `references/define-problem.md`
   - `hmw/ideate` -> `references/hmw-ideate.md`
   - `prototype` -> `references/prototype.md`
   - `test/mvp` -> `references/test-mvp.md`

4. Combine references when the question crosses stages.
   Common combinations:
   - `understand self` -> lesson 1 + define
   - `POV to ideas` -> define + HMW/ideate
   - `idea to low-cost validation` -> HMW/ideate + prototype
   - `prototype vs MVP` -> prototype + test
   - `life design end-to-end` -> all stages in order

5. Answer from the packaged course framing first.
   If you add general DT knowledge beyond these files, label it as inference or generalization.

## Stage Heuristics

Use these quick cues when routing:

- `intro/life-design`
  - DT meaning, why DT matters, diverge/converge, grow zone, life design, understanding self, why迷茫 is normal

- `define`
  - root cause, pain point, empathy, interview, insight, POV, 5 whys, 5W1H, defining the real problem

- `hmw/ideate`
  - HMW, brainstorming, ideation, idea generation, idea filtering, when to diverge or converge

- `prototype`
  - prototype, CFP, CEP, funky prototype, dark horse, box prototype, vision prototype, low-cost validation

- `test/mvp`
  - test, MVP, minimum loop, A/B testing, iteration, validating willingness to pay, validating assumptions

## Answer Shape

Prefer this structure unless the user asks for something else:

1. State the current DT stage.
2. Explain the concept in plain language.
3. Map it to the user's context:
   - life decision
   - product/project
   - course understanding
4. Name the likely next stage when useful.
5. Cite the reference files used.

For broad questions, explicitly state:

- the user's current stage
- the most relevant lesson references
- the most practical next move

## Guardrails

- Do not skip directly to solutions when the request is still in `define`.
- Do not over-read; route first, then read selectively.
- Do not force a single-stage answer when the problem is clearly cross-stage.
- Do not present all lessons at once unless the user asks for an end-to-end overview.
- Distinguish clearly between direct course content and your own synthesis.

## Optional Workspace Enrichment

If the current workspace contains additional DT files, you may use them as supplements after reading the packaged references.

Typical supplemental filenames:

- `DT1 - Router.md`
- `Design thinking 1 - The Awakening.md`
- `DT2-4 - How to Define a Problem.md`
- `DT4 - From HMW to Ideate.md`
- `DT5-6 - Prototype.md.md`
- `DT7 - Test.md`

Packaged references remain the default source of truth for this skill.
