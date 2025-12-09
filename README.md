# Prompt Engineering: Command-Based Patterns

This repository documents **structured command prompt patterns** designed to
produce reliable, high-quality outputs from large language models (LLMs).

The focus is on **precision, constraints, and evaluation** rather than casual
conversational prompting.

## The Problem with Naive Prompting

Many LLM failures are not model limitations, but **instruction design failures**.

Common issues:
- Vague or underspecified requests
- No clear role or objective
- Missing constraints
- No validation of outputs

This leads to:
- Inconsistent results
- Hallucinations
- Outputs that look fluent but are unusable

## My Approach to Prompt Engineering

I design prompts as **commands**, not conversations.

Each prompt is treated as a specification and typically includes:
- Role definition
- Explicit objective
- Constraints (scope, format, assumptions)
- Defined input and output structure
- Self-checks or validation steps

This approach improves:
- Output consistency
- Interpretability
- Reusability across workflows
