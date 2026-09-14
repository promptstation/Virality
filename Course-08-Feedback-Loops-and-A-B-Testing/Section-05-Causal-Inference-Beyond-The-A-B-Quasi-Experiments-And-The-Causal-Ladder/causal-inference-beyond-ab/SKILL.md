---
name: causal-inference-beyond-ab
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Causal Inference Beyond the A/B: Quasi-Experiments and the Causal Ladder — how the causal question is answered when the clean test is impossible — the quasi-experimental methods, their assumptions, their claims, and the natural experiment as the evidence. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around causal inference, interrupted time series, difference-in-differences, synthetic control, instrumental variable, natural experiment, parallel trends, causal ladder, platform change impact. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of the platform changed the algorithm, and the team needs to know what it did to the reach — without the clean test, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: feedback-loops-ab-testing
---

# Causal Inference Beyond the A/B: Quasi-Experiments and the Causal Ladder: Professional Module Builder

## Mission

Produce professional-level material on how the causal question is answered when the clean test is impossible — the quasi-experimental methods, their assumptions, their claims, and the natural experiment as the evidence. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach the causal ladder: the first rung (the association — what co-moves with what), the second (the action — what happens when the variable is set), and the third (the counterfactual — what would have happened otherwise) — the rungs, and the discipline that the strategy's claim is bounded by the rung the evidence supports (the association's evidence does not carry the counterfactual's claim).
2. Teach the interrupted time series: the before-after across the event (the platform's change, the policy's shift), the level and the trend (the step and the slope, per the pre-period's pattern), and the assumption (the pre-period's trend is the counterfactual's trend — the no-other-change examination, the concurrent events' naming) — the ITS as the first quasi-method, and its claim's boundary (the effect since the event, given the trend held).
3. Teach the difference-in-differences: the treated and the untreated across the event, the parallel-trends assumption (the two groups' pre-period trends are the counterfactual's evidence), and the examination (the pre-trend's plot, the placebo's test — the event's date shifted, the effect's absence) — the DiD as the treated's effect from the untreated's path, and its claim's boundary (the effect on the treated, given the trends were parallel).
4. Teach the synthetic control: the constructed untreated (the comparators' weighted match to the treated's pre-period), the counterfactual's path (the synthetic's post-period), and the inference (the permutation test — the treated's gap versus the comparators' gaps, the rank as the significance) — the synthetic as the counterfactual's construction, and its claim's boundary (the effect on the treated, given the comparators' pool and the match).
5. Teach the instrumental variable: the instrument (the variable that moves the treatment without moving the outcome — the relevance and the exclusion), the local effect (the compliers' effect, not the population's), and the read (the first stage, the second stage, the excluded-variance bound) — the IV as the endogeneity's cure, and its claim's boundary (the compliers' effect, given the instrument's validity).
6. Teach the natural experiment: the event that assigns the treatment (the platform's rollout, the algorithm's change — the assignment that is not the strategy's, and the read that is the strategy's), the design per the event (the ITS for the single system, the DiD for the treated and the untouched, the synthetic for the comparators' pool), and the honest claim (the event's effect on the system, with the assumption stated and the concurrent events named) — the natural experiment as the evidence the platform's change gives, and the strategy's read of it.

## Phase 3 — Method and Technique

- The causal question spec: the claim the business needs, the rung required, the method per the question
- The ITS design: the pre-period, the event, the post-period, the concurrent events' examination
- The DiD design: the treated, the untreated, the pre-trend's plot, the placebo's test
- The synthetic design: the comparators' pool, the match, the permutation test
- The IV design: the instrument, the first stage, the exclusion's argument, the bound
- The claim statement: the effect, the assumption, the boundary — per method, the honest read

## Phase 4 — Analysis and Diagnosis

- Diagnose the invalid causal claim in the history: the before-after without the concurrent events' examination (the ITS's breach), the DiD without the parallel trends (the assumption's breach), the synthetic with the weak comparators (the match's breach) — the method's failure, and the re-design or the claim's downgrade.
- Read the natural experiment's event: the platform's change (the rollout, the algorithm's shift) — the method per the event's structure (the single system, the treated and the untouched, the comparators' pool), and the claim's boundary.
- Check the assumption's examination: the pre-trend's plot present, the placebo's test run, the match's quality reported — the assumption's evidence, and the claim's strength per it.
- Separate the effect from the concurrent: the platform's change and the season and the competitor in the same window — the decomposition, or the claim's bound to the window's joint effect.

## Phase 5 — Application and Design

- Spec the causal question before the method: the claim the business needs, the rung required, the method per the question — the spec that keeps the method's choice from serving the answer's hope.
- Design the quasi-experiment with the assumption's examination in the plan: the pre-trend's plot, the placebo's test, the concurrent events' list — the examination before the event, not after the result.
- Read the natural experiment as it arrives: the event's structure, the method per the structure, the claim with the assumption stated — the platform's change as the evidence, read on the standing discipline.
- State the claim's boundary in the deliverable: the effect, the assumption, the method, the bound — the honest read as the standard of the deliverable, with the rung the claim sits on.

## Phase 6 — Ethics and Boundary Conditions

- The quasi-experiment reads the system's behavior under the event; the event's assignment (the platform's rollout) is not the consented experiment, and the read's use (the strategy's adaptation) is bounded by the claim's honesty — the adaptation to a read that overstates is the strategy's drift.
- The IV's instrument and the synthetic's comparators are constructed from the data's structure; the construction's choices (the instrument's relevance, the comparators' pool) are the analyst's, and the claim inherits them — the construction's record is part of the deliverable.
- The natural experiment's effect is the system's change under the platform's decision; the strategy's response (the content's adaptation, the portfolio's rebalance) is the organization's choice, and its cost (the audience's exposure to the adapted content) is the response's price — the line is the claim's honesty, and the response's care.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Write the causal question spec for a business need: the claim required, the rung, the method per the question — with the alternative methods considered and rejected.
2. Design the ITS for a platform change: the pre-period, the event, the post-period, the concurrent events' list, and the claim's boundary — with the level and the trend's read.
3. Design the DiD for a rolled-out feature: the treated, the untreated, the pre-trend's plot, the placebo's test — with the parallel-trends' examination shown.
4. Design the synthetic control for a market-level event: the comparators' pool, the match, the permutation test — with the rank and the claim.
5. Run the natural experiment read on a platform's algorithm change: the event's structure, the method chosen, the effect, the assumption stated, the concurrent events named — with the strategy's response and its line.
6. Write the causal deliverable template: the question, the method, the design, the assumption's examination, the effect, the boundary — as the standing standard, with the review's checklist.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Question spec
- The claim and the rung are stated
- The method is per the question
- The alternatives are considered

### Design
- The pre-period is sufficient
- The assumption's examination is in the plan
- The concurrent events are listed

### Read
- The effect is per the method
- The assumption's evidence is shown
- The boundary is stated

### Delivery gate
- The claim's rung is named in the deliverable
- The construction's record is present
- The response's line is stated

## Anti-Patterns

the before-after as the counterfactual; the DiD without the pre-trend; the synthetic with the weak pool; the IV without the exclusion's argument; the concurrent events unexamined; the claim past its rung.

## Decision Heuristic

Before any claim or recommendation, ask:

1. What claim does the business need, and which rung does the evidence support?
2. Is the assumption examined before the event, or argued after the result?
3. Are the concurrent events named, and does the claim bound itself to the window's joint effect?
4. What does the method's construction (the comparators, the instrument) rest on, and is it recorded?
5. Does the deliverable state the boundary, or only the effect?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not the causal proof. It is the causal read that names its rung, examines its assumption, and states its boundary — so the strategy adapts to what the evidence says, and only to what it says.
