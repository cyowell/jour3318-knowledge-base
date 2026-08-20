# Gemini Gem & AI Prompt Library

> [!IMPORTANT]
> ### 🛑 Reading this on GitBook?
> **GitBook is read-only.** You cannot upload prompt histories or edit files directly on this website.  
> To document your AI interactions or submit a prompt critique, you must **switch to GitHub**:  
> 👉 **[Click here to open the JOUR 3318 GitHub Repository →](https://github.com/cyowell/jour3318-knowledge-base)**

---

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

## 🛠️ How to Submit to the Prompt Library on GitHub

1. Copy the prompt, raw model response, and your hallucination critique from your personal `PROMPTS.md`.
2. Fork the [JOUR 3318 Knowledge Base on GitHub](https://github.com/cyowell/jour3318-knowledge-base).
3. Create your file: `prompts-library/[prompt-topic]-[your-name].md`.
4. Fill out the layout below and open a Pull Request targeting `main`.

---

## Contribution Format

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
