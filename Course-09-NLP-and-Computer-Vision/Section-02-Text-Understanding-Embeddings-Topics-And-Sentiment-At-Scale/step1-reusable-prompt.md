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

# Filled Instance — Course 09 · Section 02

```
Generate a prompt on the task:

Text Understanding: Embeddings, Topics, and Sentiment at Scale — The text's reading tasks in depth. The section teaches the embedding's use (the semantic space — the similarity, the retrieval, the clustering; the fine-tuned embedding per the domain; the embedding's limits — the surface's match versus the meaning's, the polysemy, the sarcasm), the topic modeling (the latent topic — the LDA's classic, the neural topic model, the modern substitute of the embedding's clustering; the topic's interpretation; the topic as the content's organization at scale), and the sentiment and the stance (the polarity, the intensity, the target; the stance's detection — the position on the issue, the claim's verification stance; the domain shift and its cost). It covers the scale practice (the batch reading of the corpus, the cost per the model's scale, the caching and the dedup), and the honesty of the read (the confidence per the prediction, the abstention, the human-in-the-loop for the boundary case). It ends with the text-read's application to the virality system: the content's topic as the niche's placement, the sentiment as the audience's state, and the stance as the conversation's structure — the read as the input to the strategy.

Absorbed skills:
- Apply the text-reading tasks — the embedding's similarity and retrieval, the topic model, the sentiment and the stance — at the corpus scale, with the limits named
- Read the text's output honestly: the confidence, the abstention, the human-in-the-loop — and apply the read to the virality system's inputs

You are free to install software, programs and write codes, research the internet so as to meet our goals.
You are free to search the internet, books and make sure that you have selected those of professional levels. You are also free to install softwares, programs and write codes as long as it helps in achieving the goal.
At the end let me have the result.
```
