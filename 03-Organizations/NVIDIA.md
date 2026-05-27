---
date: 2026-05-23
description: The dominant designer of the graphics processors that train and run modern artificial intelligence — a single-firm chokepoint whose hardware underpins every major AI system and whose export to China has become a central instrument of U.S. geopolitical strategy.
tags:
  - org
  - org/data-firm
  - topic/tech-right
  - topic/surveillance-state
  - topic/comparative-authoritarianism
  - era/2018-2020
  - era/2020-2024
  - era/2024-present
  - jurisdiction/us
  - jurisdiction/china
type: organization
legal_name: NVIDIA Corporation
aliases:
  - Nvidia
  - NVIDIA Corp
founded: "1993-04-05"
dissolved: ""
headquarters: Santa Clara, California, USA
jurisdiction: US
parent_org: ""
subsidiaries:
  - Mellanox Technologies
key_people:
  - Jensen Huang (co-founder, CEO)
status: active
---

# NVIDIA

## Summary

NVIDIA Corporation, founded in 1993 by Jensen Huang and others, designs the graphics processing units (GPUs) that have become the indispensable hardware substrate of the artificial-intelligence era. Originally a maker of video-game graphics chips, NVIDIA's parallel-processing architecture turned out to be ideally suited to training and running neural networks; by the 2020s the company's data-center GPUs — the H100, H200, and Blackwell generations — were the chips behind nearly every frontier AI model, including those of [[OpenAI]], [[Google]], [[xAI]], Anthropic, and Meta. For this vault, NVIDIA matters as the clearest **chokepoint** in the entire AI-power story. Compute is the scarce input to AI; NVIDIA controls the supply of that input; and the U.S. government has, since 2022, used NVIDIA's export licensing as a primary lever of geopolitical and technological strategy against China. Whoever controls the chips controls who can build large AI systems — for advertising, surveillance, military, or information-warfare purposes. NVIDIA is the bottleneck through which all of those run.

## Identity

- **Legal name(s):** NVIDIA Corporation
- **Other names:** Nvidia
- **Founded:** April 5, 1993, by Jensen Huang, Chris Malachowsky, and Curtis Priem
- **Parent / owner:** publicly traded (NASDAQ: NVDA); one of the most valuable companies in the world
- **Subsidiaries:** Mellanox Technologies (networking, acquired 2020)
- **Registered jurisdiction:** Delaware / California, US

## Leadership & key personnel

- **Jensen Huang** — co-founder and CEO since inception; the singular public face of the company and a central figure in U.S.–China technology diplomacy, repeatedly negotiating directly with the U.S. government over China export policy

## Funding & money flows

NVIDIA is a publicly traded company whose market capitalization made it, at points in 2024–2026, the most valuable company in the world. It does not depend on outside funding; its money flows are the reverse — its data-center revenue, driven by AI demand, has been the single largest beneficiary of the AI buildout, with customers including the major cloud providers ([[Amazon AWS]], [[Google Cloud]], Microsoft) and AI labs spending tens of billions of dollars on its chips.

## Activities

**AI compute supply.** NVIDIA designs the GPUs and the CUDA software ecosystem on which modern AI training depends. Its dominance is both hardware and software: the CUDA platform creates lock-in that competitors (AMD, custom silicon) have struggled to break.

**The China chokepoint.** Since October 2022, the U.S. government has restricted exports of NVIDIA's most advanced chips to China and other "Tier 3" countries (China, Russia, Iran, North Korea, Sudan). The H100, H200, and Blackwell GPUs have been fully restricted to those markets. NVIDIA designed cut-down chips (the A800, H800, and later the H20) to comply with successive control thresholds; regulators repeatedly tightened the rules in response. NVIDIA has warned in SEC filings that it may be effectively foreclosed from China's data-center market, a material business risk.

**Smuggling and enforcement.** The intensity of Chinese demand produced a black market: U.S. prosecutors in 2025 charged a smuggling ring that allegedly moved at least $160 million of restricted H100/H200 GPUs to China between October 2024 and May 2025.

**Policy reversals.** In December 2025 the Trump administration announced plans to loosen controls, approving sales of the H200 to China — a reversal that re-opened debate over whether export controls help or hurt U.S. strategic position.

## Timeline

| Date | Event |
|---|---|
| 1993-04-05 | NVIDIA founded |
| 1999 | NVIDIA coins the term "GPU" with the GeForce 256 |
| 2006 | CUDA platform launched, enabling general-purpose GPU computing |
| 2012 | AlexNet, trained on NVIDIA GPUs, ignites the deep-learning era |
| 2020 | NVIDIA acquires Mellanox |
| 2022-10 | U.S. imposes first export controls on advanced NVIDIA chips to China |
| 2023 | NVIDIA's data-center revenue surges on AI demand; designs H800/A800 for China |
| 2023-10 | U.S. tightens controls; H800 also restricted |
| 2024 | NVIDIA briefly the world's most valuable company; H20 designed for China |
| 2024-2025 | $160M smuggling ring moves restricted H100/H200 chips to China (charged 2025) |
| 2025-12 | Trump administration moves to loosen controls, approving H200 sales to China |

## Successor / related entities

- [[OpenAI]] — major customer; its models train on NVIDIA hardware
- [[xAI]] — NVIDIA GPUs power the Memphis "Colossus" supercomputer
- [[Google Cloud]] / [[Amazon AWS]] — cloud customers (Google also builds its own TPUs)
- [[Lockheed Martin]] / [[Raytheon]] — defense primes increasingly dependent on AI compute supply chains

## Controversies / investigations

- **Export-control chokepoint:** NVIDIA's role as the single supplier of frontier AI compute makes its export licensing a de facto instrument of U.S. foreign policy. Critics argue this concentrates extraordinary geopolitical leverage in one firm's product roadmap. `#claim/established`
- **China policy whipsaw:** Successive tightening and the December 2025 loosening drew criticism from China hawks who argued controls were being traded away; the Council on Foreign Relations argued controls should remain.
- **Smuggling exposure:** The $160 million smuggling case demonstrated that export controls are porous and enforcement-dependent.
- **Antitrust scrutiny:** NVIDIA's CUDA lock-in and market dominance have drawn antitrust attention in the U.S., EU, and China.

## Open questions

- [ ] Does the December 2025 loosening of China controls reflect a durable policy shift or a temporary deal?
- [ ] Can any competitor (AMD, hyperscaler custom silicon, Huawei) meaningfully break NVIDIA's chokepoint?
- [ ] How does single-firm control of AI compute interact with the defense and surveillance buildouts elsewhere in this vault?

## Sources

- NVIDIA Corp, Form 10-Q FY2025 (SEC): https://www.sec.gov/Archives/edgar/data/0001045810/000104581025000116/nvda-20250427.htm — Tier-1 (primary filing)
- IFP, "The H20 Problem: Inference, Supercomputers, and US Export Control Gaps": https://ifp.org/the-h20-problem/ — Tier-2 (policy analysis)
- Council on Foreign Relations, "China's AI Chip Deficit": https://www.cfr.org/articles/chinas-ai-chip-deficit-why-huawei-cant-catch-nvidia-and-us-export-controls-should-remain — Tier-2
- CNBC, "How $160 million worth of export-controlled Nvidia chips were allegedly smuggled into China" (2025-12-31): https://www.cnbc.com/2025/12/31/160-million-export-controlled-nvidia-gpus-allegedly-smuggled-to-china.html — Tier-2
- Introl Blog, "AI Export Controls: Navigating Chip Restrictions Globally": https://introl.com/blog/ai-export-controls-navigating-chip-restrictions-globally-2025 — Tier-3

## See also

- [[OpenAI]]
- [[xAI]]
- [[Google Cloud]]
- [[Amazon AWS]]
- [[Lockheed Martin]]
- [[tech right]]
