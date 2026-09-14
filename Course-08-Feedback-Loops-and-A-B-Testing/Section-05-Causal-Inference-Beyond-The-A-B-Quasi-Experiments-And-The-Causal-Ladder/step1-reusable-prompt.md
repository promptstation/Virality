# Step 1 — Reusable Prompt (Template)

Reusable prompt for the "section → learning-module prompt" task. The **task** is the section's Summary plus its Absorbed Skills, as produced by the research outline. Fill the placeholders, run it, and its output is the Step 2 prompt.

```
Generate a prompt on the task:

{SECTION_TITLE} — {SECTION_SUMMARY}

Absorbed skills:
- {ABSORBED_SKILL_1}
- {ABSORBED_SKILL_2}
- {ABSORBED_SKILL_3}
...

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```

---

# Filled Instance — Course 08 · Section 05

```
Generate a prompt on the task:

Causal Inference Beyond the A/B: Quasi-Experiments and the Causal Ladder — When the clean test is impossible. The section teaches the causal ladder (the association, the action, the counterfactual — the rungs, and what each rung's evidence permits the strategy to claim) and the quasi-experimental methods for the rungs above the clean A/B: the interrupted time series (the before-after across the event — the platform's change, the policy's shift), the difference-in-differences (the treated and the untreated across the event — the parallel-trends assumption, and its examination), the synthetic control (the constructed untreated from the comparators — the match, the counterfactual's path), and the instrumental variable (the instrument that moves the treatment without moving the outcome — the relevance, the exclusion). It covers the natural experiment (the event that assigns the treatment — the platform's rollout, the algorithm's change — and the read of its effect on the system), and the honest claims per method (what each one can say, what it cannot, and the assumption that carries the claim). It ends with the strategy's use: the causal question the business needs answered, the method per the question, the assumption's examination, and the claim's boundary stated.

Absorbed skills:
- Choose and apply the quasi-experimental method — the interrupted time series, the difference-in-differences, the synthetic control, the instrumental variable — with the assumption and the claim's boundary per method
- Read the natural experiment (the platform's change) as the causal evidence for the system, with the honest claim

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
