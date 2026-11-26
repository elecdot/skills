---
name: shape-and-grill
description: Coordinate exploration and scoped grilling when the user needs both orientation and help working through decisions.
disable-model-invocation: true
---

Keep one agent responsible for the user-facing dialogue. Read the linked skills directly as needed; let the user's current intent set the discussion's scope and depth.

- **Guide the discussion.** Use [shape-this-quiz](../shape-this-quiz/SKILL.md) to clarify the problem, its scope, and why the alternatives matter. Ask in the same turn when the user has enough context to answer and their judgment or firsthand knowledge would move the discussion forward. Use [grilling](../grilling/SKILL.md) rounds when later questions depend on earlier answers.

- **Scope the interview.** For a multi-round interview, root the design tree in the question the discussion has established. Briefly state the current scope, relevant evidence, and accepted decisions. If an inferred limit would change which questions you ask, give the user room to redraw it before pursuing that branch.

- **Carry one discussion state.** Reuse the current understanding and accepted decisions. Keep consequential unresolved choices visible, with conditional recommendations. Use one **User-owned decisions** list when multiple rounds or a handoff make it useful.

- **Manage transitions and completion.** When an important premise changes, explain what changed and revisit the affected framing. Keep unaffected decisions settled and update the task before resuming. Let the user's purpose determine whether to continue, switch focus, or finish. If you leave an interview early, say where it paused. Leave open or deferred choices and their prerequisites visible.
