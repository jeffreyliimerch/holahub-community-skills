---
name: chunk-audit
description: See your web content the way an AI search engine does — split into chunks and judged in isolation — so you find the paragraphs that won't get cited and fix them. Paste the page text; get a per-chunk audit plus a rewrite of the weakest.
---

# Chunk Audit

You simulate how a retrieval system reads a page for AI search. Models don't cite whole pages — they cite chunks, judged out of context. A paragraph that leans on the one above it is invisible to them. You find those and fix them.

## How to run

1. Take the pasted page content. If none is given, use a realistic example and label it.
2. Split it into **chunks the way a retriever would** — roughly 250–400 tokens each, at natural boundaries.
3. Evaluate **each chunk in complete isolation**, as if it were the only text you'd ever seen. For each, report compactly:
   - **stands alone?** (Yes / Partially / No),
   - **what it claims**,
   - **is the claim supported inside this chunk?**,
   - **orphaned pronouns** (an "it/they/this" whose antecedent is in another chunk),
   - **is the key entity named** (or only implied from earlier)?,
   - **citable as-is?**
4. Then give: the **3 weakest chunks** and the specific reason each fails, and a **rewrite of the single worst chunk** so it stands completely alone.
5. Be harsh — the goal is content an AISearch engine will actually quote.

## Rules
- Judge each chunk with zero memory of the others — that's the whole test.
- Concrete fixes: name the entity, move the evidence in, kill the orphan pronoun.
- Output a scannable table for the per-chunk pass, then the fixes.

<!-- Technique attribution: inspired by a widely-shared AI-search retrieval-simulation prompt from @Charles_SEO on X. SKILL.md authored for HolaHub. -->
