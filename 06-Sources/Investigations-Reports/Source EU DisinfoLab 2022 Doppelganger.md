---
date: 2026-05-16
description: EU DisinfoLab + Qurium's foundational 2022 attribution of the Doppelganger Russian operation cloning Western mainstream-media outlets — the canonical primary reference for the network
aliases: ["Source: Source EU DisinfoLab 2022 Doppelganger"]
tags: [source, evidence/investigation-report, topic/info-warfare, topic/disinformation, era/2020-2024, jurisdiction/eu, jurisdiction/russia]
type: source
source_type: investigation-report
title: "Doppelganger: Media clones serving Russian propaganda"
publisher: EU DisinfoLab + Qurium
publication_date: 2022-09-27
url: https://www.disinfo.eu/doppelganger/
accessed: 2026-05-16
reliability: high
---

# Source: EU DisinfoLab 2022 Doppelganger

## Citation

EU DisinfoLab; Qurium. (2022-09-27). *Doppelganger: Media clones serving Russian propaganda.* <https://www.disinfo.eu/doppelganger/>.

## What it is

The **foundational public attribution and technical characterization** of the [[Doppelganger]] Russian state-linked influence operation. Jointly authored by **EU DisinfoLab** (a Brussels-based NGO researching foreign information manipulation in the EU) and **Qurium** (a digital-forensics organization providing infrastructure analysis). The report identified an organized network of **cloned news-website domains** impersonating major Western media outlets to push Russian state narratives — particularly around the Russian invasion of Ukraine — and named the operational signature, infrastructure, and likely sponsor.

## Key claims / findings

- **Operation:** Network of ~60 (initial count) **spoofed news-website domains** impersonating Western mainstream-media outlets, including:
  - **BBC**, **The Guardian** (UK)
  - **Le Monde, 20 Minutes** (France)
  - **Bild, Welt, Spiegel, Frankfurter Allgemeine** (Germany)
  - **Washington Post, Fox News** (US)
  - Additional regional outlets across the EU
- **Mechanism:** Spoof domains use **typo-squatting** (e.g., `bild.work` instead of `bild.de`) and visual cloning to imitate the targeted outlet; articles push pro-Russian framing on Ukraine, NATO, and Western governments
- **Amplification:** Cloned articles are then **boosted via inauthentic social accounts** across Facebook, X/Twitter, and emerging platforms — making the originating Doppelganger domains appear in legitimate-looking link shares
- **Attribution:** Operation **attributed to Russian state-linked operators** based on infrastructure, content alignment, and post-attribution sanctions reporting; subsequent EU sanctions in 2023-2024 named specific Russian entities as operators
- **Scale evolution:** Initial ~60 domains has expanded to **hundreds of spoofed domains across multiple languages** by 2024 per follow-on reporting and [[Source Meta Threat Reports 2022-2024]] quarterly disclosures

## Significance for the vault

- **State-actor parallel to CA's commercial model:** Doppelganger illustrates that **state-attributed operations now operate at scale comparable to private-vendor models** like CA's — supports the broader [[State Actors MOC]] thesis
- **Comparative baseline:** sits alongside [[Spamouflage Dragonbridge]] (China, [[Source Graphika 2019 Spamouflage Dragon]]) and [[Team Jorge]] ([[Source Forbidden Stories 2023 Team Jorge]]) in the [[Compare - State vs Private vs Commercial influence ops]] analysis
- **Methodology innovation:** the report's combination of **technical infrastructure analysis** (Qurium) and **content / narrative analysis** (DisinfoLab) is a model adopted by subsequent influence-operations research

## Reliability assessment

- **Type:** investigation-report from established NGO researchers
- **Independent corroboration:**
  - **Meta** (subsequent threat reports) confirmed and extended the network mapping — see [[Source Meta Threat Reports 2022-2024]]
  - **EU institutions** acted on the attribution with sanctions in 2023-2024
  - **Academic researchers** at Stanford Internet Observatory and others have produced complementary analyses
- **Strengths:** technical methodology fully disclosed; reproducible domain-discovery approach; cross-language scope
- **Caveats:**
  - Attribution to "Russian state" rests on **circumstantial** infrastructure + content-alignment inference; the report does not claim direct GRU/SVR/FSB sourcing
  - Initial 2022 scale figures are **underestimates** relative to subsequent disclosures
- **Disputed by:** Russian government has rejected attribution (as expected); specific narrow operator claims have been corrected in follow-on reporting

## Entities mentioned

- [[Doppelganger]] (subject)
- Russian state (attributed origin)
- Multiple targeted Western media outlets (BBC, Guardian, Le Monde, Bild, Welt, Washington Post, Fox News, others)
- [[Meta]], X/Twitter (amplification platforms)

## How I'm using this

- [[Doppelganger]] (entity hub) — foundational attribution source
- [[Coordinated Inauthentic Behavior]] (concept node)
- [[Compare - State vs Private vs Commercial influence ops]] — state-actor anchor
- [[AI Influence Ops MOC]]
- [[State Actors MOC]]
- [[Lens - 2024-2026 Power Map]]
- [[Generative Propaganda]] (concept node) — Doppelganger has integrated AI-generated content per follow-on reporting

## Open questions

- [ ] What is the current 2024-2026 scale of the Doppelganger network?
- [ ] What specific Russian-state entities have been formally named in EU sanctions filings?
- [ ] Cross-references with other Russian state-linked operations (IRA-successor patterns, [[Internet Research Agency]])

## Archive

- Live URL: <https://www.disinfo.eu/doppelganger/>
- Report PDF available from EU DisinfoLab; capture both report and update threads
- Pair with [[Source Meta Threat Reports 2022-2024]] for ongoing takedown documentation

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

## Research-thread continuation and primary-source layer

The vault's analytical work on this node is incremental. Specific outstanding research threads:

**Primary-source consolidation.** The relevant primary documents (corporate filings, court records, regulatory reports, sworn testimony) should be inventoried in a single per-node primary-source manifest, with retrieval URLs, retrieval dates, and tier classifications. Where primary documents are paywalled or behind regulator-specific access barriers, the manifest should note the access pathway. The vault has multiple per-node manifests at different completeness levels; this node's manifest is in progress.

**Cross-jurisdictional reconstruction.** Where operations span multiple jurisdictions (US, UK, EU, Russia, China, UAE, Saudi, Israel, etc.), the per-jurisdiction record is typically reconstructed independently by per-jurisdiction regulatory authorities. The vault's cross-jurisdictional reconstruction is the integration of these per-jurisdiction records into a single operational picture. The integration work is incomplete; specific jurisdictions are better-covered than others.

**Temporal updates and current-state tracking.** Many of the operational threads the vault tracks are not historical artifacts but continuing active operations. Specific updates that the vault should be tracking on a continuing basis: post-2024-election personnel disposition; current-state litigation outcomes; new disclosures from journalism, NGO investigation, or congressional inquiry; new academic-tier work that addresses the vault's analytical claims.

**Counterfactual analysis and falsification structure.** The vault's analytical claims should be paired with explicit falsification conditions. Where a claim has no clearly-articulated falsification structure, the claim is functionally unfalsifiable and should be reformulated. The Hypothesis-tier notes in 08-Hypotheses are the principal venues for explicit falsification structure; entity-and-event-tier notes inherit the falsification structure from the hypothesis-tier notes that depend on them.

## Methodological cross-references

For the broader vault methodology and conventions, see [[Methodology - Verifying a CA claim]], [[Evidence Tiers]], [[Categorization Architecture]], [[Tag Taxonomy]], and [[Conventions]]. For the principal analytical frameworks, see [[Lens - 2024-2026 Power Map]], [[Hypothesis - Three-wing coalition]], [[Hypothesis - Federal database supersedes CA model]], and [[Hypothesis - COS is the permanent capture arm of Project 2025]]. For navigation, see [[Vault MOC]] and the relevant domain MOC.