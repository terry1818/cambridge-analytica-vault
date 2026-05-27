---
date: 2026-05-22
description: Russia's drive to create a nationally controlled, technically isolatable internet infrastructure — a "sovereign" RuNet capable of being disconnected from the global internet and managed internally.
tags:
  - concept
  - topic/surveillance
  - topic/info-warfare
  - era/2018-2020
  - era/2020-2024
  - era/2024-present
  - jurisdiction/russia
type: concept
aliases: ["Sovereign internet (RuNet isolation)"]
domain: internet governance / state censorship
first-documented: "2014 (legislative proposals); 2019 (enacted)"
---

# Sovereign Internet (RuNet Isolation) — Russia's Drive to Wall Off Its Internet

## Definition

"Sovereign internet" (suverennyy internet) refers to the Russian state project of constructing a nationally controlled network infrastructure capable of operating independently from the global internet — either selectively (throttling or blocking specific foreign services) or entirely (full disconnection from international routing). The legislative foundation is Federal Law No. 90-FZ, signed by President [[Vladimir Putin]] in May 2019, which obliged all Russian internet service providers to install state-mandated deep packet inspection (DPI) equipment and route traffic through state-controlled exchange points managed by [[Roskomnadzor]]. The concept builds directly on the surveillance architecture of [[SORM]] and extends it from passive interception to active traffic management.

## Origin / History

The idea of a nationally bounded Russian internet predates 2014 but was marginal until the Crimea annexation made Western sanctions and platform sanctions imaginable. The 2014 data-localization law (requiring Russian user data to be stored on Russian territory) was an early structural building block. Legislative proposals for a "sovereign internet" circulated from 2017. The proximate trigger was the US Senate Intelligence Committee's open use of social media data from Russian platforms in its election interference investigation, which Russian officials cited as evidence that dependence on foreign infrastructure was a strategic vulnerability. Federal Law 90-FZ passed in April 2019 and entered force in November 2019. Implementation has been gradual and technically uneven, with DPI deployment proceeding network segment by segment through the early 2020s.

## How It Works

1. **DPI hardware mandate**: Every Russian ISP must install Roskomnadzor-specified DPI equipment that allows the state to inspect, filter, throttle, reroute, or block traffic at the packet level — without the ISP's active participation.
2. **State-controlled traffic exchange**: Roskomnadzor maintains the right to designate traffic exchange points through which all international routing must flow, enabling a single disconnection switch in theory.
3. **National DNS**: A parallel Russian domain name system was created, allowing resolution of Russian domains to continue if international DNS is cut off.
4. **TSPU (Technical Means for Countering Threats)**: The official name for the DPI devices; installed at ISP expense, managed remotely by Roskomnadzor.
5. **Blocking and throttling**: Roskomnadzor used DPI to throttle Twitter in 2021 (reducing speeds by up to 50%) and to degrade VPN services from 2022 onward.

## Application in This Domain

Sovereign internet is the infrastructure layer enabling Russia's information environment to be fully sealed domestically — removing the ability of foreign platforms, independent media, or anti-war voices to reach Russian audiences through technical means. It represents the physical infrastructure complement to the legal architecture of [[SORM]] and [[Yarovaya Law]] and the institutional authority of [[Roskomnadzor]]. In the info-warfare frame it is both a defensive measure (preventing foreign influence operations from reaching Russian citizens) and an offensive enabler (the same DPI that throttles VPNs could amplify coordinated domestic messaging).

## Examples

- **Twitter throttling (2021)**: Roskomnadzor slowed Twitter's speed by 50% across mobile networks, then reversed after Twitter removed some flagged content. The episode demonstrated DPI capability without full block.
- **Post-invasion 2022 crackdown**: Facebook and Instagram blocked; independent outlets Novaya Gazeta and Echo of Moscow shut down; VPN use surged but has since been subject to progressive blocking.
- **VPN crackdowns 2023–2026**: Hundreds of VPN services blocked; some major VPN providers reported near-total blocks on their Russian infrastructure.

## Effectiveness / Critique

Technically, full disconnection ("RuNet island") has never been tested in a sustained real-world scenario, and experts at the Atlantic Council and Internet Governance Project have questioned whether the infrastructure can actually sustain full isolation without catastrophic damage to Russian commerce and finance. In practice, Russian authorities have used sovereign internet tools selectively and incrementally rather than attempting full disconnection. The project has been compared to China's Great Firewall, but Russia's starting point of a more open internet and more technically sophisticated user base makes equivalence difficult. VPN adoption surged after 2022; by 2024 an estimated 25–30% of Russian internet users used VPNs regularly.

## Related Concepts

- [[SORM]]
- [[Roskomnadzor]]
- [[Yarovaya Law]]
- [[Managed democracy (Surkovism)]]
- [[Active measures]]

## Sources

Evidence tier: **Established / Documented** — law text published; DPI deployment confirmed by independent network measurement organizations (OONI, Censored Planet, NetBlocks).

- [[Source - Soldatov Borogan 2015 - The Red Web]] — foundational account of the surveillance architecture preceding the 2019 law
- Atlantic Council, "Reassessing RuNet: Russian internet isolation and implications for Russian cyber behavior": https://www.atlanticcouncil.org/in-depth-research-reports/issue-brief/reassessing-runet-russian-internet-isolation-and-implications-for-russian-cyber-behavior/
- Internet Governance Project, "A closer look at the 'sovereign Runet' law" (2019): https://www.internetgovernance.org/2019/05/16/a-closer-look-at-the-sovereign-runet-law/
- DGAP, "Deciphering Russia's Sovereign Internet Law": https://dgap.org/en/research/publications/deciphering-russias-sovereign-internet-law
- HRW, "Russia: Growing Internet Isolation, Control, Censorship" (2020): https://www.hrw.org/news/2020/06/18/russia-growing-internet-isolation-control-censorship

## See Also

- [[SORM]]
- [[Roskomnadzor]]
- [[Yarovaya Law]]
- [[Agentura.ru]]
- [[Internet Research Agency]]
- [[Vladimir Putin]]
