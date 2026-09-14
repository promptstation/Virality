---
name: reproduction-number-thresholds
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on The Basic Reproduction Number R0: Thresholds and Herd Immunity — R0 and the thresholds it defines — the takeoff condition, the saturation point, and their estimation and strategic use. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around R0, basic reproduction number, threshold dynamics, herd immunity, saturation threshold, growth rate estimation. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of whether an idea will take off at all, and how much of the market must be fatigued for it to stop, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: sir-epidemiology
---

# The Basic Reproduction Number R0: Thresholds and Herd Immunity: Professional Module Builder

## Mission

Produce professional-level material on R0 and the thresholds it defines — the takeoff condition, the saturation point, and their estimation and strategic use. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Define R0 = β/γ and derive the threshold: the spread grows while R·S/N > 1 and dies once S/N falls below 1/R — the same mathematics as the herd-immunity threshold 1 − 1/R0.
2. Teach the strategic reading: raising β (more exposure, better hooks, seeding to hubs) or lowering γ (slower fatigue, evergreen content) raises R0; the levers map onto the parameters.
3. Show R0 estimation from data: the initial exponential growth rate (r ≈ β−γ early on) gives R0 ≈ 1 + r/γ; the early-curve fit gives both parameters jointly.
4. Cover variation: R0 is not a constant of the content — it depends on platform (contact structure), audience (susceptibility), and timing (concurrent events change the susceptible pool).
5. Connect to the final size: the higher the R0, the larger the fraction ever reached — the final-size equation and its reading.

## Phase 3 — Method and Technique

- Estimating the initial growth rate from the early I-curve (log-linear fit)
- The joint early-curve fit for β and γ (hence R0) with confidence intervals
- Computing the herd-immunity threshold 1 − 1/R0 for the estimated R0
- The final-size equation and its numerical check against the simulated R-curve
- Re-estimating R0 per platform/audience slice to test the variation claim

## Phase 4 — Analysis and Diagnosis

- Diagnose a failed takeoff as R0 ≤ 1: measure the early growth rate, and if it is flat or negative, no amount of late boosting changes the threshold.
- Read a stalling diffusion through the threshold: is S/N now below 1/R (saturation), or has β fallen (content fatigue, algorithmic demotion)?
- Check the R0 provenance: an R0 estimated after the peak is contaminated by the depletion of susceptibles; the early window is the valid one.
- Compare R0 across slices (platform, audience) to find where the same content is above and below the threshold.

## Phase 5 — Application and Design

- Measure R0 in the early window as the first KPI of any new diffusion — it is the takeoff signal, earlier and cleaner than the curve.
- Set the seeding budget against the threshold: the minimum reach needed to push R above 1 is a computable target, not a guess.
- Design for lower γ where the goal is longevity (evergreen formats), and for higher β where the goal is speed (launch windows).
- Report the herd-immunity threshold to the business: the realistic ceiling on total reach for this R0.

## Phase 6 — Ethics and Boundary Conditions

- Quoting R0 without its estimation window is misleading: the number is a property of the early phase, not of the whole campaign.
- Using a disease R0 from the literature as a prior for a novel content format transfers an assumption, not a fact.
- The threshold logic can be used to manufacture false scarcity ('almost everyone has seen it') — the line is whether the saturation claim is the measured S/N or a marketing number.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. From an early diffusion curve (first 10 data points), estimate the growth rate, β, γ, and R0 with confidence intervals; state the threshold verdict.
2. Compute the herd-immunity threshold for three estimated R0 values and compare to the observed final size.
3. Re-estimate R0 for the same content on three platform slices; interpret the differences in contact-structure terms.
4. Diagnose a stalling diffusion: is it saturation (S/N < 1/R) or a β collapse? Design the test that distinguishes them.
5. Design the seeding plan that pushes a marginal case (R=0.9) above the threshold: the reach target, the hub selection, and the validation point.
6. Write the R0 methodology note: the estimation window, the method, the uncertainty, and the misuse warnings — for a team that will reuse it.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Estimation integrity
- The early window is defined and used
- The method is named (log-linear or joint fit)
- The confidence interval is reported

### Threshold reading
- The R>1 verdict is stated from the estimate
- The saturation point 1−1/R is computed
- The final size is consistent with R0

### Strategy mapping
- The β levers and γ levers are named for this case
- The seeding target is computable from the threshold
- The reach ceiling is reported

### Delivery gate
- The slice comparison was run
- The misuse warnings are in the note
- The re-estimation trigger (new platform, new audience) is defined

## Anti-Patterns

R0 quoted from the whole curve; a literature R0 transferred without comment; the threshold verdict stated without the interval; the saturation claim used as marketing; seeding spent after the threshold is met; slices ignored (one R0 for all platforms).

## Decision Heuristic

Before any claim or recommendation, ask:

1. Is this R0 from the early window, and how wide is its interval?
2. Is R above or below 1, and what does that verdict actually permit?
3. Which parameter — β or γ — is the binding lever here?
4. What is the reachable ceiling (herd threshold) for this R0?
5. Does R0 hold across the slices, or is the single number hiding a split market?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a bigger R0. It is a threshold you can compute, an early signal you can read, and a reach ceiling you can plan against — so the bet is placed on the mathematics, not the mood.
