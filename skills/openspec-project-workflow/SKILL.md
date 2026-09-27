---
name: openspec-project-workflow
description: Inspect, plan, implement, validate, and hand off repository work using OpenSpec. Use when a project benefits from traceable proposals, implementation tasks, or acceptance evidence.
---

# OpenSpec project workflow

Use this skill when OpenSpec can make repository work easier to review or continue. Keep the work grounded in the repository's current state and the user's requested scope.

## Establish the current state

- Confirm the workspace, repository, branch, and working-tree state before relying on folder names or earlier notes.
- Read applicable repository instructions and the current handoff or work log. For multi-repository work, inspect each repository independently and identify its role and remote.
- Inspect relevant code and existing OpenSpec changes. Treat plans and handoffs as context; current code and explicit user direction determine what is true now.
- For a read-only review, inspect and report only. Do not edit, implement, deploy, or imply that checks were run.

## Plan with OpenSpec

- Find active changes before creating a new one. Continue a matching change instead of duplicating it.
- Ground proposals in observed workflows and code. State the problem, intended behavior, affected areas, acceptance criteria, and open questions; distinguish confirmed facts from assumptions.
- Keep the scope bounded. Preserve existing data and workflows unless the user asks to change them. Do not introduce migrations, seeds, or formal-data writes without a concrete requirement and a verified target.

## Implement and hand off

- Implement only when the user asks for implementation or the request clearly includes it. Follow repository conventions and applicable OpenSpec instructions.
- Verify the affected behavior at a scope appropriate to the change. Report the commands and outcomes accurately, and distinguish local checks from authenticated or production checks.
- Update OpenSpec tasks and project handoff records when the repository uses them. Record completed work, evidence, remaining acceptance, Git state, and a concrete next step.
- Do not commit, push, or deploy unless the user requests that action or an applicable standing instruction authorizes it. Treat each as a separate action with its own authorization.