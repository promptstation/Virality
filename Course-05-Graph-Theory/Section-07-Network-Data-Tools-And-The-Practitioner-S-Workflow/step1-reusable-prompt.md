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

# Filled Instance — Course 05 · Section 07

```
Generate a prompt on the task:

Network Data, Tools, and the Practitioner's Workflow — The hands-on layer: building and analyzing networks end to end. The section covers the toolchain (the standard network libraries and their graph metrics, the visualization layer, the statistical software for the fits), the data workflow in practice (the recurring pulls, the versioning of the graph, the update cadence), the scale problems (the million-node graph, the sampling strategies, the approximate metrics), and the data-quality discipline (the edge validation, the bot handling, the time alignment). It closes with the practitioner's deliverables: the network report (the shape, the hubs, the communities, the cascade read), the living dashboard (the metrics that track over time), and the reuse pattern (the next campaign starts from the versioned graph, not from zero).

Absorbed skills:
- Run the end-to-end network workflow — pulls, versioning, metrics, visualization, reporting — at the scale of real social data
- Maintain a living network dashboard and version the graph so each campaign inherits the last one's state

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
