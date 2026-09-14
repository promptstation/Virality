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

# Filled Instance — Course 08 · Section 06

```
Generate a prompt on the task:

Bandits and Online Learning: Allocating the Traffic That Learns — When the experiment is the production. The section teaches the multi-armed bandit (the allocation across the arms — the variants, the hooks, the content types — that balances the exploitation of the known good and the exploration of the untested), the formal models (the UCB — the confidence bound as the exploration's purchase; the Thompson sampling — the posterior's draw as the allocation; the contextual bandit — the arm's choice per the context: the audience segment, the content type, the time), and the platform's version (the test-and-expand as the bandit at the content level, the exploration slice as the allocation's floor). It covers the regret (the loss to the optimal, the bandit's cost measure, and its bound), the cold start in the bandit (the new arm's prior, the content's seed), and the ethics of the allocation (the inferior arm's exposure, the audience's cost, and the guardrail's bound on the exploration). It ends with the bandit's strategy use: the allocation design for the creative's production (the variant's budget per the posterior), the exploration's floor (the new content's minimum, the diversity's protection), and the handoff to the guardrail (the bandit's metric versus the target's pairing).

Absorbed skills:
- Design the bandit allocation — the UCB, the Thompson sampling, the contextual version — for the creative's traffic, with the regret and the cold start handled
- Set the exploration's floor and the guardrail's bound on the exploration, as the ethics and the target's pairing of the allocation

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
