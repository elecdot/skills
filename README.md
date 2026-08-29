---
last-updated: 2026-08-29
---

# Personal SKILLs

## Resources / Inspired by

- [mattpocock/skills](https://github.com/mattpocock/skills)
    - `grilling`, `handoff`, `writing-great-skills`, `grill-with-docs`, 
    `zoom-out`, `code-review`, `ask-matt`, `tdd`, `to-tickets`, `to-spec`,
    `improve-codebase-architecture`, `setup-matt-pocock-skills`, `triage`,
    `domain-modeling`, `codebase-design`, `implement`, `prototype`, `research`,
    `wayfinder`, `writing-for-agents`
- [skills.sh](https://www.skills.sh/)
    - `find-skills`

## Productivity

- [grilling](/grilling/SKILL.md) - Get relentlessly interviewed about a plan 
or design until every branch of the decision tree is resolved.
- [handoff](/handoff/SKILL.md) — Compact the current conversation into a 
handoff document so another agent can continue the work.
- [writing-great-skills](/writing-great-skills/SKILL.md) — Reference for writing
and editing skills well: the vocabulary and principles that make a skill
predictable.
- [writing-for-agents](/writing-for-agents/SKILL.md) — Write predictable skills,
agent instructions, and documents reached through agent context pointers.
- [write-better-english](/write-better-english/SKILL.md) — Turn settled ideas
in Chinese, English, or both into natural, context-appropriate English while
preserving meaning and voice.

## Engineering

**User-invoked**:

- [ask-matt](/ask-matt/SKILL.md) — Ask which skill or flow fits your situation. A router over the user-invoked skills in this repo.
- [grill-with-docs](/grill-with-docs/SKILL.md) - Grilling session that 
challenges your plan against the existing domain model, sharpens terminology,
and updates `CONTEXT.md` and ADRs inline.
- [setup-matt-pocock-skills](/setup-matt-pocock-skills/SKILL.md) — Configure this repo for the engineering skills: issue tracker, triage labels, and domain docs layout.
- [triage](/triage/SKILL.md) — Move issues and external PRs through a state machine of triage roles, verify claims, and write agent-ready briefs.
- [to-spec](/to-spec/SKILL.md) - Turn the current conversation into a spec and publish it to the issue tracker. No interview, just synthesizes what you've already discussed.
- [to-tickets](/to-tickets/SKILL.md) - Break any plan, spec, or conversation into a set of tracer-bullet tickets, each declaring its blocking edges, written as text in a local file, or as native blocking links on a real tracker.
- [implement](/implement/SKILL.md) — Implement a spec or ticket with TDD, regular checks, and a final code review.
- [wayfinder](/wayfinder/SKILL.md) — Map a multi-session effort as decision tickets and resolve them until the route to the destination is clear.
- [improve-codebase-architecture](/improve-codebase-architecture/SKILL.md) — Scan a codebase for deepening opportunities, present them as a visual HTML report, then grill through whichever one you pick.

**Model-invoked**:

- [acquire-tools](/acquire-tools/SKILL.md) — Preview a missing-tool plan, use
an appropriate runner, and inspect the resulting artifacts and assets.
- [domain-modeling](/domain-modeling/SKILL.md) - Actively build and sharpen a project's domain model — challenge terms against the glossary, stress-test with edge-case scenarios, and update `CONTEXT.md` and ADRs inline.
- [codebase-design](/codebase-design/SKILL.md) — Shared vocabulary and principles for deep modules, clean seams, and testable interfaces.
- [code-review](/code-review/SKILL.md) — Two-axis review of the diff since a fixed point: Standards (does it follow the repo's coding standards, plus a Fowler smell baseline?) and Spec (does it faithfully implement the originating issue/spec?), run as parallel sub-agents so neither pollutes the other.
- [prototype](/prototype/SKILL.md) — Build a throwaway logic or UI prototype to answer one design question.
- [research](/research/SKILL.md) — Delegate primary-source research to a background agent and save cited findings in the repo.
- [tdd](/tdd/SKILL.md) — Test-driven development guidance for red → green tracer-bullet loops with behavior-first seams and durable tests.

## Deprecated

- [zoom-out](/zoom-out/SKILL.md) - Tell the agent to zoom out and give broader 
context or a higher-level perspective on an unfamiliar section of code.
