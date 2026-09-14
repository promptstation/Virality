---
name: networks-as-graphs
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Networks as Graphs: The Basic Representation — how to represent a social system as a graph — the right nodes, edges, weights, and time axis — and the limits of the graph you can actually see. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around graph representation, social network graph, nodes and edges, directed network, weighted edges, building a network from data. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of which graph to build when the question is 'who will this content reach', use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: graph-theory-networks
---

# Networks as Graphs: The Basic Representation: Professional Module Builder

## Mission

Produce professional-level material on how to represent a social system as a graph — the right nodes, edges, weights, and time axis — and the limits of the graph you can actually see. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Define the graph: nodes (the units that can spread — people, accounts, brands), edges (the channels of exposure or influence — follows, shares, replies, co-viewing), and the attributes: direction (does A reaching B imply B reaching A?), weight (how strong, how frequent), and time (when the edge was active).
2. Teach the edge-type distinction: a follow edge measures declared attention, a share edge measures active amplification, a reply edge measures dialogue, and an exposure co-occurrence edge measures algorithmic co-delivery — each answers a different question about spread.
3. Show the direction logic: influence is asymmetric (a follower does not necessarily influence the followed); the directed graph is the default for spread questions, and the undirected simplification is a decision with a cost.
4. Build the graph from data: the API pulls, the log joins, the edge aggregation (frequency → weight), and the node universe (who is in scope, who is missing).
5. State the visibility problem: the platform's graph is a sample of the real contact structure — the private messages, the offline sharing, the other platforms — and the representation's claims must be bounded by it.

## Phase 3 — Method and Technique

- The question-to-edge mapping: which edge type answers this question
- The API/log pipeline: the pulls, the joins, the dedup
- The edge aggregation: the weight function (frequency, recency, engagement depth)
- The node-scope decision: the universe, the inclusions, the exclusions
- The visibility memo: what this graph contains, what it cannot see, and the claim bound

## Phase 4 — Analysis and Diagnosis

- Diagnose a representation error before any metric: the wrong edge type (following attention for a question about amplification) invalidates everything downstream.
- Check the direction assumption: a metric computed on an undirected graph for an asymmetric process is a silent model error.
- Read the weights: a uniform-weight graph erases the difference between a casual follow and a daily engagement.
- Audit the node universe: who is missing (the private accounts, the other platforms) and how the absence biases the reach estimates.

## Phase 5 — Application and Design

- Choose the edge type from the question before any data is pulled; the pipeline follows the definition.
- Weight by frequency and recency with the stated function, and test the sensitivity of the downstream metric to the weight choice.
- Time-stamp the edges: spread is a process, and the static graph is a photograph of it.
- Write the visibility memo with every graph deliverable — the bound on the claim is part of the result.

## Phase 6 — Ethics and Boundary Conditions

- The graph of private relationships (DMs, close circles) is the most sensitive data in the system; its use is bound by consent and by the platform's own rules.
- A graph built from a sampled or partial platform view presented as 'the network' is a misrepresentation, however careful the metrics.
- The edge definitions can encode the analyst's theory; the definition choices must be stated, not hidden in the pipeline.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. For a research question ('which creators will this video reach next week?'), choose the node set, the edge type, the direction, and the weight; justify each from the question.
2. Build the graph pipeline spec for a platform: the API pulls, the joins, the dedup, the weight function, the node scope.
3. Compare two edge types (follow vs. share) on the same node set; show how a downstream metric (the hub list) changes, and which edge the question requires.
4. Write the visibility memo for a graph built from a single platform: what is in, what is out, and the bound on the reach claim.
5. Test the direction assumption: compute a metric on the directed and the undirected version and quantify the difference.
6. Time-slice a static graph into weekly graphs; show how the edge dynamics (births, deaths) change the hub list over time.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Definition audit
- The node set is justified
- The edge type matches the question
- The direction decision is stated

### Pipeline spec
- The pulls and joins are documented
- The weight function is stated
- The scope (in/out) is listed

### Bound integrity
- The visibility memo is written
- The sampling limits are named
- The claim does not exceed the bound

### Delivery gate
- The time axis is present
- The sensitivity to the weight choice was tested
- The graph version is dated

## Anti-Patterns

the follower graph as 'the network'; the undirected default without a decision; the uniform weights; the static graph for a process question; the private-graph use without consent; the visibility memo skipped.

## Decision Heuristic

Before any claim or recommendation, ask:

1. Which edge type does this question actually need, and is that what was built?
2. Is the direction right for the process being modeled?
3. What does the weight function measure, and is that the strength the question cares about?
4. Who is not in this graph, and how does that absence bend the numbers?
5. Is the graph dated, and does the claim carry its visibility bound?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not the biggest graph. It is the graph whose edges answer the question, whose bounds are stated, and whose claims stop exactly where the visibility stops.
