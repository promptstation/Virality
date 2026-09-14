---
name: network-topology-diffusion
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Network Topology: Small Worlds, Scale-Free Structures, and Why Shape Matters for Spread — how the measured shape of a network — small-world, scale-free, the heavy tail — determines the speed, the reach, and the fragility of spread. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around small-world network, scale-free network, power-law degree distribution, preferential attachment, clustering coefficient, average path length, network topology. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of why a piece of content exploded in one community and died in another of the same size, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: graph-theory-networks
---

# Network Topology: Small Worlds, Scale-Free Structures, and Why Shape Matters for Spread: Professional Module Builder

## Mission

Produce professional-level material on how the measured shape of a network — small-world, scale-free, the heavy tail — determines the speed, the reach, and the fragility of spread. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach the three canonical topologies: the Erdős–Rényi random graph (the null model, the benchmark), the Watts–Strogatz small world (high clustering + short paths, the 'six degrees' structure), and the Barabási–Albert scale-free graph (preferential attachment, the power-law degree distribution).
2. Define the measurements: the clustering coefficient (how tight the neighbors are), the average shortest-path length (how fast information crosses), and the degree distribution (the histogram of connections, and its tail fit).
3. Show the identification workflow: fit the degree distribution (power-law exponent or not), measure the clustering against the random null, measure the path length — and name the topology the data supports.
4. Teach the diffusion consequences: the hub-rich tail makes the early phase explosive (a hub hit cascades) but the outcome fragile (miss the hubs, miss the cascade); the clusters trap content (high inside-cluster clustering, few between-cluster edges); the short paths make the whole network reachable in a few steps.
5. Read the real case: social networks are small-worlds with heavy tails — the combination that makes virality both possible (the paths are short) and unpredictable (the hubs decide the outcome) — and the two failure modes that follow (the echo chamber, the single-point dependence).

## Phase 3 — Method and Technique

- The clustering coefficient (global and local) and its random-null comparison
- The average path length (and its estimator for large graphs)
- The degree-distribution fit: the tail check, the exponent, the goodness-of-fit
- The topology classification memo: the measurements, the nulls, the verdict
- The diffusion simulation per topology: the same R0 on the three shapes, the outcome comparison

## Phase 4 — Analysis and Diagnosis

- Diagnose a community's spread behavior by its local topology: the high-clustering trap (content loops inside), the low-betweenness isolation (nothing leaves).
- Read the tail: the top 1% of nodes by degree — what share of the observed propagation did they carry? The answer is the hub-dependence measure.
- Detect the topology shift over time (the platform change, the growth phase): the degree distribution's tail is a living object, and the strategy must track it.
- Separate the topology effect from the content effect in a cross-community comparison: same content, different shapes — the difference is the structure.

## Phase 5 — Application and Design

- Measure the topology of the target network before the campaign: the classification memo is the first deliverable, not an appendix.
- Design the seeding from the tail: the hub list is the primary seed set, the bridge list (the betweenness of the hubs' neighborhoods) is the secondary — the two-layer design.
- For the trapped community, the strategy is the bridge, not the hub: the cross-cluster edge is the scarce asset, and it is bought or built deliberately.
- Simulate the two failure modes (the hub miss, the cluster trap) on the real graph before launch; the simulation is the pre-mortem.

## Phase 6 — Ethics and Boundary Conditions

- The topology of a real social graph encodes people's relationships; its analysis is bound by the consent and the platform rules that govern the underlying data.
- The hub-dependence insight can be weaponized (the single-node buyout that captures a cascade); the line is the legitimacy of the influence being placed.
- The echo-chamber diagnosis is also a value judgment about the community; the measurement is neutral, and the recommendation must say what it optimizes.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Classify a real network: the clustering, the path length, the degree-distribution fit — and the topology verdict with the null comparisons.
2. Quantify the hub dependence: the top-1% degree nodes' share of the observed propagation, per community, over time.
3. Run the same diffusion simulation on the three canonical topologies at the same R0; plot and explain the outcome differences.
4. Diagnose a trapped community: the local clustering, the between-cluster edge count, and the bridge-building plan.
5. Design the two-layer seeding (hubs + bridges) for a cross-community campaign, with the simulation pre-mortem of the two failure modes.
6. Track the topology over a growth phase: the tail's evolution, the platform-change effect, and the strategy update it forces.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Classification
- The three measurements are computed
- The null comparisons are shown
- The verdict is stated from the evidence

### Hub analysis
- The tail's share of propagation is quantified
- The hub list is versioned
- The single-point dependence is flagged

### Seeding design
- The two-layer design (hubs + bridges) is specified
- The failure-mode simulations were run
- The bridge plan for trapped communities is named

### Delivery gate
- The topology is tracked over time
- The consent bound is recorded
- The pre-mortem results are in the launch memo

## Anti-Patterns

the network treated as uniform; the degree histogram read as 'big' without the tail fit; the hub seeded without the behavior overlay; the bridge ignored; the topology assumed static; the echo-chamber diagnosis made as a value verdict.

## Decision Heuristic

Before any claim or recommendation, ask:

1. What shape is this network, and what did the null comparison show?
2. How much of the spread does the tail carry, and what happens if the tail is missed?
3. Is the target community trapped, and where is its bridge?
4. Did the simulation pre-mortem run, and what did it find?
5. Has the shape changed since the last measurement?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a cleaner graph. It is a shape you have measured, a tail you have read, and a seeding design that survives its own pre-mortem — so the structure works for the campaign instead of against it.
