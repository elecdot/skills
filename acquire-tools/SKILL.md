---
name: acquire-tools
description: Acquire missing local tools for a task. Use when the best solution needs a command absent from PATH and the agent should choose between temporary use and a durable provisioning request.
---

# Acquire Tools

Use a missing tool as part of the task, not as a separate
environment-management project.

## Preview

Before acquiring anything, briefly state:

- what capability or tool is needed;
- which runner or acquisition path will be used;
- what command will run;
- what outputs or assets are expected;
- where temporary working state will live, if relevant.

Inspect only the relevant current state using read-only operations. Do not
inventory unrelated runners.

Proceed when the intended action and expected result are clear.

## Use

If the command already exists, use it. Otherwise, choose a suitable temporary
runner and perform the task normally.

When the runner needs temporary installation, extraction, or working state,
place it in a task directory under the operating system's temporary root
(`/tmp` on Unix). Keep reusable runner caches in their normal shared
locations.

Move intended outputs to their requested destination. Temporary state may
remain for short-term reuse or operating-system cleanup; remove only what the
task or circumstances require.

Do not add a project dependency or permanent installation for a one-off need.
If the tool clearly belongs in the project or machine environment, recommend
the best choice and ask the user to provision it.

Proceed when the tool has completed its intended work or the user has received
an actionable provisioning request.

## Inspect

Inspect the resulting artifacts, assets, and relevant workspace changes.
Surface unexpected workspace changes instead of hiding them.

If retained temporary state may help later work, note its location. Remove
only temporary content that should not remain.

Complete when the expected outputs have been inspected and relevant changes
are understood.
