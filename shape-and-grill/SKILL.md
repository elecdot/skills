---
name: shape-and-grill
description: Guide a discussion between problem exploration and scoped decision interviews. Use when the user needs both useful orientation and help working through choices, including when to move between them.
---

Coordinate exploration and decision interviews in the current conversation. Keep the same agent responsible for user dialogue. Read the linked skills directly when their work is needed; their exploration and interview methods stay at their sources.

## Follow the discussion's purpose

Let the user's current intent determine the scope and destination: useful orientation, a particular decision, or agreed choices ready for planning. Use the request and accepted decisions to establish that purpose; ask a focused question if an ambiguity would materially change the work.

Start with whichever work is useful now. An already understandable choice can go straight to an interview; an exploration can finish once the requested orientation is useful. Choose each next step from what the discussion needs.

## Carry one discussion state

Maintain a concise current understanding, accepted decisions, and unresolved matters across exploration and interviews. Keep one explicit **User-owned decisions** list, carrying forward the list from exploration when present. Each entry names the choice, its consequences, and any prerequisites. Explain recommendations with the assumptions or trade-offs they depend on.

An entry can await explanation, factual evidence, or the user's judgment. Make those dependencies visible. Listing a choice leaves it open; accepted answers become part of the current understanding and leave the open list.

Keep offering useful guidance as choices emerge. A focused question and a recommendation may resolve an item without a full interview. Use the same state throughout; an interview's design tree expresses dependencies among the choices in its task.

## Choose and scope the next work

**Explore:** Read and follow [shape-this-quiz](../shape-this-quiz/SKILL.md) when goals, paths, criteria, assumptions, or boundaries need exploration, or when the user needs to understand why a difference matters before choosing. Carry its outcome back into the ongoing discussion.

**Interview:** Read and follow [grilling](../grilling/SKILL.md) when a concrete, understandable choice benefits from working through dependent decisions in rounds and the user's intent includes resolving it. Before starting, briefly state the question to resolve, relevant accepted decisions and evidence, and what remains outside this task. That task is the root of grilling's design tree; its interview and confirmation rules apply within that scope.

Explain why the next work is useful without requiring the user to select or invoke a skill. If resolving the scoped question exposes an important dependency outside it, surface that dependency and reassess the scope before continuing.

## Revisit affected framing

If an answer or new evidence changes an important goal, option, assumption, or boundary, pause the interview and explain what changed and which choices it affects. Explore that part using shape-this-quiz. Keep unaffected accepted decisions settled; make the reason explicit when an accepted decision needs reconsideration.

Carry the updated understanding forward and restate the interview task when resuming. Handle ordinary factual lookups and small explanations within the current work. A pending fact remains an unsettled prerequisite, with dependent choices visibly waiting for it.

## Finish at the requested depth

After an exploration or interview completes its task, assess what the overall discussion still needs. Preserve grilling's requirement for the user's confirmation of shared understanding before treating its outcome as settled.

Finish when the requested orientation is useful, or when the user has accepted the choices needed for the current decision or next phase. Distinguish completion from a pause for evidence or user input. Keep consequential unresolved or deferred matters visible with their prerequisites and next useful step; their presence can coexist with completion of the current purpose.
