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

# Filled Instance — Course 07 · Section 04

```
Generate a prompt on the task:

Content-Based and Hybrid Systems: The Features the Engine Reads — The other half of the engine: what the content itself says to the system. The section teaches content-based recommendation (the content's features — the topic, the format, the visual, the audio, the text — as the recommendation's input), the feature engineering for the modern platforms (the NLP of the caption and the transcript, the CV of the frame and the thumbnail, the audio's signature, the multimodal embedding that places the content in a shared space with the text), and the hybrid architectures (the collaborative core wrapped with the content features and the context — the modern stack's composition). It covers how the NLP and the CV courses connect here (the caption's topic is the recall's input, the thumbnail's quality is the ranking's signal), and the strategy's lever: the content's features are the part of the engine's input the creator fully controls.

Absorbed skills:
- Explain the content-based and hybrid architectures and the feature pipeline (NLP, CV, audio, the multimodal embedding) that feeds them
- Engineer the content's features deliberately — the metadata, the transcript, the thumbnail, the format — as the strategy's controlled input to the engine

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
