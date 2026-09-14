---
name: k-factor-instrumentation
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Estimating i and c from Data: Instrumentation and the Error List — how the loop's factors are measured — the instrumentation, the estimation choices, and the error list that separates the real k from the artifact. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around referral instrumentation, invite tracking, referral attribution window, cohort K-factor, dedup referral, referral event schema, referral measurement errors. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of whether the K-factor on the dashboard is the loop's real coefficient or an artifact of the instrumentation, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: k-factor-viral-coefficient
---

# Estimating i and c from Data: Instrumentation and the Error List: Professional Module Builder

## Mission

Produce professional-level material on how the loop's factors are measured — the instrumentation, the estimation choices, and the error list that separates the real k from the artifact. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Define the three events: the invite (the referrer sends, with the channel and the moment), the journey (the invitee's click, the landing, the signup, with the timestamps), and the join (the referrer–invitee link that closes the loop) — the schema, the keys, and the join logic that makes k computable.
2. Teach the estimation choices: the cohort (the referrers who entered in the period, and the invites they sent), the attribution window (how long after the invite the signup still counts — the window is a decision, and it moves c), the cycle (the aggregation period of the k), and the denominators (the invites sent, the invites delivered, the invites clicked — the c's denominator is a choice).
3. Cover the error list, in order of damage: the attribution failure (the invitee arrives without the token and is counted organic — the loop's c is understated), the dedup failure (the same invitee, two invites, two counts — the i is overstated), the survivorship (the k on the active referrers, not the whole user base — the i is overstated by the composition), the channel mix (the email and the in-app invites convert differently, and the blended c hides both), and the sampling (the platform's API returns a sample of the journeys, and the unweighted sample biases c).
4. Teach the validation: the known-referral test (the seeded cohort whose referrals are known, the pipeline's recovery rate), the reconciliation (the k from the events versus the k from the aggregate reports, the gap and its source), and the uncertainty (the interval on k from the sample, the cohort's size, and the error corrections).
5. Institute the standing discipline: the instrumentation spec (the schema, the window, the denominators, documented), the monthly recomputation with the error checks, and the change log (every change to the window or the schema re-bases the series, and the re-base is recorded).

## Phase 3 — Method and Technique

- The event schema: the three events, the keys, the timestamps, the channel and moment fields
- The cohort and window spec: the cohort definition, the attribution window, the cycle
- The denominator decision: the c's denominator, stated per computation
- The error-check battery: the attribution recovery, the dedup audit, the composition check, the mix decomposition, the sampling weight
- The validation protocol: the seeded test cohort, the reconciliation, the interval on k

## Phase 4 — Analysis and Diagnosis

- Diagnose a k discrepancy by error mode: the dashboard k versus the recomputed k — the gap decomposed into the attribution loss, the dedup inflation, the composition shift, the mix, the sampling.
- Read the channel mix before the average: the c per channel is the diagnostic; the blended c is the summary that hides the lever.
- Check the window sensitivity: the c at the 24-hour, the 7-day, and the 30-day windows — the gap is the delayed-conversion mass, and the window choice is the claim.
- Audit the composition: the referrer population's activity over time — the survivorship drift in the i, and the correction (the full-base i versus the active i).

## Phase 5 — Application and Design

- Specify the instrumentation before the loop ships: the schema, the window, the denominators — the spec is the contract between the product and the analytics.
- Compute k with the error battery every cycle: the corrections are applied and logged, not ad-hoc.
- Report k per channel and per moment, with the blended as the summary — the working resolution is the decomposed one.
- Run the seeded test at launch and after any pipeline change: the recovery rate is the pipeline's credibility number.

## Phase 6 — Ethics and Boundary Conditions

- The referral data (who invited whom) is the relationship graph of the user base; its storage, access, and retention are bound by the consent and the minimization rules.
- The attribution window can be extended to flatter the loop (the 90-day window that captures the coincidence as the conversion); the line is the window's justification (the behavior evidence for the delay), stated.
- The dedup and the dedup-failure both touch identity resolution; the identity handling is a privacy design, and its choices (the join key, the retention) are part of the spec.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Write the event schema for a referral loop: the three events, the keys, the fields, and the join logic — with the test cases that break it.
2. Compute k three ways (the naive, the dedup-corrected, the full-base) on a dataset with a known error; quantify each correction and the final k with its interval.
3. Run the window sensitivity: the c at three windows, the delayed-conversion mass, and the window choice with its behavior evidence.
4. Decompose the blended c by channel and by moment; identify the lever channel and the lever moment from the decomposition.
5. Run the seeded test cohort: the known referrals, the pipeline's recovery rate, and the discrepancy diagnosis.
6. Write the instrumentation spec and the change log for the team: the schema, the window, the denominators, the error battery, and the re-base rule.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Instrumentation
- The schema is specified
- The keys and the join logic are tested
- The channel and moment fields are present

### Estimation integrity
- The cohort and the window are stated
- The denominators are decided
- The error battery ran, with the corrections logged

### Validation
- The seeded recovery rate is measured
- The reconciliation gap is decomposed
- The interval is reported

### Delivery gate
- The spec is versioned
- The change log is live
- The privacy handling of the referral data is stated

## Anti-Patterns

the k without a schema; the window chosen for the number it produces; the blended c reported without the decomposition; the dedup skipped; the survivorship uncorrected; the seeded test never run; the re-base silent.

## Decision Heuristic

Before any claim or recommendation, ask:

1. Can the three events be joined, and was the join tested?
2. What window is this c from, and what is the evidence for it?
3. What do the error corrections move the number by, and were they logged?
4. Does the channel decomposition change the lever decision?
5. Has the pipeline passed the seeded test since the last change?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a bigger k. It is a k that survives the error battery, the seeded test, and the change log — so the number on the dashboard is the loop's coefficient, not the pipeline's artifact.
