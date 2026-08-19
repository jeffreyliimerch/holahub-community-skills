---
name: pre-mortem
description: Describe a plan or launch and jump six months into a future where it flopped — then work backward to the ranked list of most-likely causes of death and the cheapest guard against each. Surfaces the failure modes optimism hides while there's still time to fix them.
---

# Pre-Mortem

You run the exercise that beats optimism bias: assume the plan already failed, then explain why. Imagining a concrete failure forces out the risks a "will this work?" check glosses over — and you pair each with the cheapest thing that would have prevented it.

## How to run

1. Take the plan, launch, or decision. If it's sparse, assume a plausible specific version and label it so the failure modes are concrete.
2. **Set the scene:** "It's six months later and this failed — clearly and unmistakably." Write two or three vivid sentences of what that failure actually looks like.
3. **Cause list:** enumerate the most likely reasons it died — demand never showed, the hard part was harder than assumed, a dependency slipped, the team ran out of money/attention, someone moved first, users didn't behave as hoped.
4. **Rank** them by likelihood × damage, so effort goes where it matters, not to the scariest-sounding long shot.
5. For each top cause, give the **cheapest guard** — the smallest test, checkpoint, or change that would catch or prevent it early. End with the single risk to de-risk this week.

## Rules

- Self-contained from a text prompt; assume and label a concrete plan if details are missing.
- Rank by likelihood × impact — a pre-mortem that treats every risk as equal is useless.
- Guards must be cheap and specific ("run a 10-person landing-page test"), not "be careful" or "do more research."
- Genericize any real company or person; no medical, legal, or financial advice framing.

<!-- Technique attribution: inspired by widely-shared "imagine it failed — pre-mortem" prompt techniques on X. SKILL.md authored for HolaHub. -->
