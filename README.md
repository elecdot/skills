# Personal SKILLs

> Skills currently use a flat directory structure. Some cross-skill references use relative paths (for example, in [shape-and-grill](/shape-and-grill/SKILL.md)). If the directory structure changes, these internal links must be updated and validated.

## Sources and inspiration

- [mattpocock/skills](https://github.com/mattpocock/skills)
    - `grilling`, `handoff`, `writing-great-skills`, `grill-with-docs`,
    `zoom-out`, `code-review`, `ask-matt`, `tdd`, `to-tickets`, `to-spec`,
    `improve-codebase-architecture`, `setup-matt-pocock-skills`, `triage`,
    `domain-modeling`, `codebase-design`, `implement`, `prototype`, `research`,
    `wayfinder`, `writing-for-agents`, `diagnosing-bugs`, `retro`
- [skills.sh](https://www.skills.sh/)
    - `find-skills`

Matt-derived skills are selectively maintained. Reliability fixes and the
`diagnosing-bugs` / `retro` additions were reviewed
against [upstream `5863806`](https://github.com/mattpocock/skills/commit/5863806dd4e15c63174bee4e7515a4256792ecfa)
on 2026-11-16. The `CONTEXT.md` / `CONTEXT-MAP.md` convention and local invocation
policies are retained. Existing projects refresh generated tracker docs as needed;
this update changes the skill sources and seed templates only.
`diagnosing-bugs` has a narrower automatic trigger for difficult debugging;
`retro` remains user-invoked and proposes improvements before implementation.

## Productivity

- [shape-and-grill](/shape-and-grill/SKILL.md): Guide a discussion between
problem exploration and scoped decision interviews, carrying shared
understanding and open choices across both without changing the base skills.
- [shape-this-quiz](/shape-this-quiz/SKILL.md): Build a shared understanding
of a problem, the paths worth considering, and why their differences matter
before detailed questioning, planning, or commitment.
- [grilling](/grilling/SKILL.md): Interview the user relentlessly about a plan,
decision, or idea until every branch of the design tree is resolved. The
reusable interview primitive behind `grill-me`, `grill-with-docs`, `triage`,
`wayfinder` and `improve-codebase-architecture`.
- [handoff](/handoff/SKILL.md): Compact the current conversation into a
handoff document so another agent can continue the work.
- [writing-great-skills](/writing-great-skills/SKILL.md): Reference for writing
and editing skills well: the vocabulary and principles that make a skill
predictable.
> This skill originally came from Matt's collection, but he replaced it with
> `writing-for-agents` in the v1.2 breaking change. I have kept my own version
> because it is better suited to writing and maintaining skills, and updated
> it with the advanced ideas from `writing-for-agents`.
- [writing-for-agents](/writing-for-agents/SKILL.md): Writing documents for
agents: skills, AGENTS.md/CLAUDE.md, and any doc an agent reaches by a pointer.
- [write-better-english](/write-better-english/SKILL.md): Turn settled ideas
in Chinese, English, or both into natural, context-appropriate English while
preserving meaning and voice.

## Engineering

**User-invoked**:

- [ask-matt](/ask-matt/SKILL.md): Ask which skill or flow fits your situation. A router over the user-invoked skills in this repo.
- [grill-with-docs](/grill-with-docs/SKILL.md): Grilling session that also
builds your project's domain model, sharpening terminology and updating
`CONTEXT.md` and ADRs inline.
- [setup-matt-pocock-skills](/setup-matt-pocock-skills/SKILL.md): Configure this repo for the engineering skills (issue tracker, triage labels, domain doc layout). Run once per repo before using the other engineering skills.
- [triage](/triage/SKILL.md): Move issues through a state machine of triage roles.
- [to-spec](/to-spec/SKILL.md): Turn the current conversation into a spec and publish it to the issue tracker. No interview, just synthesizes what you've already discussed.
- [to-tickets](/to-tickets/SKILL.md): Break any plan, spec, or conversation into a set of tracer-bullet tickets, each declaring its blocking edges, written as text in a local file, or as native blocking links on a real tracker.
- [implement](/implement/SKILL.md): Build the work described by a spec or set of tickets, driving `/tdd` at pre-agreed seams and closing out with `/code-review` before committing.
- [retro](/retro/SKILL.md): Review a coding session and suggest improvements to the agent's environment, using session evidence and listing candidates by severity.
- [wayfinder](/wayfinder/SKILL.md): Plan a huge chunk of work, more than one agent session can hold, as a shared map of decision tickets on the issue tracker, and resolve them one at a time until the way to the destination is clear.
- [improve-codebase-architecture](/improve-codebase-architecture/SKILL.md): Scan a codebase for deepening opportunities, present them as a visual HTML report, then grill through whichever one you pick.

**Model-invoked**:

- [acquire-tools](/acquire-tools/SKILL.md): Select suitable task tools,
isolate temporary state, and manage project dependency changes.
  Provisional: current behavioral benefit is unverified. Tool-selection bias
  may have diminished; direct manifest edits occurred, but dependency damage
  has not been observed. Reassess each branch against runs without this skill.
- [diagnosing-bugs](/diagnosing-bugs/SKILL.md): Diagnose difficult bugs and performance regressions through a tight reproduction loop, minimisation, falsifiable hypotheses, targeted instrumentation, and regression testing.
- [domain-modeling](/domain-modeling/SKILL.md): Actively build and sharpen a project's domain model: challenge terms against the glossary, stress-test with edge-case scenarios, and update `CONTEXT.md` and ADRs inline.
- [codebase-design](/codebase-design/SKILL.md): Shared discipline and vocabulary for designing deep modules: a lot of behaviour behind a small interface, placed at a clean seam, testable through that interface.
- [code-review](/code-review/SKILL.md): Two-axis review of the diff since a fixed point: **Standards** (does it follow the repo's coding standards, plus a Fowler smell baseline?) and **Spec** (does it faithfully implement the originating issue/spec?), run as parallel sub-agents so neither pollutes the other.
- [prototype](/prototype/SKILL.md): Build a throwaway prototype to answer a design question, either a single shareable HTML file for state/logic questions, or several radically different UI variations toggleable from one route.
- [research](/research/SKILL.md): Investigate a question against high-trust primary sources and capture the findings as a cited Markdown file in the repo, run as a background agent.
- [tdd](/tdd/SKILL.md): Test-driven development through a red-green loop at pre-agreed seams. Builds one vertical slice at a time, with refactoring during review.

## Deprecated

- [zoom-out](/zoom-out/SKILL.md): Tell the agent to zoom out and give broader
context or a higher-level perspective on an unfamiliar section of code.
