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

# Filled Instance — Course 09 · Section 07

```
Generate a prompt on the task:

Evaluation, Robustness, and the Failure Modes of Machine Reading — The reading's honesty in depth. The section covers the evaluation's design (the metric per the task — the accuracy's limits, the precision-recall per the class's balance, the calibration per the confidence, the faithfulness per the generation; the test set's honesty — the unseen, the out-of-distribution, the temporal holdout; the human's evaluation — the annotation's agreement, the task's rubric), the robustness (the input's perturbation — the paraphrase, the noise, the adversarial example; the model's drift — the data's change, the concept's change; the deployment's monitoring — the performance's trend, the drift's detection), and the failure modes catalog (the systematic error per the group — the bias; the confabulation per the generation — the hallucination; the overconfidence per the calibration — the sureness without the accuracy; the manipulation per the input — the prompt's and the adversarial's attack). It covers the defense per the mode (the bias's audit and the correction, the hallucination's grounding and the citation, the calibration's measurement and the abstention, the attack's detection and the input's validation), and the evaluation's culture (the failure's record, the correction's feed, the model's version and the evaluation's standing). It ends with the standard: the reading system that reports its error, its drift, its boundary — the honesty as the system's quality, not its afterthought.

Absorbed skills:
- Design the evaluation and the robustness test for a reading system — the metric per the task, the honest test set, the perturbation, the drift monitor — with the failure modes cataloged
- Apply the defense per the mode — the bias's audit, the grounding, the calibration, the input's validation — and run the evaluation as the standing culture

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
