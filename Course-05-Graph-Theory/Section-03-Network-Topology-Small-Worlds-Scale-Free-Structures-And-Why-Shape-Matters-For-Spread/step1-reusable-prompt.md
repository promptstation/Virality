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

# Filled Instance — Course 05 · Section 03

```
Generate a prompt on the task:

Network Topology: Small Worlds, Scale-Free Structures, and Why Shape Matters for Spread — The shapes that real social networks have, and why the shape is a variable in the spread equation. The section covers the three canonical topologies — the random (Erdős–Rényi), the small-world (Watts–Strogatz: high clustering plus short paths), the scale-free (Barabási–Albert: preferential attachment, the power-law degree distribution, the hubs) — with the measurements that identify them (clustering coefficient, average path length, the degree-distribution fit) and the diffusion consequences of each: why hubs make spread explosive but fragile, why clusters trap content inside communities, and why the real network (a small-world with a heavy tail) is the case that matters.

Absorbed skills:
- Characterize a network's topology (clustering, path length, degree distribution) and classify it against the canonical models
- Predict the diffusion consequences of the topology — speed, reach, fragility — from the measured shape

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
