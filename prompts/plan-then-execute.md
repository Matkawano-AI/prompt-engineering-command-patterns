# Plan → Execute Prompt Pattern

This pattern separates **reasoning** from **execution** to
improve accuracy, clarity, and reliability.

The model is instructed to first think about *how* to solve the task
before producing the final output.

---

## Example Prompt

PHASE 1 — PLANNING:
Analyze the task and outline a step-by-step plan.
Do not produce the final answer yet.

PHASE 2 — EXECUTION:
Using the approved plan, complete the task.

ROLE:
You are an AI assistant helping improve an operational workflow.

TASK:
Identify inefficiencies in a manual reporting process
and suggest improvements.

CONSTRAINTS:

Planning must be a numbered list

Execution must follow the plan exactly

Limit total output to 300 words

Avoid introducing new tools

OUTPUT FORMAT:

Section: Plan

Section: Execution

VALIDATION:
Confirm that execution strictly follows the plan.

---

## Why This Pattern Works

- Reduces reasoning errors
- Prevents rushed or incomplete answers
- Makes outputs auditable
- Enables human-in-the-loop review
