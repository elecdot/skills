---
name: shape-this-quiz
description: Reshape a problem before solving it. Use before grilling, planning, or committing when you want to inspect and learn the decision space first.
disable-model-invocation: true
---

**Shape the quiz; do not answer it yet.**

The user's request is a starting frame, not the boundary of the problem. Build a useful map of what should be considered before detailed questioning or execution begins.

Throughout shaping, investigate facts needed to establish the frame or identify its important dimensions, using available evidence and focused lookups. Defer research that only resolves the eventual choice. Where evidence remains unavailable, make the affected part of the map conditional. Update the frame, dimensions, and decision dependencies when findings change them.

## 1. Recover the intent

State briefly:

* what the user is currently asking;
* what underlying outcome they appear to be trying to achieve.

Keep uncertainty visible where these differ.

Complete this step when the apparent objective is clear enough to examine the framing around it.

## 2. Break the frame

Look outside the request's current structure.

Check whether it may have prematurely fixed:

* the option set;
* the objective;
* the evaluation criteria;
* the problem boundary;
* important assumptions;
* the level at which the decision is being made.

Consider alternative framings, including options outside any fixed set of choices in the request. Keep only those that could materially change what should be considered. If the original option space is already appropriate, say so.

Pay special attention to **unknown unknowns**: dimensions an informed practitioner would consider that are absent from the user's current mental model.

Complete this step when another plausible framing is unlikely to materially reshape the decision space.

## 3. Build the learning map

Lay out the important dimensions of the problem.

For each dimension, explain briefly why it exists or why it matters. Show important dependencies between dimensions when useful.

Distinguish:

**Core** — likely to affect the current decision.

**Context** — useful for understanding the domain but unlikely to change the immediate decision.

Avoid exhaustive taxonomy for its own sake. The map should improve the user's mental model, not maximize branch count.

Complete this step when the major high-impact dimensions are represented and additional branches would mostly add detail rather than reshape the problem.

## 4. Build the decision surface

From the broader learning map, identify what actually needs resolution before a decision or plan can be committed.

Classify unresolved items as:

**Facts** — discoverable from tools, environment, research, or evidence. These are the agent's responsibility to investigate.

**User-owned decisions** — preferences, values, goals, constraints, and trade-offs that require the user's authority.

**Assumptions** — currently relied-on beliefs that have not been established.

**Open uncertainties** — a temporary holding category for unresolved items whose importance is not yet known.

Show prerequisite relationships when one decision cannot be sensibly resolved before another.

Complete this step when each open uncertainty has been resolved, reclassified into one of the other categories, or dropped with a reason because it does not affect the current decision. If its relevance still needs evidence, carry that check forward as a Fact and state what it could change.

Do not begin the full interview yet.

## 5. Hand off

Finish with a compact **Problem Shape** containing:

### Working objective

The outcome currently being optimized.

### Core dimensions

The dimensions likely to change the decision.

### Important context

Dimensions worth learning but not currently decision-critical.

### Frame challenges

Material alternatives or assumptions the original request may have excluded.

### Facts to investigate

Deferred factual questions for the agent to investigate, each linked to the judgment it could change.

### User-owned decisions

Questions requiring the user's preferences or authority.

### Assumptions

Material premises currently being carried without confirmation.

### Suggested next phase

Usually one of:

* grill the unresolved decision surface;
* investigate facts first;
* proceed directly if the problem is already sufficiently specified.

Stop here. Do not silently choose the unresolved branches or execute the resulting plan.
