# Step 2 — Generated Prompt (Result of the Reusable Prompt)

```
Develop a comprehensive, professional-level learning module on **“The SIR Equations: The Core Model”** as part of an advanced course on how ideas and information spread through populations, using the mathematics of epidemics. The module should the core SIR model — its equations, its two parameters, and the trajectory shape they generate — and how to simulate and read it.

The material should teach the equations and their reading: what β and γ do, what the curve's regions mean, and how the final size emerges. Go beyond knowing the curves exist without knowing which two parameters drive them and derive the dynamics from the equations rather than memorizing the curve.

Derive the three equations from the state transitions (S→I at rate proportional to contact SI, I→R at rate γ), and interpret each term in information-diffusion language.

Teach the two parameters: β (effective contact rate — how often a spreader's content meets a susceptible) and γ (recovery rate — how fast a spreader fatigues or stops); everything downstream is a function of their ratio.

Read the epidemic curve's regions: the slow takeoff (few infected, few contacts), the exponential growth phase, the peak (where dI/dt crosses zero), the decaying tail, and the final size (the fraction ever infected).

Teach the conservation: S+I+R=N — the compartments are a partition of the population, and the curve is a transfer of mass between them.

Run the simulation: solve the system numerically (Euler or a standard ODE solver), and produce the standard three-curve plot with the regions annotated.

Include practical methods for working at a professional level:
* Setting up the system in a solver (initial conditions S0, I0, R0; N; β; γ)
* Choosing the time step and validating conservation (S+I+R=N at every step)
* Locating the peak analytically (dI/dt=0) and confirming it in the simulation
* Reading the final size off the R-curve and comparing to the peak height
* The standard three-curve plot with regions annotated for a report

Include practical exercises that require the learner to:
1. Derive the SIR system from the state transitions, annotating each term in information-diffusion language.
2. Simulate the model with N=10,000, I0=10, β=0.3, γ=0.1: produce the three curves, locate the peak, and state the final size.
3. Fit β and γ to a real partial diffusion curve; report the fit, the peak forecast, and the final-size forecast with uncertainty.
4. Verify the peak condition on a real dataset: observed peak date versus model prediction, and the error.
5. Produce the standard annotated three-curve plot for a report, with the regions labeled and the two parameters named.
6. Identify the model mis-specification in a curve with two peaks; name the variant model it suggests and why.

For each exercise, provide the scenario, objective, constraints, expected deliverable, evaluation criteria, and an expert-quality example solution where appropriate.

Structure the material progressively, beginning with the derivation and the two parameters, moving through the curve's regions and the simulation, then to a fitted model with peak and final-size forecasts. Establish clear conceptual distinctions between **contact rate, recovery rate, epidemic peak, final size, and trajectory region** before showing how they interact.

Use professional terminology from epidemiology, mathematical modeling, and diffusion science where relevant, but explain specialized terminology in clear language. Do not make the material sound like generic AI-generated advice; the register should be that of an advanced professional training module used by quantitative marketers, growth analysts, and communication researchers.

Research the subject using high-quality professional and academic sources where external research materially strengthens the material. Prioritize authoritative sources: the classic epidemic-modeling literature (Kermack and McKendrick 1927 onward), the SIR/SEIR compartment-model literature, network-based diffusion models, and the computational epidemiology textbooks and toolkits. Avoid relying primarily on low-quality SEO articles, generic sir epidemiology blogs, or unsupported “best practice” claims. Where useful, distinguish established research findings from professional conventions and informed recommendations.

Pay particular attention to the relationship between this module and principles such as **two-parameter determinism, the peak condition, conservation, and region-based strategy**. Connect these concepts to concrete analytical and design decisions rather than discussing them only theoretically.

Create a professional framework that quantitative marketers, growth analysts, and communication researchers could actually use in a real project. The final material should therefore function simultaneously as a learning resource, a practical reference, and a working methodology for predicting and steering the spread of content, products, and ideas.

Throughout the module, prioritize language that is:

* Precise without being jargon-heavy
* Empirical without being statistical theater
* Confident about what the evidence establishes
* Explicit about what the evidence does not establish
* Conditional where the findings are conditional
* Practical where the decisions are practical

Where a claim depends on context (platform, audience, topic, measurement), explicitly explain the trade-off and the boundary condition rather than presenting it as an absolute rule.

End the module with **Model setup checklist**, **Fit quality checklist**, **Forecast integrity checklist**, and a **Delivery gate checklist** that a professional team can use before acting on predicting and steering the spread of content, products, and ideas.

The final result should be comprehensive enough to serve as an advanced professional training module, but organized clearly enough that a learner can study it progressively and apply each concept in predicting and steering the spread of content, products, and ideas.
```
