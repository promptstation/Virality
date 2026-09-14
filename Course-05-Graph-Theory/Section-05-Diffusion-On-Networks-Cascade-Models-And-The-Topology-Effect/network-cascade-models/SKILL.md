---
name: network-cascade-models
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Diffusion on Networks: Cascade Models and the Topology Effect — how the cascade processes (independent cascade, linear threshold) run on network topologies, the topology effects they produce, and how to calibrate them from observed spread. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around independent cascade model, linear threshold model, diffusion on networks, cascade simulation, percolation, transmission probability, activation threshold. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of why the same content cascades in one network structure and not another, and what the spread data says about the underlying process, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: graph-theory-networks
---

# Diffusion on Networks: Cascade Models and the Topology Effect: Professional Module Builder

## Mission

Produce professional-level material on how the cascade processes (independent cascade, linear threshold) run on network topologies, the topology effects they produce, and how to calibrate them from observed spread. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Derive the independent cascade: the seeded set, the edge transmission probabilities, the single-shot exposure trials per time step, and the branching-process reading (the expected offspring and the sub/supercritical split).
2. Derive the linear threshold model: the node's threshold, the weighted fraction of active neighbors, the monotone activation — the social-reinforcement logic (people act when enough of their world has acted).
3. Teach the two psychologies: the cascade is the one-exposure decision (the viral hit), the threshold is the accumulation decision (the norm crossing) — and the real behavior is a mixture, with the mix as a parameter of the strategy.
4. Run the simulations on the real graph: the same seed size and parameters on the hub-rich versus the clustered topology; the speed and the reach differences, and the mechanism behind each.
5. Cover the percolation intuition: the active set as a percolating cluster on the network, the critical probability that separates the die-out from the macro-scale cascade, and the network's critical point as a function of its degree distribution.
6. Teach the calibration: from the observed adoption times and the adoption graph, estimate the transmission probabilities (the cascade) or the threshold distribution (the threshold model) — the likelihood from the event times, and the identifiability limits (the two models can fit the same aggregate).

## Phase 3 — Method and Technique

- The cascade simulation on the graph (the seed set, the probabilities, the time-course)
- The threshold-model simulation (the threshold distribution, the weights, the activation order)
- The topology comparison protocol: same process, three shapes, the outcome table
- The percolation critical-probability estimate for the graph
- The calibration fit: the event-time likelihood, the parameter recovery, the identifiability note

## Phase 4 — Analysis and Diagnosis

- Diagnose the process from the adoption signature: the one-shot spikes (the cascade) versus the smooth accumulation (the threshold) — and the mixed signature that both models miss.
- Read the topology effect in the data: the fast early phase (the hubs ignited) and the slow tail (the clusters sustained) — the two-phase signature of the real shape.
- Check the calibration's identifiability: a parameter set that fits the aggregate but not the node-level times is a warning, not a success.
- Locate the operating regime relative to the critical probability: the subcritical case (the campaign is below the network's ignition point) is a structural verdict, not a creative one.

## Phase 5 — Application and Design

- Choose the process from the behavior signature before the simulation; the mix parameter (the cascade/threshold blend) is estimated from the data where possible.
- Simulate on the real graph, not the surrogate: the shape is the variable, and a random surrogate erases the very effect being studied.
- Use the critical-probability estimate as the ignition target: the seed size and the seed placement that push the process supercritical is the computable launch criterion.
- Calibrate per community where the data allow: the transmission and the thresholds are local objects, and the global parameter is their weighted average.

## Phase 6 — Ethics and Boundary Conditions

- The calibration uses individual adoption times — the data that identify who adopted when; its handling is bound by the consent and the anonymization the platform rules require.
- The subcritical verdict (the network is below ignition for this content) can be used to justify cutting a campaign that the sponsor wants; the honesty of the verdict is the analyst's standing, and the alternative (the bridge investment that raises the effective probability) must be offered, not hidden.
- The percolation framing tempts the binary thinking (ignited or not); the real regime is a probability, and the forecast must carry it.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Simulate the independent cascade and the threshold model on the same graph with the same seed; compare the speed and the reach curves and explain the mechanism difference.
2. Run the topology comparison: the same process on the hub-rich, the clustered, and the random surrogates; produce the outcome table and the mechanism notes.
3. Estimate the critical probability for the graph; simulate at 0.8×, 1.0×, and 1.2× and show the regime split.
4. Calibrate the cascade parameters from an observed adoption dataset: the event-time fit, the recovery check, and the identifiability note.
5. Diagnose a real diffusion's process signature: the spike/accumulation decomposition, the topology phases, and the parameter estimates.
6. Write the launch criterion memo: the ignition target (the seed size and placement for supercritical), the data behind it, and the subcritical case's alternative (the bridge investment).

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Process choice
- The behavior signature was read
- The model (or mix) follows from it
- The choice is stated

### Simulation integrity
- The real graph was used
- The parameter set is stated
- The topology comparison was run

### Calibration
- The event-time fit was shown
- The identifiability limits are noted
- The per-community parameters were checked

### Delivery gate
- The ignition criterion is computable
- The subcritical alternative was offered
- The data-consent bound is recorded

## Anti-Patterns

the random surrogate for a real-shape question; the single model for a mixed signature; the aggregate fit claimed as the node-level truth; the subcritical verdict hidden; the consent bound skipped; the binary ignited/not framing.

## Decision Heuristic

Before any claim or recommendation, ask:

1. Which psychology does the adoption signature show — one-shot or accumulation?
2. Was the simulation run on the real shape, and what did the comparison show?
3. Where is the operating point relative to the critical probability?
4. Does the calibration hold at the node level, or only in the aggregate?
5. If the verdict is subcritical, was the alternative (the bridge investment) offered?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a cleaner simulation. It is a process the data support, a shape the simulation respects, and an ignition target that can be computed — so the launch decision rests on the network's physics, not on its photograph.
