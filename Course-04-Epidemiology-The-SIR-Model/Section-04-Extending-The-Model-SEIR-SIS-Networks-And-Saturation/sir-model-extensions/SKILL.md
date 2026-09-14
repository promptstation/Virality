---
name: sir-model-extensions
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Extending the Model: SEIR, SIS, Networks, and Saturation — the model variants — SEIR, SIS, network-based, multi-strain — when each is required, how the equations change, and the signature shape that reveals the variant. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around SEIR model, SIS model, network-based diffusion, susceptible-exposed-infected, reinfection model, competing content, model variants. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of why the observed curve does not match the simple SIR shape, and which variant explains it, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: sir-epidemiology
---

# Extending the Model: SEIR, SIS, Networks, and Saturation: Professional Module Builder

## Mission

Produce professional-level material on the model variants — SEIR, SIS, network-based, multi-strain — when each is required, how the equations change, and the signature shape that reveals the variant. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach SEIR: the exposed (E) compartment for people who saw the content but have not started spreading — the incubation delay between exposure and activation, with the added parameter σ (exposed→infectious rate) and the signature delayed peak.
2. Teach SIS: the recovered return to susceptible — re-exposure and re-activation for recurring topics, seasonal content, and evergreen categories; the signature sustained oscillation or persistent endemic level instead of the SIR final size.
3. Teach network-based SIR: spread on an explicit contact network where individuals have different contact rates — heterogeneous mixing, the emergence of super-spreaders, and why the mean-field R0 under-predicts the final size on hub-rich networks.
4. Teach multi-strain (competing content): two or more 'pathogens' sharing the susceptible pool — interference, priority effects, and the dynamics of a new entry against an entrenched one.
5. Cover the saturation mechanics: finite N, topic exhaustion (γ as a decay), and the platform's implicit removal of content from distribution (algorithmic expiry as an exogenous recovery).

## Phase 3 — Method and Technique

- The variant-selection workflow: list the deviations from the base shape, map each to a variant
- The SEIR fit (β, σ, γ) and the incubation-period estimate
- The SIS fit and the endemic-level prediction
- The network-based simulation on a real or synthetic contact graph
- The two-strain competition simulation with a timing of entry as the variable

## Phase 4 — Analysis and Diagnosis

- Read the signature shapes: the delayed peak (SEIR), the persistent level (SIS), the right-skewed outbreak (network), the suppression pattern (competition) — and name the variant each reveals.
- Diagnose the incubation: is there a measurable lag between exposure and activation? If yes, SEIR or later; if no, the base model.
- Detect the re-exposure: does the I-curve rise again after the first peak? If yes, SIS or a re-exposure term.
- Test the heterogeneity: does the final size exceed the mean-field prediction for the same R0? If yes, the network structure matters.

## Phase 5 — Application and Design

- Choose the variant from the signature, then fit; never fit the base model to a two-peak curve and call it done.
- Use the incubation estimate (σ) for timing decisions: seeding before the exposed converts is where the leverage is.
- For network cases, select the contact graph from data (or a calibrated synthetic) and report the hub statistics.
- For competition cases, model the entry timing — the window in which a new content can displace an entrenched one is often narrow.

## Phase 6 — Ethics and Boundary Conditions

- A variant chosen to make the fit look better, rather than to match a structural feature, is curve-fitting dressed as modeling.
- The network's hubs are real people; modeling them as super-spreaders without understanding why they spread (trust, expertise, position) mis-allocates the seeding budget.
- The algorithmic-expiry assumption (exogenous removal) must be checked against the platform's actual behavior, or the saturation forecast is built on a guessed γ.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Given four curves (standard, delayed peak, two peaks, hub-biased), name the variant each reveals and justify from the signature.
2. Fit SEIR to a diffusion with a visible exposure→activation lag; report σ and the timing implication for seeding.
3. Fit SIS to a seasonal content case; predict the endemic level and the re-peak timing.
4. Simulate network-based SIR on a scale-free graph versus an Erdős–Rényi graph at the same R0; compare final sizes and explain the gap.
5. Run the two-strain competition: the entrenched content versus a new entry at three entry times; plot the displacement windows.
6. Produce the variant-selection memo for a live case: the deviations observed, the variant chosen, the rejected variants, and the fit.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Selection audit
- The deviations from the base shape are listed
- Each maps to a named variant
- The rejected variants are recorded

### Fit integrity
- The variant's parameters are estimated with uncertainty
- The signature is confirmed in the fit
- The base model was not forced

### Structure report
- The contact graph's statistics are reported (if network-based)
- The entry timing is the variable (if competition)
- The incubation is measured (if SEIR)

### Delivery gate
- The variant memo is written
- The timing decisions use the structural parameters
- The next data point is scheduled for the variant's validation

## Anti-Patterns

the base model forced onto a mismatched curve; the variant chosen for fit cosmetics; hubs modeled without their cause; the algorithmic expiry assumed, not checked; the incubation ignored in timing; the competition window missed.

## Decision Heuristic

Before any claim or recommendation, ask:

1. What is the curve doing that the base model cannot do?
2. Does the signature match a named variant, or is this a genuine novelty?
3. Is the new parameter measured, or assumed?
4. Where is the leverage in the variant's structure (incubation, hubs, entry time)?
5. Would the next data point confirm or refute this variant?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not more compartments. It is the simplest model the data admits — and the one structural parameter, in it, that the strategy actually turns on.
