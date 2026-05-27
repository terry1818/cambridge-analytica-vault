---
date: 2026-05-23
description: The legal and technical channels through which federal and state government-held data — voter rolls, tax, Social Security, immigration, benefits, license records — are merged and cross-queried, building a de facto national data apparatus.
tags:
  - concept
  - topic/surveillance-state
  - topic/algorithmic-governance
  - topic/democratic-backsliding
  - topic/election-interference
  - topic/data-broker
  - era/2024-present
  - jurisdiction/us
type: concept
domain: legal / political science / tech policy
first-documented: "Long precedent (SAVE 1980s; ERIC 2012); decisive escalation 2025 (Trump executive order on data-silo elimination)"
aliases:
  - Federal-state data-sharing pipelines
  - Government data integration
  - Inter-agency data sharing
---

# Federal-state data-sharing pipelines

## Definition

Federal-state data-sharing pipelines are the legal agreements, statutory authorities, and technical systems through which personal data held by different government bodies — federal agencies, state agencies, and the two tiers between them — is combined, matched, and cross-queried. The relevant data includes voter registration rolls, tax records, Social Security records, immigration and citizenship records, public-benefits enrollment, motor-vehicle and ID records, and criminal-justice data. Individually each dataset is held by a specific agency for a specific purpose; a "pipeline" is any mechanism that lets one body's data be checked against, or merged into, another's — producing, in aggregate, something close to a unified national profile of a person.

## Origin / history

Inter-agency data matching is not new. The SAVE program (Systematic Alien Verification for Entitlements), run by what is now DHS/USCIS, was created in the 1980s to let benefits agencies check immigration status. The Electronic Registration Information Center (ERIC), a state-led compact founded in 2012, let member states cross-check voter rolls to flag movers, duplicates, and deaths — and several states withdrew from ERIC in 2023 amid partisan controversy. The decisive escalation came in 2025. A March 2025 Trump executive order directed federal agencies to share data across departments to "eliminate information silos." DHS and the Department of Government Efficiency (DOGE) moved to repurpose SAVE into a national citizenship-verification database; the DOJ began collecting state voter rolls — by reporting, 17 mostly Republican-led states turned theirs over — to run them through SAVE. In April 2026, NPR reported that a DOJ privacy officer resigned as the department prepared to transfer state voter data to DHS, with no Privacy Act notice published in the Federal Register.

## How it works

A pipeline has three components. (1) **Authority**: a memorandum of understanding, a statutory mandate, or an executive order that permits the transfer — sometimes lawfully, sometimes (critics argue) in tension with the 1974 Privacy Act, which requires public Federal Register notice when data is put to a new use. (2) **Transfer / matching**: data is copied or queried between systems; SAVE acts as a matching hub for citizenship questions, and integration platforms (notably [[Palantir Technologies]]' Foundry) can join previously siloed records into a single queryable environment. (3) **Action**: matched output drives a decision — removing a name from a voter roll, flagging a benefits claim, prioritizing someone for immigration enforcement. The same record can thus move from a benefits office to an enforcement system without the individual's knowledge or consent.

## Application in this domain

Federal-state data-sharing pipelines are the governmental backbone of the vault's central hypothesis. Where [[Cambridge Analytica]] had to *assemble* a population dataset by [[Facebook-CA Data Scandal|harvesting]] and buying from [[data brokers]], a government already *holds* authoritative, identity-resolved records on essentially everyone — and pipelines let those records be merged. Combined with [[commercial surveillance]] inputs and an [[algorithmic governance]] action layer, this produces a profiling-and-targeting capability of a kind CA only marketed. The 2025–2026 voter-data-to-DHS transfers also tie the pipeline directly to electoral mechanics: voter rolls are no longer just election-administration data but inputs to a citizenship-verification and enforcement system.

## Examples

- SAVE program — citizenship/immigration-status matching hub, repurposed 2025
- ERIC — state voter-roll cross-checking compact (2012; contested 2023)
- DOJ → DHS voter-roll transfers (2025–2026) — pipeline tying voter data to enforcement
- [[Palantir Technologies]] Foundry — the integration layer joining siloed federal records

## Effectiveness / critique

- **Stated rationale:** Proponents frame pipelines as fraud prevention, accurate voter rolls, and efficient government — "eliminating information silos."
- **Documented concerns:** Privacy-law experts note the 1974 Privacy Act's Federal Register-notice requirement; reporting indicates no such notice for the voter-data transfers. A federal judge (Judge David Carter, January 2026 ruling) found a DOJ voter-data demand violated federal and California privacy law. Voting-rights groups warn SAVE-based checks produce false non-citizen flags from stale or mismatched data.
- **Critique:** The core objection is purpose creep — data gathered for benefits, taxation, or election administration becomes an enforcement and surveillance instrument with no consent and weak [[algorithmic accountability]]. The vault treats the *existence and 2025–2026 expansion* of these pipelines as documented fact, and their lawfulness as actively litigated and contested.

## Related concepts

- [[algorithmic governance]]
- [[algorithmic accountability]]
- [[commercial surveillance]]
- [[data brokers]]
- [[democratic backsliding]]

## Sources

- NPR, "As DOJ prepares to share state voter data with DHS, a key privacy officer resigns" (April 2026): https://www.npr.org/2026/04/03/nx-s1-5768455/privacy-doj-dhs-voter-data — Tier-2
- NPR, "DOJ plans to share states' sensitive voter data with DHS" (March 2026): https://www.npr.org/2026/03/27/nx-s1-5764266/voter-data-trump-doj-dhs — Tier-2
- Campaign Legal Center, "What is the SAVE System?": https://campaignlegal.org/update/what-save-system — Tier-2
- Democracy Now!, "Palantir... Helps DOGE Build Master Database" (June 2025): https://www.democracynow.org/2025/6/3/makena_kelly — Tier-2

## See also

- [[algorithmic governance]]
- [[algorithmic accountability]]
- [[Palantir Technologies]]
- [[commercial surveillance]]
- [[data brokers]]
- [[Cambridge Analytica]]
- [[Hypothesis - Federal database supersedes CA model]]
