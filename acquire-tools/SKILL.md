---
name: acquire-tools
description: Choose better-suited tools when current tooling limits result quality, acquire task tools, or change project dependencies.
---

# Acquire Tools

Before material persistent changes, make their purpose and scope clear to the
user. Proceed within existing task authorization; seek confirmation when a
change exceeds that scope or requires a new user decision. Report the resulting
changes and any unexpected differences.

## Tool choice

Choose tools for the task's quality requirements, considering tools available
through acquisition when the current approach limits the result. Prefer the
environment's established runners and package managers for acquisition, and
briefly explain the expected improvement.

## Temporary tools

Use temporary acquisition for one-off tools. Keep installations, extracted
files, and working state in a task directory under the platform-configured
temporary directory (e.g. `$TMPDIR` on Unix, with `/tmp` as a fallback;
`%TEMP%` on Windows). Keep reusable runner caches in their normal locations
and deliverables at their requested destination.

## Project dependencies

Add a project dependency when it belongs to the project's ongoing workflow.
Prefer the project's package-manager CLI for supported dependency operations;
let the manager generate lockfiles. Inspect manifest and lockfile diffs and
keep dependency changes scoped to the task.
