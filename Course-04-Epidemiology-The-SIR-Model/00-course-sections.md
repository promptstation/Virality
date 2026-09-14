# Course 04 — Epidemiology (The SIR Model): Studying Susceptible, Infectious, and Recovered Populations (Researched Curriculum Outline)

Source: `uploads/Virality.txt`, entry 4. Section count: 8 (compressed to ≤15). Progression: beginner → expert.

**From Pathogens to Ideas: Why Epidemiology Models Virality**

**Summary:** The conceptual bridge: treating an idea, product, or piece of content as a 'pathogen' that spreads through a population of people. The section defines the unit of analysis (individual, content, network), maps epidemic concepts onto information diffusion (exposure = contact, infection = adoption or share, recovery = fatigue or uninterest), and states honestly where the analogy holds and where it breaks (ideas can be re-encountered, there is no biological immunity, and platform algorithms act as an external force). It covers the history of the field from Kermack and McKendrick (1927) to modern computational diffusion modeling.

**Absorbed Skill:** Map the SIR framework onto information diffusion and state where the analogy holds and where it breaks; Choose the right unit of analysis (individual, content, network) for a given virality question.

**The SIR Equations: The Core Model**

**Summary:** The mathematics of the core model. The section derives and interprets the three compartment equations: dS/dt = −βSI/N, dI/dt = βSI/N − γI, dR/dt = γI, with β (effective contact rate) and γ (recovery rate) as the two parameters that determine everything. It covers the shape of the trajectory — the epidemic curve: slow start, exponential growth, the peak, the long tail to the final size — the meaning of each region, and the conservation S+I+R=N. It ends with a hands-on simulation: solving the system numerically and reading the curves.

**Absorbed Skill:** Write down, derive, and interpret the SIR equations and their parameters; Simulate SIR trajectories and read the epidemic curve's regions (takeoff, peak, tail, final size).

**The Basic Reproduction Number R0: Thresholds and Herd Immunity**

**Summary:** The single most important derived quantity. The section defines R0 = β/γ (the average number of new infections caused by one infected individual in a fully susceptible population), the threshold R0>1 (below it, the idea dies out; above it, it spreads), and the herd-immunity threshold 1 − 1/R0 (the fraction of the population that must be 'recovered' — uninterested or fatigued — for the spread to stall). It covers how to estimate R0 from real diffusion data (initial exponential growth rate, early-curve methods), how R0 differs for different content and platforms, and the strategic reading: what raising or lowering R0 means operationally.

**Absorbed Skill:** Compute, interpret, and estimate R0 from diffusion data and state the threshold logic it implies; Use the herd-immunity (saturation) threshold to reason about when and why a diffusion stalls.

**Extending the Model: SEIR, SIS, Networks, and Saturation**

**Summary:** The model variants that real diffusions require. The section covers SEIR (the latent stage E: people who were exposed but are not yet spreading — saw it, saved it, will share later), SIS (re-infection: people can be re-exposed and re-activate — recurring categories, seasonal content), network-based SIR (heterogeneous mixing: spread on a network with hubs, not in a uniform population — the source of super-spreading), multi-strain models (competing content), and the saturation mechanics (finite population, exhaustion, topic fatigue). For each variant: when to use it, the modified equations, and the signature curve shape that reveals it.

**Absorbed Skill:** Select and justify an extended model (SEIR, SIS, network-based) from the observed curve and the case structure; Modify the base equations for the chosen variant and read its signature shape.

**Parameter Estimation from Real Diffusion Data**

**Summary:** Making the model touch reality. The section covers how to estimate β, γ (and the variant parameters) from real share/adoption/retweet curves: the data pipeline (collection, cleaning, denominators, censoring), the fitting methods (least squares on the curve, maximum likelihood on the event data, the early-window growth-rate method), model selection (AIC/BIC, cross-validation, holdout prediction), and the practical pathology list: platform API limits, survivorship bias, the difference between reach and adoption, and the measurement noise that masquerades as dynamics. It ends with a worked end-to-end fit on a real dataset.

**Absorbed Skill:** Estimate SIR-family parameters from real diffusion data using an appropriate fitting method and honest uncertainty; Run model selection and validation (AIC/BIC, holdout) and diagnose data pathologies before the fit.

**Interventions in Model Terms: Steering the Spread**

**Summary:** From prediction to control. The section translates the levers of a virality strategy into model parameters: reducing contact (throttling exposure, retargeting discipline), reducing transmission (message strength, hook quality — β), and managing recovery (fatigue management, content refresh — γ). It covers the classic epidemic interventions and their information analogs: social distancing (limiting who sees what and how often), ring vaccination (pre-seeding the neighbors of likely spreaders), and prophylaxis (priming the susceptible pool). It ends with the timing problem: when intervention helps, when it is too late, and the cost of over-intervention (killing a diffusion you want).

**Absorbed Skill:** Design intervention strategies in model terms — contact, transmission, recovery levers — with explicit parameter targets; Time interventions against the curve (takeoff, growth, peak) and evaluate the cost of under- and over-intervention.

**Forecasting and Scenario Analysis**

**Summary:** The model as a decision instrument. The section covers what a diffusion forecast should produce (peak date, final size, regional trajectory) and how to build them honestly: the parameter uncertainty propagated to the forecast (the ensemble, not the point), the scenario analysis (high/low R0, early/late intervention, platform change), the sensitivity analysis (which parameter the forecast turns on), and the communication of forecasts (the range, the confidence, the assumptions — in a form a non-technical decision maker can use). It closes with the forecast audit: what to check when the forecast is wrong, and how the miss updates the model.

**Absorbed Skill:** Produce ensemble diffusion forecasts (peak, final size, trajectory) with propagated uncertainty and sensitivity analysis; Communicate the forecast to non-technical decision makers and run the post-mortem audit when it misses.

**Beyond SIR: Hybrid Models and Validation for Real Virality**

**Summary:** The capstone: the models as they are actually used. The section covers the hybrid models of real virality work — SIR on an explicit network with platform-algorithm dynamics (the exogenous forcing term), the combination of the compartment model with the K-factor loop (the referral-driven reinfection) and with the recommendation-engine dynamics (the exposure allocation as a time-varying contact rate) — and the validation discipline: backtesting on past diffusions, the calibration set, the out-of-sample test, and the standing comparison of the model family against the simple baseline (the 'does the model beat the last quarter's curve extended linearly' test). It ends with the practitioner's judgment: when the model earns its complexity, and when the honest answer is a simpler one.

**Absorbed Skill:** Build hybrid diffusion models that combine the compartment structure with network, loop, and platform dynamics; Validate a model family by backtesting and calibration, and judge when a model earns its complexity.
