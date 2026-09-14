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

# Filled Instance — Course 08 · Section 03

```
Generate a prompt on the task:

A/B Testing Fundamentals: The Design That Makes the Call — The instrument's foundations. The section teaches the A/B test in its rigorous form — the hypothesis (the null and the alternative, the direction, the effect of interest), the unit (the unit of randomization: the user, the content, the impression — and the contamination between units), the sample (the size from the effect, the variance, the power, the duration), the assignment (the randomization, the holdout, the segmentation), and the read (the difference, the confidence interval, the significance, and the multiple-comparisons problem when the test has many metrics or many arms). It covers the classic errors in order of damage: the peeking (the early stop on the significance that inflates the false positive), the underpower (the sample too small for the effect of interest), the novelty (the effect that is the newness, not the change), the interference (the units that affect each other's outcomes), and the metric-gaming (the variant that wins on the tested metric and loses on the untested). It ends with the test's decision: the ship, the reject, the extend — with the pre-registered rule, not the read's convenience.

Absorbed skills:
- Design an A/B test that makes the call — the hypothesis, the unit, the sample, the assignment, the read — with the classic errors named and avoided
- Apply the decision rule (the ship, the reject, the extend) pre-registered, with the multiple-metric and the novelty handling

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
