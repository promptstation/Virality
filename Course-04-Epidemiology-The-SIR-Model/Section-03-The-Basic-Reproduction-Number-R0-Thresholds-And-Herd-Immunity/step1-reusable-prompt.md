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

# Filled Instance — Course 04 · Section 03

```
Generate a prompt on the task:

The Basic Reproduction Number R0: Thresholds and Herd Immunity — The single most important derived quantity. The section defines R0 = β/γ (the average number of new infections caused by one infected individual in a fully susceptible population), the threshold R0>1 (below it, the idea dies out; above it, it spreads), and the herd-immunity threshold 1 − 1/R0 (the fraction of the population that must be 'recovered' — uninterested or fatigued — for the spread to stall). It covers how to estimate R0 from real diffusion data (initial exponential growth rate, early-curve methods), how R0 differs for different content and platforms, and the strategic reading: what raising or lowering R0 means operationally.

Absorbed skills:
- Compute, interpret, and estimate R0 from diffusion data and state the threshold logic it implies
- Use the herd-immunity (saturation) threshold to reason about when and why a diffusion stalls

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
