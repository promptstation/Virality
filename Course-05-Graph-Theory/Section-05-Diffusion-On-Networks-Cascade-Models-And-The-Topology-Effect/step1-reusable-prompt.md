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

# Filled Instance — Course 05 · Section 05

```
Generate a prompt on the task:

Diffusion on Networks: Cascade Models and the Topology Effect — How the spread actually runs on the graph. The section teaches the two canonical diffusion processes — the independent cascade (each edge has a transmission probability, the exposure trials are independent) and the linear threshold model (each node activates when the fraction of active neighbors crosses its threshold, the social-reinforcement logic) — with the derivations, the parameter meanings, and the simulations. It covers the topology effects: how the same process runs differently on a hub-rich graph versus a clustered graph, the role of the clusters (the ignition vs. the sustain) and the bridges (the crossing), and the percolation intuition (the subcritical vs. supercritical regime on a network). It closes with the calibration: estimating the process parameters from observed spread data on a real network.

Absorbed skills:
- Simulate and interpret the independent cascade and linear threshold models on real network topologies
- Explain and predict the topology effects on cascade speed and reach, and calibrate the process parameters from data

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
