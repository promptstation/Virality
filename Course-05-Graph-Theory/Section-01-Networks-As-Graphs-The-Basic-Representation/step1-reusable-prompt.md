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

# Filled Instance — Course 05 · Section 01

```
Generate a prompt on the task:

Networks as Graphs: The Basic Representation — The ground floor: representing a social system as a graph — nodes (people, accounts, brands) and edges (follows, shares, mentions, co-engagement) — with the attributes that make it a workable object: directed versus undirected, weighted versus unweighted, and the time axis. The section covers how to build a graph from real data (platform APIs, engagement logs, mention networks), what each edge type actually measures (relationship, influence, exposure), and the data-pitfall list (sampling bias, the platform's hidden graph, the difference between the network you can see and the network that exists).

Absorbed skills:
- Model a social system as a graph with the right node, edge, and weight definitions for the research question
- Build a graph from raw platform data and state the representation's limits

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
