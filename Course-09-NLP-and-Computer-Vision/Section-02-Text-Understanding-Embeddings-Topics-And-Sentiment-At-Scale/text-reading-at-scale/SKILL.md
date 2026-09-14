---
name: text-reading-at-scale
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Text Understanding: Embeddings, Topics, and Sentiment at Scale — how the text is read at scale — the embedding, the topic, the sentiment and the stance — with the limits named and the honesty held. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around text embedding, semantic similarity, topic modeling, LDA, sentiment analysis, stance detection, sarcasm, polysemy, batch NLP, confidence calibration. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of the corpus needs to be read — the topics, the tone, the positions — and the team needs the read to be usable and honest, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: nlp-computer-vision
---

# Text Understanding: Embeddings, Topics, and Sentiment at Scale: Professional Module Builder

## Mission

Produce professional-level material on how the text is read at scale — the embedding, the topic, the sentiment and the stance — with the limits named and the honesty held. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach the embedding's use: the semantic space (the content's vector, the similarity as the cosine, the retrieval as the nearest neighbor, the clustering as the group) — the three uses, and the fine-tuned embedding per the domain (the general embedding's gap on the domain's language, the fine-tuning on the domain's corpus, the retrieval's improvement). Cover the limits: the surface's match versus the meaning's (the similar words, the different intent), the polysemy (the word's sense, the embedding's average), the sarcasm and the negation (the polarity's flip, the embedding's blindness), and the embedding's drift (the model's version, the space's non-comparability across versions) — the limits, and the design that works around each.
2. Teach the topic modeling: the latent topic (the word's distribution per the topic, the topic's weight per the document — the LDA's classic form), the neural topic model and the embedding's clustering (the modern substitute — the embedding's space clustered, the cluster's topic named by the member's words), the topic's interpretation (the topic's words to the topic's meaning — the analyst's judgment, the named label, the boundary case), and the topic as the organization (the corpus's structure, the content's placement, the niche's map) — the task, the modern form, and the interpretation as the human's step.
3. Teach the sentiment and the stance: the polarity (the positive, the negative, the neutral — the three-class read) and the intensity (the degree, the emotion's type — the anger, the joy, the awe — the arousal's read, the connection to the emotion course), the target (the sentiment's object — the product, the person, the event — the aspect-level read), and the stance (the position on the issue — the for, the against, the neutral; the claim's verification — the supported, the refuted, the unverifiable) — the tasks, the domain shift's cost (the sentiment model on the domain's corpus, the re-fine-tuning), and the sarcasm's problem (the detection as its own task, the flip's correction).
4. Teach the scale practice: the batch reading of the corpus (the pipeline per the model's throughput, the cost per the scale — the small model on the GPU, the large model via the API, the cost per the token and the image), the caching and the dedup (the repeated content's read once, the cache per the content's hash and the model's version), and the incremental read (the new content's read on the arrival, the standing pipeline) — the practice, and the cost's management.
5. Teach the honest read: the confidence per the prediction (the calibrated probability — the model's sureness measured, not assumed), the abstention (the threshold below which the read is withheld — the boundary case to the human), and the human-in-the-loop (the boundary case's review, the correction's record, the fine-tuning's data from the correction) — the honesty per the prediction, and the loop that the correction feeds.
6. Apply the read to the virality system: the content's topic as the niche's placement (the topic's map versus the niche's profile — the alignment, the misplacement), the sentiment and the emotion as the audience's state (the arousal's read, the valence's read — the input to the emotion course's strategy), and the stance as the conversation's structure (the position's map, the claim's verification — the input to the newsjacking's relevance) — the read as the strategy's instrument.

## Phase 3 — Method and Technique

- The embedding's use spec: the space, the similarity, the retrieval, the clustering — per the task, with the domain's fine-tuning
- The topic pipeline: the model (the LDA, the neural, the clustering), the interpretation's step, the niche's map
- The sentiment and stance spec: the polarity, the intensity, the target, the stance — per the domain, with the sarcasm's handling
- The scale spec: the throughput, the cost per the model, the cache, the incremental pipeline
- The honesty spec: the calibration, the abstention's threshold, the human-in-the-loop, the correction's record

## Phase 4 — Analysis and Diagnosis

- Diagnose the read's error by mode: the surface's match (the similar, the different intent), the polysemy (the sense's error), the sarcasm (the polarity's flip), the domain shift (the general model on the domain) — the mode per the case, and the fix (the fine-tuning, the target's read, the sarcasm's task).
- Check the confidence's calibration: the predicted probability versus the realized frequency (the reliability's curve) — the miscalibration, and the correction (the temperature, the isotonic).
- Read the abstention's state: the threshold's placement (the abstention's rate, the error inside the abstained, the error inside the read) — the trade, and the threshold per the cost.
- Audit the human-in-the-loop: the boundary case's review rate, the correction's record, the fine-tuning's update from the correction — the loop's state, and its feed to the next read.

## Phase 5 — Application and Design

- Choose the task per the need: the embedding for the similarity and the retrieval, the topic for the organization, the sentiment for the state, the stance for the position — the task per the strategy's question, not the task's availability.
- Fine-tune per the domain where the gap is measured: the general model's read on the domain's sample, the gap quantified, the fine-tuning on the domain's corpus — the domain's model, earned.
- Run the scale practice with the cost managed: the throughput per the model, the cache per the hash and the version, the incremental on the arrival — the corpus read standing, at the cost stated.
- Hold the honesty per the prediction: the calibration, the abstention, the human-in-the-loop — the read with its sureness, and the correction feeding the next model.

## Phase 6 — Ethics and Boundary Conditions

- The text read at scale is the reading of the people's words, including the private and the sensitive; the corpus's consent (the public versus the private, the scraped versus the licensed) is the read's precondition, and the read's use (the targeting, the moderation) inherits the consent's state.
- The sentiment and the stance read is the state's measurement; its use on the vulnerable state (the distress's detection, the target's selection) is the line — the detection as the care, not the targeting, and the use's policy as the record.
- The topic and the embedding's map is the conversation's structure; its use in the ranking and the moderation is the platform's, and the team's use (the niche's placement, the conversation's read) is bounded by the map's honesty and the data's consent.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Run the embedding's use on a corpus: the similarity, the retrieval, the clustering — with the domain's gap measured and the fine-tuning's plan per the gap.
2. Run the topic pipeline on the corpus: the model's choice, the topic's interpretation, the niche's map — with the boundary case to the analyst.
3. Run the sentiment and the stance read on a domain corpus: the polarity, the intensity, the target, the stance — with the domain shift's cost and the sarcasm's handling.
4. Design the scale spec for the corpus read: the throughput, the cost per the model, the cache, the incremental pipeline — with the cost's budget.
5. Run the honesty spec on a read: the calibration's curve, the abstention's threshold, the human-in-the-loop's review — with the correction's record and the fine-tuning's update.
6. Apply the read to the virality system: the topic's placement versus the niche, the sentiment's state read, the stance's map — with the strategy's input per the read.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Tasks
- The task is per the strategy's question
- The domain's gap is measured
- The limits are named per the read

### Scale
- The throughput and the cost are stated
- The cache is per the hash and the version
- The incremental is standing

### Honesty
- The calibration is measured
- The abstention is per the cost
- The human-in-the-loop ran, with the record

### Delivery gate
- The correction fed the next model
- The consent's state is noted
- The read's use is within the policy

## Anti-Patterns

the sentiment score as the meaning; the topic label without the interpretation; the sarcasm unread; the domain shift unmeasured; the confidence assumed; the abstention absent; the read on the unconsented corpus.

## Decision Heuristic

Before any claim or recommendation, ask:

1. What question is this read for, and is the task per the question?
2. What is the domain's gap, and was the fine-tuning earned?
3. Where is the confidence low, and did the abstention hold?
4. What does the human-in-the-loop correction say, and did it feed the model?
5. Is the corpus's consent noted, and is the use within the policy?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not the labeled corpus. It is the read that names its task, measures its domain, states its confidence, abstains at the boundary, and feeds its correction back — so the meaning reported is the meaning measured, with its sureness, and the strategy's input is honest.
