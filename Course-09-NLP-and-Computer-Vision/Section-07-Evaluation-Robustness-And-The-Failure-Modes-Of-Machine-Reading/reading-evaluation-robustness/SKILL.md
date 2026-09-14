---
name: reading-evaluation-robustness
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Evaluation, Robustness, and the Failure Modes of Machine Reading — how the reading's honesty is built — the evaluation per the task, the robustness per the perturbation, the defense per the mode, and the culture that keeps it standing. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around model evaluation, precision recall, calibration, out-of-distribution, adversarial example, model drift, bias audit, hallucination, prompt injection, monitoring. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of the reading system works on the sample — where does it fail, and does the team know before the audience does, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: nlp-computer-vision
---

# Evaluation, Robustness, and the Failure Modes of Machine Reading: Professional Module Builder

## Mission

Produce professional-level material on how the reading's honesty is built — the evaluation per the task, the robustness per the perturbation, the defense per the mode, and the culture that keeps it standing. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Teach the evaluation's design: the metric per the task (the classification's accuracy and its limit per the class's balance — the precision and the recall per the class, the F per the need; the regression's error per the scale; the generation's faithfulness — the output's ground truth, the citation's presence, the refusal's appropriateness), the test set's honesty (the unseen per the content, the out-of-distribution per the domain, the temporal holdout per the drift — the set per the claim), and the human's evaluation (the annotation's agreement — the inter-annotator, the rubric per the task, the human's read as the reference with its own error) — the design per the claim, not per the convenience.
2. Teach the robustness: the input's perturbation (the paraphrase — the meaning's invariant, the surface's changed; the noise — the recognition's error, the frame's corruption; the adversarial example — the input designed to break the model — the perturbation per the mode, with the effect measured), the model's drift (the data's drift — the input's distribution's change; the concept's drift — the label's meaning's change; the drift's detection — the performance's trend, the distribution's monitor), and the deployment's monitoring (the standing evaluation — the per-cycle's metric on the fresh data, the drift's alert, the model's version's comparison) — the robustness per the mode, and the monitor that catches it.
3. Catalog the failure modes: the systematic error per the group (the bias — the performance's gap per the attribute: the language, the accent, the demographic, the content's type — the gap measured, the cause examined, the correction per the gap), the confabulation per the generation (the hallucination — the output's claim without the ground truth — the frequency, the type, the grounding's absence), the overconfidence per the calibration (the sureness without the accuracy — the miscalibration per the group, the abstention's absence), and the manipulation per the input (the prompt's attack — the input that changes the model's behavior; the adversarial's attack — the input that breaks the detection — the attack per the form, the detection, the input's validation) — the four modes, per the signature.
4. Teach the defense per the mode: the bias's audit and the correction (the gap's measure per the attribute, the data's re-sampling, the model's re-training, the monitor's standing), the hallucination's grounding and the citation (the output's claim to the source, the citation's presence, the refusal per the unknown), the calibration's measurement and the abstention (the reliability per the group, the temperature's correction, the threshold per the cost), and the attack's detection and the input's validation (the input's schema, the content's filter, the behavior's monitor, the model's hardening) — the defense per the mode, with the test per the defense.
5. Teach the evaluation's culture: the failure's record (the failure per the case, the mode, the cause, the correction — the standing log), the correction's feed (the correction to the data, to the model, to the spec — the loop's close), and the model's version and the evaluation's standing (the version per the model, the evaluation per the cycle, the comparison per the version) — the culture per the record, and the standard: the reading system that reports its error, its drift, its boundary — the honesty as the quality.

## Phase 3 — Method and Technique

- The evaluation spec: the metric per the task, the test set per the claim, the human's rubric — per the system, with the cycle
- The robustness spec: the perturbation per the mode, the drift's monitor, the deployment's evaluation — per the system, with the alert
- The failure catalog: the mode per the signature, the case per the mode, the cause per the case — the standing log
- The defense spec: the defense per the mode, the test per the defense, the monitor per the defense — per the system, with the owner
- The culture spec: the record's template, the feed's rule, the version's comparison — per the cycle, with the review

## Phase 4 — Analysis and Diagnosis

- Diagnose the deployment's failure by mode: the bias's signature (the gap per the attribute), the hallucination's signature (the claim without the ground), the miscalibration's signature (the sureness without the accuracy), the attack's signature (the behavior's change per the input) — the mode per the case, and the defense per the mode.
- Check the evaluation's honesty: the test set from the training's distribution (the in-distribution's illusion), the metric without the class's balance (the accuracy's lie), the human's reference without the agreement's measure — the evaluation's breach, and the re-design.
- Read the drift in the monitor: the data's drift (the input's distribution), the concept's drift (the label's meaning), the performance's trend — the drift per the type, and the response (the re-training, the re-labeling, the re-spec).
- Audit the defense's state: the bias's monitor's standing, the grounding's presence, the calibration's current, the input's validation's live — the defense per the mode, and the gap per the defense.

## Phase 5 — Application and Design

- Run the evaluation per the claim: the metric per the task, the set per the claim, the human's rubric — with the cycle and the owner, and the failure's record per the case.
- Run the robustness per the mode: the perturbation, the drift's monitor, the deployment's evaluation — with the alert and the response per the drift.
- Apply the defense per the mode: the bias's audit, the grounding, the calibration, the validation — with the test per the defense and the monitor per the standing.
- Hold the culture per the record: the log per the case, the feed per the correction, the version per the comparison — with the review per the cycle and the standard stated: the system reports its error, its drift, its boundary.

## Phase 6 — Ethics and Boundary Conditions

- The bias's audit is the performance's gap per the group; the correction's data (the re-sampling per the attribute) is the group's content, and its use in the model's training carries the consent's state — the correction per the consent.
- The hallucination's grounding is the output's claim to the source; the source's content (the personal, the private) is the grounding's boundary, and the citation's public form is the source's consent — the grounding per the consent.
- The failure's record is the system's honesty at the organization's level; the record's use (the accountability, the improvement, the public's report) is per the sensitivity — the record per the use, with the correction's honesty as the standard.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Design the evaluation for a reading system: the metric per the task, the test set per the claim (the unseen, the out-of-distribution, the temporal), the human's rubric — with the cycle and the owner.
2. Run the robustness spec on the system: the perturbation per the mode, the effect measured, the drift's monitor, the deployment's evaluation — with the alert and the response.
3. Catalog the failures on a case set: the mode per the signature, the cause per the mode, the correction per the case — with the standing log.
4. Apply the defense per the mode on the system: the bias's audit per the attribute, the grounding per the output, the calibration per the group, the validation per the input — with the test per the defense.
5. Run the culture spec for a quarter: the record per the case, the feed per the correction, the version per the comparison — with the review and the standard's statement.
6. Write the evaluation standard document: the metric per the task, the set per the claim, the failure's catalog, the defense per the mode, the culture's record — as the standing standard, with the review's cadence.

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Evaluation
- The metric is per the task and the balance
- The set is per the claim
- The human's rubric has the agreement

### Robustness
- The perturbation is per the mode
- The drift is monitored with the alert
- The deployment's evaluation is per the cycle

### Failure
- The catalog is per the case
- The cause is per the mode
- The correction is per the case

### Delivery gate
- The defense is per the mode, with the test
- The record is per the culture
- The standard is stated and current

## Anti-Patterns

the benchmark as the quality; the sample as the readiness; the accuracy without the balance; the set from the training; the drift discovered at the incident; the bias unmeasured; the hallucination ungrounded; the sureness uncalibrated; the input unvalidated; the failure unrecorded.

## Decision Heuristic

Before any claim or recommendation, ask:

1. What claim is this evaluation for, and is the design per the claim?
2. What perturbation breaks this system, and was it tested?
3. What does the drift monitor say, and is the response per the drift?
4. Which failure mode does this case show, and is the defense per the mode?
5. Is the failure recorded, corrected, and fed back, with the version compared?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not the high benchmark. It is the reading system that knows its error per the task, its drift per the monitor, its boundary per the abstention, and its failure per the record — so the honesty is the system's quality, and the report says where the system is sure.
