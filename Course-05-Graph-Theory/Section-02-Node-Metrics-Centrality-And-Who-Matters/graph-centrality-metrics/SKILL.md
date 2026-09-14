---
name: graph-centrality-metrics
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Node Metrics: Centrality and Who Matters — what the centrality measures capture — degree, betweenness, closeness, eigenvector — when they disagree, and how to choose among them for a spread question. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around centrality, betweenness centrality, degree centrality, PageRank, eigenvector centrality, closeness centrality, influencer score, hub and bridge. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of which node to seed, and why the most-followed node is not automatically the answer, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: graph-theory-networks
---

# Node Metrics: Centrality and Who Matters: Professional Module Builder

## Mission

Produce professional-level material on what the centrality measures capture — degree, betweenness, closeness, eigenvector — when they disagree, and how to choose among them for a spread question. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Define degree centrality (in/out): the volume of a node's connections — the reach proxy, and its failure (a high-follower node with a dormant audience).
2. Define betweenness centrality: the fraction of shortest paths through the node — the broker who connects clusters, and the strategic value of the bridge versus the hub in a diffusion.
3. Define closeness centrality: the average distance to all other nodes — the fast-reacher, and its reading for speed-focused goals.
4. Define eigenvector/PageRank centrality: the centrality of the neighbors, weighted recursively — the connected-to-important measure, and its sensitivity to the network's hub structure.
5. Teach the disagreement structure: the four measures rank nodes differently, and the difference is information — the hub-inert case, the bridge-prime case, the echo-chamber case (high degree, zero betweenness) — each with its strategic meaning.
6. Cover the calibration: centrality is a structural claim; influence is an observed behavior — the engagement-quality overlay (actual share propagation from the node's posts, audience overlap, activity recency) that converts structure into a working score.

## Phase 3 — Method and Technique

- The four centralities computed on the graph (with the standard toolkits)
- The rank-disagreement table: the top-N per measure, the nodes that appear in some but not others
- The structural-role labels: hub, bridge, broker, periphery — assigned from the profile, not one number
- The influence overlay: the observed propagation metrics joined to the node
- The targeting shortlist: the nodes scored by the role the strategy needs

## Phase 4 — Analysis and Diagnosis

- Diagnose the seeding miss by role: a hub that did not propagate (inert audience), a bridge that was skipped (the betweenness was not read), the echo chamber that amplified only to itself.
- Read the profile, not the score: the node's full centrality vector is the diagnostic; a single number is a summary that hides the role.
- Check the overlay: a structurally central node with weak observed propagation is a structure-behavior mismatch — trust the behavior, re-check the structure.
- Detect the metric gaming: bought followers inflate the degree; the betweenness and the overlay are the checks that survive it.

## Phase 5 — Application and Design

- Choose the measure from the role the strategy needs: volume (degree), cross-cluster reach (betweenness), speed (closeness), prestige (eigenvector) — and state the choice.
- Build the shortlist from the profile (the role label), then rank within the role; the role filter is the strategy, the score is the ordering.
- Overlay the observed propagation before the spend: the structural candidate list is the hypothesis, the behavior is the evidence.
- Time the seeding to the node's activity window — centrality is a property of the graph, but propagation is a property of the moment.

## Phase 6 — Ethics and Boundary Conditions

- The centrality of a node is computed from a graph that includes sensitive relationship data; the publication of node-level scores is a privacy decision, not a default.
- A 'top influencers' list is a public signal that the listed nodes can (and do) monetize; publishing one changes the market it describes.
- The metric can be gamed (the bought degree, the astroturfed betweenness); the overlay and the audit are the defense, and the audit must be stated.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Compute the four centralities on a network; produce the rank-disagreement table and label the structural roles of the top twenty nodes.
2. Take a seeding that failed; reconstruct the seeded node's profile and the overlay, and diagnose the mismatch (structure vs. behavior).
3. Design the targeting shortlist for a cross-cluster campaign: the role needed, the measure chosen, the overlay applied, the top ten with their profiles.
4. Quantify the metric-gaming effect: a node with bought followers — which measures catch it, and how much do the scores shift after the cleanup?
5. Build the influence-overlay pipeline: the observed propagation metrics, the join to the node, the score, and its update cadence.
6. Write the privacy and market-signal memo for publishing a node-level score list: the data, the consent, the effect on the market it describes.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Metric choice
- The role the strategy needs is named
- The measure follows from the role
- The choice is stated in the deliverable

### Profile integrity
- The full vector is shown for the shortlist
- The role labels are assigned
- The disagreements are read, not averaged away

### Overlay evidence
- The observed propagation is joined
- The structure-behavior mismatches are flagged
- The update cadence is set

### Delivery gate
- The gaming checks were run
- The privacy memo is written
- The shortlist is versioned

## Anti-Patterns

the follower count as the score; the single number presented as the profile; the hub seeded on degree alone; the bridge skipped because the betweenness was not computed; the published list without the privacy memo; the overlay skipped (structure without behavior).

## Decision Heuristic

Before any claim or recommendation, ask:

1. What role does the strategy need, and does the chosen measure capture that role?
2. What does the full profile say that the headline number hides?
3. Has this node actually propagated before, and does the structure match the behavior?
4. Could the scores be gamed, and which measure is the check?
5. Is the list versioned, and is the privacy decision recorded?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not a ranking. It is a role, a measure that matches it, and a behavior overlay that proves it — so the seed lands on a node that is structurally placed and observed to act.
