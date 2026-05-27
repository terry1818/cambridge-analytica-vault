---
date: 2026-05-22
description: Russian SVR-linked advanced persistent threat (APT) group attributed to multiple high-profile cyber-espionage operations including the 2016 DNC intrusion and the 2020 SolarWinds supply chain compromise.
tags:
  - org
  - org/state-actor
  - topic/cyber-operations
  - topic/information-warfare
  - topic/russia
  - era/2014-2016
  - era/2016-2018
  - era/2018-2020
  - era/2020-2024
type: organization
legal_name: Unknown (attributed unit within SVR, Russia's Foreign Intelligence Service)
aliases:
  - APT29
  - "The Dukes"
  - CozyDuke
  - NOBELIUM
  - "Midnight Blizzard (Microsoft designation)"
  - Dark Halo
  - UNC2452
founded: "c. 2008 (estimated from earliest attributed activity)"
dissolved: active
headquarters: Russia (attributed; specific facilities not publicly confirmed)
jurisdiction: Russia (attributed)
parent_org: SVR (Foreign Intelligence Service of Russia) — per US government attribution
subsidiaries: []
key_people: []
status: active
---

# Cozy Bear (APT29)

## Summary

Cozy Bear, tracked by the threat-intelligence community as APT29, is an advanced persistent threat group attributed by the US government and multiple private cybersecurity firms to Russia's SVR (Foreign Intelligence Service). It is distinct from [[Fancy Bear (APT28)]], which is attributed to the GRU (military intelligence). APT29 is assessed to focus primarily on long-term espionage — stealing credentials, harvesting communications from governments, think tanks, and corporations — rather than destructive operations or leak-and-amplify influence operations (the latter being more associated with APT28). Attribution is based on technical indicators (malware signatures, infrastructure patterns, operational security behaviors), US government indictments, and declassified intelligence assessments; no Russian official has confirmed APT29's existence or affiliations.

**Evidence discipline**: All attribution claims in this note come from named public sources. The SVR connection is assessed with high confidence by US government agencies and major cybersecurity vendors but remains an attribution, not a courtroom conviction.

## Identity

APT29 emerged in approximately 2008 by analyst estimates. It uses a range of custom malware toolsets (CozyDuke, MiniDuke, CosmicDuke, HAMMERTOSS, and others). Its operational security is assessed as high, and it typically prioritizes long-term persistent access over immediate exploitation. MITRE ATT&CK tracks it as Group G0016.

Multiple vendor naming conventions apply: Mandiant/FireEye uses APT29; CrowdStrike uses Cozy Bear; Microsoft has used NOBELIUM and (as of 2023) Midnight Blizzard; Recorded Future uses others. These designations refer to overlapping but not necessarily identical activity clusters.

## Leadership & Key Personnel

No individuals have been publicly indicted in connection with APT29 as of the vault's knowledge cutoff (unlike APT28/GRU, where the US DOJ issued 2018 indictments naming specific GRU officers). This absence of named indictees is itself a data point about the relative opacity of SVR operations vs. GRU.

## Activities

Notable attributed operations (per cited sources):

- **2015–2016 DNC/DCCC intrusion**: APT29 penetrated Democratic National Committee networks as early as summer 2015 — approximately a year before [[Fancy Bear (APT28)]] — and maintained persistent access for months. CrowdStrike, which investigated the intrusion, publicly attributed both APT28 and APT29. The US Intelligence Community Assessment (January 2017) attributed the DNC breach to Russian intelligence.
- **2020 SolarWinds supply chain compromise (NOBELIUM/UNC2452)**: APT29 is attributed by the US government (CISA, NSA, FBI, ODNI joint advisory, January 2021) to the compromise of SolarWinds' Orion software update process, which gave access to approximately 18,000 customer networks including multiple US federal agencies. This is considered one of the most sophisticated supply-chain attacks on record.
- **COVID-19 vaccine research targeting (2020)**: UK NCSC, US CISA, and Canadian CSE jointly attributed attacks on COVID-19 vaccine research organizations to APT29 (July 2020 advisory).
- **Microsoft corporate email compromise (2024)**: Microsoft disclosed in January 2024 that a group it calls Midnight Blizzard (APT29) had compromised senior Microsoft executive email accounts starting in late 2023.
- Ongoing: attributed to targeting embassies, foreign ministries, and NATO-adjacent organizations.

## Timeline

| Date | Event |
|---|---|
| c. 2008 | Earliest estimated APT29 activity |
| 2015 | DNC network penetration (CrowdStrike attribution) |
| 2016 | DNC breach confirmed; US IC Assessment implicates Russian intelligence |
| Jan 2017 | US IC Assessment publicly attributes DNC breach to Russian state actors |
| July 2020 | UK/US/Canada joint advisory attributes vaccine-research targeting to APT29 |
| Dec 2020 | SolarWinds breach publicly disclosed |
| Jan 2021 | US government joint advisory attributes SolarWinds to APT29/SVR |
| Jan 2024 | Microsoft discloses Midnight Blizzard (APT29) breach of exec email accounts |

## Successor / Related Entities

APT29 is an ongoing active entity as of 2024. Its SVR parent is the institutional successor to the KGB's First Chief Directorate. Analysts including Rid argue that SVR active measures — including digital operations — are the institutional descendants of [[KGB Service A]].

## Controversies / Investigations

- The absence of named indictments (unlike the GRU/APT28 case) limits legal accountability.
- CrowdStrike's private attribution of the DNC breach was contested by some at the time; subsequent US government assessments corroborated the attribution.
- The SolarWinds compromise raised questions about supply-chain vulnerability standards across the US public and private sectors.

## Open Questions

- What is the precise organizational structure of APT29 within SVR?
- Are there operational overlaps between APT29 and active-measures influence operations, or is APT29 strictly a collection unit?
- What proportion of APT29 targets are publicly known vs. classified?

## Sources

- [[Source - Rid 2020 - Active Measures]] — Tier 1 (contextual; for SVR as KGB successor)
- MITRE ATT&CK Group G0016: https://attack.mitre.org/groups/G0016/ — Tier 1 (technical reference)
- US CISA/NSA/FBI/ODNI Joint Advisory on SolarWinds (January 2021) — Tier 1 (US government attribution)
- RAND/SOCRadar: "Dark Web Profile: Cozy Bear / APT29" — https://socradar.io/blog/apt-profile-cozy-bear-apt29/ — Tier 2

## See Also

- [[Fancy Bear (APT28)]]
- [[GRU]]
- [[KGB Service A]]
- [[Active measures]]
- [[Internet Research Agency (IRA)]]
- [[Doppelganger]]
