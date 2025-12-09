# Self-Check / Validation Prompt Pattern

This pattern instructs the model to **verify its own output** against
explicit criteria before finalizing the response.

It is essential for reducing hallucinations and enforcing constraints.

---

## Example Prompt

ROLE:
You are an AI assistant providing procedural guidance.

TASK:
Explain how to implement a consistent daily reporting workflow.

CONSTRAINTS:

No more than 5 steps

Steps must be actionable

Avoid vague language

Do not assume specialized tools

OUTPUT FORMAT:

Numbered list

One sentence per step

SELF-CHECK:
Before finalizing, verify that:

All steps are actionable

No constraints are violated

Language is precise and unambiguous

If any issue is found, revise the output before responding.

---

## Why This Pattern Works

- Forces the model to re-evaluate its output
- Reduces over-confident but incorrect responses
- Increases trust in AI-generated results
