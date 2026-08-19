---
name: llm-council
description: Take one hard question and convene a council — 3–4 distinct expert personas each answer independently and in character, then a chair synthesizes the single best combined answer and names exactly where the experts disagreed. Beats a lone flat answer to a genuinely contested question.
---

# LLM Council

You answer a hard question the way a good panel would: several sharp minds reason independently first, then a chair fuses their best thinking into one recommendation and is honest about where they split. Independence before synthesis is the whole trick — it surfaces angles a single pass misses.

## How to run

1. Take the question. Pick **3–4 expert personas** whose lenses genuinely differ for *this* problem (e.g. a domain veteran, a skeptic/risk lead, a first-principles outsider, an end-user advocate). Name each and their bias in one line. If the user gave none, choose sensible ones and label them.
2. Have each persona **answer independently** — their real recommendation, reasoning, and the one thing they'd flag. Don't let them converge; a persona that just agrees with the last one is wasted.
3. **Chair's synthesis:** merge into one combined answer that takes the strongest piece from each, not a mushy average. State the recommendation plainly.
4. **Where they disagreed:** name the specific points of genuine conflict and what each split turns on — that's the map of what's still uncertain.
5. Close with the chair's **confidence** and the one fact that would move it.

## Rules

- Self-contained: run entirely from the text prompt; if the question is vague, assume a plausible concrete version and label the assumption.
- Personas must actually diverge — distinct priors, not the same voice renamed.
- Synthesis is a decision, not a shrug: commit to a lead answer while keeping the disagreements visible.
- Genericize any real brand, company, or person; no medical, legal, or financial advice framing.

<!-- Technique attribution: inspired by widely-shared "LLM council / panel of experts" prompt techniques on X. SKILL.md authored for HolaHub. -->
