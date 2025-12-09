# Role–Task–Constraint Prompt Pattern

This pattern separates **who the AI is**, **what it must do**, and **what rules it must follow**.
It is the core building block of reliable prompt engineering.

---

## Example Prompt

ROLE:
You are a senior operations analyst assisting with process optimization.

TASK:
Analyze a manual inventory tracking workflow and identify inefficiencies.

CONSTRAINTS:

Do not introduce new tools or technologies

Focus only on process improvements

Limit recommendations to five items

Each recommendation must include a brief justification

OUTPUT FORMAT:

Numbered list

Bolded issue name

One-sentence explanation per item

SELF-CHECK:
Verify that all recommendations are practical
and do not exceed the stated constraints.

---

## Why This Pattern Works

- The **role** sets expectations and tone
- The **task** narrows scope and intent
- The **constraints** prevent overreach and hallucination
- The output format improves consistency
- The self-check reinforces reliability
