---
date: 2026-05-23
description: Companies whose core business is acquiring, aggregating and reselling personal data on individuals — the aggregation layer that supplied Cambridge Analytica's raw material and now supplies both political campaigns and government surveillance agencies.
tags:
  - concept
  - topic/data-broker
  - topic/surveillance-state
  - topic/psychographics
  - era/pre-2014
  - era/2014-2016
  - era/2018-2020
  - era/2020-2024
  - era/2024-present
  - jurisdiction/us
type: concept
domain: tech / political economy / legal
first-documented: "1969 (Demographics Inc., later Acxiom); industry term in wide use by the 1990s"
aliases:
  - Data broker
  - Data brokers
  - Information broker
---

# data brokers

## Definition

A data broker is a company whose core business is collecting personal information about individuals — usually from sources other than direct relationships with those individuals — aggregating it, and selling or licensing it to third parties. Data brokers typically have no consumer-facing relationship with the people whose data they trade, which is precisely what makes the industry hard for individuals to see or escape. The category spans consumer-marketing brokers ([[Acxiom]], Epsilon, Experian, Oracle Data Cloud), people-search and risk brokers ([[LexisNexis Risk Solutions]], Thomson Reuters CLEAR), and location-data brokers ([[Gravy Analytics]], [[Babel Street]], [[Venntel]], X-Mode/Outlogic).

## Origin / history

The industry is older than the internet. Acxiom traces to Demographics Inc., founded in 1969; the modern direct-marketing data trade matured through the 1980s and 1990s on mailing lists, credit headers, and public records. The internet, smartphones, and the advertising-technology "bidstream" massively expanded the available raw material. The global data-broker market was estimated at roughly $278 billion in 2024 and is forecast to keep growing. Two regulatory shocks reshaped the industry: the EU's GDPR (2018) and the California Consumer Privacy Act, plus the reputational damage of the [[Facebook-CA Data Scandal]] — after which Acxiom sold its marketing-services arm and rebranded its parent as LiveRamp. A 2014 FTC report, "Data Brokers: A Call for Transparency and Accountability," remains a key reference point; state data-broker registries (Vermont 2018, California's Delete Act) followed.

## How it works

Data brokers run a four-stage pipeline. **Sourcing**: data is acquired from public records (voter rolls, property, court filings), commercial transactions (loyalty programs, warranty cards), credit headers, web and app tracking, and the real-time-bidding ad ecosystem. **Matching and resolution**: a persistent identifier (Acxiom's AbiliTec, LiveRamp's IdentityLink) is used to link records across sources to a single person, even as cookies expire and devices change. **Enrichment and scoring**: dossiers are augmented with inferred attributes — income, health interests, political leanings, [[Psychographics|psychographic]] scores. **Licensing**: access is sold to advertisers, insurers, employers, landlords, debt collectors, political campaigns, and government agencies. The individual is never a party to these transactions and usually cannot inspect or correct the dossier.

## Application in this domain

Data brokers are the supply layer for every actor the vault tracks. [[Cambridge Analytica]] bought commercial data to enrich its voter models; the firm itself functioned partly as a political data broker. After CA, the same brokered data flows to campaigns through ordinary ad tech. The more consequential thread is governmental: [[Babel Street]] and [[Venntel]] resell brokered location data to ICE, CBP, the Secret Service and others, letting agencies sidestep warrant requirements; [[LexisNexis Risk Solutions]]' Accurint platform sells encyclopedic dossiers to ICE under multi-million-dollar contracts. The 2025 [[Gravy Analytics]] breach exposed how a single broker can hold precise location histories on millions of people sourced from ~15,000 ordinary apps. This is the empirical core of the vault's hypothesis that a brokered/federal data apparatus has superseded the need for a bespoke CA-style firm.

## Examples

- [[Acxiom]] — archetypal consumer-marketing data broker
- [[LexisNexis Risk Solutions]] — risk/people-search broker with government contracts
- [[Gravy Analytics]] — location-data broker; 2025 breach
- [[Babel Street]] — location-data broker repackaging for government
- [[Cambridge Analytica]] — political data consumer and partial broker

## Effectiveness / critique

- **Industry defense:** Brokers argue they enable fraud detection, identity verification, marketing efficiency, and missing-persons work.
- **Documented harms:** FTC enforcement, journalism, and academic work document harms — exposure of survivors of abuse, sale of sensitive location data (clinics, places of worship), unverified data leading to wrongful targeting, and warrantless government access.
- **Critique:** Civil-liberties scholars and regulators argue the industry operates with minimal transparency, no meaningful consent, and weak accountability. A 2025 *Big Data & Society* analysis specifically faulted using LexisNexis-type databases — never designed for immigration enforcement and full of unverified data — in ICE operations. The vault treats the *scale and government use* of data brokers as well-documented fact.

## Related concepts

- [[commercial surveillance]]
- [[surveillance capitalism]]
- [[behavioral surplus]]
- [[Psychographics]]
- [[Federal-state data-sharing pipelines]]

## Sources

- FTC, "Data Brokers: A Call for Transparency and Accountability" (2014): https://www.ftc.gov/reports/data-brokers-call-transparency-accountability-report-federal-trade-commission-may-2014 — Tier-1
- Grand View Research, "Data Broker Market Size And Share, Industry Report 2033": https://www.grandviewresearch.com/industry-analysis/data-broker-market-report — Tier-2 (market sizing)
- [[Source - Tau 2024 - Means of Control]] — Tier-2 (documents the broker-to-government pipeline)
- Needle & Rubel, "The ICE–Lexis nexus," *Big Data & Society* (2025): https://journals.sagepub.com/doi/10.1177/20539517251351323 — Tier-1 (peer-reviewed)

## See also

- [[commercial surveillance]]
- [[surveillance capitalism]]
- [[Acxiom]]
- [[LexisNexis Risk Solutions]]
- [[Gravy Analytics]]
- [[Babel Street]]
- [[Cambridge Analytica]]
- [[Federal-state data-sharing pipelines]]
- [[Hypothesis - Federal database supersedes CA model]]
