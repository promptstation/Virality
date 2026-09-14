---
name: sir-parameter-estimation
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Parameter Estimation from Real Diffusion Data — how to estimate the model's parameters from real diffusion data — the pipeline, the methods, the selection, and the pathologies that corrupt them. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around parameter estimation, fitting epidemic models, growth rate method, maximum likelihood diffusion, model selection, AIC BIC, holdout validation. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of whether the parameters behind a forecast are actually supported by the data, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: sir-epidemiology
---

# Parameter Estimation from Real Diffusion Data: Professional Module Builder

## Mission

Produce professional-level material on how to estimate the model's parameters from real diffusion data — the pipeline, the methods, the selection, and the pathologies that corrupt them. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Build the data pipeline: collection (API, platform analytics, CMS), cleaning (dedup, bot filtering), denominators (impressions, unique reach), and censoring (left-truncation of pre-launch, right-truncation of the open curve).
2. Teach the fitting methods: least squares on the I-curve (simple, bias-prone), maximum likelihood on the event data (the principled choice when counts are available), and the early-window growth-rate method (the cheap, robust R0 estimate).
3. Teach the reach-versus-adoption distinction: most platform counts measure exposure, not the state transition; the model needs the adoption (share, purchase, activation) series, not the view series.
4. Cover model selection: AIC/BIC for the variant family, and holdout prediction (fit on the first half, predict the second) as the honest test.
5. Run the pathology list: platform API rate limits and sampling, survivorship (only the successful content is studied), measurement noise (the platform's own count revisions), and the bot fraction — each with its correction or its warning.

## Phase 3 — Method and Technique

- The pipeline spec: source, dedup, denominator, censoring window, bot filter
- The least-squares fit with residual diagnostics
- The maximum-likelihood fit on event counts with the profile likelihood for the interval
- The early-window growth-rate estimate with its window-sensitivity check
- The holdout validation: fit on t<τ, predict t>τ, score the error

## Phase 4 — Analysis and Diagnosis

- Diagnose a bad fit by component: the data (censoring, noise, wrong series) before the model (wrong variant) before the method (wrong likelihood).
- Check the series identity: is the fitted series the adoption series the model requires, or a reach series wearing its clothes?
- Read the interval honestly: a parameter with a wide interval is an unknown, and the forecast inherits the width.
- Detect the over-fit: the curve that fits the noise (many wiggles) fails the holdout; the holdout is the referee.

## Phase 5 — Application and Design

- Specify the pipeline before the fit; the series definition is a decision, not a default.
- Use the growth-rate method for the early decision (the R0 verdict) and the full fit for the forecast — the two serve different moments.
- Report the holdout error as the forecast's credibility number, not the in-sample fit.
- Automate the pipeline: a repeatable fit on every new data point, so the parameters track the diffusion, not the last analyst's spreadsheet.

## Phase 6 — Ethics and Boundary Conditions

- Studying only successful content (survivorship) inflates the parameters; the base rate of failure is part of the estimate.
- Bot-filtered data without a stated filter transfers the filter's assumptions into the parameters.
- The platform's count revisions mean the 'final' data changes after the fact; the provenance timestamp is part of the record.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Specify the pipeline for a chosen dataset: source, dedup, denominator, censoring, bot filter — and identify which counts are reach and which are adoption.
2. Fit the base SIR by least squares and by maximum likelihood to the same data; compare the parameters and explain the gap.
3. Estimate R0 by the early-window growth-rate method at three window lengths; report the sensitivity.
4. Run the holdout validation on a variant family; select the model by prediction error and state the runner-up.
5. Apply the pathology list to a dataset with a known bot fraction; quantify the parameter shift the correction makes.
6. Produce the worked end-to-end fit on a real dataset: pipeline, fit, selection, holdout, and the forecast with its uncertainty.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Pipeline spec
- The source and cleaning are documented
- The denominator is named
- The censoring window is stated
- The bot filter is specified

### Fit integrity
- The method matches the data (counts → likelihood, curve → LS)
- The residuals were inspected
- The interval is reported

### Selection and validation
- The variant family was compared
- The holdout error is the headline
- The over-fit was checked

### Delivery gate
- The provenance timestamp is recorded
- The survivorship warning is stated
- The automated re-fit is scheduled

## Anti-Patterns

the reach series fitted as adoption; the in-sample fit reported as credibility; the full fit used for the early decision; the bot filter unstated; survivorship silently assumed; the pipeline as a one-off spreadsheet.

## Decision Heuristic

Before any claim or recommendation, ask:

1. Is the fitted series the series the model requires?
2. Does the method match the data at hand, and the moment the decision serves?
3. What is the holdout error, and does the interval match the claim?
4. Which pathologies touched this data, and what did they do to the numbers?
5. Would a second analyst, from the spec, reproduce this fit?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a perfect fit. It is a parameter with a pipeline, a method, an interval, and a holdout error — so that the forecast is a measurement, not a mood.
