---
name: sir-forecasting-scenarios
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Forecasting and Scenario Analysis — how to turn the fitted model into a decision instrument — ensembles, scenarios, sensitivity, and the honest communication of what the forecast can and cannot say. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around diffusion forecasting, scenario analysis, sensitivity analysis, ensemble forecast, forecast communication, forecast post-mortem, what-if analysis. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of what will happen if we launch on Tuesday, double the seeding, or the platform changes its algorithm, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: sir-epidemiology
---

# Forecasting and Scenario Analysis: Professional Module Builder

## Mission

Produce professional-level material on how to turn the fitted model into a decision instrument — ensembles, scenarios, sensitivity, and the honest communication of what the forecast can and cannot say. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach the ensemble forecast: draw the parameters from their joint uncertainty distribution, simulate each draw, and report the decision variables (peak date, final size) as ranges with the central tendency — the point forecast is the median of the ensemble, not the answer.
2. Build the scenario grid: the decision-relevant variations (R0 high/low, intervention early/late/none, platform algorithm change, competing entry) as named scenarios, each a full simulation, and the comparison table that shows which scenarios change the decision.
3. Teach the sensitivity analysis: perturb each parameter by its uncertainty and read the decision variables — the forecast turns on the sensitive parameters, and the monitoring budget follows the sensitivity.
4. Cover the communication form: the range, the central case, the assumptions in plain language, and the explicit list of what the forecast does not cover — in one page for the decision maker.
5. Run the forecast audit: when the observed curve leaves the forecast band, the audit separates the parameter error (re-fit), the structural miss (wrong variant), and the exogenous shock (an event the model did not contain) — and the model is updated accordingly.

## Phase 3 — Method and Technique

- The ensemble: parameter sampling from the joint posterior/profile, the simulation loop, the quantile report
- The scenario grid spec: the scenarios, the parameter changes, the decision variables per scenario
- The sensitivity: per-parameter perturbation and the elasticity of each decision variable
- The one-page forecast form: range, central case, assumptions, exclusions
- The audit protocol: the band-exit detection, the three-branch diagnosis, the update rule

## Phase 4 — Analysis and Diagnosis

- Diagnose a forecast miss by branch: parameter (re-fit), structure (re-select the variant), or shock (extend the model) — the branch decides the fix.
- Read the sensitivity before the scenario grid: the scenarios that do not move the sensitive parameters are decoration.
- Detect the over-precise forecast: a narrow band from an over-confident fit (the interval ignored) is the most dangerous form.
- Check the exclusions list honestly: a forecast that silently assumes no competing entry is a forecast about a world that is not this one.

## Phase 5 — Application and Design

- Report the decision variables as ranges from the ensemble; the point is the central case, never the claim.
- Run only the scenarios that touch the sensitive parameters; the grid is a tool, not a deliverable.
- Deliver the one-page form: the decision maker needs the range, the assumptions, and the exclusions — not the solver's log.
- Institute the audit as a standing step: the miss is the data that updates the model, and the branch is recorded.

## Phase 6 — Ethics and Boundary Conditions

- A forecast used to justify sunk spend (the 'we are already past the peak, so keep going' fallacy) inverts the instrument; the forecast serves the next decision, not the last one.
- Scenario analysis can be gamed (the scenarios chosen to flatter the preferred plan); the grid must include the adverse case by rule.
- The exclusions list is the ethics of the forecast: hiding the assumptions is a form of misrepresentation, even when the math is right.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Produce the ensemble forecast for a fitted case: the peak-date and final-size ranges with quantiles, and the central case labeled as such.
2. Build the scenario grid for a launch decision: four scenarios (base, high-R0, late intervention, platform change) and the comparison table.
3. Run the sensitivity analysis; identify the two parameters the forecast turns on and the monitoring plan that follows.
4. Write the one-page forecast form for a non-technical reader: the range, the assumptions, the exclusions — and test it on a real decision maker.
5. Run the forecast audit on a missed forecast: the band-exit date, the branch diagnosis, and the update to the model.
6. Design the standing forecast protocol: the cadence, the ensemble, the scenario rule (adverse case included), the form, and the audit — as a team document.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Ensemble integrity
- The parameter uncertainty was propagated
- The quantiles are reported
- The central case is labeled, not claimed

### Scenario discipline
- The grid touches the sensitive parameters
- The adverse scenario is included by rule
- The decision-relevant differences are the deliverable

### Communication form
- The one-page form has the range, assumptions, exclusions
- The reader is non-technical and it worked
- The point forecast is not the headline

### Audit protocol
- The band-exit was detected
- The branch was diagnosed (parameter/structure/shock)
- The update was recorded

## Anti-Patterns

the point forecast as the claim; the narrow band from an over-confident fit; the scenario grid that flatters the plan; the sensitivity skipped; the exclusions hidden; the audit skipped after the miss.

## Decision Heuristic

Before any claim or recommendation, ask:

1. What is the range, and is the central case labeled as the median of an ensemble?
2. Which parameters does the forecast actually turn on?
3. Is the adverse scenario in the grid by rule?
4. Can the decision maker read the assumptions and the exclusions in one page?
5. When the curve leaves the band, is the branch already defined?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a precise number. It is a range with its assumptions, a scenario set that includes the bad case, and an audit that learns from the miss — so the forecast is a decision instrument, not a commitment device.
