---
date: 2026-05-16
description: Delivering distinct political messages to narrow audience segments using data-driven audience identification
tags: [concept, topic/microtargeting, topic/psychographics, era/pre-2014, era/2014-2016, era/2016-2018, era/2018-2020, era/2020-2024, era/2024-present]
type: concept
domain: political-strategy
---

# Microtargeting

## Definition

Practice of delivering **distinct, individually-tailored political messages** to narrowly defined audience segments based on data accumulated about each person. Distinguishes from traditional broadcast political communication which delivers identical messages to mass audiences.

## Historical evolution

### Origins (2000s)
- 2000 â€” Bush re-election campaign credited with early commercial-data-driven microtargeting
- 2004 â€” Bush campaign refined methodology
- 2008 â€” Obama campaign expanded with significant data-science investment
- 2012 â€” Obama campaign's targeting infrastructure became industry benchmark (Catalist, NGP VAN)

### CA era (2013-2018)
- [[Cambridge Analytica]] layered **psychographic targeting** ([[OCEAN Model]]) onto behavioral and demographic targeting
- Claimed 5,000 data points Ã— 220M Americans
- Claimed 32 personality clusters per US adult
- Effectiveness substantially contested (Hersh, Nyhan)

### AI era (2022+)
- Embedding-based audience modeling using foundation models
- Less explicit segmentation; more continuous personalization
- LLM-generated content for individual recipients
- Cross-platform identity resolution

## Effectiveness debate

- **[[Brendan Nyhan]]** (Dartmouth): research shows altering voter choice is hard; mobilizing partisans is easier
- **[[Eitan Hersh]]** (Tufts): "Every claim about psychographics etc made by or about [CA] is BS"
- Academic literature: targeting can boost mobilization 1-3 percentage points among already-aligned voters; persuasion of swing voters is much harder
- **Industry overclaims for sales/marketing reasons** while internal research often suggests modest effects

## Key methods

- Voter file segmentation (party registration, demographics)
- Behavioral targeting (search/browsing/purchase data)
- Psychographic targeting (CA-era)
- Lookalike modeling
- Cross-platform identity matching
- Real-time content optimization

## Why this matters for the vault

Microtargeting is the **central methodology** at the heart of the CA story. Understanding the gap between **CA's marketing claims** (transformative effectiveness) and **empirical research** (modest effects) is essential for evaluating any claim about CA's actual impact on 2016 or 2018 elections.

The vault treats microtargeting effectiveness claims with `#claim/disputed` by default, reflecting the contested empirical literature.

## Related

- [[OCEAN Model]]
- [[Psychographic Targeting]]
- [[Embedding-based Audience Modeling]] (AI-era successor)
- [[Dark Ads]]
- [[Coordinated Inauthentic Behavior]]

## Sources

- [[Source Wikipedia - Cambridge Analytica]]
- [[Source Hersh Hacking the Electorate 2015]]
- [[Source Matz Kosinski Nave Stillwell 2017 PNAS]]
- Multiple academic literature on targeting effectiveness

## Operational definition

[[Microtargeting]] is the use of granular individual-level data (demographics, voter file behaviour, commercial purchase history, online behaviour, geolocation, psychographic inference) to deliver tailored political messaging at scale through addressable channels (digital advertising, direct mail, SMS, sometimes door-knocking with tablet-served content). It pre-dates CA; CA's contribution was layering psychographic inference on top of the demographic and behavioural microtargeting that 2008 Obama, 2012 Romney, and 2014-cycle campaigns had already operationalised.

## Where CA's microtargeting was distinct

CA's distinctive overlay was the use of [[OCEAN Model]] psychographic scores derived from the [[Aleksandr Kogan]] / GSR Facebook data (and from subsequent enrichment work) to tailor not just the audience but the message framing for each audience. The pitch was that a high-Neuroticism individual would respond to fear-framed messaging that a high-Openness individual would reject; a high-Conscientiousness individual would respond to order-and-stability framing; a high-Extraversion individual to social-proof framing. The operational deployment matched ad creatives to inferred personality clusters, not just to demographic clusters.

Whether this overlay produced measurable persuasion lift beyond the demographic-and-behavioural baseline is the live empirical question. The Matz/Kosinski line of research shows measurable lift in experimental settings; the field-deployment evidence is more ambiguous. The vault's position is that microtargeting works (the underlying audience-segmentation and ad-serving infrastructure is real and effective); CA's specific psychographic overlay produced incremental rather than transformative gains over the baseline.

## Why microtargeting matters even if the psychographic overlay is overstated

The infrastructure CA built (data ingestion from multiple sources, identity resolution across devices, programmatic ad delivery to inferred individuals, A/B testing at scale) is now baseline campaign infrastructure for all serious campaigns in the US and several other jurisdictions. The CA story is not "psychographic targeting won an election." It is "an infrastructure was built that lets any sufficiently well-funded actor influence specific individuals at scale, and that infrastructure persists and has grown." The vault treats microtargeting as the load-bearing technical reality and psychographic claims as one specific overlay among many.

## See also

- [[Psychographic Targeting]]
- [[OCEAN Model]]
- [[Dark Ads]]
- [[Astroturf at Scale]]
- [[Cambridge Analytica]]
- [[Facebook Graph API v1]]
- [[Facebook]]
- [[Lens - Data Flows]]

## Post-CA evolution of microtargeting capability

The microtargeting capability the vault tracks has substantially evolved since the 2014-2018 CA-era window:

**2014-2018 (CA-era baseline):** Third-party data-collection (the GSR-Facebook pipeline), commercial data-broker enrichment, voter-file integration, ad-creative-testing at scale, dark-ad deployment via Facebook (and to lesser extents Twitter and YouTube). The CA distinctive layer was the psychographic-overlay.

**2018-2024 (post-CA reckoning, GDPR, increased platform restriction):** Third-party data-access via social-platform APIs was substantially restricted; data-broker products consolidated and became more institutionally regulated; voter-file integration continued at expanded scale; ad-creative-testing matured into baseline practice; dark-ad deployment partially transparentised by platform ad-library disclosures.

**2024-2026 (AI-era, federal data-aggregation, post-Twitter-Files content-moderation rollback):** Generative-AI tools substantially reduce the cost of ad-creative production at scale; federal data-aggregation via [[DOGE]] creates a new internal-government data substrate; content-moderation rollback at major platforms increases the deployment surface for previously-restricted ad categories; the AI-assistant integration across major platforms creates richer behavioural-and-intent data than the prior browsing-and-engagement data alone.

The vault's analytical position: microtargeting capability has continued to expand across the post-2014 window, with brief regulatory restriction in the 2018-2022 period followed by substantial re-expansion in the 2024-2026 window. The CA reckoning did not eliminate the capability; it produced platform-level structural changes that the post-2024 platform-policy realignment has substantially reversed.

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