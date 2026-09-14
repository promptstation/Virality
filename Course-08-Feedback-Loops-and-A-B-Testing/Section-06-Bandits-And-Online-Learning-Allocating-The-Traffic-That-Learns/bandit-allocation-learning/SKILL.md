---
name: bandit-allocation-learning
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Bandits and Online Learning: Allocating the Traffic That Learns — how the allocation learns — the bandit models, the regret, the cold start, and the floor and the bound that keep the learning honest. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around multi-armed bandit, UCB, Thompson sampling, contextual bandit, exploration exploitation, regret, test and expand, allocation learning, content seeding. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of the traffic is finite and the variants are many — how much of the audience's time goes to the known good, and how much buys the next one, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: feedback-loops-ab-testing
---

# Bandits and Online Learning: Allocating the Traffic That Learns: Professional Module Builder

## Mission

Produce professional-level material on how the allocation learns — the bandit models, the regret, the cold start, and the floor and the bound that keep the learning honest. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

Optimize simultaneously for:

- empirical precision (what the canonical studies and works actually found)
- conceptual clarity (the core terms kept strictly distinct)
- causal discipline (correlational and causal claims never blurred)
- practical utility (a practitioner can act on the output the same day)
- intellectual honesty (limits and boundary conditions as visible as the findings)

Do not produce generic advice or pop-science hype. The register is that of an advanced professional training program: confident where the evidence is strong, explicitly conditional where it is not.

## Use Cases

### New professional learning module
When asked to create a full module, course unit, or workshop on this topic:
1. Establish scope: audience, depth, and which claims the module must cover.
2. Build the evidence base from primary sources and canonical works.
3. Develop the core mechanisms and diagnostic logic.
4. Add method, critique, and application sections.
5. End with exercises and the delivery checklists.
6. Deliver the complete artifact with no placeholders.

### Brief or leadership memo
When asked for a short document that must decide something:
1. State the question the document must answer in one sentence.
2. Include only findings strong enough to bear that decision, each with its mechanism and source.
3. Convert results into plain-language implications.
4. End with the specific decisions the evidence changes.
5. Cap length; cut context before cutting caveats.

### Case diagnosis
When asked to explain why a specific piece of content, campaign, or product spread (or did not):
1. Identify the operative mechanisms — never a single assumed cause.
2. Map the case onto the diagnostic framework of this skill.
3. Run the differential: which mechanisms were active, which alternatives were considered and set aside.
4. State confidence and the evidence that would revise the diagnosis.

### Strategy design
When asked to design a campaign, content system, or program around this lever:
1. Fix the objective, audience, and platform context.
2. Select the mechanisms from this skill that fit that context.
3. Specify implementation, sequencing, and the measurement plan.
4. State the boundary conditions under which the plan breaks.

## Core Output Requirements

Regardless of format:

- Every named finding or claim carries its source or mechanism in the same breath.
- Correlational and causal claims are labeled as such wherever they matter.
- Effect claims carry their metric and a plain-language rendering.
- Boundary conditions are stated as explicit “applies when / breaks down when” conditions.
- Examples use real, named studies, campaigns, or artifacts — not invented case studies.
- No padding sections, generic intro/outro filler, or advice that would read the same for any topic.

## Phase 1 — Scope and Claim Audit

### Artifact and audience
What the user actually needs (module vs. memo vs. diagnosis) and who reads it. Different readers make different cuts of the same material.

### Claim inventory
List the claims the artifact will make. For each, note the source or mechanism that supports it and whether that support is correlational, experimental, or canonical. Downgrade or cut unsupported claims — not the caveat.

### Depth budget
Match length to the decision the artifact serves. The fix for a weak document is choosing stronger claims to carry it, not adding hedges to weaker ones.

## Phase 2 — Foundations and Core Content

1. Teach the bandit problem: the arms (the variants, the hooks, the content types — the choices with the unknown reward), the allocation (the traffic's split across the arms, per the learned state), and the balance (the exploitation of the current best, the exploration of the untested — the information's purchase per unit of the exposure) — the problem, and its distinction from the A/B (the fixed allocation, the final call) — the bandit is the continuous allocation, the A/B is the one-shot decision.
2. Teach the UCB: the confidence bound (the arm's reward estimate plus the uncertainty's width — the exploration's purchase priced by the doubt), the allocation (the arm with the highest bound gets the traffic), and the behavior (the uncertain arm's early traffic, the known arm's dominance as the certainty grows) — the UCB as the exploration's optimistic pricing.
3. Teach the Thompson sampling: the posterior (the arm's reward distribution, updated per the outcome), the draw (the allocation from the drawn value — the probability of the best as the traffic's share), and the behavior (the stochastic allocation, the self-limiting exploration) — the Thompson as the exploration's probabilistic pricing, and its practical edge (the simplicity, the calibration).
4. Teach the contextual bandit: the context (the audience segment, the content type, the time — the state the arm's choice is conditioned on), the model (the reward per the arm and the context — the linear, the tree, the neural per the context's richness), and the read (the per-context allocation, the winner per the segment) — the contextual as the bandit's refinement, and its cost (the model's complexity, the context's data need).
5. Teach the regret and the cold start: the regret (the loss to the optimal arm's reward over the horizon — the bandit's cost, its bound per the model, and the read as the learning's efficiency), and the cold start (the new arm's prior — the content's seed, the metadata's input to the posterior, the exploration's floor for the new) — the regret as the measure, the cold start as the new arm's entry.
6. Teach the platform's version and the ethics: the test-and-expand as the bandit at the content level (the seed, the read, the expansion — the allocation across the content's states), the exploration slice as the floor (the minimum traffic the untested gets — the diversity's protection), and the ethics (the inferior arm's exposure is the audience's cost — the guardrail's bound on the exploration: the harm's cap, the duration's limit, the consent's design) — the platform's bandit, and the line that the allocation respects.

## Phase 3 — Method and Technique

- The bandit design doc: the arms, the reward, the context, the model, the floor, the guardrail — the allocation's contract
- The UCB and the Thompson implementations: the parameters, the update rule, the allocation per the state
- The contextual model: the context's features, the reward model, the per-context read
- The regret computation: the bound, the realized, the learning's efficiency per the horizon
- The cold-start spec: the new arm's prior, the seed, the floor — the new content's entry

## Phase 4 — Analysis and Diagnosis

- Diagnose the allocation's state: the exploration's excess (the traffic on the known-inferior — the bound's miscalibration, the prior's optimism) and the exploration's deficit (the untested starved — the floor's absence, the certainty's premature) — the state per the data, and the parameter's fix.
- Read the regret's trend: the regret's decay (the learning's convergence) versus the regret's plateau (the model's limit, the context's absence) — the learning's state, and the model's upgrade decision.
- Check the contextual read's honesty: the per-context winner's stability (the winner that flips per the noise — the context's overfit) — the context's signal versus its noise, and the model's simplification.
- Audit the ethics' state: the inferior arm's exposure over the horizon (the audience's cost accumulated), the floor's respect (the new arm's minimum), the guardrail's bound (the harm's cap held) — the allocation's line, examined.

## Phase 5 — Application and Design

- Design the bandit for the creative's production: the arms per the element (the hook variants, the content types), the reward per the target (the paired metric, not the proxy alone), the context per the segment — the design doc with the floor and the guardrail in the contract.
- Run the allocation with the regret watched: the bound, the realized, the convergence — the learning's efficiency as the standing read, with the model's upgrade on the plateau.
- Manage the cold start as the entry: the new arm's prior from the metadata and the seed, the floor for the new, the context's input — the new content's entry, designed.
- Hold the ethics as the bound: the inferior exposure's cap, the duration's limit, the consent's design — the line per the guardrail, with the review per the horizon.

## Phase 6 — Ethics and Boundary Conditions

- The bandit allocates the audience's attention across the arms; the inferior arm's exposure is the attention spent on the weaker — the cap on the exposure is the audience's protection, and the floor on the exploration is the diversity's protection, both stated in the contract.
- The bandit's learning is the audience's model at the allocation's resolution; the model's use (the per-segment winner, the per-context allocation) is the personalization's engine, and its honesty (the context's fairness, the segment's definition) is the line at the use.
- The regret is the cost of the learning, paid by the audience's time; the bound is the cost's promise, and the realized is the cost's record — both stated, and the learning's value (the winner found) against them, the allocation's honest account.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Design the bandit for the hook variants: the arms, the reward, the context, the model, the floor, the guardrail — with the UCB and the Thompson parameters.
2. Implement and compare the UCB and the Thompson on a dataset: the allocation per the state, the regret per the horizon, the convergence — with the read per the model.
3. Design the contextual bandit for the per-segment allocation: the context's features, the reward model, the per-context read — with the overfit's check.
4. Run the cold-start spec for the new content: the prior from the metadata, the seed, the floor — with the new arm's entry tracked over the horizon.
5. Audit the allocation's ethics over a horizon: the inferior exposure's total, the floor's respect, the guardrail's bound — with the line's examination and the correction.
6. Write the bandit governance: the design doc's approval, the regret's watch, the floor's and the bound's review, the model's upgrade rule — as the standing policy, with the owner.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Design
- The arms and the reward are per the target
- The context is per the segment
- The floor and the guardrail are in the contract

### Models
- The UCB and the Thompson are implemented
- The contextual model is per the context's richness
- The overfit is checked

### Learning
- The regret is computed per the horizon
- The convergence is read
- The model's upgrade is on the plateau

### Delivery gate
- The cold start is designed for the new
- The ethics' audit ran
- The governance is live

## Anti-Patterns

the 50/50 as the exploration; the winner-take-all before the certainty; the reward on the proxy alone; the context without the overfit's check; the new arm without the floor; the inferior exposure uncapped; the regret unwatched.

## Decision Heuristic

Before any claim or recommendation, ask:

1. What are the arms, and is the reward the target, paired with the proxy?
2. Is the exploration priced — the bound, the posterior — or is it the fixed split?
3. What does the regret say about the learning's state, and is the model's upgrade due?
4. Does the new arm have its prior, its seed, and its floor?
5. Is the inferior exposure capped, and is the cap held over the horizon?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not the optimal allocation. It is the allocation that learns — the exploration priced, the regret watched, the new arm entered, and the exposure capped — so the traffic's time is spent on the finding, and the finding is worth the time.
