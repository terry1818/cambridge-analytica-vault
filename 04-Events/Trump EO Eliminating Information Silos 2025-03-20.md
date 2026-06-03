---
date: 2026-05-16
description: Trump executive order authorizing inter-agency federal data sharing - legal pretext for Palantir-built federated master database
tags: [event, topic/federal-database, topic/surveillance, era/2024-2026, jurisdiction/us]
type: event
event_date: 2025-03-20
location: White House
actors: [Donald Trump, Russ Vought, Stephen Miller, Palantir Technologies, DOGE]
outcome: Inter-agency data sharing authorized; Palantir/DOGE consolidation begins; 12+ Privacy Act lawsuits filed
status: ongoing
---

# Trump EO Eliminating Information Silos (2025-03-20)

## Summary

On **March 20, 2025**, Donald Trump signed Executive Order **"Stopping Waste, Fraud, and Abuse by Eliminating Information Silos"** -- directing federal agencies to share data across departments. Framed as anti-waste/anti-fraud. **In practice, this is the legal pretext that authorizes [[Palantir Technologies]] to build a federated master database covering the entire US population**, as inferred from subsequent reporting by NYT, NextGov, Democracy Now, and the New Republic. Brookings characterized the result as an attempt to build **"one big, beautiful database"** of Americans' most sensitive information ([[Source GWU One Big Beautiful Dataset]]).

## When & where

- **Date:** 2025-03-20
- **Signed at:** White House
- **EO designation:** Not yet assigned a standard EO number in this search; "Stopping Waste, Fraud, and Abuse by Eliminating Information Silos"

## Actors

- **Donald Trump** -- signer
- **[[Russ Vought]]** -- OMB Director; principal implementer
- **[[Stephen Miller]]** -- Deputy COS; policy advocate
- **[[Palantir Technologies]]** -- integration vendor (no formal acknowledgement of master-database contract)
- **DOGE** -- internal-government coordination body; embeds Palantir-derived personnel at IRS, SSA, HHS

## What it authorizes

- Inter-agency federal data sharing across departments
- Consolidation of data silos that **Privacy Act of 1974** specifically created to prevent
- Effective bypass of legacy Privacy Act protections

## Data sources known to be consolidated (per NYT / NextGov / ACLU reporting)

- IRS tax returns and SSNs
- SSA records
- DHS / ICE databases (passport, visa, immigration)
- HHS data (Medicaid, Medicare, ACA, refugee health programs)
- Department of Education student loan data
- VA records
- License plate reader feeds (via [[Flock Safety]] side-door access; CBP pilot)

## Sequence of events

- `2025-03-20` -- Trump signs EO
- `2025-04` -- Palantir staff embedded at IRS alongside DOGE staff to build "mega-API"
- `2025-04` -- $30M ICE [[ImmigrationOS]] contract announced
- `2025-05-30` -- NYT reports Palantir's expanding federated database role
- `2025-06-03` -- Democracy Now / Makena Kelly investigation on Palantir + DOGE
- `2025-06-17` -- Wyden / AOC oversight letter to Alex Karp
- `2025-09` -- ImmigrationOS prototype due
- `2025-12-09` -- Fortune reports new Palantir USCIS contract; 12 federal departments now contracted
- `2026-01-2026-04` -- At least 12 Privacy Act lawsuits filed against the consolidation

## Outcome / consequences

- **Direct outcome:** Federated master database under construction
- **Downstream:** ICE deportation operations dramatically expanded; voter-roll-purge litigation (DOJ suing 24 states); broader surveillance posture
- **Investigations triggered:** Senate Finance, House Judiciary, multiple Privacy Act civil suits, ACLU litigation
- **Legal challenge:** Privacy Act of 1974 statutory framework -- does the EO violate?

## Disputed facts

- **Existence of a single master-database contract** -- Palantir publicly denies; NYT and Democratic senators assert via reported sources. **`#claim/disputed`**
- **Scope of cross-agency data sharing actually achieved** -- varies by agency; full inventory unclear

## How it fits the architecture

This EO is **the legal load-bearing element** of the 2024-2026 surveillance architecture. Every other piece (Palantir contracts, ICE operations, Flock federal access, voter roll purges) traces back to the data-sharing authorization this EO created. **Repeal this EO and the architecture loses its spine.** Leave it standing and the rest is engineering work.

## Open questions

- [ ] Full EO text and citation number (search returned title but not standard EO number)
- [ ] Status of Privacy Act lawsuits -- outcomes by mid-2026
- [ ] Specific agencies that have NOT participated (resistance pockets)
- [ ] Court rulings on impoundment / unitary executive challenges

## Sources

- [[Source GWU One Big Beautiful Dataset]]
- [[Source New Republic 2025 Trump Palantir Database]]
- [[Source Snopes 2025-06-13 Palantir Database]]
- [[Source NextGov 2025-06 Democrats Palantir IRS]]
- [[Source Wyden AOC Karp Letter 2025-06-17]]
- [[Source Democracy Now 2025-06-03 Makena Kelly Palantir]]
- [[Source State of Surveillance 2026 DOGE Privacy Act Lawsuits]]

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