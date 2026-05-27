---
date: 2026-05-16
description: ALPR (license-plate-reader) surveillance company; $7.5B valuation; ~6,000 law-enforcement agencies; 4,000+ ICE-related lookups via "side door" 2025
tags: [org, org/tech-platform, org/surveillance, topic/alpr, era/2024-2026, jurisdiction/us]
type: organization
legal_name: Flock Group Inc.
aliases: [Flock Safety, Flock]
founded: 2017
headquarters: Atlanta GA
jurisdiction: US (private)
parent_org: ""
key_people: [Garrett Langley, Matt Feury, Paige Todd]
status: active
wikipedia_url: https://en.wikipedia.org/wiki/Flock_Safety
---

# Flock Safety

## Summary

Atlanta-based surveillance company founded 2017, providing **automated license-plate reader (ALPR) cameras** to ~**6,000 US law enforcement agencies** and **100+ public school systems**. **$7.5B valuation as of March 2025** ($275M Series E round). Lead VC: **Andreessen Horowitz (a16z)**. Cap table includes **Founders Fund (Peter Thiel)**, Bedrock Capital (Thiel-adjacent), Y Combinator, Kleiner Perkins, Tiger Global. Initial seed capital was largely **PayPal Mafia** money. Throughout 2025, Flock was implicated in **4,000+ ICE-related "side door" lookups** by local police on behalf of ICE, plus an **undisclosed CBP pilot program** that gave direct federal access ([[Source 404 Media 2025-05 Flock ICE Side Door]]).

## Identity

- **Founded:** 2017
- **HQ:** Atlanta, GA
- **Valuation:** $7.5B (March 2025)
- **Latest round:** $275M Series E led by Andreessen Horowitz (March 2025)

## Leadership

- Garrett Langley Ã¢â‚¬â€ Co-founder, CEO
- Matt Feury Ã¢â‚¬â€ Co-founder
- Paige Todd Ã¢â‚¬â€ Co-founder

## Capital structure / investors

- **Andreessen Horowitz (a16z)** Ã¢â‚¬â€ Series D lead ($150M) and Series E lead ($275M)
- **Founders Fund** ([[Peter Thiel]] VC firm)
- **Bedrock Capital** (Geoff Lewis; Thiel-adjacent)
- **Greenoaks Capital**
- **Meritech Capital**
- **Matrix Partners**
- **Sands Capital**
- **Kleiner Perkins**
- **Tiger Global**
- **Y Combinator** (seed; Thiel-orbit)
- **Initialized Capital** (Garry Tan; PayPal Mafia)

## Footprint

- **~6,000 law enforcement agencies** using Flock LPRs
- **100+ public school systems** with Flock devices installed
- Cameras read **license plates + vehicle make/model/color/decals** ("vehicle fingerprints")
- AI-searchable national network

## Federal access incidents 2025

- **May 2025:** 404 Media revealed local police were performing Flock searches "on behalf of ICE" Ã¢â‚¬â€ discovered because users typed "ICE" or "illegal immigration" in the search-reason field
- **August 2025:** Colorado local news discovered **CBP accessing Flock data via undisclosed "pilot program"**; Flock acknowledged
- **Virginia:** ~3,000 immigration-related searches over 12 months on the state network
- **At least 8 Washington state agencies** enabled 1:1 direct sharing with US Border Patrol
- **Alvin Independent School District (TX):** 733,000+ searches in one month (Dec 2025-Jan 2026); civil immigration searches outnumbered criminal immigration ~2:1
- **August 2025:** Flock publicly announced it would no longer conduct pilot projects with federal agencies
- **January 2026:** Flock introduced an admin-level toggle to disable all federal sharing per agency

## How it fits the architecture

Flock is the **distributed physical-sensor mesh** complement to [[Palantir Technologies]]'s data-integration layer. Where Palantir consolidates the records the federal government already holds, Flock provides **real-time location data on every car on the road** Ã¢â‚¬â€ and pipes it into federal investigations via local-police intermediation ("side door"). Combined with **school-camera coverage**, the system reaches minors and non-driving residents through their proximity to vehicles.

## Timeline

- `2017` Ã¢â‚¬â€ founded by Langley, Feury, Todd
- `2022` Ã¢â‚¬â€ Series D $150M led by a16z; targets reducing crime in America by 25% in 3 years
- `2025-03` Ã¢â‚¬â€ Series E $275M, $7.5B valuation
- `2025-05` Ã¢â‚¬â€ 404 Media exposes ICE "side door" via local police
- `2025-08` Ã¢â‚¬â€ CBP pilot program revealed; Flock pledges no more federal pilots
- `2025-10` Ã¢â‚¬â€ VPM / UW Center for Human Rights reporting on Virginia + Washington networks
- `2026-01` Ã¢â‚¬â€ Flock launches federal-sharing toggle

## Related entities

- [[Palantir Technologies]] Ã¢â‚¬â€ data-integration layer; complementary surveillance partner
- [[Peter Thiel]] Ã¢â‚¬â€ Founders Fund investor; shared funder pattern
- [[Trump EO Eliminating Information Silos 2025-03-20]] Ã¢â‚¬â€ broader legal pretext for federal access

## Open questions

- [ ] Did the January 2026 federal-sharing toggle materially reduce ICE access, or is it cosmetic?
- [ ] Full school-district deployment list (100+ school systems)
- [ ] Are camera feeds being retained beyond stated 30-day windows?
- [ ] Cross-state data persistence after agency-level federal-sharing toggle disabled

## Sources

- [[Source 404 Media 2025-05 Flock ICE Side Door]]
- [[Source UW Center for Human Rights 2025-10 Flock Washington]]
- [[Source VPM 2025-10-09 Virginia Flock Immigration]]
- [[Source The 74 2025 ICE School Cameras]]
- [[Source Flock Safety Series D Andreessen Horowitz]]
- [[Source Wikipedia - Flock Safety]]

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