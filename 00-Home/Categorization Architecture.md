---
date: 2026-05-17
description: The vault's node-routing architecture -- which type of folder a claim, fact, or research item belongs in, and how they cross-link
tags: [meta, methodology, architecture]
type: methodology
---

# Categorization Architecture

When you have a new piece of information -- a claim, a fact, a document, a relationship, a hunch -- **which folder does it go in?** This note is the routing manual. Each top-level vault folder corresponds to a distinct **node type** with its own conventions for what counts as a valid instance.

The categorization works alongside [[Evidence Tiers]] (which grades source quality) and [[Methodology - Verifying a CA claim]] (which walks specific verification workflows).

## The node types

### `02-People/` -- individuals

**Goes here:** Named human individuals who appear in the vault as **investigative subjects** (operators, funders, beneficiaries, whistleblowers, journalists, researchers).

**Sub-folders:** `CA-Core/`, `Investigators-Journalists/`, `Political-Figures/`, `State-Actors/`, `Tech-Industry/`, `Whistleblowers/`. Choose by the person's **primary role in the vault's analytical narrative**, not by their day job.

**Does NOT go here:** Personal contacts (those live in a personal vault, not this one). Public figures with only a one-line passing mention (those can stay as wikilink-only references that may resolve later when expanded).

### `03-Organizations/` -- corporate / institutional entities

**Goes here:** Named corporate entities, government agencies, NGOs, political vehicles (Super PACs, campaign organizations), academic institutions.

**Sub-folders:** `CA-SCL-Group/`, `Government-Agencies/`, `Media-Research/`, `Policy-Apparatus/`, `State-Actors/`, `Successor-Orgs/`, `Tech-Platforms/`. Choose by the **organization's primary role**, not by its legal form.

### `04-Events/` -- discrete temporal events

**Goes here:** Specific campaigns, hearings, leaks, scandals, settlements, broadcasts, releases -- anything that has a **definite date or date range** and a **subject-of-record framing**.

**Sub-folders:** `2016-US-Election/`, `Brexit/`, `Hearings-Investigations/`, `Other-Campaigns/`, `Whistleblower-Disclosures/`. New event types create new sub-folders.

**Does NOT go here:** Ongoing operations without a specific event-of-record (those go in MOCs or Lenses).

### `05-Concepts/` -- methods, doctrines, technologies

**Goes here:** Named techniques, doctrines, technical methodologies, ideological frameworks. Not entities, not events -- concepts.

**Sub-folders:** `AI-Influence-Ops/`, `Cognitive-Warfare/`, `Information-Warfare/`, `Microtargeting/`, `Psychographics-OCEAN/`.

### `06-Sources/` -- primary evidence

**Goes here:** Every source the vault cites should have a corresponding source note. Even brief news articles. Every wikilink to `[[Source X]]` should resolve to a real file.

**Sub-folders:** `Academic-Papers/`, `Articles/`, `Books/`, `Court-Filings/`, `Investigations-Reports/`, `Leaked-Materials/`, `Primary-Documents/`, `Videos-Documentaries/`. Choose by source type, not subject.

**Naming convention:** `Source ` + short distinct title. See [[Conventions]] for the canonical naming rule.

### `07-Connections/` -- relationships between entities

**Goes here:** A documented relationship -- money flow, personnel migration, data flow, influence channel -- between two or more entities, that deserves its own note rather than being captured only as a wikilink on the related entity notes.

**Sub-folders:** `Data-Flows/`, `Influence-Networks/`, `Money-Flows/`, `Personnel-Movements/`.

**Heuristic:** if the relationship is the analytical subject (not just a fact about an entity), it gets its own connection note.

### `08-Hypotheses/` -- working theories

**Goes here:** Specific working theories with explicit **falsification criteria** and **confidence labels**. A hypothesis is not a guess -- it's a structured claim with documented support and disconfirming evidence.

**Required structure:** Claim → Why it matters → Supporting evidence → Disconfirming evidence → Falsification criterion → Current confidence label.

### `09-Threads/` -- narrative drafts and active research threads

**Goes here:** Drafts of articles, explainers, state-level playbooks, research threads in progress. This is the **active-writing** folder, distinct from the **reference** folders above.

### `10-Timeline/` -- chronological views

**Goes here:** Per-entity timelines, era-specific timelines, the master timeline. A timeline note is a **chronological view** over the same facts that live in the entity / event / connection notes -- it does not contain facts that aren't elsewhere; it organizes them by date.

### `11-Canvases/` -- visual relationship maps

**Goes here:** `.canvas` files for visual relationship mapping. Each canvas should have a clear analytical purpose (network map, money-flow diagram, four-cluster overlap, etc.).

### `12-App-Backend/` -- structured exports for the Political app

**Goes here:** Entity schemas, export-ready JSON, app-data documentation. This folder is the **bridge between research vault and product app**.

## Cross-routing rules

When a piece of information could fit multiple folders, **prefer the most specific type**:

- A claim that an organization funded another organization → **money-flow connection**, not a fact buried on either org's note
- A pattern across multiple events → **hypothesis**, not commentary in a single event note
- A reusable technique → **concept**, not a technique-named entity note
- A specific dated investigation → **event**, not a body of work on an entity note

When a piece of information **belongs everywhere**, write it **once** in the most specific node type, then **wikilink from the broader nodes**. The wikilink graph is the network; don't duplicate content.

## Folder-to-MOC mapping

Each major folder has its own MOC that indexes its contents:

- `02-People/` → [[People MOC]]
- `03-Organizations/` → [[Organizations MOC]]
- `04-Events/` → [[Events MOC]]
- `05-Concepts/` → [[Concepts MOC]]
- `06-Sources/` → [[Source Bibliography MOC]]
- `07-Connections/` → [[Connections MOC]]
- `08-Hypotheses/` → Hypotheses are indexed in [[Vault MOC]] directly
- `10-Timeline/` → [[Timelines MOC]]
- Methodology docs → [[Methodology MOC]]

## Related

- [[Evidence Tiers]] -- companion methodology doc for source-tier grading
- [[Methodology - Verifying a CA claim]] -- the verification workflow that uses both tiering and categorization
- [[Tag Taxonomy]] -- orthogonal tag axes that cross-cut categorization
- [[Conventions]] -- naming, linking, citation rules
- [[Vault MOC]] -- top-level navigation

## Multi-axis tagging in operational use

The vault's 11-axis tag taxonomy is the substrate that makes lens-based queries possible. The principal axes:

**Entity type.** person / organization / event / concept / source / connection / hypothesis / timeline / moc / canvas / schema. This is the highest-level distinction and determines which other axes apply.

**Role.** operator / funder / target / whistleblower / investigator / regulator / intermediary / political-figure / state-actor. This applies principally to person and organization entities.

**Topic.** CA / SCL / Mercer / Brexit / 2016 / theocratic / Tech-Right / state-actor / COS / P2025 / etc. The topic axis is the broadest and supports cross-cluster queries.

**Era.** pre-2014 / 2014-2018 / 2018-2024 / 2024-2026. The era axis supports timeline-based queries.

**Jurisdiction.** US / UK / EU / Russia / China / UAE / Saudi / Israel / international / etc. The jurisdiction axis supports geography-based queries.

**Evidence type.** primary-document / investigative-journalism / insider-testimony / academic / aggregator / advocacy. This applies principally to source entities.

**Confidence.** high / medium / low / disputed. This applies principally to hypothesis and analytical-claim entities.

**Claim status.** established / contested / unresolved / refuted. This applies to analytical claims within entities.

**Status.** active / dissolved / pending / archived. This applies principally to organisation and event entities.

**Cluster.** tech-right / religious-right / patron-wing / state-actor / ca-operator / etc. This is the cross-cluster operational grouping.

**Power-relationship.** funder-of / employer-of / member-of / coordinator-of / target-of / etc. This applies to connection entities.

## Why 11 axes rather than fewer

The 11-axis structure is intentionally over-specified for current needs. The reason: each axis supports a class of analytical question that a smaller axis set would not support cleanly. Removing axes (consolidating, simplifying) would force analytical questions back into ad-hoc tag conventions that have failed in previous schema iterations.

The trade-off is tagging-overhead-per-note. The vault accepts the per-note tagging overhead in exchange for the queryability benefit. Tools like Obsidian Bases substantially reduce the per-note tagging burden by automating tag application based on note-template defaults.

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