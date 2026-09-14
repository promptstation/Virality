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

# Filled Instance — Course 04 · Section 02

```
Generate a prompt on the task:

The SIR Equations: The Core Model — The mathematics of the core model. The section derives and interprets the three compartment equations: dS/dt = −βSI/N, dI/dt = βSI/N − γI, dR/dt = γI, with β (effective contact rate) and γ (recovery rate) as the two parameters that determine everything. It covers the shape of the trajectory — the epidemic curve: slow start, exponential growth, the peak, the long tail to the final size — the meaning of each region, and the conservation S+I+R=N. It ends with a hands-on simulation: solving the system numerically and reading the curves.

Absorbed skills:
- Write down, derive, and interpret the SIR equations and their parameters
- Simulate SIR trajectories and read the epidemic curve's regions (takeoff, peak, tail, final size)

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
