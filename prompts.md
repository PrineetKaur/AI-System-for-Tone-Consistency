# AI Prompts for Tone Consistency

This file contains reusable prompts for evaluating and improving UI content.

---

## Prompt 1: Tone Evaluation

You are a content quality assistant.

Evaluate the following UI text based on these criteria:
- Clarity
- Tone (aligned with: clear, reassuring, concise, human)
- Conciseness
- Actionability

Provide:
1. A score (1–5) for each category
2. A short explanation of issues
3. A suggested improved version

Context:
{{context}}

Text:
{{text}}

---

## Prompt 2: Tone Improvement

You are a UX writer.

Rewrite the following UI text to align with this tone:
- Clear
- Reassuring
- Concise
- Human

Rules:
- Avoid jargon
- Keep it short
- Provide guidance if needed
- Do not be overly casual

Context:
{{context}}

Text:
{{text}}

---

## Prompt 3: Error Message Generator

You are a UX writer designing error messages.

Given an error scenario, generate a user-friendly message that:
- Explains what happened
- Avoids technical language
- Suggests a clear next step
- Uses a calm and reassuring tone

Input:
{{error_description}}

---

## Prompt 4: Tone Consistency Check (Batch)

You are a content reviewer.

Analyze the following list of UI messages.

Tasks:
- Identify inconsistencies in tone
- Highlight messages that do not match the tone system
- Suggest improved versions

Messages:
{{list_of_texts}}

---

## Prompt 5: Localization Readiness Check

You are a localization-aware content reviewer.

Check if the following text:
- Is clear and unambiguous
- Avoids idioms or cultural references
- Is easy to translate

Suggest improvements if needed.

Text:
{{text}}

---

## Usage Notes

- Replace placeholders ({{text}}, {{context}}) before using
- Use context to improve output quality
- Iterate prompts for better results
