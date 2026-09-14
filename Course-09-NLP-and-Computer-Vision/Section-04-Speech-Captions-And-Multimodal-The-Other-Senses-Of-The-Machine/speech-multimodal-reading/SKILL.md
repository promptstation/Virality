---
name: speech-multimodal-reading
description: Build comprehensive, professional-level learning modules, evidence briefs, case diagnoses, and strategy documents on Speech, Captions, and Multimodal: The Other Senses of the Machine — how the machine reads the spoken and the moving — the speech's pipeline, the multimodal composition, the error's chain, and the access and the consent. Use this skill whenever the user asks to teach, explain, research, synthesize, critique, or design around speech recognition, transcription, auto captions, speaker diarization, scene detection, multimodal alignment, highlight extraction, clipping, ASR error rate. Apply it even when the user never says “learning module” — if they request a brief, memo, workshop, training, or an analysis of the content is spoken and moving — how does the machine read it, where does the error enter, and what does the read enable, use this skill.
compatibility: Text-only environment; web research permitted for primary sources and canonical works. No special tools required.
metadata:
  author: Promptstation
  version: 1.0.0
  category: nlp-computer-vision
---

# Speech, Captions, and Multimodal: The Other Senses of the Machine: Professional Module Builder

## Mission

Produce professional-level material on how the machine reads the spoken and the moving — the speech's pipeline, the multimodal composition, the error's chain, and the access and the consent. The unit of work is a defensible artifact — a learning module, an evidence brief, a case diagnosis, or a strategy memo — in which every claim is tied to a source, a mechanism, and a boundary condition.

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

1. Cover the speech's recognition: the waveform to the text (the acoustic model, the language model, the end-to-end's form — the model family per the scale), the domain's state (the language, the accent, the vocabulary — the recognition's error rate per the domain, the misrecognition's pattern), and the read's input (the transcript as the text's existence — the topic's read, the search's index, the sentiment's read on the spoken) — the recognition as the spoken's text-ification, with the error named.
2. Cover the caption's pipeline: the transcript's generation (the recognition per the segment, the timestamp, the speaker's separation — the diarization's task, the speaker's count, the turn's boundary), the caption's form (the display's design, the access's standard — the reading speed, the placement), and the caption's role (the access for the hearing-impaired, the search for the content, the read for the platform — the three roles, and the quality per the role) — the pipeline, and the role per the design.
3. Cover the multimodal composition: the video as the frame sequence plus the audio (the scene's detection — the shot's boundary, the scene's type; the audio's event — the music, the speech, the sound), and the joint read (the visual plus the transcript's alignment — the moment's identification, the speaker's and the scene's match, the highlight's extraction — the moment that the read composes from the two modalities) — the composition, and the highlight as the read's output.
4. Teach the error's chain: the recognition's error to the read's error (the misrecognized word in the topic's read, the misassigned speaker in the alignment, the missed scene in the highlight) — the propagation per the pipeline's stage, the error rate's domain state (the measure per the domain's corpus), and the human's review (the transcript's correction, the alignment's check — the review per the content's value, the correction's record feeding the domain's model).
5. Teach the access and the ethics: the caption as the access's design (the standard, the completeness — the transcript that serves the access, not the summary), the speaker's consent in the transcript (the recorded speech's transcription — the consent to the recording, to the transcript, to the transcript's use), and the identification in the read (the face's detection, the voice's identification — the personal attribute in the read's output, the consent to the identification, the minimization in the use) — the access served, the consent held, the identification bounded.
6. Apply to the strategy: the transcript as the content's text existence (the recall's input, the topic's placement — the connection to the content-based course section, for the spoken content), the highlight as the clipping's selection (the moment's read, the clip's design — the input to the first-window course section, for the clip), and the moment as the strategy's unit (the composed moment — the scene plus the speech — as the content's addressable unit, the strategy's resolution) — the read as the strategy's extension to the spoken and the moving.

## Phase 3 — Method and Technique

- The recognition spec: the model per the scale, the domain's state (the language, the accent, the vocabulary), the error rate's measure
- The caption pipeline: the generation, the diarization, the display's design — per the role (the access, the search, the read)
- The multimodal composition: the scene's detection, the alignment, the highlight's extraction — per the content's structure
- The error's chain audit: the propagation per the stage, the domain's error rate, the human's review spec
- The consent spec: the recording, the transcript, the identification — per the content's people, with the minimization

## Phase 4 — Analysis and Diagnosis

- Diagnose the read's failure in the chain: the recognition's error (the domain's gap, the vocabulary's miss), the diarization's error (the speaker's merge, the turn's miss), the alignment's error (the scene's and the speech's mismatch) — the stage per the case, and the fix (the domain's model, the review, the re-alignment).
- Check the caption's role's quality: the access's standard (the completeness, the reading speed) versus the summary's form — the role's breach, and the correction per the role.
- Read the error rate's state: the domain's corpus's measure, the trend per the model's version, the review's coverage — the error's standing read, and the model's upgrade decision.
- Audit the consent's chain: the recording's consent, the transcript's consent, the identification's consent — per the content's people, the gap named, and the minimization's design.

## Phase 5 — Application and Design

- Run the recognition per the domain's state: the model per the scale, the vocabulary per the domain, the error rate measured on the domain's corpus — the recognition earned, not assumed.
- Design the caption per the role: the access's standard for the access, the completeness for the search, the read's input for the platform — the form per the role, with the display's design.
- Compose the multimodal read per the content's structure: the scene's detection, the alignment, the highlight — with the moment as the output, and the clip's design from the moment.
- Hold the error's chain and the consent's chain as the standing audit: the propagation per the stage, the review per the value, the consent per the people — the two chains, with the record and the correction.

## Phase 6 — Ethics and Boundary Conditions

- The transcript is the recorded speech's text; the speaker's consent to the recording does not carry to the transcript's use (the search's index, the read's input, the training's data) — the chain per the use, stated.
- The identification in the read (the face, the voice) is the personal attribute at the read's output; the minimization (the attribute not stored where the use does not need it, the retention per the use) is the design, and the public form is the non-identifying one.
- The caption's access role is the service to the hearing-impaired; the line is the completeness (the transcript that serves, not the summary that substitutes) and the standard (the reading speed, the placement) — the service per the standard, not the convenience.

## Phase 7 — Exercises and Assessment

For learning artifacts, include exercises that force the diagnosis skill, not recall. Use the standard set:

1. Run the recognition on a domain corpus: the model's choice, the vocabulary's spec, the error rate's measure — with the domain's gap and the upgrade's plan.
2. Build the caption pipeline for a content type: the generation, the diarization, the display — with the role's quality per the role (the access, the search, the read).
3. Run the multimodal composition on a video: the scene's detection, the alignment, the highlight's extraction — with the moment as the output and the clip's design.
4. Run the error's chain audit on a pipeline: the propagation per the stage, the domain's error rate, the review's spec — with the correction per the stage.
5. Write the consent spec for the spoken content: the recording, the transcript's use, the identification — per the people, with the minimization's design.
6. Apply the read to the strategy: the transcript's placement, the highlight's clip, the moment's unit — with the input per the strategy's section (the recall, the first window).

For each exercise provide scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

## Phase 8 — Quality Gate and Delivery

Before delivering, run the delivery checklists. The artifact fails the gate on any “no.”

### Recognition
- The model is per the scale
- The domain's state is measured
- The vocabulary is per the domain

### Caption
- The pipeline is per the role
- The access's standard is met
- The display is designed

### Composition
- The scene is detected
- The alignment is checked
- The highlight is the read's output

### Delivery gate
- The error's chain was audited
- The review ran per the value
- The consent's chain is complete

## Anti-Patterns

the auto-caption unreviewed; the domain's error assumed away; the summary as the access; the speaker merged; the scene missed; the identification stored where the use does not need it; the consent to the recording read as the consent to the use.

## Decision Heuristic

Before any claim or recommendation, ask:

1. What is the recognition's error rate on this domain, and was it measured?
2. Does the caption serve the access's standard, or the convenience?
3. What does the composition say about the moment, and is the clip from the read?
4. Where does the error enter the chain, and is the review per the value?
5. Is the consent's chain complete — the recording, the use, the identification?

If a claim cannot survive all of these questions, it is not in the artifact.

## Final Principle

The goal is not the transcript. It is the read of the spoken and the moving — the recognition earned on the domain, the caption per the role, the composition per the structure, the chain audited, the consent held — so the moment the machine reports is the moment the content has, with its error and its people named.
