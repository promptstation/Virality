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

# Filled Instance — Course 07 · Section 03

```
Generate a prompt on the task:

Collaborative Filtering: The Engine's Core Inference — The classic engine, and the intuition behind the modern one. The section teaches collaborative filtering from first principles: the user-item interaction matrix, the user-user and the item-item similarity (the 'people like you liked' and the 'items like this were liked' inferences), the matrix factorization (the latent factors that explain the interactions, the low-rank approximation, the training), and the cold start (the new user, the new item — the problem that the content features and the social graph solve). It covers the classical cases (the Netflix prize, the Amazon's 'customers who bought'), the failure modes (the popularity bias, the filter bubble's seed, the staleness of the taste model), and the honest frame for the strategy: the collaborative core is still the engine's heart, wrapped in the features and the context that the modern stack adds.

Absorbed skills:
- Explain and implement the collaborative-filtering core — the similarities, the factorization, the cold start — and read its outputs as the engine's taste model
- Diagnose the collaborative core's failure modes (popularity bias, staleness, the cold start) in a platform's behavior

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
