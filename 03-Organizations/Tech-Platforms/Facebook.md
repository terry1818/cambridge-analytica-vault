---
date: 2026-05-16
description: Meta Platforms - social network whose Graph API v1 enabled CA harvest; $5B FTC fine; $725M class settlement
tags: [org, org/tech-platform, topic/facebook-data, topic/cambridge-analytica, era/pre-2014, era/2014-2016, era/2016-2018, era/2018-2020, era/2020-2024, era/2024-present, jurisdiction/us]
type: organization
legal_name: Meta Platforms, Inc. (formerly Facebook, Inc.)
aliases: [Meta, FB]
founded: 2004
jurisdiction: US
key_people: [Mark Zuckerberg]
status: active
wikipedia_url: https://en.wikipedia.org/wiki/Meta_Platforms
---

# Facebook / Meta

## Summary

Social network platform founded 2004 at Harvard by [[Mark Zuckerberg]] with classmates Eduardo Saverin, Andrew McCollum, Dustin Moskovitz, Chris Hughes. Publicly listed 2012. Rebranded as **Meta Platforms** in October 2021 to signal pivot toward "metaverse" / VR.

## Central role in CA scandal

Facebooks **[[Facebook Graph API v1.0]] friends-data permission** (2010-2015) was the technical mechanism that enabled [[Cambridge Analytica]]s harvest of up to 87 million user profiles via [[Aleksandr Kogan]]s app. Facebook:

- **Patented similar personality-prediction technology in 2012** (US Patent 8,825,764)
- **Knew of CAs "improper data-gathering practices" before December 2015** per March 2019 court filing by US AG for DC
- Received signed certifications in January 2016 from Nix and Kogan that data was deleted (later proven false)
- Deprecated friends-data API in April 2014; shut it down April 2015 â€” but data already harvested remained in developers hands
- Hired Joseph Chancellor (GSR co-founder) as quantitative researcher in 2015 â€” kept him through 2018 scandal

## Financial consequences

| Year | Action | Amount |
|---|---|---|
| 2018 | Market cap drop in week after scandal | ~$134 billion |
| 2019-07 | FTC fine | **$5 billion** (largest US privacy fine) |
| 2019-07 | SEC settlement (misleading investors) | $100 million |
| 2019-10 | UK ICO fine | Â£500,000 |
| 2022-12 | Meta class action settlement (US) | **$725 million** |
| 2023+ | Multiple EU fines (Irish DPC) | â‚¬1.2B and continuing |

**Total CA-related liabilities: ~$6.35 billion across jurisdictions and forums.**

## Other major consequences

- 2018-04 â€” Applied EU GDPR provisions globally (not just EU)
- 2018-04 â€” Established Social Science One research consortium
- 2018-04 â€” Mark Zuckerberg testifies before US Congress
- 2018-05 â€” Testifies before European Parliament
- 2019 â€” FTC 20-year consent decree
- 2019 â€” Independent Privacy Committee created on Facebooks board
- 2020-2021 â€” Frances Haugen disclosures
- 2021-10 â€” Rebranded as Meta
- 2024+ â€” AI pivot; major Llama model investments

## Adversarial Threat Reports

Since 2022, Meta publishes quarterly Adversarial Threat Reports documenting coordinated inauthentic behavior takedowns. Major networks identified include:
- [[Doppelganger]] (Russian state-linked)
- [[Spamouflage Dragonbridge]] (Chinese state-linked)
- Iranian influence operations
- Various commercial CIB operations

## Connections

- **CEO:** [[Mark Zuckerberg]]
- **CA scandal mechanism:** [[Facebook Graph API v1.0]] â†’ [[Global Science Research (GSR)]] â†’ [[Cambridge Analytica]]
- **Board (CA era):** [[Peter Thiel]] (2005-2022)
- **Major regulator:** US FTC, Irish DPC, UK ICO

## Sources

- [[Source Wikipedia - Facebook-CA scandal]]
- [[Source Wikipedia - Cambridge Analytica]]
- [[Source Kang Frenkel 2018-04-04 NYT 87 Million]]
- [[Source Meta Settlement 2022 Reuters]]
- [[Source Meta Threat Reports 2022-2024]]

## Platform role in the CA story

[[Facebook]] (rebranded Meta in 2021) is the platform whose [[Facebook Graph API v1]] design produced the data-exposure surface that GSR / Kogan / CA exploited, and whose ad-targeting infrastructure (Custom Audiences, Lookalike Audiences, programmatic ad serving with detailed targeting parameters) is the operational substrate on which CA's microtargeting deployment ran. The vault treats Facebook not as a CA accomplice but as the platform whose architecture made the CA event mechanically possible.

The 2014-2015 Graph API v1 friend-data exposure (the developer pattern that thisisyourdigitallife exploited) was not unique to CA. Facebook estimated tens of thousands of apps had access to comparable data scopes during the v1 window. CA is the documented case largely because [[Christopher Wylie]] surfaced it; the broader data exposure is partially documented but not comprehensively reconstructed.

## Regulatory consequences and structural change

The [[FTC v Facebook 2019]] settlement ($5 billion penalty plus structural privacy reforms) is the largest single privacy enforcement action in US history. The settlement required new internal privacy review processes, board-level privacy oversight, and ongoing FTC compliance reporting. The ICO separately fined Facebook GBP 500,000 (the maximum under pre-GDPR rules) for the UK-side exposure.

Structurally, Facebook deprecated Graph API v1 in 2015 (well before the public CA disclosures) and progressively tightened developer data access through v2 and v3. The Cambridge Analytica disclosure accelerated the public-facing communication of those changes but did not fundamentally drive them; the v1 to v2 transition was already underway for product and security reasons.

## Post-2018 political-content moderation

Facebook's approach to political content moderation has shifted multiple times: aggressive misinformation labelling and fact-checking partnerships through 2020-2022; partial rollback under various stakeholder pressures in 2023; further realignment in late 2024 / early 2025 (the [[Big Tech Trump 2.0 Alignment 2024-2025]] thread tracks the Meta-specific component). The vault treats each shift as a separate event with its own primary-source documentation rather than as a single coherent platform philosophy.

## Meta in the AI era

Meta's AI investments (Llama open-weight models, the AI assistant integration across Facebook, Instagram, and WhatsApp, and the Meta-OpenAI / Meta-Anthropic competitive positioning) are reshaping the persuasion-infrastructure layer that CA originally exploited. The vault tracks Meta's AI strategy as a continuation of the same underlying capability stack (massive data, sophisticated inference, addressable delivery at scale) rather than as a discontinuous new domain.

## See also

- [[Facebook-Cambridge Analytica Scandal]]
- [[Facebook Graph API v1]]
- [[Mark Zuckerberg]]
- [[Aleksandr Kogan]]
- [[GSR to CA data flow]]
- [[FTC v Facebook 2019]]
- [[ICO Investigation]]
- [[Source Levy 2020 Facebook Inside Story]]
- [[Source An Update on Our Plans to Restrict Data Access 2018-04]]
- [[Big Tech Trump 2.0 Alignment 2024-2025]]

## The platform's role in the post-2018 political-content-moderation evolution

Facebook's approach to political content moderation has shifted multiple times across the post-CA period. The evolution timeline:

**2018-2020: aggressive labelling and fact-checking.** Following the CA reckoning, Facebook expanded its third-party fact-checking partnerships, introduced policies prohibiting voter-suppression content, removed substantial volumes of accounts deemed inauthentic, and substantially expanded its trust-and-safety infrastructure. The 2020 election period saw the platform's most aggressive content-moderation posture in its history.

**2020-2022: Trump-account suspension and the post-January-6 environment.** Facebook suspended Trump's accounts on 7 January 2021 following the Capitol attack. The suspension was substantial (initially indefinite, then converted to a two-year suspension with subsequent quarterly review). The Oversight Board (Facebook's external content-moderation review body) reviewed and partially modified the Trump-suspension decision in 2021.

**2023: partial rollback.** Facebook restored Trump's account access in 2023. The broader content-moderation posture began to soften, with substantial reductions in fact-checking-partnership relationships, relaxation of certain misinformation policies, and reduced investment in trust-and-safety infrastructure.

**2024-2026: explicit Trump-administration alignment.** The post-2024 election period saw substantial further policy changes: elimination of third-party fact-checking partnerships in the US (replaced by community-notes-style user-driven labelling); relaxation of content-moderation policies on a number of categories that had been previously restricted; appointment of Trump-aligned board members; the broader public-posture realignment documented in [[Big Tech Trump 2.0 Alignment 2024-2025]].

## The Meta AI strategy and its implications for vault analysis

Meta's AI investments (Llama open-weight models since 2023, the AI assistant integration across Facebook / Instagram / WhatsApp, the substantial GPU infrastructure investment running into the tens-of-billions-of-dollars annually) are reshaping the persuasion-infrastructure layer that CA originally exploited. The vault tracks Meta's AI strategy as a continuation of the same underlying capability stack (massive data, sophisticated inference, addressable delivery at scale) rather than as a discontinuous new domain.

Specific implications for vault analysis:

- The Llama open-weight model release strategy makes high-capability AI models available to third-party developers and adversarial actors who would not otherwise have access to comparable capability. The implication for the persuasion-infrastructure question is substantial: even if Meta itself restricts the use of its in-platform capabilities, the open-weight model release makes the underlying capability widely available.
- The AI-assistant integration across Meta's platforms substantially expands the platform's own data-collection scope (conversations with the AI assistant produce richer behavioural-and-intent data than browsing-and-engagement data alone) and the platform's own persuasion-targeting capability.
- The competitive positioning relative to OpenAI, Anthropic, xAI, and the broader frontier-AI ecosystem is partially a Meta-strategy question and partially a vault-relevant infrastructure question.

## Why the vault treats Facebook as a top-tier load-bearing entity

Facebook is the platform whose architecture and policies have most directly shaped the post-CA information environment. Its decisions on developer-platform access, on political-content moderation, on AI integration, and on political-alignment positioning have direct effects on the substrate the vault analyses. The 2024-2026 Trump 2.0 alignment specifically has shifted Meta from a contested-and-occasionally-adversarial relationship with the Trump-orbit political ecosystem into a substantially-aligned relationship that the vault is tracking as a Tier-1 documented shift.