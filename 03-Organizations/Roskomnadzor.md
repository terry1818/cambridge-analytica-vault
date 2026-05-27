---
date: 2026-05-22
description: Russia's federal media and internet regulator, functioning as the state's primary instrument of online censorship, content blocking, and personal-data enforcement.
tags:
  - org
  - org/regulator
  - org/government
  - topic/surveillance
  - topic/disinformation
  - topic/info-warfare
  - era/pre-2014
  - era/2014-2016
  - era/2016-2018
  - era/2018-2020
  - era/2020-2024
  - era/2024-present
  - jurisdiction/russia
type: organization
legal_name: Federal Service for Supervision of Communications, Information Technology and Mass Media (Roskomnadzor)
aliases:
  - RKN
  - Federal Communications Agency (predecessor)
founded: "2008-07-01"
dissolved: null
headquarters: Moscow, Russia
jurisdiction: Russian Federation
parent_org: Ministry of Digital Development, Communications and Mass Media of Russia
subsidiaries: []
key_people:
  - Mikhail Oseevsky (current head, from 2024)
  - Alexander Zharov (head 2012–2019)
  - Andrei Lipov (head 2019–2024)
status: active
---

# Roskomnadzor — Russia's Communications, Media, and Internet Regulator

## Summary

Roskomnadzor (abbreviated RKN) is the Russian federal executive body responsible for supervising mass communications, information technology, and telecommunications. In practice it functions as the Kremlin's primary censorship enforcement tool for the Russian internet, administering a national blocklist that had surpassed 1.2 million URLs by the early 2020s. It also administers personal data protection law, media licensing, and the technical enforcement of the [[Sovereign internet (RuNet isolation)]] legislation. Soldatov and Borogan's *The Red Web* traces how its powers were steadily expanded under [[Vladimir Putin]] from a routine licensing body into a censorship machine.

## Identity

Roskomnadzor was formed on 1 July 2008 by merging two predecessor agencies: the Federal Service for Supervision of Mass Media and Protection of Cultural Heritage (Rosokhranknadzor) and the Federal Service for Supervision of Communications (Rossvyaznadzor), pursuant to Government Decree No. 419. In its first years the agency was relatively low-profile, handling broadcast licensing and spectrum allocation. Its censorship role accelerated sharply after 2012 when legislation introduced mandatory website blocking without court orders, and again after 2014 when political opposition websites were blocked during the Ukraine crisis.

## Leadership & Key Personnel

- **Sergei Sitnikov** — first director, 2008–2012
- **Alexander Zharov** — director 2012–2019; presided over the agency's aggressive expansion of the national blocklist
- **Andrei Lipov** — director 2019–2024; oversaw implementation of the sovereign internet law DPI infrastructure
- **Mikhail Oseevsky** — director from 2024

## Funding & Money Flows

Roskomnadzor is a federal executive body funded through the Russian state budget. Its operational and technical expansion was substantially subsidized through state contracts with [[SORM]] equipment suppliers and the DPI vendors who built out the sovereign internet infrastructure.

## Activities

- **Blocklist administration**: Roskomnadzor maintains the Unified Register of Prohibited Sites, enabling it to order ISPs to block content related to drugs, child exploitation, suicide, extremism, and political opposition without prior judicial order in many categories.
- **Platform enforcement**: Issued thousands of "demand" notices to Google, Facebook/Meta, Twitter, YouTube, and TikTok threatening fines and speed-throttling for failure to remove prohibited content. Throttled Twitter in 2021 over failure to delete content before reversing.
- **Sovereign internet enforcement**: Since 2019 it has been the primary agency deploying deep packet inspection (DPI) hardware at ISPs under the RuNet isolation law.
- **SORM coordination**: Works alongside FSB as the regulatory counterpart for [[SORM]] obligations — operators must satisfy both Roskomnadzor licensing requirements and FSB hardware mandates.
- **Personal data localization**: Enforces the 2014 requirement that Russian citizens' personal data be stored on servers physically located within Russia; used to fine LinkedIn and block it in 2016.

## Timeline

| Date | Event |
|------|-------|
| 2008-07-01 | Founded by merger decree |
| 2012 | Federal Law No. 139-FZ creates mandatory blocklist without court orders |
| 2014 | Blocks Navalny blog, Kasparov.ru, Grani.ru during Crimea annexation |
| 2016 | Blocks LinkedIn for personal data localization violation |
| 2017–2018 | Attempts to block Telegram; Telegram uses Amazon/Google IPs, RKN blocks millions of IPs, collateral damage embarrasses agency; ban lifted 2020 |
| 2019 | Sovereign internet law passes; RKN begins DPI rollout |
| 2022 | Blocks Facebook, Instagram (designated "extremist") following Ukraine invasion; blocks independent Russian outlets |
| 2024–2026 | Accelerates VPN crackdown; 200,000+ Ukraine-related URLs blocked |

## Controversies / Investigations

The 2017–2018 attempt to block Telegram is the most documented operational failure: to enforce the block RKN ordered ISPs to block IP ranges used by Amazon Web Services and Google, inadvertently disabling millions of unrelated services. The episode exposed the technical limitations of blocklist-based censorship against sophisticated circumvention. The Council of Europe, EFF, Amnesty International, and Human Rights Watch have all published critiques of Roskomnadzor's censorship architecture as incompatible with Article 10 of the European Convention on Human Rights.

## Open Questions

- What is the effective rate of compliance among smaller Russian ISPs with DPI mandates, and to what degree is blocking geographically inconsistent?
- Does Roskomnadzor share blocklist data with allied governments (Belarus, etc.) in real time?

## Sources

Evidence tier: **Established / Documented** — statutory basis published in official Russian government decrees; blocking actions confirmed by independent network monitoring (OONI, Censored Planet).

- [[Source - Soldatov Borogan 2015 - The Red Web]]
- Wikipedia — Roskomnadzor: https://en.wikipedia.org/wiki/Roskomnadzor
- CFR, "Russia's Internet Censor is Also a Surveillance Machine": https://www.cfr.org/articles/russias-internet-censor-also-surveillance-machine
- RFE/RL, "Inside the Obscure Russian Agency That Censors the Internet": https://www.rferl.org/a/russia-agency-internet-censorship/32262102.html
- Meduza, "This is how Russian Internet censorship works" (2015): https://meduza.io/en/feature/2015/08/13/this-is-how-russian-internet-censorship-works

## See Also

- [[SORM]]
- [[Yarovaya Law]]
- [[Sovereign internet (RuNet isolation)]]
- [[Vladimir Putin]]
- [[Internet Research Agency]]
- [[Agentura.ru]]
