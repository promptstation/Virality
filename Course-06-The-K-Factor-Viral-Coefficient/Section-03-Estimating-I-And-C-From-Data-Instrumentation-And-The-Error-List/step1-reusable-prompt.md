# Step 1 — Reusable Prompt (Template)

Reusable prompt for the "section → learning-module prompt" task. The **task** is the section's Summary plus its Absorbed Skills, as produced by the research outline. Fill the placeholders, run it, and its output is the Step 2 prompt.

```
Generate a prompt on the task:

{SECTION_TITLE} — {SECTION_SUMMARY}

Absorbed skills:
- {ABSORBED_SKILL_1}
- {ABSORBED_SKILL_2}
- {ABSORBED_SKILL_3}
...

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```

---

# Filled Instance — Course 06 · Section 03

```
Generate a prompt on the task:

Estimating i and c from Data: Instrumentation and the Error List — Where the numbers come from. The section covers the instrumentation of the loop: the invite event (the send, the channel, the moment), the invitee's journey (the click, the landing, the signup), and the referrer's identity (the join key that closes the loop) — the three events and the schema that makes k computable. It covers the estimation in practice: the cohort definition, the attribution window, the per-cycle aggregation, and the denominator choices. Then the error list, in order of damage: the attribution failure (the invitee signs up and the referral is lost to organic), the dedup failure (the same invite counted twice), the survivorship (the k computed on the loop's survivors, not the loop's population), the channel mix (the email invite converts differently from the in-app invite, and the average hides the mix), and the platform-API limits (the sampling that biases the invitee's journey). It ends with the validation: the known-referral test (the seeded test cohort), the reconciliation against the raw event logs, and the uncertainty on the k.

Absorbed skills:
- Instrument the referral loop's three events (invite, journey, referrer join) and compute k with the right cohort, window, and denominators
- Diagnose and correct the estimation errors — attribution, dedup, survivorship, channel mix, sampling — and validate with a known-referral test

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
