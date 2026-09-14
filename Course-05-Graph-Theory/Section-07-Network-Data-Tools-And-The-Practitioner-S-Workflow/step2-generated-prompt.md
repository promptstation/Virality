# Step 2 — Generated Prompt (Result of the Reusable Prompt)

```
Develop a comprehensive, professional-level learning module on **“Network Data, Tools, and the Practitioner's Workflow”** as part of an advanced course on the structure of social networks and how that structure determines who spreads what, where, and how fast. The module should how the network work is actually done — the toolchain, the data workflow, the scale handling, and the deliverables that make the analysis a standing asset.

The material should teach the operations layer: the tools, the pipeline, the scale, and the standing deliverables that keep the network knowledge alive between campaigns. Go beyond the one-off analysis that dies in a notebook and examine the scale and the sampling — what can be computed exactly at what size, and what the approximations cost.

Map the toolchain: the graph libraries (the metric implementations, the simulation engines), the visualization layer (the structure read by eye), and the statistical layer (the fits, the calibrations) — the roles each plays, and the handoffs between them.

Build the data workflow: the recurring pulls (the cadence, the API limits, the incremental updates), the graph versioning (the snapshot per period, the diff between versions), and the edge validation (the consistency checks, the time alignment across sources).

Teach the scale handling: the exact metrics up to a size limit, the sampling strategies beyond it (the node sampling, the edge sampling, the snowball sample) and their bias, and the approximate metrics (the estimator, the confidence, the use case).

Cover the data-quality discipline: the bot handling (the filter, the sensitivity of the metrics to the filter), the dedup, the privacy minimization (the aggregation before the storage, the retention policy), and the provenance record (the source, the timestamp, the transformation per version).

Produce the standing deliverables: the network report (the shape, the hubs, the communities, the cascade read — the one-page-plus-figures deliverable per period), the living dashboard (the metrics that track: the tail share, the community stability, the bridge state), and the reuse pattern (the next campaign's starting point is the versioned graph and the last report, not a blank notebook).

Include practical methods for working at a professional level:
* The pull spec: the cadence, the endpoints, the incremental logic, the API budget
* The versioning scheme: the snapshot naming, the diff report, the retention
* The scale decision: exact vs. sampled vs. approximate, with the bias note per choice
* The quality gate: the validation checks per version, the bot-filter sensitivity, the provenance record
* The deliverable templates: the network report, the dashboard spec, the handoff note to the next campaign

Include practical exercises that require the learner to:
1. Write the pull spec for a new platform: the endpoints, the cadence, the incremental logic, the API budget, and the week-one stand-up plan.
2. Design the versioning and the diff report for a graph that updates weekly; show the version diff that separates the data shift from the structural movement.
3. Run the scale decision on a 5-million-node graph: the exact metrics that remain tractable, the sampling plan for the rest, and the bias notes.
4. Build the quality gate: the validation checks, the bot-filter sensitivity test, and the provenance record for one version.
5. Produce the network report for a period: the shape, the hubs, the communities, the cascade read — in the one-page-plus-figures form.
6. Write the handoff note to the next campaign: the inherited state, the open questions, and the first decision the next team faces — as the standing template.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively, beginning with the toolchain and the pull spec, moving through the versioning, the scale, and the quality gate, then to the standing report, the dashboard, and the handoff. Establish clear conceptual distinctions between **pull, version, approximation, and provenance** before showing how they interact.

Use professional terminology from graph theory, network science, and social network analysis where relevant, but explain specialized terminology in clear language. Do not make the material sound like generic AI-generated advice; the register should be that of an advanced professional training module used by growth analysts, social researchers, and data scientists working with network data.

Research the subject using high-quality professional and academic sources where external research materially strengthens the material. Prioritize authoritative sources: the network-science literature (Watts and Strogatz 1998, Barabási and Albert 1999, the Watts small-world and Barabási scale-free papers), the centrality and community-detection literature, the diffusion-on-networks models (independent cascade, linear threshold), and the standard network-analysis toolkits. Avoid relying primarily on low-quality SEO articles, generic graph theory networks blogs, or unsupported “best practice” claims. Where useful, distinguish established research findings from professional conventions and informed recommendations.

Pay particular attention to the relationship between this module and principles such as **the stage isolation, the stated approximation, the traceable number, and the compounding handoff**. Connect these concepts to concrete analytical and design decisions rather than discussing them only theoretically.

Create a professional framework that growth analysts, social researchers, and data scientists working with network data could actually use in a real project. The final material should therefore function simultaneously as a learning resource, a practical reference, and a working methodology for targeting, seeding, and analyzing spread on social networks.

Throughout the module, prioritize language that is:

* Precise without being jargon-heavy
* Empirical without being statistical theater
* Confident about what the evidence establishes
* Explicit about what the evidence does not establish
* Conditional where the findings are conditional
* Practical where the decisions are practical

Where a claim depends on context (platform, audience, topic, measurement), explicitly explain the trade-off and the boundary condition rather than presenting it as an absolute rule.

End the module with **Pipeline checklist**, **Scale and quality checklist**, **Deliverables checklist**, and a **Delivery gate checklist** that a professional team can use before acting on targeting, seeding, and analyzing spread on social networks.

The final result should be comprehensive enough to serve as an advanced professional training module, but organized clearly enough that a learner can study it progressively and apply each concept in targeting, seeding, and analyzing spread on social networks.
```
