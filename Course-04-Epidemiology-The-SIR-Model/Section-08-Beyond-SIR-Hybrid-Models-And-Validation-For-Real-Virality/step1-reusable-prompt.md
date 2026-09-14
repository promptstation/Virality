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

# Filled Instance — Course 04 · Section 08

```
Generate a prompt on the task:

Beyond SIR: Hybrid Models and Validation for Real Virality — The capstone: the models as they are actually used. The section covers the hybrid models of real virality work — SIR on an explicit network with platform-algorithm dynamics (the exogenous forcing term), the combination of the compartment model with the K-factor loop (the referral-driven reinfection) and with the recommendation-engine dynamics (the exposure allocation as a time-varying contact rate) — and the validation discipline: backtesting on past diffusions, the calibration set, the out-of-sample test, and the standing comparison of the model family against the simple baseline (the 'does the model beat the last quarter's curve extended linearly' test). It ends with the practitioner's judgment: when the model earns its complexity, and when the honest answer is a simpler one.

Absorbed skills:
- Build hybrid diffusion models that combine the compartment structure with network, loop, and platform dynamics
- Validate a model family by backtesting and calibration, and judge when a model earns its complexity

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
