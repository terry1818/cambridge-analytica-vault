---
date: 2026-05-17
description: The three-tier evidence-quality framework the vault uses to grade any factual claim -- Tier-1 primary record, Tier-2 corroborated testimony, Tier-3 reporting
tags: [meta, methodology, evidence-tiers]
type: methodology
---

# Evidence Tiers

The vault rates the evidentiary weight of every factual claim on a **three-tier scale**. The tier is implicit in the source-of-truth used; the explicit tag (`#tier/1`, `#tier/2`, `#tier/3`) is optional but recommended on hypothesis notes and contested-claim notes.

The framework intentionally **prioritizes primary documents over journalism over opinion**, while acknowledging that **good journalism on contested topics is often the highest-tier source available** when primary records remain sealed, classified, or destroyed.

## Tier-1 -- Primary record

**Definition:** The actual document, court filing, regulatory action, statutory registry entry, leaked internal communication, or recorded primary-source statement.

**Examples in this vault:**
- [[Source Mueller Report 2019]] -- Special Counsel's primary investigative report
- [[Source DCMS Final Report 2019]] -- UK Parliament committee report
- [[Source Senate Intel Vol 5 2020]] -- Senate Select Committee on Intelligence final volume
- [[Source FTC Complaint Cambridge Analytica 2019]] -- FTC administrative complaint
- [[Source Companies House 2018-03-16 Emerdata appointments]] -- statutory registry filing
- [[Source UK Electoral Commission Vote Leave 2018]] -- regulatory enforcement
- [[Source gov.uk 2020-09-24 Nix disqualification]] -- UK Insolvency Service action
- [[Source HindsightFiles 2020]] -- primary leaked internal documents (curated)
- [[Source Channel 4 2018-03-19 Exposed]] -- primary recorded statements (hidden camera)
- [[Source Greenwald Intercept 2014 JTRIG]] -- primary leaked classified documents
- [[Source Anderson Ars 2011 HBGary]] -- based on primary leaked communications

**Use this tier when:** the source IS the underlying record, not commentary on it.

**Tag:** `#tier/1`

## Tier-2 -- Corroborated testimony / academic analysis

**Definition:** Named-source whistleblower testimony, sworn affidavits, named-source investigative journalism with named documentary corroboration, peer-reviewed academic analysis of primary materials.

**Examples in this vault:**
- [[Source Mindfck (Wylie 2019)]] -- whistleblower memoir based on Wylie's direct experience
- [[Source Targeted (Kaiser 2019)]] -- whistleblower memoir based on Kaiser's direct experience
- [[Source Rosenberg et al 2018-03-17 NYT]] -- investigative journalism with named-source whistleblower + viewed-the-evidence corroboration
- [[Source Cadwalladr Graham-Harrison 2018-03-17 Guardian]] -- companion Observer/Guardian piece
- [[Source Forbidden Stories 2023 Team Jorge]] -- multi-newsroom-corroborated investigation with hidden-camera primary footage
- [[Source Briant OCCRP 2020-10-12]] -- academic analysis from researcher with primary-document access
- [[Source Parliament DCMS Briant essays]] -- parliamentary-record submission with primary-source audio
- [[Source Kosinski Stillwell Graepel 2013 PNAS]] -- peer-reviewed academic primary research

**Use this tier when:** the source is one step removed from the primary record but is built on direct access to it.

**Tag:** `#tier/2`

## Tier-3 -- Reporting / commentary / tertiary synthesis

**Definition:** Journalism without primary-document access, opinion analysis, tertiary syntheses (encyclopedias, explainers), trade-press coverage.

**Examples in this vault:**
- [[Source Wikipedia - Cambridge Analytica]] -- encyclopedic synthesis of primary sources
- [[Source Wikipedia - SCL Group]] -- same category
- [[Source Wired UK 2018-07-13 ethical data firm]] -- briefing piece reliant on contemporary coverage
- [[Source Accesswire 2018-05-29 CloudCommerce launches]] -- corporate press release (factual but PR-framed)
- News briefings, opinion columns, secondary blog analysis, and other commentary-layer content

**Use this tier when:** the source is **synthesizing or commenting** rather than **establishing** the underlying fact.

**Tag:** `#tier/3`

## How to use the tiers

### When writing a claim

1. **State the claim** in vault language
2. **Cite the highest-tier available source** that establishes the claim
3. **If only Tier-3 is available, mark with `#confidence/low`** unless multiple independent Tier-3 sources converge
4. **If the claim is contested**, cite both the supporting and disconfirming sources at their respective tiers

### When evaluating a hypothesis

A hypothesis should generally rest on **Tier-1 or Tier-2 evidence** for its core claim. Tier-3 support is acceptable for context and framing but should not be load-bearing.

A `#confidence/high` hypothesis should be cited from **multiple independent Tier-1 or Tier-2 sources**. A hypothesis citing only Tier-3 should be marked `#confidence/speculative` until upgraded.

### When using AI-assisted writing

AI synthesis is **never** a tier in itself -- it is a writing aid. Any AI-generated claim must be **backed by the same tier discipline** as user-authored content. If a claim cannot be grounded to a Tier-1 or Tier-2 source after AI drafting, **the claim should be marked `#claim/unverified`** until a source is identified.

## Common errors to avoid

- **Citing a Tier-3 synthesis when a Tier-1 primary is available.** When Wikipedia is your only citation for a claim that has an FTC consent order or court filing behind it, you have under-tiered.
- **Treating commentary on a primary source as itself primary.** A journalist's analysis of the Mueller Report is Tier-3; the Mueller Report itself is Tier-1.
- **Conflating personal testimony with corroborated testimony.** Wylie's claims in his memoir are Tier-2 because they describe his direct experience and are heavily documented; an uncorroborated anonymous-source claim is Tier-3 until corroborated.

## Related

- [[Categorization Architecture]] -- how to route claims into the right node once you've tiered them
- [[Methodology - Verifying a CA claim]] -- the verification workflow
- [[Source Bibliography MOC]] -- the catalogue of all source notes by category
- [[Open Questions]] -- research backlog for claims that need source-tiering work

## How tier classification gets applied in practice

The evidence-tier framework is applied at the source-note level (each source gets a tier classification in its frontmatter) and at the analytical-claim level (each hypothesis or connection note cites sources with their tier classifications visible).

The principal failure mode the framework guards against: building hypothesis-tier analytical claims on Tier-3 or Tier-4 sources without explicit acknowledgment. When a vault claim depends on a Tier-3 source (working journalism, aggregator material) and no higher-tier source is available, the claim should be flagged as tentative; when only Tier-4 sources are available, the claim should be flagged as speculation.

The secondary failure mode: building claims on Tier-1 sources but mischaracterising what the source actually establishes. The ICO 2020 Brexit final report is Tier-1, but the report's specific findings (substantial data-protection violations; declining to confirm strongest Russian-coordination claims) are sometimes mischaracterised by secondary commentary in ways that overstate or understate what the report established.

## Cross-tier convergence as additional evidence weight

A specific feature of the framework: when multiple independent sources at different tiers converge on the same claim, the convergence itself carries additional evidence weight beyond what any single source provides. The CA story is well-served by this pattern: the regulatory record (ICO, FTC), the insider testimony (Wylie, Kaiser), the investigative journalism (Cadwalladr, NYT, Channel 4), and the academic analysis (multiple post-2018 academic papers) all substantially converge on the core CA narrative even where they disagree on specific subsidiary claims.

When all tiers converge: the claim is treated as established (Tier-1-equivalent regardless of which individual source is being cited). When tiers diverge: the higher-tier source wins; the divergence is itself flagged as a research thread.

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