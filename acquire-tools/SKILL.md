---
name: acquire-tools
description: Choose better-suited tools when current tooling limits result quality, acquire task tools, or change project dependencies. Excludes routine execution of existing commands.
---

# Acquire Tools

## Tool choice

Choose tools for the task's quality requirements, considering tools available
through acquisition when the current approach limits the result. Prefer the
environment's established runners and package managers for acquisition, and
briefly explain the expected improvement.

## Temporary tools

Use temporary acquisition for one-off tools. Keep installations, extracted
files, and working state in a task directory under the system's temporary root
(`/tmp` on Unix). Keep reusable runner caches in their normal locations and
deliverables at their requested destination.

## Project dependencies

Add a project dependency when it belongs to the project's ongoing workflow.
Use the project's package-manager CLI for supported dependency operations;
let the manager generate lockfiles. Inspect manifest and lockfile diffs,
keep changes scoped to the task, and summarize the dependency changes.
