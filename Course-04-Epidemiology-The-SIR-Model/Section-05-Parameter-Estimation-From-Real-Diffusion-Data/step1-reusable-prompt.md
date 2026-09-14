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

# Filled Instance — Course 04 · Section 05

```
Generate a prompt on the task:

Parameter Estimation from Real Diffusion Data — Making the model touch reality. The section covers how to estimate β, γ (and the variant parameters) from real share/adoption/retweet curves: the data pipeline (collection, cleaning, denominators, censoring), the fitting methods (least squares on the curve, maximum likelihood on the event data, the early-window growth-rate method), model selection (AIC/BIC, cross-validation, holdout prediction), and the practical pathology list: platform API limits, survivorship bias, the difference between reach and adoption, and the measurement noise that masquerades as dynamics. It ends with a worked end-to-end fit on a real dataset.

Absorbed skills:
- Estimate SIR-family parameters from real diffusion data using an appropriate fitting method and honest uncertainty
- Run model selection and validation (AIC/BIC, holdout) and diagnose data pathologies before the fit

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
