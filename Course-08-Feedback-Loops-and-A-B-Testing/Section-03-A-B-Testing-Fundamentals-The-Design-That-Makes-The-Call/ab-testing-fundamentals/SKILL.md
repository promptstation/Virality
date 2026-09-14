---
name: ab-testing-fundamentals
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on A/B Testing Fundamentals: The Design That Makes the Call — how the A/B test is designed to make the call — the elements, the classic errors, and the pre-registered decision that keeps the call honest. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around A/B testing, hypothesis testing, sample size, power, confidence interval, peeking, novelty effect, multiple comparisons, holdout, randomization unit. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of the test says the new hook wins, but the team is not sure the call is real, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: feedback-loops-ab-testing
---

# A/B Testing Fundamentals: The Design That Makes the Call: Professional Module Builder

## Mission

Produce professional-level material on how the A/B test is designed to make the call — the elements, the classic errors, and the pre-registered decision that keeps the call honest. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach the hypothesis and the effect of interest: the null (the no-difference) and the alternative (the direction, the change), and the effect of interest (the minimum difference that is worth acting on — the practical threshold, not the statistical one) — the hypothesis as the test's contract: what difference the test is built to detect, and the decision it is built to serve.
2. Teach the unit and the assignment: the unit of randomization (the user, the content, the impression — the unit the assignment operates on) and the contamination (the units that share the outcome — the audience that sees both variants, the network that crosses the arms), and the assignment (the randomization per unit, the holdout as the standing control, the segmentation as the sub-read) — the unit's integrity as the test's validity, and the contamination's cure (the cluster, the time split, the holdout's discipline).
3. Teach the sample and the duration: the size from the effect of interest, the baseline's rate, the variance, and the power (the probability of detecting the effect when it is present) — the computation, and the duration (the cycles the test must span — the weekly pattern, the window's completeness) — the sample as the test's adequacy, and the underpower as its classic failure (the test that cannot detect the effect it was built for).
4. Teach the read: the difference (the variant minus the control), the confidence interval (the range the difference is in, with the stated confidence), the significance (the probability of the difference under the null — the p-value, and its honest use as the decision's input, not the truth's measure), and the multiple-comparisons problem (the many metrics, the many arms — the false-positive inflation from the searching, and the cures: the primary metric pre-registered, the correction for the family, the exploration-exploitation split of the read).
5. Teach the classic errors in order of damage: the peeking (the early stop on the significance that crosses — the repeated look's inflation of the false positive, and the cure: the pre-registered duration, the sequential method where the early stop is required), the underpower (the small sample, the effect undetected, the 'no difference' that is the 'no detection'), the novelty (the effect that is the newness — the first exposure's reaction, not the change's value, and the cure: the duration past the novelty, the repeat-exposure read), the interference (the units' cross-effect — the audience's arms seeing each other's content, the network's spillover, and the cure: the cluster's assignment, the holdout's separation), and the metric-gaming (the variant that wins on the tested metric and loses on the untested — the proxy's win, the target's loss, and the cure: the guardrail metric in the design, the target's pairing).
6. Teach the decision: the ship (the effect past the threshold, the guardrail clean), the reject (the effect absent or negative, the reason recorded), and the extend (the effect present but the window incomplete, the novelty unpassed, the extension with the pre-registered rule) — the decision per the pre-registered rule (the threshold, the window, the guardrail stated before the test), and the rule's discipline (the decision that the read's convenience would have made differently is the rule's proof).

## Phase 3 — Method and Technique

- The test design doc: the hypothesis, the effect of interest, the unit, the sample, the duration, the primary and the guardrail metrics, the decision rule — the contract
- The sample-size computation: the baseline, the effect, the variance, the power — with the stated assumptions
- The assignment spec: the randomization per unit, the holdout, the segmentation, the contamination's cure
- The read report: the difference, the interval, the significance, the multiple-comparison's handling, the guardrail's state
- The decision record: the rule applied, the verdict, the reason — the ship, the reject, the extend

## Phase 4 — Analysis and Diagnosis

- Diagnose the invalid call in the history: the peeked test (the early stop's signature), the underpowered test (the 'no difference' with the small sample), the novelty-unpassed test (the effect's decay over the weeks) — the error per test, and the re-run's design.
- Check the unit's integrity: the contamination's signature (the arms' audiences overlapping, the content's network crossing) — the unit's breach, and the cluster's or the holdout's fix.
- Read the multiple-comparison's state: the primary metric pre-registered versus the family searched — the false-positive's risk, and the correction or the split.
- Audit the decision's honesty: the verdict versus the rule (the ship that the rule would have rejected, the reject that the rule would have shipped) — the rule's bypass, and the discipline's restoration.

## Phase 5 — Application and Design

- Run the design doc before the test: the hypothesis, the effect of interest, the unit, the sample, the duration, the metrics, the rule — approved, pre-registered, the contract in force.
- Compute the sample with the stated assumptions: the baseline from the standing data, the effect from the practical threshold, the power at the acceptable — the adequacy checked before the launch.
- Assign per the unit's integrity: the randomization per unit, the holdout standing, the contamination's cure in place — the assignment as the validity.
- Decide per the pre-registered rule: the ship, the reject, the extend — with the record of the rule applied, and the guardrail's state examined before the verdict.

## Phase 6 — Ethics and Boundary Conditions

- The test assigns the audience to the variants; the assignment's fairness (the user's exposure to the inferior variant, the consent to the experiment) is the test's human constraint, and the guardrail's design (the harm's bound) is its enforcement.
- The test's read is the audience's behavior measured at scale; the metric-gaming's line (the tested metric's win at the untested's cost) is the designer's share, and the target's pairing is its standard.
- The holdout is the standing control; its existence (the control that the variant is measured against forever) is the measurement's integrity, and its removal (the 'all users on the winner') is the learning's end — the holdout's permanence as the discipline.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Write the test design doc for a hook change: the hypothesis, the effect of interest, the unit, the sample, the duration, the primary and the guardrail metrics, the decision rule — with the sample-size computation shown.
2. Diagnose four historical tests: the peeked, the underpowered, the novelty-unpassed, the contaminated — with the signature per test and the re-run's design.
3. Design the assignment for a networked audience: the unit's integrity, the contamination's cure (the cluster, the time split, the holdout's separation) — with the spec.
4. Run the read report on a completed test: the difference, the interval, the significance, the multiple-comparison's handling, the guardrail's state — with the decision per the pre-registered rule.
5. Design the sequential method for a test that must allow the early stop: the boundary, the stopping rule, the inflation's control — with the comparison to the fixed-duration design.
6. Write the testing governance: the design doc's approval, the pre-registration, the decision's record, the holdout's permanence, the guardrail's design — as the standing policy, with the owner.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Design
- The hypothesis and the effect of interest are stated
- The unit is chosen with the contamination's cure
- The sample is computed with the assumptions shown

### Assignment
- The randomization is per unit
- The holdout is standing
- The segmentation is the sub-read

### Read
- The difference and the interval are reported
- The multiple-comparison is handled
- The guardrail's state is examined

### Delivery gate
- The rule was applied as pre-registered
- The decision is recorded with the reason
- The holdout remains in place

## Anti-Patterns

the test without the effect of interest; the peek as the stopping rule; the 'no difference' from the small sample; the novelty read as the value; the contamination unexamined; the family searched without the primary pre-registered; the verdict that the rule would not have made.

## Decision Heuristic

Before any claim or recommendation, ask:

1. What difference is this test built to detect, and is the sample adequate for it?
2. Is the unit's integrity held — the contamination examined and cured?
3. Was the duration pre-registered, and did the stop respect it?
4. Is the primary metric pre-registered, and how is the family handled?
5. Does the verdict follow the rule, and is the holdout still standing?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a winning variant. It is the test that could be wrong — the design that names the error, the sample that detects the effect, the rule that decides before the hope — so the call is the instrument's, and the learning is the team's.
