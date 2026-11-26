---
name: shape-and-grill
description: Coordinate exploration and scoped grilling when the user needs both orientation and help working through decisions.
disable-model-invocation: true
---

Keep the same agent responsible for dialogue. Read the linked skills directly as needed; let the user's current intent set the discussion's scope and depth.

- **Choose the work.** Follow [shape-this-quiz](../shape-this-quiz/SKILL.md) for framing and understanding consequences; follow [grilling](../grilling/SKILL.md) when an understandable choice needs dependent questions in rounds. Start with whichever is useful.

- **Scope the interview.** Root the design tree in the question the discussion has established. Briefly state the current scope, relevant evidence, and accepted decisions. If an inferred limit would change which questions you ask, give the user room to redraw it before pursuing that branch.

- **Carry one discussion state.** Reuse the current understanding and accepted decisions. Keep consequential unresolved choices visible, with conditional recommendations. Use one **User-owned decisions** list when multiple rounds or a handoff make it useful; a focused question can settle a simple choice.

- **Manage transitions and completion.** When an important premise changes, pause, explain what changed, and explore the affected framing. Keep unaffected decisions settled and update the task before resuming. After shaping or grilling, let the user's current purpose determine whether to finish or pursue an open question. Finish at the requested depth, leaving unresolved or deferred choices and evidence prerequisites visible.
