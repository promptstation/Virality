---
name: sir-hybrid-validation
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Beyond SIR: Hybrid Models and Validation for Real Virality — how the compartment model is actually deployed — hybridized with network, loop, and platform dynamics — and validated by backtesting against the baselines that matter. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around hybrid diffusion models, model validation, backtesting, calibration, platform algorithm dynamics, K-factor SIR combination, model complexity judgment. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of whether the sophisticated model actually beats the simple baseline on this data, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: sir-epidemiology
---

# Beyond SIR: Hybrid Models and Validation for Real Virality: Professional Module Builder

## Mission

Produce professional-level material on how the compartment model is actually deployed — hybridized with network, loop, and platform dynamics — and validated by backtesting against the baselines that matter. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach the hybrid architecture: the compartment structure (the states) on an explicit network (the contacts) with an exogenous forcing term (the platform's exposure allocation, time-varying) — the three layers, and where each of the course's other mechanics enters (K-factor as the loop layer, recommendation dynamics as the forcing layer).
2. Cover the K-factor combination: the referral loop as a structured reinfection channel — the invited cohort returns to the susceptible pool with a known probability, and the loop's k enters the model as an edge type, not a fudge factor.
3. Cover the recommendation-engine forcing: the platform allocates exposure by engagement velocity, which is a function of the current I — the feedback between the diffusion and the allocator, and the instability it can create (the amplification loop).
4. Teach the validation discipline: the calibration set (past diffusions used to estimate the structural parameters), the backtest (predict the held-out diffusions), and the baseline test (the model must beat the naive extension of the recent curve, or it has not earned its place).
5. Cover the complexity judgment: the model earns its complexity when the held-out prediction improves over the baseline by a decision-relevant margin; otherwise the simpler model is the honest one — and the judgment is recorded, not assumed.

## Phase 3 — Method and Technique

- The hybrid spec: the state layer, the network layer, the forcing term, the loop edges
- The K-factor loop integration: the invited cohort, the return probability, the k as edge weight
- The forcing-term estimation from platform allocation data (or its proxy)
- The backtest protocol: the calibration set, the holdout set, the scoring metric, the baseline
- The complexity memo: the held-out improvement, the decision-relevance test, the verdict

## Phase 4 — Analysis and Diagnosis

- Diagnose a hybrid model's failure by layer: the states (wrong variant), the contacts (wrong network), or the forcing (the platform assumption) — the layer decides the fix.
- Detect the amplification instability: the I→exposure→I loop that the forcing term creates, and the signature (the super-exponential early phase the base model cannot hold).
- Read the backtest honestly: a model that beats the baseline on the calibration set but not on the holdout is over-fit to its own past.
- Run the baseline test every time: the naive extension is the competitor, and it is often strong.

## Phase 5 — Application and Design

- Build the hybrid only layer by layer: add the network, then the forcing, then the loop — and keep the layer that earns its holdout improvement.
- Estimate the forcing from data where possible; where not, bracket it (low/high allocation scenarios) and carry the bracket into the forecast.
- Institute the baseline test as a gate: no model ships to the decision maker without its held-out comparison.
- Record the complexity memo per model: what was added, what it earned, and what was rejected — the library learns.

## Phase 6 — Ethics and Boundary Conditions

- The forcing term encodes the platform's policy; a policy change is a model break, and the monitoring must detect the allocation shift, not just the curve shift.
- The hybrid's complexity is also its opacity: the decision maker must still receive the one-page form; the model's depth does not excuse the communication's shallowness.
- The backtest's past diffusions are the survivors and the known; the model's claim about the novel case must state the transfer assumption.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Spec the hybrid model for a live case: the state layer, the network layer, the forcing term, the loop edges — with the data source for each.
2. Integrate the K-factor loop into the base model for a referral product; simulate the with/without loop and read the final-size difference.
3. Estimate or bracket the forcing term from platform data; run the low/high scenarios and the forecast bracket they produce.
4. Run the backtest protocol on a past campaign: the calibration set, the holdout, the baseline (naive extension), and the scoring.
5. Write the complexity memo for the backtest result: the improvement, the decision-relevance test, and the verdict (keep/simplify/reject).
6. Produce the practitioner's judgment note: for three real cases, which model family earned its complexity, which did not, and why — as a standing reference.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Hybrid spec
- Each layer is named with its data source
- The forcing is estimated or bracketed
- The loop edges carry the measured k

### Validation
- The calibration and holdout sets are defined
- The baseline was run and reported
- The over-fit was checked

### Complexity judgment
- The held-out improvement is decision-relevant
- The memo records what was added and rejected
- The transfer assumption for the novel case is stated

### Delivery gate
- The one-page form is still the deliverable
- The forcing monitor (policy shift) is live
- The library's judgment notes are updated

## Anti-Patterns

the hybrid built in one leap; the forcing assumed, not bracketed; the backtest without the baseline; the calibration set leaked into the holdout; the complexity kept out of loyalty; the one-page form abandoned for the solver's log.

## Decision Heuristic

Before any claim or recommendation, ask:

1. Which layer is this model's claim actually resting on?
2. Is the forcing from data, or is it a bracketed assumption — and does the forecast carry it?
3. Did the model beat the naive baseline on the holdout, by a decision-relevant margin?
4. What was added in the last revision, and what did it earn?
5. Can the decision maker still read this in one page?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not the biggest model. It is the model that beats the baseline on the data it has not seen, with its layers named, its assumptions bracketed, and its complexity justified in writing — so that the next team inherits a tool, not a monument.
