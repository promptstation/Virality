---
name: collaborative-filtering-core
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Collaborative Filtering: The Engine's Core Inference — how the collaborative core works — the similarities, the factorization, the cold start — and how to read its failure modes in the platform's behavior. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around collaborative filtering, matrix factorization, item-item similarity, user-user similarity, cold start, latent factors, Netflix Prize, taste model, popularity bias. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of why the recommendations look like a popularity list, or like a fossil of the user's past, or like nothing for the new user, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: recommendation-engines
---

# Collaborative Filtering: The Engine's Core Inference: Professional Module Builder

## Mission

Produce professional-level material on how the collaborative core works — the similarities, the factorization, the cold start — and how to read its failure modes in the platform's behavior. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach the interaction matrix: the users × the items, the ratings (the watch, the like, the purchase) as the entries — the data the collaborative engine reads, and the sparsity (the observed fraction, the missing as the unknown).
2. Teach the two similarity inferences: the user-user (the users whose interaction patterns match, the 'people like you' recommendation) and the item-item (the items co-interacted, the 'because you watched this' recommendation) — the two directions, the computation, and the cases each one dominates (the item-item for the catalog, the user-user for the community).
3. Teach the matrix factorization: the latent factors (the low-dimensional space where the users and the items live, the dot product as the predicted interaction), the training (the error minimization over the observed entries), and the read (the factors as the taste dimensions — the content's position in the taste space is its identity to the engine).
4. Cover the cold start: the new user (no interactions, the fallback to the demographic, the social graph, the onboarding probe) and the new item (no interactions, the fallback to the content features, the similar-item pool, the exploration allocation) — the two cold starts, and the strategies' exposure to each (the new creator's first audience, the new format's first reach).
5. Teach the failure modes: the popularity bias (the factorization's convergence to the popular, the long tail's starvation, the engine's Matthew effect), the staleness (the taste model as the past's fossil, the drift untracked), and the bubble's seed (the similar-user inference that narrows the exposure, the filter bubble's engine-level origin) — the three modes, the evidence, and the platform's countermeasures (the diversity injection, the exploration, the freshness).

## Phase 3 — Method and Technique

- The interaction-matrix build from a dataset: the entries, the sparsity, the normalization
- The item-item and the user-user similarity computation, with the neighborhood size and the decay
- The factorization run: the factor count, the regularization, the fit, the factor interpretation
- The cold-start design: the new-user and the new-item fallbacks, the exploration allocation
- The failure-mode audit: the popularity concentration, the staleness test, the exposure-narrowing measure

## Phase 4 — Analysis and Diagnosis

- Diagnose the recommendation's character: the popularity list (the bias), the fossil (the staleness), the vacuum (the cold start) — the mode the data shows, and the countermeasure the platform runs against it.
- Read the factor interpretation: the taste dimensions the factorization learned (the content's position per factor) — the engine's map of the taste space, and the strategy's alignment with it.
- Check the exploration's state: the new content's allocation (the test-and-expand, the seed distribution) — the engine's answer to the cold start, and the window the new content has.
- Audit the bubble's seed: the exposure narrowing over the user's history (the topic spread's trend) — the inference's cost, and the diversity injection's presence.

## Phase 5 — Application and Design

- Position the content in the taste space: the factors the content should occupy (from the target audience's factor profile) — the content's identity to the engine, designed, not accidental.
- Manage the cold start deliberately: the new content's metadata and the seed audience (the social graph, the follow structure) — the fallback's inputs, prepared.
- Exploit the exploration window: the test-and-expand's dynamics (the early engagement's role in the expansion) — the launch's timing against the window.
- Monitor the failure modes as the standing read: the popularity concentration in the account's reach, the staleness (the audience's drift), the exposure narrowing — the engine's modes, watched.

## Phase 6 — Ethics and Boundary Conditions

- The taste model is built from the behavior, including the behavior the user did not choose knowingly (the autoplay's watch, the scroll's dwell); the model's use of it is the platform's design, and the strategy's alignment with a model built on the passive behavior carries the designer's share of the question.
- The popularity bias is the long tail's starvation; the strategy that benefits from it (the winner-take-all) is the strategy that collapses the diversity the platform's countermeasures protect — the line is the tail's access, and the platform's stated diversity goals are the direction.
- The bubble's seed is the inference's cost at the population level (the exposure narrowing as the polarization's engine-level contribution); the strategy's contribution to the narrowing (the niche farming) is the share of the cost it owns.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Build the interaction matrix from a dataset (the reviews, the ratings): the sparsity, the normalization, and the two similarity computations — with the neighborhood and the decay chosen.
2. Run the factorization on the matrix: the factor count, the fit, and the factor interpretation (the taste dimensions, the content's position per factor).
3. Design the cold-start fallbacks for a new platform: the new-user (the onboarding probe, the social graph) and the new-item (the features, the similar pool, the exploration) — with the allocation.
4. Audit a platform's recommendation behavior for the three failure modes: the popularity concentration, the staleness, the exposure narrowing — with the evidence per mode.
5. Map a content piece into the learned taste space: the factors it occupies, the target audience's factor profile, and the gap's design fix.
6. Write the ethics note for the alignment strategy: the passive-behavior model, the tail's access, the narrowing's cost — with the line per item.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Model build
- The matrix is built and normalized
- The similarities are computed with the stated parameters
- The factorization's fit is reported

### Interpretation
- The factors are interpreted
- The content's position is mapped
- The target profile is compared

### Cold start
- The new-user and the new-item fallbacks are designed
- The exploration allocation is set
- The window is timed

### Delivery gate
- The failure modes are audited
- The countermeasures are tracked
- The ethics note is written

## Anti-Patterns

the popularity list read as the taste; the factor uninterpreted (the number without the meaning); the cold start assumed handled; the staleness unwatched; the narrowing unmeasured; the alignment strategy without the ethics note.

## Decision Heuristic

Before any claim or recommendation, ask:

1. Which inference is the engine running here — the user-user or the item-item — and what does that imply?
2. What are the factors, and where is the content in the space they define?
3. What is the cold-start fallback for this case, and is it prepared?
4. Which failure mode does the behavior show, and what is the platform's countermeasure?
5. What does the alignment cost the tail, the drift, and the narrowing?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not to reverse-engineer the black box. It is to understand the taste model — its construction, its space, its cold starts, its failure modes — so the content is positioned where the engine can find it, and the cost of the position is named.
