---
name: shape-and-grill
description: Coordinate exploration and scoped grilling when the user needs both orientation and help working through decisions.
---

Keep the same agent responsible for dialogue. Read the linked skills directly as needed; let the user's current intent set the discussion's scope and depth.

- **Choose the work.** Follow [shape-this-quiz](../shape-this-quiz/SKILL.md) for framing and understanding consequences; follow [grilling](../grilling/SKILL.md) when an understandable choice needs dependent questions in rounds. Start with whichever is useful.

- **Scope the interview.** Briefly state the question to resolve, relevant accepted decisions and evidence, and what remains outside this task. This task defines grilling's design tree.

- **Carry one discussion state.** Reuse the current understanding, accepted decisions, and a single **User-owned decisions** list across both kinds of work. Surface choices with conditional recommendations as they emerge; a focused question may resolve one without a full interview.

- **Manage transitions and completion.** When an important premise changes, pause, explain what changed, and explore the affected framing. Keep unaffected decisions settled and update the task before resuming. After either task completes, assess what the discussion still needs. Finish at the requested depth, leaving unresolved or deferred choices and evidence prerequisites visible.
