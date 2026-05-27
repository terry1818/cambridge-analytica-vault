---
date: 2026-05-22
description: GRU cyber espionage unit (Unit 26165) responsible for the 2016 DNC/DCCC hack-and-leak operation and sustained campaigns against NATO governments, election infrastructure, and civil society. Attributed by the Mueller Report and the July 2018 US federal grand jury indictment.
tags:
  - org
  - org/state-actor
  - era/pre-2014
  - era/2014-2016
  - era/2018-2020
  - era/2020-2024
  - era/2024-present
  - topic/info-warfare
  - topic/disinformation
  - topic/psyops
  - topic/election-interference
  - topic/russia-investigation
  - jurisdiction/russia
  - power/state-intel
  - cluster/continuity
type: organization
legal_name: "GRU Unit 26165"
aliases:
  - Fancy Bear
  - APT28
  - Sofacy
  - Sofacy Group
  - Pawn Storm
  - STRONTIUM (Microsoft designation)
  - Tsar Team
  - Sednit
  - Forest Blizzard (Microsoft updated designation)
  - Iron Twilight
  - GruesomeLarch
  - Threat Group-4127
founded: "~2004–2008 (active; exact formation date classified)"
dissolved: null
headquarters: "20 Komsomolsky Prospekt, Moscow, Russia (GRU headquarters)"
jurisdiction: Russia
parent_org: "[[GRU]] (Main Directorate of the General Staff)"
subsidiaries: []
key_people:
  - "Viktor Borisovich Netyksho (commanding officer at time of 2016 operations; lead defendant in US v. Netyksho)"
  - "Boris Alekseyevich Antonov (named defendant, 2018 indictment)"
  - "Aleksey Viktorovich Lukashev (named defendant, 2018 indictment)"
  - "Sergey Aleksandrovich Morgachev (named defendant, 2018 indictment)"
  - "Nikolay Yuryevich Kozachek (named defendant; developer of X-Agent)"
  - "Pavel Yershov (named defendant)"
  - "Artem Malyshev (named defendant)"
  - "Aleksandr Osadchuk (named in 2018 indictment as commanding officer of Unit 74455, coordinating with Unit 26165)"
  - "Anatoliy Kovalev (named defendant; election-board intrusion track)"
status: active
---

# Fancy Bear (APT28)

## Summary

Fancy Bear — the name coined by CrowdStrike in 2016 — is the colloquial designation for [[GRU]] Unit 26165, Russia's primary military cyber-espionage unit. It has been active in identifiable form since at least 2008 and is the unit directly responsible for the 2016 hack-and-leak operation against the [[2016 US Election]]: the intrusion into Democratic National Committee (DNC) and Democratic Congressional Campaign Committee (DCCC) networks, the theft of John Podesta's emails, and the subsequent deployment of the Guccifer 2.0 cover persona and DCLeaks distribution platform to weaponise stolen material.

The attribution of Fancy Bear to the GRU is among the most robustly documented claims in the entire Russia investigation record. It rests on: CrowdStrike's forensic analysis (2016); the July 2018 grand jury indictment *US v. Netyksho et al.* naming 12 Unit 26165 officers by name; the Mueller Report (2019) detailing the operations; and formal intelligence community attribution by the US, UK, EU, and allied governments.

Thomas Rid's *Active Measures* (2020) contextualises Fancy Bear's operations as the most recent iteration of a Soviet/Russian active-measures tradition — in particular the "hack-and-leak" track extending back to KGB forgery and document-planting operations.

## Identity

The group is designated APT28 by Mandiant/FireEye (the APT = "Advanced Persistent Threat" taxonomy; number 28 reflects its chronological identification). Microsoft tracks it as STRONTIUM (later Forest Blizzard). CrowdStrike's "Bear" naming convention for Russian state actors produced "Fancy Bear" to distinguish it from Cozy Bear (APT29, FSB-linked). MITRE ATT&CK catalogs it as Group G0007.

The group's principal tooling includes: **X-Agent** (cross-platform remote access trojan; also called Sofacy or CHOPSTICK); **X-Tunnel** (encrypted communications); **Foozer** (data collection); **DownRange** (dropper); **Komplex** (macOS implant). The consistent use of this proprietary toolset across years of operations is a primary basis for attribution continuity.

## Leadership & Key Personnel

The 12 named defendants in the July 2018 indictment (*US v. Netyksho et al.*) are the only GRU officers publicly identified by name in connection with these operations. Key figures:

- **Viktor Netyksho**: Commanding officer of Unit 26165; oversaw the DNC/DCCC operation.
- **Nikolay Kozachek**: Developer and maintainer of the X-Agent malware, deployed in the DNC/DCCC intrusions.
- **Anatoliy Kovalev**: Officer focused on US state election board and Secretary of State intrusions, representing the election-infrastructure track distinct from the DNC/Podesta email track.
- **Boris Antonov**: Department head within Unit 26165 overseeing the anti-Clinton spearphishing campaign.

All named defendants remain in Russia and none has been arrested or extradited.

## Funding & Money Flows

Funded through the Russian federal defence budget as part of the [[GRU]]. The 2018 indictment specifically documented that the conspirators used Bitcoin (mined independently and purchased via exchanges to obscure origin) to pay for operational infrastructure — servers, VPN services, domain registrations. This cryptocurrency layer was an attempt to evade financial-attribution tracing. (Tier-1 — indictment details)

## Activities

### 2016 US Election Interference (Primary focus for this vault)

The following is drawn from *US v. Netyksho et al.* (Tier-1) and the Mueller Report (Tier-1):

- **March 2016**: Unit 26165 officers begin researching DNC.org, HillaryClinton.com, and identifying individual targets for credential phishing.
- **March 19, 2016**: Spearphishing email sent to John Podesta (Clinton Campaign chairman); credentials harvested. Approximately 50,000 emails stolen from Podesta's Gmail account.
- **April 12, 2016**: Through stolen DCCC employee credentials, GRU gains access to the DCCC network.
- **~April 19, 2016**: Through a private DNC–DCCC network connection, GRU accesses DNC network.
- **April–June 2016**: GRU maintains covert access to approximately 29 DCCC and 30 DNC computers; deploys X-Agent implants and X-Tunnel for data exfiltration.
- **June 14, 2016**: DNC and CrowdStrike go public with the intrusion. In direct response, Unit 74455 (the companion GRU unit; see [[GRU]]) creates the **Guccifer 2.0** online persona, falsely claiming to be a lone Romanian hacker, to muddy attribution and undermine the Russian-state narrative.
- **June–November 2016**: Stolen documents distributed via Guccifer 2.0 (directly to journalists and to Wikileaks), DCLeaks website, and ultimately via WikiLeaks (Podesta emails released October 2016, coordinated with Unit 74455).
- **~October 2016**: Despite CrowdStrike remediation efforts, a Linux-based X-Agent implant remained active on the DNC network.
- **2016 election infrastructure targeting**: Kovalev's sub-track targeted election-administration entities: at least one Florida county election board, multiple state Secretaries of State offices, and a US election technology vendor (SBOE, Illinois, Arizona targeted). No evidence of vote-count manipulation; operations focused on voter-roll data and election-system vulnerabilities.

### Pre-2016 Operations (selected, documented)

- **2014**: Hack of German Bundestag (attributed by BfV/German domestic intelligence; confirmed by Bundestag investigation).
- **2015**: Spearphishing of French television network TV5Monde; attempted sabotage of broadcast systems.
- **2014–2016**: Sustained targeting of NATO governments, East European military and government agencies, and Ukrainian defence entities.
- **2015**: Targeting of WADA; theft of athlete therapeutic-use exemption data (part of 2018 US indictment; documents released as retaliation for Russian doping revelations).
- **2016**: French Presidential election targeting (Emmanuel Macron campaign) — documented by ANSSI (French cybersecurity agency) and MITRE attribution.
- **2016–2018**: Targeting of OPCW, Spiez Swiss lab, and US nuclear facility (all in 2018 indictment for operations related to anti-Russian international inquiries).

## Timeline

| Date | Event |
|---|---|
| ~2004–2008 | Unit 26165 operational in identifiable form (earliest attributed intrusions vary by source) |
| 2014 | Bundestag hack; increased tempo of NATO-government targeting |
| Mar–Jun 2016 | DNC/DCCC/Podesta intrusions |
| Jun 2016 | CrowdStrike publicly names Fancy Bear; Guccifer 2.0 persona created by Unit 74455 in response |
| Oct 2016 | WikiLeaks releases Podesta emails; coordinated with Unit 74455 |
| Nov 2016 | US presidential election; stolen material deployed |
| Jul 2018 | *US v. Netyksho et al.* grand jury indictment; 12 GRU Unit 26165 officers named (Tier-1) |
| 2019 | Mueller Report published; most detailed public account of Fancy Bear's 2016 operations (Tier-1) |
| 2020–present | Continued operations against European governments, COVID research institutions, defense contractors |

## Successor / Related Entities

- **Unit 74455 (Sandworm)**: The companion GRU unit that handled the weaponisation/release track — managing the Guccifer 2.0 persona, DCLeaks, and coordination with WikiLeaks. Also responsible for destructive operations (NotPetya, Ukraine power grid). Distinct from Fancy Bear in function: 26165 = collect; 74455 = disseminate and destroy.
- **APT29 / Cozy Bear**: FSB-linked group that separately intruded into DNC networks; distinct from Fancy Bear in both parent organisation (FSB vs. GRU) and method (quieter, longer-term access vs. exfiltration-and-release).

## Controversies / Investigations

- **CrowdStrike attribution (2016)**: First private-sector attribution to Russia; basis for DNC going public. CrowdStrike's methodology — identifying X-Agent tooling and infrastructure overlaps with previously attributed operations — has been challenged by Kremlin-adjacent commentators but is corroborated by NSA, FBI, CIA, and allied agency assessments. (Tier-2 for initial private attribution; Tier-1 for government confirmation)
- **US v. Netyksho et al. (2018)**: The indictment is the highest-confidence public document; it provides specific officer names, unit numbers, dates, Bitcoin transaction records, and technical indicators. Defendants have not appeared in court; indictment's evidentiary basis has not been tested adversarially. (Tier-1 as grand jury finding; caveat: untested in trial)
- **"No evidence of vote manipulation"**: The Mueller Report and the 2018 indictment are explicit that no evidence was found of altered vote counts. The election-infrastructure intrusions (Kovalev track) targeted voter rolls and systems but did not demonstrably alter tallies. This is a critical scope boundary for this vault.
- **WikiLeaks coordination**: The Mueller Report establishes that Unit 74455 (not Unit 26165 directly) coordinated the timing of releases with WikiLeaks, which the report treats as a knowing participant in the distribution operation rather than a neutral publisher. This remains contested by WikiLeaks/Assange supporters.

## Open Questions

- The precise degree to which the [[Internet Research Agency]] troll operation (a separate, Prigozhin-funded track) was coordinated with the GRU hack-and-leak track is not established in public record. Mueller investigated them separately.
- Whether specific content releases were timed in coordination with the Trump campaign's public statements (alleged in Part I of the Mueller Report but not charged as criminal conspiracy) is an area of unresolved evidentiary dispute.
- Ongoing Fancy Bear operations post-2020 against European election infrastructure, COVID-19 research institutions, and defence contractors are documented in government advisories but specific details are often classified.

## Sources

- [[Source - Rid 2020 - Active Measures]] — contextualises hack-and-leak in active-measures tradition; covers Fancy Bear operations (Tier-2)
- *United States v. Viktor Borisovich Netyksho et al.*, Indictment, US District Court DC, 13 July 2018. (Tier-1) https://www.justice.gov/file/1080281/download
- Mueller Report, Volume I (2019). US Department of Justice. (Tier-1) https://www.justice.gov/archives/sco/file/1373816/download
- CrowdStrike. "Who Is Fancy Bear?" https://www.crowdstrike.com/en-us/blog/who-is-fancy-bear/ (Tier-2 — originating private-sector attribution)
- MITRE ATT&CK: APT28 / Group G0007. https://attack.mitre.org/groups/G0007/ (Tier-2 — curated technical attribution database)

## See Also

- [[GRU]]
- [[2016 US Election]]
- [[Mueller Report]]
- [[active measures]]
- [[Internet Research Agency]]
- [[Russia]]
- [[Vladislav Surkov]]
- [[Doppelganger]]
