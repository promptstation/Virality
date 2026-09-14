---
name: network-data-workflow
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Network Data, Tools, and the Practitioner's Workflow — how the network work is actually done — the toolchain, the data workflow, the scale handling, and the deliverables that make the analysis a standing asset. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around network analysis tools, graph libraries, NetworkX, Gephi, network dashboard, graph versioning, large graph sampling, network report. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of how to stand up the network analysis for a new platform in a week, and keep it current after, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: graph-theory-networks
---

# Network Data, Tools, and the Practitioner's Workflow: Professional Module Builder

## Mission

Produce professional-level material on how the network work is actually done — the toolchain, the data workflow, the scale handling, and the deliverables that make the analysis a standing asset. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Map the toolchain: the graph libraries (the metric implementations, the simulation engines), the visualization layer (the structure read by eye), and the statistical layer (the fits, the calibrations) — the roles each plays, and the handoffs between them.
2. Build the data workflow: the recurring pulls (the cadence, the API limits, the incremental updates), the graph versioning (the snapshot per period, the diff between versions), and the edge validation (the consistency checks, the time alignment across sources).
3. Teach the scale handling: the exact metrics up to a size limit, the sampling strategies beyond it (the node sampling, the edge sampling, the snowball sample) and their bias, and the approximate metrics (the estimator, the confidence, the use case).
4. Cover the data-quality discipline: the bot handling (the filter, the sensitivity of the metrics to the filter), the dedup, the privacy minimization (the aggregation before the storage, the retention policy), and the provenance record (the source, the timestamp, the transformation per version).
5. Produce the standing deliverables: the network report (the shape, the hubs, the communities, the cascade read — the one-page-plus-figures deliverable per period), the living dashboard (the metrics that track: the tail share, the community stability, the bridge state), and the reuse pattern (the next campaign's starting point is the versioned graph and the last report, not a blank notebook).

## Phase 3 — Method and Technique

- The pull spec: the cadence, the endpoints, the incremental logic, the API budget
- The versioning scheme: the snapshot naming, the diff report, the retention
- The scale decision: exact vs. sampled vs. approximate, with the bias note per choice
- The quality gate: the validation checks per version, the bot-filter sensitivity, the provenance record
- The deliverable templates: the network report, the dashboard spec, the handoff note to the next campaign

## Phase 4 — Analysis and Diagnosis

- Diagnose the metric anomaly by pipeline stage: the pull (the missing window), the join (the dedup failure), the filter (the bot shift), or the metric (the scale approximation) — the stage isolation is the workflow's value.
- Read the version diff: what changed between periods (the tail, the communities, the bridges) and whether the change is data (the pull shift) or structure (the real movement).
- Check the approximation's cost: the sampled metric versus the exact metric on the tractable subgraph — the gap is the price of the scale decision, and it is stated.
- Audit the provenance: any number in the report traceable to the source, the timestamp, and the transformation — the traceability is the discipline's test.

## Phase 5 — Application and Design

- Stand up the workflow in a week: the pull spec, the versioning, the quality gate — the minimum pipeline before any metric is trusted.
- Choose the scale mode from the graph size and the question; the sampling is a stated decision with its bias, not a silent shortcut.
- Publish the report on the cadence: the period, the diff, the read — the standing document the team reads, not the ad-hoc notebook.
- Institute the handoff: the next campaign inherits the versioned graph, the last report, and the open questions — the compounding is the point.

## Phase 6 — Ethics and Boundary Conditions

- The graph is the most sensitive aggregate in the organization (it encodes who relates to whom); the access control, the retention, and the minimization are the standing rules, not the per-project decisions.
- The dashboard's public version (the shareable chart) must be the aggregated form; the node-level view is the restricted form, and the boundary is enforced, not aspirational.
- The provenance record is also the audit trail for the claims; without it, the report's numbers are unauditable, and the team's standing is the audit's standing.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Write the pull spec for a new platform: the endpoints, the cadence, the incremental logic, the API budget, and the week-one stand-up plan.
2. Design the versioning and the diff report for a graph that updates weekly; show the version diff that separates the data shift from the structural movement.
3. Run the scale decision on a 5-million-node graph: the exact metrics that remain tractable, the sampling plan for the rest, and the bias notes.
4. Build the quality gate: the validation checks, the bot-filter sensitivity test, and the provenance record for one version.
5. Produce the network report for a period: the shape, the hubs, the communities, the cascade read — in the one-page-plus-figures form.
6. Write the handoff note to the next campaign: the inherited state, the open questions, and the first decision the next team faces — as the standing template.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Pipeline
- The pull spec is live
- The versioning is named and diffed
- The API budget is tracked

### Scale and quality
- The scale mode is chosen and its bias stated
- The quality gate passed for the version
- The provenance is complete

### Deliverables
- The report is on the cadence
- The dashboard tracks the structural metrics
- The handoff note is written

### Delivery gate
- The access control is enforced
- The retention policy is stated
- The next period's pull is scheduled

## Anti-Patterns

the notebook that dies with the project; the silent sampling; the node-level chart shared publicly; the number without its provenance; the bot filter changed without the sensitivity note; the handoff skipped (the next campaign from zero).

## Decision Heuristic

Before any claim or recommendation, ask:

1. Can every number in the report be traced to the source, the time, and the transformation?
2. Was the scale mode a stated decision, with its bias?
3. Does the version diff separate the data from the structure?
4. Is the sensitive form restricted, and the public form aggregated?
5. Does the next campaign start from the inherited state?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not one clean graph. It is a pipeline that versions, a quality gate that audits, a report that compounds, and a handoff that makes the next team faster — so the network knowledge is an asset with a date on it, not a memory with a gap in it.
