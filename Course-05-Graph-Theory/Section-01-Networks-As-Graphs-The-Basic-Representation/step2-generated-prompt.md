# Step 2 — Generated Prompt (Result of the Reusable Prompt)

```
Develop a comprehensive, professional-level learning module on **“Networks as Graphs: The Basic Representation”** as part of an advanced course on the structure of social networks and how that structure determines who spreads what, where, and how fast. The module should how to represent a social system as a graph — the right nodes, edges, weights, and time axis — and the limits of the graph you can actually see.

The material should teach the representation layer: what a node and an edge mean here, how to choose them from the question, and how to build the graph from data. Go beyond the assumption that the platform's follower graph is 'the network' and examine what each edge type measures (relationship vs. influence vs. exposure) and which one the research question needs.

Define the graph: nodes (the units that can spread — people, accounts, brands), edges (the channels of exposure or influence — follows, shares, replies, co-viewing), and the attributes: direction (does A reaching B imply B reaching A?), weight (how strong, how frequent), and time (when the edge was active).

Teach the edge-type distinction: a follow edge measures declared attention, a share edge measures active amplification, a reply edge measures dialogue, and an exposure co-occurrence edge measures algorithmic co-delivery — each answers a different question about spread.

Show the direction logic: influence is asymmetric (a follower does not necessarily influence the followed); the directed graph is the default for spread questions, and the undirected simplification is a decision with a cost.

Build the graph from data: the API pulls, the log joins, the edge aggregation (frequency → weight), and the node universe (who is in scope, who is missing).

State the visibility problem: the platform's graph is a sample of the real contact structure — the private messages, the offline sharing, the other platforms — and the representation's claims must be bounded by it.

Include practical methods for working at a professional level:
* The question-to-edge mapping: which edge type answers this question
* The API/log pipeline: the pulls, the joins, the dedup
* The edge aggregation: the weight function (frequency, recency, engagement depth)
* The node-scope decision: the universe, the inclusions, the exclusions
* The visibility memo: what this graph contains, what it cannot see, and the claim bound

Include practical exercises that require the learner to:
1. For a research question ('which creators will this video reach next week?'), choose the node set, the edge type, the direction, and the weight; justify each from the question.
2. Build the graph pipeline spec for a platform: the API pulls, the joins, the dedup, the weight function, the node scope.
3. Compare two edge types (follow vs. share) on the same node set; show how a downstream metric (the hub list) changes, and which edge the question requires.
4. Write the visibility memo for a graph built from a single platform: what is in, what is out, and the bound on the reach claim.
5. Test the direction assumption: compute a metric on the directed and the undirected version and quantify the difference.
6. Time-slice a static graph into weekly graphs; show how the edge dynamics (births, deaths) change the hub list over time.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively, beginning with nodes, edges, and the question-to-edge map, moving through direction, weights, and the pipeline, then to a bounded graph with its visibility memo. Establish clear conceptual distinctions between **node, edge type, direction, weight, and visibility bound** before showing how they interact.

Use professional terminology from graph theory, network science, and social network analysis where relevant, but explain specialized terminology in clear language. Do not make the material sound like generic AI-generated advice; the register should be that of an advanced professional training module used by growth analysts, social researchers, and data scientists working with network data.

Research the subject using high-quality professional and academic sources where external research materially strengthens the material. Prioritize authoritative sources: the network-science literature (Watts and Strogatz 1998, Barabási and Albert 1999, the Watts small-world and Barabási scale-free papers), the centrality and community-detection literature, the diffusion-on-networks models (independent cascade, linear threshold), and the standard network-analysis toolkits. Avoid relying primarily on low-quality SEO articles, generic graph theory networks blogs, or unsupported “best practice” claims. Where useful, distinguish established research findings from professional conventions and informed recommendations.

Pay particular attention to the relationship between this module and principles such as **question-first definition, edge-type honesty, the time axis, and the claim bound**. Connect these concepts to concrete analytical and design decisions rather than discussing them only theoretically.

Create a professional framework that growth analysts, social researchers, and data scientists working with network data could actually use in a real project. The final material should therefore function simultaneously as a learning resource, a practical reference, and a working methodology for targeting, seeding, and analyzing spread on social networks.

Throughout the module, prioritize language that is:

* Precise without being jargon-heavy
* Empirical without being statistical theater
* Confident about what the evidence establishes
* Explicit about what the evidence does not establish
* Conditional where the findings are conditional
* Practical where the decisions are practical

Where a claim depends on context (platform, audience, topic, measurement), explicitly explain the trade-off and the boundary condition rather than presenting it as an absolute rule.

End the module with **Definition audit checklist**, **Pipeline spec checklist**, **Bound integrity checklist**, and a **Delivery gate checklist** that a professional team can use before acting on targeting, seeding, and analyzing spread on social networks.

The final result should be comprehensive enough to serve as an advanced professional training module, but organized clearly enough that a learner can study it progressively and apply each concept in targeting, seeding, and analyzing spread on social networks.
```
