---
date: 2026-05-16
description: How audience-targeting methodology has evolved from CAs psychographic models to AI-era embedding-based targeting
tags: [moc, lens, topic/psychographics, topic/microtargeting, topic/llm-propaganda]
type: moc
---

# Compare: Psychographic Targeting (2014) vs. Embedding-Based Targeting (2024)

CA's psychographic targeting was the cutting edge in 2014. By 2024 the methodology has been superseded by **embedding-based audience modeling** that is faster, cheaper, less explainable, and far more scalable. The evolution is structurally important.

## CA-era psychographic targeting (2013-2018)

**Methodology:**
1. Recruit ~200K participants via Qualtrics; collect Big Five questionnaire responses + Facebook profile data
2. Train supervised ML model to predict Big Five scores from Facebook Likes
3. Apply model to broader population of profiles harvested via Graph API friends-data permission
4. Segment audience into 32 personality clusters
5. Tailor content to each cluster's predicted personality

**Strengths:**
- Theoretically grounded ([[OCEAN Model]])
- Interpretable (you can name what each cluster cares about)
- Validated against academic research

**Limitations:**
- Required harvest of explicit Facebook Likes data (closed off post-2015)
- Required survey-validated training data (expensive)
- Bound to Big Five framework (limited dimensionality)
- Effectiveness empirically contested

## AI-era embedding-based targeting (2022-present)

**Methodology:**
1. Collect any behavioral signal (posts, comments, engagement, browsing â€” whatever's available)
2. Generate high-dimensional embeddings using a foundation model (LLM or vision-language model)
3. Cluster embedding space using unsupervised methods
4. Generate tailored content for each cluster (either AI-generated or AI-selected)
5. Test, iterate, optimize via engagement signals

**Strengths:**
- Doesn't need explicit personality framework â€” embeddings capture latent dimensions automatically
- Doesn't need supervised training data â€” works on whatever signals are available
- Far higher dimensionality than Big Five
- Generates content on-the-fly
- Operates at full platform scale

**Limitations:**
- Not interpretable (you can't say "this cluster is high-openness" anymore)
- Harder to detect / regulate
- Quality varies with foundation model used
- Effectiveness still empirically uncertain

## The big shift

| Dimension | CA 2014 | Modern 2024 |
|---|---|---|
| Theoretical framework | Big Five personality psychology | Foundation model embeddings (latent) |
| Training data | Survey-validated personality scores | Behavioral signals + foundation model |
| Interpretability | High (named clusters) | Low (opaque embeddings) |
| Content production | Human-written, model-targeted | AI-generated, model-targeted |
| Required data access | Explicit harvest (now restricted) | Any behavioral signal |
| Detection difficulty | Medium (psychographic claims auditable) | High (opaque embeddings + AI content) |
| Cost per profiled person | High | Negligible |
| Scaling | Limited by Facebook API | Effectively unlimited |

## What this means for investigation

CA-era investigation could **audit psychographic claims** by checking the underlying personality framework. Modern operations are largely **post-auditable** â€” you can identify the network and content but cannot reverse-engineer the targeting logic, because there is no human-interpretable targeting logic.

## Related

- [[OCEAN Model]]
- [[Psychographic Targeting]]
- [[Microtargeting]]
- [[Generative Propaganda]]
