---
date: 2026-05-16
description: Big Five personality model (Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism) that CA built psychographic targeting on
tags: [concept, topic/psychographics, era/pre-2014, era/2014-2016]
type: concept
domain: psychology
first-documented: ~1981 (Goldberg)
---

# OCEAN Model (Big Five)

## Definition

Psychological model defining five broad dimensions of human personality: **Openness**, **Conscientiousness**, **Extraversion**, **Agreeableness**, **Neuroticism**. Established consensus model in academic personality psychology since the 1980s. CA built its psychographic profiling claims on inferring Big Five scores from Facebook digital footprints.

## How CA used it

1. Recruited ~200,000 US participants via Qualtrics ($4 to complete personality questionnaire + share Facebook profile)
2. Trained a model linking Facebook Likes/behavior → Big Five scores
3. Applied model to millions of profiles harvested via [[Aleksandr Kogan]] / [[GSR]] from [[Facebook Graph API v1.0]]
4. Used inferred personality profiles to target political messaging -- tone tailored to predicted personality

## Effectiveness -- disputed

- [[Source Kosinski Stillwell Graepel 2013 PNAS]] showed personality predictable from Facebook Likes with measurable accuracy
- [[Source Matz Kosinski Nave Stillwell 2017 PNAS]] -- personality-tailored ads boosted sales ~50%
- [[Eitan Hersh]] (Tufts): "Every claim about psychographics etc made by or about [CA] is BS"
- NYT March 2017: CA executives conceded company never actually used psychographics in Trump campaign

## Related concepts

- [[Psychographic Targeting]]
- [[Microtargeting]]

## Sources

- [[Source Wikipedia - Cambridge Analytica]]
- [[Source Kosinski Stillwell Graepel 2013 PNAS]]
- [[Source Matz Kosinski Nave Stillwell 2017 PNAS]]
- [[Source Confessore Hakim 2017-03-06 NYT Secret Sauce]]

## Vault context and open research threads

This concept is in the vault because it is one of the operational primitives the CA-to-present information warfare stack relies on. Concepts here are not academic curiosities. Each one corresponds to a real deployed tactic, a documented capability, or an analytical frame used to interpret deployments.

Use this node to anchor: a clear working definition, the methodological origin (academic paper, military doctrine, commercial product, hacker community), the documented deployments tied to this concept inside the vault, and the difference between the academic claim and the operational reality.

## Open research threads

- Origin trace: who first formalized this concept, in what paper, doctrine, or product? Add the primary source.
- Deployment trace: in which vault events was this concept demonstrably used? Cross-link the events.
- Effect-size evidence: what does the strongest peer-reviewed evidence say about how well this concept actually works on real populations? Where the literature has retracted or weakened a claim, note it.
- Adjacent concepts: which other vault concepts are confused with this one, and what is the clean distinction?

## See also

- [[Concepts MOC]]
- [[Methodology MOC]]
- [[Vault MOC]]

## The model and why CA picked it

The [[OCEAN Model]] (also called the Big Five) is the dominant five-factor personality framework in modern academic psychology: Openness to experience, Conscientiousness, Extraversion, Agreeableness, and Neuroticism. It is empirically derived (lexical hypothesis -> factor analysis of trait adjectives across languages), reasonably stable across cultures, and has substantial published correlation evidence with behaviour, life outcomes, and political attitudes.

CA chose OCEAN over alternative frameworks (Myers-Briggs, the HEXACO six-factor model, ideological self-placement) for three operational reasons: it had the largest published research base (and therefore the most academic legitimacy in pitch decks), the [[Michal Kosinski]] / [[David Stillwell]] Cambridge work had demonstrated it could be predicted from Facebook Like data at meaningful accuracy, and its scoring is dimensional (continuous scores along each axis) rather than typological, which fits microtargeting better than discrete-type frameworks.

## What the published evidence actually supports

Peer-reviewed literature supports four claims that the vault treats as established: (1) Facebook Likes can predict OCEAN scores with modest but real accuracy (better than human friends in some studies); (2) OCEAN scores correlate meaningfully with political attitudes (high Openness correlates with progressive positions; high Conscientiousness with traditionalist ones); (3) message framings tailored to OCEAN profiles produce measurable persuasion lifts in controlled-experiment settings (Matz, Appel, Kosinski 2017-2020 line of work); (4) effect sizes in field deployment are smaller than in laboratory settings, and have shrunk further under attempted replication.

What the literature does not support: that CA's specific deployment achieved decisive electoral effect; that psychographic microtargeting is meaningfully more effective than the demographic-plus-behavioural microtargeting that all sophisticated campaigns now use as baseline; that the persuasion lift in field settings is large enough to swing close elections on its own.

## How the vault treats OCEAN claims

The vault tags OCEAN-related claims with explicit evidence levels. Academic claims about prediction accuracy are Tier-1 (peer-reviewed and replicated). Claims about CA's specific operational effectiveness are Tier-2 or Tier-3 (testimony and reporting, not measured outcomes). Claims that psychographic targeting was the determining factor in a specific election outcome are explicitly flagged as unsupported by the available evidence.

## See also

- [[Psychographic Targeting]]
- [[Microtargeting]]
- [[Michal Kosinski]]
- [[David Stillwell]]
- [[Aleksandr Kogan]]
- [[Cambridge Analytica]]
- [[Source Matz Appel Kosinski 2020 Current Opinion Psychology]]

## Application beyond CA

The OCEAN / Big Five framework has substantial application beyond the CA-era political-targeting use case the vault primarily tracks. Other documented applications:

**Commercial market research.** OCEAN-based audience segmentation is now standard practice across major consumer-marketing organisations. Brand-positioning research, product-development testing, and marketing-creative-testing routinely use OCEAN inference layers.

**Workplace organisational psychology.** OCEAN-based personality assessment is used in hiring (with substantial debate about predictive validity for job performance), team-composition planning, and organisational development. The HireVue and adjacent AI-recruitment vendors have integrated OCEAN inference into their assessment products.

**Clinical and counselling psychology.** OCEAN-based assessment is now incorporated into many clinical assessment batteries, complementing earlier personality-assessment frameworks (MMPI, NEO-PI-R variants).

**Online dating and matching services.** OCEAN-based compatibility matching is used (with widely varying scientific rigour) across multiple dating-platform products.

The vault's interest is in the political-targeting application, but the broader institutional acceptance of OCEAN as a measurement framework is part of why the political-targeting application has operational legitimacy.

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