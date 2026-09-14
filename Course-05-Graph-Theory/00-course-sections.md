# Course 05 — Graph Theory: Mapping Social Networks to Identify Super-Spreaders, Nodes, Bridges, and Clusters (Researched Curriculum Outline)

Source: `uploads/Virality.txt`, entry 5. Section count: 8 (compressed to ≤15). Progression: beginner → expert.

**Networks as Graphs: The Basic Representation**

**Summary:** The ground floor: representing a social system as a graph — nodes (people, accounts, brands) and edges (follows, shares, mentions, co-engagement) — with the attributes that make it a workable object: directed versus undirected, weighted versus unweighted, and the time axis. The section covers how to build a graph from real data (platform APIs, engagement logs, mention networks), what each edge type actually measures (relationship, influence, exposure), and the data-pitfall list (sampling bias, the platform's hidden graph, the difference between the network you can see and the network that exists).

**Absorbed Skill:** Model a social system as a graph with the right node, edge, and weight definitions for the research question; Build a graph from raw platform data and state the representation's limits.

**Node Metrics: Centrality and Who Matters**

**Summary:** The core toolkit for 'who matters'. The section defines and derives the centrality measures — degree (in/out), betweenness (the broker), closeness (the fast reacher), eigenvector/PageRank (the connected-to-important) — explains what each actually captures in a spread process, the classic cases where they disagree (the hub that is central but inert, the bridge that matters more than the hub), and the calibration of centrality to real influence (engagement quality, audience overlap, temporal activity). It closes with the practical read: which centrality answers which targeting question, and why no single number is 'the influencer score'.

**Absorbed Skill:** Compute and interpret the standard centrality measures and explain what each captures in a spread process; Diagnose where the centralities disagree and choose the right one for a targeting or seeding question.

**Network Topology: Small Worlds, Scale-Free Structures, and Why Shape Matters for Spread**

**Summary:** The shapes that real social networks have, and why the shape is a variable in the spread equation. The section covers the three canonical topologies — the random (Erdős–Rényi), the small-world (Watts–Strogatz: high clustering plus short paths), the scale-free (Barabási–Albert: preferential attachment, the power-law degree distribution, the hubs) — with the measurements that identify them (clustering coefficient, average path length, the degree-distribution fit) and the diffusion consequences of each: why hubs make spread explosive but fragile, why clusters trap content inside communities, and why the real network (a small-world with a heavy tail) is the case that matters.

**Absorbed Skill:** Characterize a network's topology (clustering, path length, degree distribution) and classify it against the canonical models; Predict the diffusion consequences of the topology — speed, reach, fragility — from the measured shape.

**Communities, Bridges, and Structural Holes**

**Summary:** The internal architecture of the network. The section covers community detection (modularity, the Louvain/Leiden methods, the resolution problem), the meaning of the community structure for spread (the inside-cluster loop, the between-cluster bottleneck), the bridges that connect communities (their identification and their strategic scarcity), and Burt's structural holes — the gaps between the ego's clusters that create informational control for the node that spans them. It closes with the practical map: the community atlas of a target network, the bridge inventory, and the hole-holders as a distinct target class.

**Absorbed Skill:** Detect and interpret the community structure of a network, including the resolution and stability of the detection; Identify the bridges and the structural-hole holders, and use them as a distinct targeting class.

**Diffusion on Networks: Cascade Models and the Topology Effect**

**Summary:** How the spread actually runs on the graph. The section teaches the two canonical diffusion processes — the independent cascade (each edge has a transmission probability, the exposure trials are independent) and the linear threshold model (each node activates when the fraction of active neighbors crosses its threshold, the social-reinforcement logic) — with the derivations, the parameter meanings, and the simulations. It covers the topology effects: how the same process runs differently on a hub-rich graph versus a clustered graph, the role of the clusters (the ignition vs. the sustain) and the bridges (the crossing), and the percolation intuition (the subcritical vs. supercritical regime on a network). It closes with the calibration: estimating the process parameters from observed spread data on a real network.

**Absorbed Skill:** Simulate and interpret the independent cascade and linear threshold models on real network topologies; Explain and predict the topology effects on cascade speed and reach, and calibrate the process parameters from data.

**Identifying Super-Spreaders: From Centrality to Verified Influence**

**Summary:** The operational core: finding the nodes whose spread is disproportionately large — and knowing which of them will actually amplify. The section goes beyond the centrality scores: the distinction between the structurally central (the position) and the behaviorally super (the observed propagation), the temporal dimension (the super-spreader is active at the moment the content is live), the audience-quality overlay (the overlap with the target, the engagement depth, the cross-posting habit), and the cost model (the reach per unit of spend or effort). It covers the empirical evidence on super-spreading in real social data (the heavy tail of sharing behavior) and the failure modes: the dormant hub, the echo-chamber amplifier, the bought audience, and the one-hit wonder. It closes with the seeding decision: the verified list, the budget allocation, and the validation design.

**Absorbed Skill:** Identify true super-spreaders by combining structural position, observed propagation, temporal activity, and audience quality; Allocate a seeding budget across the verified list and design the validation that the seeds actually amplified.

**Network Data, Tools, and the Practitioner's Workflow**

**Summary:** The hands-on layer: building and analyzing networks end to end. The section covers the toolchain (the standard network libraries and their graph metrics, the visualization layer, the statistical software for the fits), the data workflow in practice (the recurring pulls, the versioning of the graph, the update cadence), the scale problems (the million-node graph, the sampling strategies, the approximate metrics), and the data-quality discipline (the edge validation, the bot handling, the time alignment). It closes with the practitioner's deliverables: the network report (the shape, the hubs, the communities, the cascade read), the living dashboard (the metrics that track over time), and the reuse pattern (the next campaign starts from the versioned graph, not from zero).

**Absorbed Skill:** Run the end-to-end network workflow — pulls, versioning, metrics, visualization, reporting — at the scale of real social data; Maintain a living network dashboard and version the graph so each campaign inherits the last one's state.

**Synthesis: Network Strategy for Virality**

**Summary:** The capstone: the network as the strategy. The section integrates the course — the representation, the centralities, the topology, the communities, the cascade models, the super-spreaders, and the workflow — into a single network-aware virality strategy: reading the target network (the atlas), choosing the play (the community play, the crossing play, the hub ignition), designing the seed set (the verified list with its budget), timing against the network's dynamics (the activity windows, the community rhythms), and measuring the structural outcome (the crossing achieved, the community won, the tail captured). It closes with the synthesis case: a full campaign from the network report to the post-campaign structural audit, with the post-audit feeding the versioned graph and the next report.

**Absorbed Skill:** Build a network-aware virality strategy: the play choice, the seed design, the timing, and the structural measurement; Run the post-campaign structural audit and fold the results into the standing network asset.
