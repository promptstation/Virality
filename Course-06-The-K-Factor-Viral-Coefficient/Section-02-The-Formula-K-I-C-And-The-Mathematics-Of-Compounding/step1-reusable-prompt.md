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

# Filled Instance — Course 06 · Section 02

```
Generate a prompt on the task:

The Formula: k = i × c, and the Mathematics of Compounding — The core mathematics. The section defines the K-factor precisely — k = i × c, where i is the average number of invites sent per user and c is the conversion rate of an invite to a new user — and works the arithmetic: the per-cycle growth, the compound trajectory when k > 1 (the exponential), the trajectory when k < 1 (the convergence to a finite ceiling on the loop's contribution), and the time-to-scale at various k. It covers the recursion (the users at cycle t+1 from the users at cycle t), the distinction between the loop's contribution and total growth (the paid input at each cycle), and the sensitivity: how much c must move to push k across 1, and why the two factors are levers with different costs.

Absorbed skills:
- Compute the K-factor from i and c and model the growth trajectory it implies (the k>1 and the k<1 cases)
- Reason about the sensitivity of k to i and to c, and choose the lever from the cost structure

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
