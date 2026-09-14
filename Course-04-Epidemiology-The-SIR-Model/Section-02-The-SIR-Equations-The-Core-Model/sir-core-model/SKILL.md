---
name: sir-core-model
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on The SIR Equations: The Core Model — the core SIR model — its equations, its two parameters, and the trajectory shape they generate — and how to simulate and read it. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around SIR equations, compartment model, epidemic curve, beta gamma parameters, epidemic simulation, final size. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of what shape a diffusion will take, and when it will peak, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: sir-epidemiology
---

# The SIR Equations: The Core Model: Professional Module Builder

## Mission

Produce professional-level material on the core SIR model — its equations, its two parameters, and the trajectory shape they generate — and how to simulate and read it. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Derive the three equations from the state transitions (S→I at rate proportional to contact SI, I→R at rate γ), and interpret each term in information-diffusion language.
2. Teach the two parameters: β (effective contact rate — how often a spreader's content meets a susceptible) and γ (recovery rate — how fast a spreader fatigues or stops); everything downstream is a function of their ratio.
3. Read the epidemic curve's regions: the slow takeoff (few infected, few contacts), the exponential growth phase, the peak (where dI/dt crosses zero), the decaying tail, and the final size (the fraction ever infected).
4. Teach the conservation: S+I+R=N — the compartments are a partition of the population, and the curve is a transfer of mass between them.
5. Run the simulation: solve the system numerically (Euler or a standard ODE solver), and produce the standard three-curve plot with the regions annotated.

## Phase 3 — Method and Technique

- Setting up the system in a solver (initial conditions S0, I0, R0; N; β; γ)
- Choosing the time step and validating conservation (S+I+R=N at every step)
- Locating the peak analytically (dI/dt=0) and confirming it in the simulation
- Reading the final size off the R-curve and comparing to the peak height
- The standard three-curve plot with regions annotated for a report

## Phase 4 — Analysis and Diagnosis

- Diagnose a trajectory's current region (takeoff, growth, peak, tail) from its slope and curvature — the strategy differs per region.
- Separate parameter uncertainty from model uncertainty when a forecast misses.
- Verify the peak condition in a real dataset: did the observed peak match the model's crossing?
- Detect model mis-specification: a curve the SIR shape cannot produce (two peaks, a plateau) signals a variant model.

## Phase 5 — Application and Design

- Estimate β and γ from a partial curve before forecasting — the two-parameter fit is the minimal job.
- Forecast the peak date and the final size as the two headline numbers, each with its uncertainty.
- Use the region reading for timing decisions: seeding is a takeoff/growth tool, not a tail tool.
- Present the three curves, not one: the S, I, R transfer is the mechanism, the I-curve is only the symptom.

## Phase 6 — Ethics and Boundary Conditions

- A forecast stated without its parameter source is a prediction, not a model result; the provenance of β and γ is part of the claim.
- Cutting a diffusion at the 'peak' on a disease-curve intuition can destroy a structurally two-wave case; the model variant must be checked first.
- The model's parameters encode assumptions about the population (mixing, fatigue); deploying it to a different population without re-estimation is a silent change of claim.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Derive the SIR system from the state transitions, annotating each term in information-diffusion language.
2. Simulate the model with N=10,000, I0=10, β=0.3, γ=0.1: produce the three curves, locate the peak, and state the final size.
3. Fit β and γ to a real partial diffusion curve; report the fit, the peak forecast, and the final-size forecast with uncertainty.
4. Verify the peak condition on a real dataset: observed peak date versus model prediction, and the error.
5. Produce the standard annotated three-curve plot for a report, with the regions labeled and the two parameters named.
6. Identify the model mis-specification in a curve with two peaks; name the variant model it suggests and why.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Model setup
- The states and parameters are defined
- Initial conditions are stated
- Conservation is validated numerically

### Fit quality
- β and γ are estimated from data with provenance
- The fit is shown, not asserted
- The uncertainty is stated

### Forecast integrity
- The peak date and final size are the headline numbers
- Each carries its uncertainty
- The region reading is stated

### Delivery gate
- The three-curve plot is annotated
- The mis-specification check was run
- The next data point is scheduled for validation

## Anti-Patterns

the I-curve presented alone; parameters without provenance; the peak read from intuition; conservation violated in the simulation; one fit applied to a different population; two-peak curves forced into an SIR shape.

## Decision Heuristic

Before any claim or recommendation, ask:

1. Where on the curve are we now, and what does that region allow?
2. What are β and γ, where did they come from, and how uncertain are they?
3. Does the data actually have the SIR shape, or is a variant needed?
4. Is the forecast the peak and the final size, each with its uncertainty?
5. Was conservation and the peak condition verified numerically?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a scary curve. It is two honest parameters, one verified shape, and a forecast that says exactly what it can — so the decision maker acts on the mechanism, not the drama.
