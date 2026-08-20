# Gemini Gem & AI Prompt Library

## Overview

In accordance with the UbD blueprint's mandate for **methodological transparency and prompting logic oversight**, this library archives evaluated interactions between students and generative AI systems (including the custom course Gemini Gem, Google AI Studio, and large language models).

Rather than viewing AI as an automated shortcut, entries here demonstrate rigorous editorial oversight: detecting hallucinations, assessing cognitive bias, and auditing the reliability of AI-generated synthesis.

---

## Evaluation Taxonomy

Every archived prompt exchange is tagged with an editorial outcome:

- `[ACCEPTED]` — The model output was independently verified as factually accurate and adopted.
- `[MODIFIED]` — The output contained useful structure but required substantial factual or stylistic correction by the student.
- `[REJECTED - HALLUCINATION]` — The model fabricated citations, misidentified dates, invented non-existent URLs, or produced false biographical details.
- `[REJECTED - BIAS/SYCOPHANCY]` — The model exhibited algorithmic bias, ideological drift, or uncritical agreement with leading prompts.

---

## Contribution Format

When submitting a prompt interaction to this library, use the following layout:

```markdown
# [Prompt Title / Task Context]

**Contributor:** [Your Name]  
**Tool / Model:** [e.g., Custom Course Gemini Gem / Gemini 1.5 Pro / Claude 3.5 Sonnet]  
**Editorial Verdict:** `[ACCEPTED]` / `[MODIFIED]` / `[REJECTED - HALLUCINATION]`  

### 1. The Prompt (Input)
```text
[Paste exact system prompt or user query provided to the AI]
```

### 2. The Model's Response (Output)
```text
[Paste raw response without student edits]
```

### 3. Critical Verification & Hallucination Audit
- **Fact-Check Vector 1:** How did you verify the primary claim?
- **Identified Errors / Hallucinations:** Detail any fabricated names, numbers, or facts.
- **Why this matters:** What risk would publishing this output unmodified have posed to the audience?
```
