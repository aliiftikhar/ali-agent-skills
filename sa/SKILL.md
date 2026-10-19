---
name: sa
description: Give a short, direct answer (1–3 sentences). Use only when the user invokes /sa.
disable-model-invocation: true
argument-hint: <question>
---

# Short Answer

Applies only to the question asked with this invocation; return to your normal style afterwards.

- Lead with the answer. For yes/no questions, start with "Yes" or "No".
- Keep it to 1–3 sentences where possible.
- No introductions, restating the question, or closing summaries.
- If the answer is a command or snippet, give it in a code block with at most one line of context.
- Use bullets only when they make the answer clearer.
- Keep accuracy and important warnings; a warning can be one short line.
- If the question is ambiguous, answer the most likely reading instead of asking a clarifying question.
- Still read files or run checks when needed for accuracy; only the reply is short.
- Expand only if the question genuinely requires it.
