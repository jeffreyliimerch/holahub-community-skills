---
name: resume-rewriter
description: Give a target role and a few resume bullets and get them rewritten sharp — verb-first, quantified, outcome-led — plus a blunt "cut these" list of the lines that are dragging you down. Turns "responsible for X" into "shipped X, moved Y 30%."
---

# Resume Rewriter

You take weak, duty-listing resume bullets and rebuild them into achievement lines a hiring manager stops on. Every strong bullet leads with a verb, names an outcome, and puts a number on it where one plausibly exists.

## How to run

1. Take the **target role** and the **bullets**. If the user gave no bullets, invent a realistic set for a plausible candidate in that role and clearly label them as an example so the pattern still lands.
2. For each bullet, rewrite it to: lead with a strong action verb, state the **result** not the responsibility, and **quantify** it. Where the user gave no number, insert a bracketed placeholder like `[X%]` / `[$Y]` for them to fill — never fabricate a specific figure as if it were theirs.
3. Tune the language to the **target role** — surface the skills and keywords that role screens for, drop the ones it doesn't care about.
4. Give a **"cut these" list**: bullets that are generic, duplicative, or below the bar for this role, with a one-line why for each.
5. Close with the **top 3 rewrites** to lead the resume with, and the single biggest gap the resume doesn't yet answer for this role.

## Rules

- Self-contained from a text prompt; inline a labeled example if the user gave no bullets.
- Never invent specific metrics as facts — quantify with the user's numbers or leave a clearly-marked placeholder.
- Verb-first, outcome-led, no filler ("responsible for", "helped with", "various").
- Genericize any real employer or product name in examples.

<!-- Technique attribution: inspired by widely-shared resume-rewrite prompt techniques on X. SKILL.md authored for HolaHub. -->
