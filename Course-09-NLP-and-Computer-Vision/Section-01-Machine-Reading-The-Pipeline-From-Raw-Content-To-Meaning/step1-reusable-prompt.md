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

# Filled Instance — Course 09 · Section 01

```
Generate a prompt on the task:

Machine Reading: The Pipeline from Raw Content to Meaning — The ground floor: what the machine does with content. The section explains the machine-reading pipeline in its general form — the ingestion (the content's capture: the text, the transcript, the frame, the audio), the preprocessing (the tokenization, the normalization, the frame's sampling), the representation (the embedding — the content's vector in the learned space), and the task head (the classifier, the regressor, the generator that reads the representation) — and the two modalities' paths (the text's path through the transformer, the image's path through the convolution and the attention). It covers the model family (the pre-trained language model fine-tuned per task, the vision model the same way, and the multimodal model that places both in one space), the scale question (the platform's proprietary model versus the open model the team can run), and the honest frame: the pipeline is the standard, the model is the commodity, and the skill is the task's specification and the evaluation's honesty.

Absorbed skills:
- Describe the machine-reading pipeline — ingestion, preprocessing, representation, task head — across the text and the image paths
- Specify a reading task (the embedding's choice, the head's design, the fine-tuning's data) and frame the model's scale question honestly

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
