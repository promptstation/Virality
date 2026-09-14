# Step 2 — Generated Prompt (Result of the Reusable Prompt)

```
Develop a comprehensive, professional-level learning module on **“Network Topology: Small Worlds, Scale-Free Structures, and Why Shape Matters for Spread”** as part of an advanced course on the structure of social networks and how that structure determines who spreads what, where, and how fast. The module should how the measured shape of a network — small-world, scale-free, the heavy tail — determines the speed, the reach, and the fragility of spread.

The material should teach the topology layer: the canonical shapes, the measurements that identify them, and the diffusion consequences each one carries. Go beyond the intuition that 'the network is just big' without knowing its shape and examine the degree distribution's tail — the small fraction of nodes that carry most of the spread, and the strategy that follows.

Teach the three canonical topologies: the Erdős–Rényi random graph (the null model, the benchmark), the Watts–Strogatz small world (high clustering + short paths, the 'six degrees' structure), and the Barabási–Albert scale-free graph (preferential attachment, the power-law degree distribution).

Define the measurements: the clustering coefficient (how tight the neighbors are), the average shortest-path length (how fast information crosses), and the degree distribution (the histogram of connections, and its tail fit).

Show the identification workflow: fit the degree distribution (power-law exponent or not), measure the clustering against the random null, measure the path length — and name the topology the data supports.

Teach the diffusion consequences: the hub-rich tail makes the early phase explosive (a hub hit cascades) but the outcome fragile (miss the hubs, miss the cascade); the clusters trap content (high inside-cluster clustering, few between-cluster edges); the short paths make the whole network reachable in a few steps.

Read the real case: social networks are small-worlds with heavy tails — the combination that makes virality both possible (the paths are short) and unpredictable (the hubs decide the outcome) — and the two failure modes that follow (the echo chamber, the single-point dependence).

Include practical methods for working at a professional level:
* The clustering coefficient (global and local) and its random-null comparison
* The average path length (and its estimator for large graphs)
* The degree-distribution fit: the tail check, the exponent, the goodness-of-fit
* The topology classification memo: the measurements, the nulls, the verdict
* The diffusion simulation per topology: the same R0 on the three shapes, the outcome comparison

Include practical exercises that require the learner to:
1. Classify a real network: the clustering, the path length, the degree-distribution fit — and the topology verdict with the null comparisons.
2. Quantify the hub dependence: the top-1% degree nodes' share of the observed propagation, per community, over time.
3. Run the same diffusion simulation on the three canonical topologies at the same R0; plot and explain the outcome differences.
4. Diagnose a trapped community: the local clustering, the between-cluster edge count, and the bridge-building plan.
5. Design the two-layer seeding (hubs + bridges) for a cross-community campaign, with the simulation pre-mortem of the two failure modes.
6. Track the topology over a growth phase: the tail's evolution, the platform-change effect, and the strategy update it forces.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively, beginning with the canonical shapes and their measurements, moving through the identification and the diffusion consequences, then to a topology-informed seeding design with its pre-mortem. Establish clear conceptual distinctions between **clustering, path length, degree tail, hub, and bridge** before showing how they interact.

Use professional terminology from graph theory, network science, and social network analysis where relevant, but explain specialized terminology in clear language. Do not make the material sound like generic AI-generated advice; the register should be that of an advanced professional training module used by growth analysts, social researchers, and data scientists working with network data.

Research the subject using high-quality professional and academic sources where external research materially strengthens the material. Prioritize authoritative sources: the network-science literature (Watts and Strogatz 1998, Barabási and Albert 1999, the Watts small-world and Barabási scale-free papers), the centrality and community-detection literature, the diffusion-on-networks models (independent cascade, linear threshold), and the standard network-analysis toolkits. Avoid relying primarily on low-quality SEO articles, generic graph theory networks blogs, or unsupported “best practice” claims. Where useful, distinguish established research findings from professional conventions and informed recommendations.

Pay particular attention to the relationship between this module and principles such as **shape as variable, the tail that carries the spread, the two failure modes, and the simulation pre-mortem**. Connect these concepts to concrete analytical and design decisions rather than discussing them only theoretically.

Create a professional framework that growth analysts, social researchers, and data scientists working with network data could actually use in a real project. The final material should therefore function simultaneously as a learning resource, a practical reference, and a working methodology for targeting, seeding, and analyzing spread on social networks.

Throughout the module, prioritize language that is:

* Precise without being jargon-heavy
* Empirical without being statistical theater
* Confident about what the evidence establishes
* Explicit about what the evidence does not establish
* Conditional where the findings are conditional
* Practical where the decisions are practical

Where a claim depends on context (platform, audience, topic, measurement), explicitly explain the trade-off and the boundary condition rather than presenting it as an absolute rule.

End the module with **Classification checklist**, **Hub analysis checklist**, **Seeding design checklist**, and a **Delivery gate checklist** that a professional team can use before acting on targeting, seeding, and analyzing spread on social networks.

The final result should be comprehensive enough to serve as an advanced professional training module, but organized clearly enough that a learner can study it progressively and apply each concept in targeting, seeding, and analyzing spread on social networks.
```
