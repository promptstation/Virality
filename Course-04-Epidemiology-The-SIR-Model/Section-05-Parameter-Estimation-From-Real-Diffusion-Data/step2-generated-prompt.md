# Step 2 — Generated Prompt (Result of the Reusable Prompt)

```
Develop a comprehensive, professional-level learning module on **“Parameter Estimation from Real Diffusion Data”** as part of an advanced course on how ideas and information spread through populations, using the mathematics of epidemics. The module should how to estimate the model's parameters from real diffusion data — the pipeline, the methods, the selection, and the pathologies that corrupt them.

The material should teach the estimation craft: data pipeline, fitting methods, model selection, and the pathology list — with a worked end-to-end fit. Go beyond a fitted curve whose parameters nobody could defend and examine the difference between reach and adoption, the censoring problem, and the noise that fakes dynamics.

Build the data pipeline: collection (API, platform analytics, CMS), cleaning (dedup, bot filtering), denominators (impressions, unique reach), and censoring (left-truncation of pre-launch, right-truncation of the open curve).

Teach the fitting methods: least squares on the I-curve (simple, bias-prone), maximum likelihood on the event data (the principled choice when counts are available), and the early-window growth-rate method (the cheap, robust R0 estimate).

Teach the reach-versus-adoption distinction: most platform counts measure exposure, not the state transition; the model needs the adoption (share, purchase, activation) series, not the view series.

Cover model selection: AIC/BIC for the variant family, and holdout prediction (fit on the first half, predict the second) as the honest test.

Run the pathology list: platform API rate limits and sampling, survivorship (only the successful content is studied), measurement noise (the platform's own count revisions), and the bot fraction — each with its correction or its warning.

Include practical methods for working at a professional level:
* The pipeline spec: source, dedup, denominator, censoring window, bot filter
* The least-squares fit with residual diagnostics
* The maximum-likelihood fit on event counts with the profile likelihood for the interval
* The early-window growth-rate estimate with its window-sensitivity check
* The holdout validation: fit on t<τ, predict t>τ, score the error

Include practical exercises that require the learner to:
1. Specify the pipeline for a chosen dataset: source, dedup, denominator, censoring, bot filter — and identify which counts are reach and which are adoption.
2. Fit the base SIR by least squares and by maximum likelihood to the same data; compare the parameters and explain the gap.
3. Estimate R0 by the early-window growth-rate method at three window lengths; report the sensitivity.
4. Run the holdout validation on a variant family; select the model by prediction error and state the runner-up.
5. Apply the pathology list to a dataset with a known bot fraction; quantify the parameter shift the correction makes.
6. Produce the worked end-to-end fit on a real dataset: pipeline, fit, selection, holdout, and the forecast with its uncertainty.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively, beginning with the pipeline and the series identity, moving through the fitting methods and model selection, then to a defended estimate with its holdout error. Establish clear conceptual distinctions between **reach, adoption, censoring, likelihood, and holdout error** before showing how they interact.

Use professional terminology from epidemiology, mathematical modeling, and diffusion science where relevant, but explain specialized terminology in clear language. Do not make the material sound like generic AI-generated advice; the register should be that of an advanced professional training module used by quantitative marketers, growth analysts, and communication researchers.

Research the subject using high-quality professional and academic sources where external research materially strengthens the material. Prioritize authoritative sources: the classic epidemic-modeling literature (Kermack and McKendrick 1927 onward), the SIR/SEIR compartment-model literature, network-based diffusion models, and the computational epidemiology textbooks and toolkits. Avoid relying primarily on low-quality SEO articles, generic sir epidemiology blogs, or unsupported “best practice” claims. Where useful, distinguish established research findings from professional conventions and informed recommendations.

Pay particular attention to the relationship between this module and principles such as **series identity, method-to-moment matching, selection by prediction, and pathology discipline**. Connect these concepts to concrete analytical and design decisions rather than discussing them only theoretically.

Create a professional framework that quantitative marketers, growth analysts, and communication researchers could actually use in a real project. The final material should therefore function simultaneously as a learning resource, a practical reference, and a working methodology for predicting and steering the spread of content, products, and ideas.

Throughout the module, prioritize language that is:

* Precise without being jargon-heavy
* Empirical without being statistical theater
* Confident about what the evidence establishes
* Explicit about what the evidence does not establish
* Conditional where the findings are conditional
* Practical where the decisions are practical

Where a claim depends on context (platform, audience, topic, measurement), explicitly explain the trade-off and the boundary condition rather than presenting it as an absolute rule.

End the module with **Pipeline spec checklist**, **Fit integrity checklist**, **Selection and validation checklist**, and a **Delivery gate checklist** that a professional team can use before acting on predicting and steering the spread of content, products, and ideas.

The final result should be comprehensive enough to serve as an advanced professional training module, but organized clearly enough that a learner can study it progressively and apply each concept in predicting and steering the spread of content, products, and ideas.
```
