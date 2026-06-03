---
date: 2026-05-16
description: Targeting individuals based on inferred psychological traits rather than just demographics; CA-era methodology
tags: [concept, topic/psychographics, topic/microtargeting, era/2014-2016, era/2016-2018, era/2018-2020]
type: concept
domain: data-science-psychology
first-documented: ~2013 (CA buildout; Kosinski PNAS paper)
---

# Psychographic Targeting

## Definition

Method of audience segmentation and targeting based on **inferred psychological traits, values, attitudes, and personality** -- as opposed to (or layered on top of) demographic targeting (age, location, income) or behavioral targeting (purchase history, browsing).

## CA-era methodology

[[Cambridge Analytica]] built psychographic targeting on the **[[OCEAN Model]]** (Big Five personality framework):

1. **Train ML model** to predict Big Five scores from Facebook Likes / behavior
2. **Recruit participants** for survey-based training data (~200,000 paid Qualtrics respondents at $4 each)
3. **Apply trained model** to broader population of profiles harvested via [[Facebook Graph API v1.0]]
4. **Segment audience** into 32 personality clusters (per CA marketing)
5. **Tailor messaging** -- adjust content, tone, imagery to inferred personality

## Effectiveness (substantially disputed)

### Pro arguments
- [[Source Kosinski Stillwell Graepel 2013 PNAS]] -- personality predictable from Facebook Likes with measurable accuracy
- [[Source Matz Kosinski Nave Stillwell 2017 PNAS]] -- personality-tailored ads boosted sales ~50% in commercial study
- CA's own marketing claims of transformative political effectiveness

### Skeptical arguments
- [[Eitan Hersh]] (Tufts): "Every claim about psychographics etc made by or about [CA] is BS"
- [[Brendan Nyhan]] (Dartmouth): political attitudes change is much harder than commercial purchasing influence
- NYT March 2017 ([[Source Confessore Hakim 2017-03-06 NYT Secret Sauce]]): CA executives **conceded** they didn't actually use psychographics in Trump campaign
- Trump campaign principals ([[Jared Kushner]], [[Brad Parscale]]) downplayed CA contribution

## The vault's stance

The vault treats psychographic-targeting effectiveness claims with `#claim/disputed` by default. The most defensible position:

- CA built genuine psychographic-prediction infrastructure
- Predictions had measurable accuracy in academic studies
- But operational political effectiveness (changing votes) is empirically uncertain
- CA's effectiveness claims were marketing-driven rather than empirically supported

## AI-era succession

The CA-era psychographic-targeting approach has been **largely superseded by embedding-based audience modeling**:

- No explicit Big Five framework required
- High-dimensional latent embeddings from foundation models
- Less interpretable but more scalable
- See [[Compare - Psychographic 2014 vs Embedding-based 2024]]

## Related

- [[OCEAN Model]]
- [[Microtargeting]]
- [[Embedding-based Audience Modeling]]
- [[Cambridge Psychometrics Centre]] (research origin)

## Sources

- [[Source Wikipedia - Cambridge Analytica]]
- [[Source Kosinski Stillwell Graepel 2013 PNAS]]
- [[Source Confessore Hakim 2017-03-06 NYT Secret Sauce]]
- [[Source Hersh Hacking the Electorate 2015]]

## Operational definition and CA framing

[[Psychographic Targeting]] is the practice of tailoring political (or commercial) messaging based on inferred psychological traits of the recipient, rather than purely on demographic or behavioural traits. In the [[Cambridge Analytica]] context, the inferred traits were [[OCEAN Model]] Big-Five scores derived from Facebook Likes (via the Kogan/GSR pipeline) plus subsequent enrichment from voter files, commercial data brokers, and proprietary survey work.

CA's commercial pitch was that psychographic targeting could outperform conventional demographic-plus-behavioural targeting on persuasion lift, voter turnout, and voter suppression effects. The pitch was supported by academic research from the [[Michal Kosinski]] / [[David Stillwell]] line of work showing that Facebook Likes could predict OCEAN scores at meaningful accuracy and that OCEAN-tailored framings could produce measurable persuasion lift in experimental settings.

## What the field-deployment evidence actually shows

The strongest peer-reviewed evidence (Matz, Appel, Kosinski et al., 2017-2020) demonstrates persuasion-lift effects in controlled settings but with relatively modest effect sizes. Subsequent replication and meta-analytic work has tended to shrink rather than expand those effect sizes. Field-deployment evidence (from actual political campaigns) is largely unavailable in peer-reviewed form because campaigns do not publish their internal A/B test results.

What survives the literature: psychographic targeting produces measurable lift over no-targeting baselines; whether it produces measurable lift over best-practice demographic-plus-behavioural targeting baselines is unclear and probably depends on the specific persuasion context. What does not survive: the maximalist CA claim that psychographic targeting was the decisive factor in 2016.

## Why the vault treats this concept carefully

Psychographic targeting is the most over-claimed and most under-evidenced concept in the entire CA story. The vault's analytical stance is to distinguish three things: (1) the underlying academic work, which is real and replicated; (2) CA's operational deployment, which is documented but whose effect size is contested; (3) the journalistic and political claims about psychographic targeting deciding elections, which are largely unsupported by the available evidence.

Where the concept matters for the present-day vault is less about psychographic-specific claims and more about what CA's infrastructure made culturally normal: the assumption that individual-level persuasion at scale is possible, profitable, and politically necessary. That assumption persists in the [[Tech Right]] data infrastructure even if the specific OCEAN overlay does not.

## See also

- [[OCEAN Model]]
- [[Microtargeting]]
- [[Michal Kosinski]]
- [[David Stillwell]]
- [[Aleksandr Kogan]]
- [[Cambridge Analytica]]
- [[Source Matz Appel Kosinski 2020 Current Opinion Psychology]]
- [[Hypothesis - Federal database supersedes CA model]]

## Practical deployment vs commercial pitch

The commercial pitch for psychographic targeting (that CA's psychographic-overlay layer produced substantial persuasion lift over the demographic-and-behavioural baseline that all sophisticated campaigns now use) has not been substantiated in the field-deployment evidence. The peer-reviewed evidence (Matz, Kosinski, Nave, Stillwell 2017 PNAS and subsequent replications) shows real but modest effect sizes in controlled experimental settings; field-deployment evidence is principally unavailable because campaigns do not publish internal A/B-test results.

What is operationally established: psychographic-style audience segmentation is now a routine feature of major-platform advertising infrastructure (Facebook Custom Audiences and Lookalike Audiences both incorporate inferred-trait targeting; commercial data-broker products offer similar capability). What is operationally contested: whether the specific OCEAN-based psychographic-overlay layer that CA pitched produces measurable lift beyond what these baseline-platform capabilities provide.

## Cross-cluster operational position

This node sits at the intersection of multiple vault clusters and its operational position deserves explicit reconstruction. The principal clusters this node touches:

- The CA-era operator cluster ([[Cambridge Analytica]], [[SCL Group]], [[AggregateIQ]], [[Emerdata]], [[Auspex International]]) and the personnel-and-methodology continuity that flowed from CA into successor structures.
- The patron / funder cluster ([[Mercer]] family, [[DeVos Family Network]], [[Koch Network]], the broader CNP-affiliated large-donor architecture, and the sovereign-wealth-adjacent flows including [[Affinity Partners]] / Saudi PIF and adjacent vehicles).
- The theocratic / religious-right cluster ([[Council for National Policy]], [[The Fellowship]], [[New Apostolic Reformation]], [[Capitol Ministries]], [[Family Research Council]], [[Alliance Defending Freedom]], [[Faith and Freedom Coalition]]).
- The Tech-Right / data-infrastructure cluster ([[Peter Thiel]] / [[Palantir Technologies]], [[Elon Musk]] / [[DOGE]], [[Marc Andreessen]] / [[a16z (Andreessen Horowitz)]], [[Anduril]], the broader frontier-AI ecosystem).
- The state-actor cluster ([[Russia]] / [[Doppelganger]], [[China]] / [[Spamouflage Dragonbridge]], [[UAE]] / [[Saudi Arabia]] / [[Affinity Partners]], [[Israel]] / [[Black Cube]] / [[Team Jorge]]).
- The policy-execution cluster ([[Project 2025]], [[Heritage Foundation]], [[America First Policy Institute]], [[Center for Renewing America]], [[America First Legal]], [[Convention of States Action]]).

The vault treats each of these clusters as operationally distinct but increasingly convergent across the 2024-2026 period. The convergence is documented in [[Lens - 2024-2026 Power Map]], [[Hypothesis - Three-wing coalition]], and [[Hypothesis - Federal database supersedes CA model]].

## Specific evidence sources

The vault's evidence-tier framework grades sources from Tier-1 (primary documents, adjudicated regulatory findings) through Tier-4 (anonymous claims, partisan-aligned advocacy). The principal Tier-1 sources for the CA-era story include [[Source Companies House CA Records]] (UK), [[Source FEC CA Records]] (US), [[Source ICO 2020-10-07 Brexit final report]], [[Source ICO 2020-11 Cambridge Analytica investigation]], [[Source Mueller Report 2019]], [[Source Senate Intel Vol 5 2020]], and [[Source FTC Complaint Cambridge Analytica 2019]]. The principal Tier-2 sources include the [[Carole Cadwalladr]] Observer/Guardian reporting, the [[Christopher Wylie]] Mindf*ck memoir, the [[Brittany Kaiser]] Targeted memoir, and the [[Source The Great Hack 2019]] documentary.

## Open research threads

Questions this node has not yet resolved:

- The complete personnel-flow record from CA into successor structures, with dated entries and primary-source citations.
- The complete funder-overlap map across the patron / theocratic / tech-surveillance wings.
- The operational mechanics of cross-jurisdictional information-operations coordination (the documented cross-pollination between Israeli-intelligence-adjacent firms, US-based commercial vendors, and state-actor operations).

For methodology see [[Methodology - Verifying a CA claim]] and [[Evidence Tiers]]. For navigation see [[Vault MOC]] and [[Categorization Architecture]].