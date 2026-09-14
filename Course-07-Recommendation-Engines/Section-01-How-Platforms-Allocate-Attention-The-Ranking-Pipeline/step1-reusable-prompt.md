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

# Filled Instance — Course 07 · Section 01

```
Generate a prompt on the task:

How Platforms Allocate Attention: The Ranking Pipeline — The ground floor: the machine behind the feed. The section explains the ranking pipeline as it is generally understood — the candidate generation (the recall stage that narrows the universe of possible content to a manageable set), the ranking (the model that scores and orders the candidates for this user, this moment), and the impression (the final selection with the diversity, the freshness, and the policy filters) — and the objective the pipeline optimizes (the predicted user value, the engagement the user is expected to produce, in the platform's chosen definition). It covers what is known versus inferred (the platforms' documented signals, the academic reconstructions, the creator-community evidence), and the honest frame: the engine is a black box with a documented perimeter, and the strategy is built on the perimeter.

Absorbed skills:
- Describe the ranking pipeline (recall, ranking, impression) and the objective it optimizes, with the known versus inferred clearly separated
- Build a strategy on the engine's documented perimeter rather than on speculation about its internals

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
