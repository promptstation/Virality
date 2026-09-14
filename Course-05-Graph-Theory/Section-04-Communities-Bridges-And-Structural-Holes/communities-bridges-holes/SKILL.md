---
name: communities-bridges-holes
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Communities, Bridges, and Structural Holes — how the community structure — the clusters, the bridges, the structural holes — organizes and constrains spread, and how to map it as a targeting instrument. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around community detection, modularity, Louvain, Leiden, structural holes, Burt, network bridges, cluster structure, resolution limit. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of which communities a piece of content will cross, and who controls the crossing, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: graph-theory-networks
---

# Communities, Bridges, and Structural Holes: Professional Module Builder

## Mission

Produce professional-level material on how the community structure — the clusters, the bridges, the structural holes — organizes and constrains spread, and how to map it as a targeting instrument. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach community detection: modularity as the objective (the density of inside-community edges versus the null), the Louvain/Leiden algorithms, and the output as a hypothesis about the network's organization, not a fact about it.
2. Cover the resolution problem: the detected structure depends on the resolution parameter (and the algorithm), and the 'right' community scale is the one that answers the question — the macro scale for platform strategy, the micro scale for a campaign's target community.
3. Teach the spread reading of the structure: the inside-cluster loop (high density, content recirculates), the between-cluster bottleneck (few edges, content dies at the border), and the two strategic positions — the community play (win the cluster) and the crossing play (own the bridge).
4. Define the bridge: the edge (or the node whose removal disconnects the communities) whose loss splits the network — the articulation points, and the bridge inventory as a strategic map of the crossing points.
5. Teach Burt's structural holes: the ego whose neighbors do not connect to each other spans a hole; the hole is the informational control (the first to know both sides, the broker who can frame the connection) — and the hole-holder as a target class distinct from the hub (the hub is many connections, the hole-holder is the connections between groups).

## Phase 3 — Method and Technique

- The community detection run: the algorithm, the resolution sweep, the stability check across runs
- The community atlas: the size, the density, the overlap, and the between-community edges per community
- The bridge inventory: the articulation points, the betweenness of the inter-community edges
- The hole-holder computation: the ego-network gaps (effective size), the constraint index
- The targeting map: the communities, the bridges, and the hole-holders as the three target classes

## Phase 4 — Analysis and Diagnosis

- Diagnose the stalled crossing: the content won its cluster but died at the border — the between-community edge count is the autopsy.
- Read the resolution honestly: the same graph at two resolutions gives two strategies; the question (platform vs. campaign) picks the scale, and the deliverable says which.
- Distinguish the bridge from the hole-holder in a targeting decision: the bridge is the place to cross, the hole-holder is the person to win — the confusable pair.
- Check the stability: a community that dissolves under a re-run or a small perturbation is a detection artifact, and the strategy built on it inherits the instability.

## Phase 5 — Application and Design

- Build the atlas before the campaign: the communities with their densities, the bridges with their capacities, the hole-holders with their constraints.
- Choose the play from the atlas: the community play (the seed inside the dense cluster) or the crossing play (the seed on the bridge or the hole-holder) — the two plays have different budgets and timelines.
- For the crossing play, target the hole-holder with a broker offer (the connection itself is the value), not the standard influencer offer (the reach is not the point).
- Map the overlap communities (the members of two clusters) as the natural crossing agents — they are the bridges with faces.

## Phase 6 — Ethics and Boundary Conditions

- The community map is a portrait of the groups' relationships; its publication (the 'here is your community' document) has social effects the analyst must anticipate.
- Winning the hole-holder means earning the trust of the broker; the manipulation of the broker's position (the staged exclusivity) corrodes the very control being purchased.
- The bridge inventory is also a vulnerability map (the platform's single points of failure); its dual use (strategy and risk) must be declared.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Run the community detection on a real network at three resolutions; produce the atlas per resolution and the stability check.
2. Build the bridge inventory: the articulation points, the inter-community edges ranked by betweenness, and the crossing-capacity read.
3. Compute the hole-holders: the constraint index, the top twenty, and the distinction from the hub list (the overlap and the difference).
4. Diagnose a stalled crossing from the atlas: the community won, the border lost — the edge count, the bridge state, and the fix.
5. Design the crossing play for a two-community campaign: the hole-holder targets, the broker offer, the overlap agents, and the budget split.
6. Write the dual-use declaration for the bridge inventory: the strategy use, the risk use, and the access control for the document.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Detection integrity
- The resolution is chosen from the question
- The stability check passed
- The atlas is versioned

### Bridge and hole maps
- The articulation points are listed
- The constraint index is computed
- The bridge/hole-holder distinction is drawn

### Play decision
- The community vs. crossing play is chosen from the atlas
- The budget split follows the play
- The overlap agents are named

### Delivery gate
- The dual-use declaration is written
- The access control is set
- The re-detection cadence is scheduled

## Anti-Patterns

one resolution assumed to be 'the' structure; the bridge confused with the hole-holder; the unstable community treated as solid; the atlas published without the social-effect note; the broker offered a reach deal instead of a connection deal; the vulnerability map used without the declaration.

## Decision Heuristic

Before any claim or recommendation, ask:

1. At what resolution was this detected, and does the question require it?
2. Did the structure survive the stability check?
3. Is this target a bridge (a place) or a hole-holder (a person), and does the offer match?
4. Where are the natural crossing agents (the overlaps)?
5. Is the dual use of this map declared and controlled?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a prettier partition. It is a map that shows where the content can cross, who controls the crossing, and which play the atlas actually supports — so the campaign is aimed at the architecture, not at the crowd.
