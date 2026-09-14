# Course 02 — Emotional Valence and Arousal (Researched Curriculum Outline)

Source: `uploads/Virality.txt`, entry 2. Section count: 12 (compressed to ≤15). Progression: beginner → expert.

**Foundations of Emotion: Discrete vs. Dimensional Models**

**Summary:** What emotion is and the two competing ways of modeling it. Discrete emotion theory treats emotions as separate categories (Ekman's basic emotions: happiness, sadness, anger, fear, disgust, surprise), each with distinct causes and expressions. Dimensional models instead represent emotional states as continuous values along fundamental properties: valence (pleasant to unpleasant), arousal (calm to agitated), and dominance (submissive to dominant) — the VAD/PAD framework developed by Mehrabian and Russell. The section covers the trade-offs of each approach, why the dimensional view is the working model for communication science, and how blended or ambiguous feelings defeat forced single-label categorization.

**Absorbed Skill:** Distinguish discrete emotion categories from dimensional emotion models, describe the three VAD dimensions, and justify why valence and arousal are the operative dimensions for studying how communication spreads.

**Russell's Circumplex Model of Affect**

**Summary:** The two-dimensional circular space that organizes emotion: a valence axis (unpleasant → pleasant) and an arousal axis (deactivation → activation). Every emotion is a coordinate in this space, producing four quadrants — excitement/joy (high A, +valence), anxiety/anger/fear (high A, −valence), calm/contentment (low A, +valence), sadness/boredom (low A, −valence). The section covers reading the diagram, angular relationships (opposites 180° apart, uncorrelated 90° apart), how mixed emotions (excited-but-anxious) map as neighbors, and the concept of core affect as the always-on background state beneath named emotions.

**Absorbed Skill:** Plot any given emotion or piece of content on the circumplex, interpret quadrant membership, and use the model to compare, contrast, and predict the similarity of emotional experiences.

**The Arousal–Sharing Link: The Central Findings**

**Summary:** The empirical anchor of the course. The large-scale field study by Berger and Milkman (2012) of nearly 7,000 New York Times articles showed that positive content is more viral than negative content, but the relationship between emotion and social transmission is more complex than valence alone: virality is driven substantially by physiological arousal. Content evoking high-arousal emotions — awe (positive), anger and anxiety (negative) — is more viral, while content evoking deactivating, low-arousal emotions such as sadness is less viral, and these effects persist after controlling for surprise, interestingness, practical usefulness, and placement. Complementary work (Berger 2011) established experimentally that arousal increases the social transmission of information, and later replications (e.g., political communication on Twitter) found high-arousal messages raise retweet probability while negative valence lowers it. The section also covers what "sharing" and "virality" were measured as, the study designs (field study plus causal experiments), and the boundary of the findings.

**Absorbed Skill:** Explain the causal chain from evoked emotion, through physiological arousal, to increased social transmission; cite and correctly interpret the key field and experimental studies that established the arousal–sharing link; and distinguish arousal effects from valence effects when analyzing why content spreads.

**Mapping the Emotions That Drive Sharing**

**Summary:** The emotion-by-emotion scorecard. Awe, amusement/excitement, anger, and anxiety each boost transmission — anger and anxiety despite being negative, because their urgency and action tendency mobilize the sharer; contentment sits at low arousal and mildly positive transmission; sadness, fatigue, and boredom suppress it. The section builds the valence–arousal matrix of the eight core emotions studied in the viral-content literature (awe, amusement, anger, anxiety, contentment, disgust, sadness, fear) and explains the "arousal regardless of valence" rule, including why the popular belief that "negative news is more viral" is only half right and where it fails.

**Absorbed Skill:** Classify any target emotion into its valence–arousal cell, rank candidate emotions by their predicted effect on social transmission, and diagnose why a specific piece of content over- or under-shared on emotional grounds.

**Mechanisms: Why Arousal Makes People Share**

**Summary:** The psychological machinery under the effect. Arousal creates action readiness — activation that needs to be discharged, and sharing is one discharge channel. Self-presentation: sharing positive, impressive content enhances the sharer's image (social currency). Social bonding: high-arousal positive states, especially awe, shrink the self and increase the desire to connect and include others. Information urgency: anger and anxiety signal threats or injustices that the sharer feels compelled to flag. The section compares these accounts, shows how mediation analyses established arousal as the mechanism (emotion → arousal → transmission), and clarifies when practical value or curiosity can substitute for emotion.

**Absorbed Skill:** Explain and critically evaluate the competing mechanism accounts (action readiness, self-presentation, social connection, urgency) for why high-arousal content gets shared, and apply the mediation logic to new cases.

**Measuring Emotion in Content**

**Summary:** The practical measurement toolkit. Lexicon-based text analysis: LIWC, the NRC Emotion Lexicon, and sentiment dictionaries, how they score text for valence, arousal, and discrete emotions, and their known limits (sarcasm, irony, culture, register). Face coding: FACS action units and systems that estimate valence–arousal from facial video. Self-report: PANAS and valence–arousal rating scales (SANS-style), including how raters are recruited and reliability is established. Physiological ground truth: skin conductance, heart rate, and EEG as the reference for activation. The section covers inter-method agreement, how to build a simple emotion-coding pipeline for a content library, and how to report and defend methodological choices.

**Absorbed Skill:** Apply lexicon-based and scale-based methods to estimate the valence–arousal profile of any piece of content, assemble a repeatable emotion-coding workflow, and state the validity limits of each measurement method.

**Measuring the Sharing Response**

**Summary:** The outcome side. What to count: raw shares, shares per impression, retweet probability, email-to-read ratios, and sharing velocity. Denominators and selection: why raw counts mislead (placement, article age, audience size, platform algorithm), and how to correct with rates and comparisons. Statistics for this field: rate ratios and effect sizes from the literature, confounder control (surprise, interestingness, practical usefulness, prominence), correlational versus causal designs, and when a before–after or split design is sufficient. The section ends with how to build a minimal analytics pipeline from a content dataset to defensible emotion–sharing estimates.

**Absorbed Skill:** Define and compute sharing metrics from raw platform data, identify and control the main confounders, and judge how strongly an observed correlation supports — or fails to support — the arousal hypothesis.

**Designing Content for High Arousal**

**Summary:** Moving from analysis to creation. Choosing the target emotion from brand, mission, and audience rather than from habit; the stylistic and narrative levers that raise arousal — stakes, specificity, sensory detail, urgency, contradiction, novelty, personal relevance — and the levers that set valence — framing, outcome, moral position. Designing specifically for awe versus anger versus excitement, since each carries different brand and ethical costs. Ethical boundaries of arousal manipulation: outrage bait, fear appeals, and moral grandstanding, plus how to keep high arousal without low-integrity tactics, and how to anticipate backfire when valence misaligns with audience identity.

**Absorbed Skill:** Design a content brief and draft that targets a specified high-arousal emotion with a controlled valence, justify each creative choice from the arousal mechanism, and audit a finished piece for both transmission potential and brand/ethical fit.

**A/B Testing Emotional Responses**

**Summary:** The experimental craft. Manipulating the emotion a piece of content evokes (the ad-campaign experimental pattern: same message, high-anger vs. low-anger versions), factorial designs that vary valence × arousal independently, measuring stated and actual sharing intention, and mediation analysis that tests emotion → arousal → transmission as a chain. The section covers pre-registration, sample sizing, avoiding pseudo-replication and novelty effects, field experiments and split delivery on social platforms, and how to read a failed or ambiguous test — including the critical case where stronger emotion of a deactivating kind reduces sharing.

**Absorbed Skill:** Design, run, and interpret factorial A/B experiments that establish the causal effect of valence and arousal manipulations on sharing, and correctly report mediation and boundary conditions.

**Platform and Audience Modifiers**

**Summary:** The effect is real but not uniform. How the arousal–sharing relationship shifts with platform mechanics and norms (short-video velocity on TikTok/Reels, retweet culture on X/Twitter, sharing-to-friends on Facebook), topic domain (political, consumer, human-interest), audience and community norms, cultural context, and the public-versus-private nature of sharing. When practical usefulness dominates emotion, when low-arousal content is the correct strategic choice (trust, consideration-stage buying, brand safety), and how moderator analysis in the literature refines the general rule.

**Absorbed Skill:** Adapt a valence–arousal strategy to a specific platform, audience, and topic; explain the known moderator effects on the arousal–sharing link; and recommend when high-arousal content is the wrong tool.

**Ethics and Risks of Arousal Engineering**

**Summary:** The dark side, explicitly. Outrage farming and engagement-driven radicalization, clickbait and bait-and-switch framing, fear-based marketing, and the platform-economy incentives that reward sustained high arousal; manipulation versus persuasion; the evidence on long-term trust erosion from chronic outrage content; platform policies on manipulative emotional content; regulation and disclosure expectations; and responsible design principles — audience consent, harm minimization, value alignment, and knowing when a brand should refuse an arousal opportunity.

**Absorbed Skill:** Evaluate an arousal-driven campaign against a professional ethics framework, identify manipulative elements, and redesign them into defensible high-arousal strategies that preserve trust.

**Integrated Strategy: Emotion as a System Lever**

**Summary:** Capstone integration. Combining emotional valence and arousal with the other virality levers — practical value, curiosity, social currency, triggers, and narrative — into a single content plan; mapping emotions across the funnel (high-arousal for awareness, moderate arousal for consideration, low-arousal contentment for loyalty); building the standing measurement program (emotion-coding the content library, sharing analytics, periodic experiments); and running the operating workflow: emotion targets in the brief, pre-publish arousal/valence checks, post-publish review against sharing data, and iteration. The section closes with a complete worked example from brief to post-mortem.

**Absorbed Skill:** Build and run a complete emotion-driven content strategy — planning, production, measurement, and iteration — that treats valence and arousal as first-class levers alongside all other diffusion mechanisms.
