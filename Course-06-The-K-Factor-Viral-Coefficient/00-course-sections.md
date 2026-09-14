# Course 06 — The K-Factor (Viral Coefficient): Mastering k = i × c (Invites per User × Conversion Rate) (Researched Curriculum Outline)

Source: `uploads/Virality.txt`, entry 6. Section count: 8 (compressed to ≤15). Progression: beginner → expert.

**What Virality Means in Products: The Referral Loop**

**Summary:** The ground floor: product virality as a mechanism, not a mood. The section defines the referral loop (an existing user causes a new user to join, at some rate, with some probability), distinguishes product virality from content virality (the loop is inside the product's use, the share is an invitation with a landing), and situates it in product-led growth (the product itself is the sales channel). It covers the classic cases — Hotmail's signature line, Dropbox's storage incentive, PayPal's two-sided incentive, Airbnb's listing split — as loop designs, not as stories, and states the honest base rate: most loops run at k < 1, and that is where the strategy lives.

**Absorbed Skill:** Define the referral loop precisely and distinguish product virality from content virality; Read a product's loop design from the classic cases and state what each one optimized.

**The Formula: k = i × c, and the Mathematics of Compounding**

**Summary:** The core mathematics. The section defines the K-factor precisely — k = i × c, where i is the average number of invites sent per user and c is the conversion rate of an invite to a new user — and works the arithmetic: the per-cycle growth, the compound trajectory when k > 1 (the exponential), the trajectory when k < 1 (the convergence to a finite ceiling on the loop's contribution), and the time-to-scale at various k. It covers the recursion (the users at cycle t+1 from the users at cycle t), the distinction between the loop's contribution and total growth (the paid input at each cycle), and the sensitivity: how much c must move to push k across 1, and why the two factors are levers with different costs.

**Absorbed Skill:** Compute the K-factor from i and c and model the growth trajectory it implies (the k>1 and the k<1 cases); Reason about the sensitivity of k to i and to c, and choose the lever from the cost structure.

**Estimating i and c from Data: Instrumentation and the Error List**

**Summary:** Where the numbers come from. The section covers the instrumentation of the loop: the invite event (the send, the channel, the moment), the invitee's journey (the click, the landing, the signup), and the referrer's identity (the join key that closes the loop) — the three events and the schema that makes k computable. It covers the estimation in practice: the cohort definition, the attribution window, the per-cycle aggregation, and the denominator choices. Then the error list, in order of damage: the attribution failure (the invitee signs up and the referral is lost to organic), the dedup failure (the same invite counted twice), the survivorship (the k computed on the loop's survivors, not the loop's population), the channel mix (the email invite converts differently from the in-app invite, and the average hides the mix), and the platform-API limits (the sampling that biases the invitee's journey). It ends with the validation: the known-referral test (the seeded test cohort), the reconciliation against the raw event logs, and the uncertainty on the k.

**Absorbed Skill:** Instrument the referral loop's three events (invite, journey, referrer join) and compute k with the right cohort, window, and denominators; Diagnose and correct the estimation errors — attribution, dedup, survivorship, channel mix, sampling — and validate with a known-referral test.

**Designing the Viral Loop: The Moment, the Invitation, the Landing**

**Summary:** The design layer: where and how the loop is built into the product. The section teaches the moment design (the value moment when the user has just gained, the winning moment when the user has just achieved, the handoff moment when the product's use naturally addresses another person), the invitation design (the payload: the reason the invitee should open, the personalization, the channel), and the landing design (the invitee's first experience: the value before the signup, the social proof of the referrer, the path to the first value). It covers the loop architecture (the single loop, the multi-loop product, the loop's placement in the funnel) and the friction audit (every step from the value moment to the new user's first value, with its conversion cost). It closes with the loop's quality gates: the spam check, the value check, and the honesty check.

**Absorbed Skill:** Design the loop's three elements — the moment, the invitation, the landing — with the friction audit that measures the cost of each step; Choose the loop architecture (single vs. multi-loop) and place the loop in the funnel from the product's natural moments.

**Optimizing i: Invite Volume, Shareable Surfaces, and the Spam Line**

**Summary:** The first lever in depth. The section covers how i (the invites per user) is actually raised: the shareable surfaces (the places in the product where the share is natural — the output, the achievement, the collaboration), the surface design (the friction of the send, the default payload, the channel choice), the frequency architecture (how often a user can trigger the loop without the goodwill breaking), and the product features that raise i structurally (the collaboration features that make the product multi-user by design, the gifting, the challenges, the shared artifacts). It covers the evidence on the volume-quality trade-off (the marginal invite's conversion decays with the referrer's send count), the spam line (the unfriend rate, the opt-out rate, the platform's rate limits), and the measurement of i's health (the distribution of sends per user, the tail of the senders, the send retention).

**Absorbed Skill:** Raise invite volume through the shareable surfaces and the structural features, within the spam line the goodwill defines; Measure i's health — the distribution, the decay of the marginal invite, the opt-out signals — and read the volume-quality trade-off.

**Optimizing c: The Invitation's Conversion and the Referred's Quality**

**Summary:** The second lever in depth. The section covers how c (the invite-to-user conversion) is actually raised: the invitation's open rate (the payload, the timing, the channel), the landing's conversion (the value before the signup, the social proof, the path), and the onboarding of the referred (the first session's design, the first-value moment, the second invite's naturalness — the referred becomes the referrer). It covers the quality dimension of c: the referred's retention versus the organic's (the loop's honesty check), the referred's LTV, and the referred's own loop participation (the cohort that closes the loop). It ends with the c experiment program: the A/B design of the invitation and the landing (the arms, the metrics, the sample), the sequential learning across the variants, and the guardrail set (the retention, the opt-out, the complaint) that bounds the conversion optimization.

**Absorbed Skill:** Raise the invitation's conversion across the open, the landing, and the referred's onboarding, with the experiment program that prices each change; Evaluate the referred cohort's quality — retention, LTV, loop participation — against the organic baseline as the loop's honesty check.

**Compound Growth and the Economics of the Loop**

**Summary:** The loop in the business model. The section covers the compound growth accounting: the user base as the recursion (the paid input, the loop's addition, the churn), the time-to-scale under the realistic parameters (the k<1 world with the paid multiplier), and the saturation (the market's ceiling, the loop's exhaustion as the susceptible pool depletes — the connection to the epidemic course). It covers the unit economics: the cost per referred (the incentive, the landing's cost, the loop's infrastructure), the referred's LTV, the viral CAC (the paid CAC reduced by the loop's multiplier, the formula and its honest use), and the payback. It ends with the strategy of the economics: when to invest in the loop (the k headroom, the quality, the market's size), when to stop (the knee of the marginal decay, the quality gap, the saturation), and the reporting of the loop's contribution to the growth story (the decomposition that the board can audit).

**Absorbed Skill:** Model the compound growth of the loop in the full recursion (paid, loop, churn, saturation) and compute the time-to-scale from the parameters; Compute the loop's unit economics — cost per referred, viral CAC, payback — and decide when to invest in and when to stop the loop.

**Synthesis: Running the Viral Engine End to End**

**Summary:** The capstone: the loop as a standing operation. The section integrates the course — the loop's design, the instrumentation, the two levers, the economics — into the operational system: the K-factor dashboard (the standing series, the cohort view, the per-surface and per-channel resolution), the experiment pipeline (the i and the c experiments in rotation, with the guardrails), the economics review (the quarterly decomposition, the invest/stop decision), and the product sync (the loop's design in the product roadmap, the moments the product's evolution creates). It covers the case studies as operating systems — the referral products that ran the loop as the strategy — and the postmortem practice: the loop's launch, its scaling, its plateau, and its handoff to the next growth engine, each with the numbers that tell the story. It closes with the engine's operating cadence: the daily monitors, the weekly experiment read, the monthly cohort review, the quarterly economics — the rhythm that keeps the engine honest.

**Absorbed Skill:** Operate the referral loop as a standing system — the dashboard, the experiment pipeline, the economics review, the product sync — on a defined cadence; Run the loop's postmortem across its life (launch, scale, plateau, handoff) with the numbers that tell the story.
