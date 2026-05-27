---
date: 2026-05-22
description: Insider memoir by a former Facebook ad-targeting product manager who built FBX and Custom Audiences — a ground-floor technical account of how Facebook's microtargeting advertising infrastructure was actually constructed.
tags: [source, book, facebook, advertising-technology, microtargeting]
type: source
tier: Tier-2
aliases: ["Source: Garcia Martinez 2016", "Source Garcia Martinez 2016 Chaos Monkeys"]
---

# Source — Chaos Monkeys: Obscene Fortune and Random Failure in Silicon Valley (Antonio García Martínez, 2016)

## Bibliographic
García Martínez, Antonio. *Chaos Monkeys: Obscene Fortune and Random Failure in Silicon Valley*. HarperCollins, 2016. 528 pp.

García Martínez founded AdGrok (a Y Combinator-backed ad-tech startup acquired by Twitter in a dual-track deal that landed him at Facebook); served as Facebook product manager for ad targeting 2011–2013; built Facebook Exchange (FBX) and co-developed Custom Audiences and Lookalike Audiences.

## Thesis & scope
Chaos Monkeys is structured as a Silicon Valley memoir but functions simultaneously as a technical exposé of how Facebook's advertising machinery was built from the inside. García Martínez's core argument is that Silicon Valley's techno-utopian self-image is a myth masking a ruthless zero-sum competitive environment in which personal relationships, data, and regulatory naivety are all monetized. More specifically for this vault's purposes: the book is the most detailed first-person account of how Facebook's advertiser-targeting infrastructure — the same infrastructure later exploited by Cambridge Analytica's downstream model — was architected and the design choices made.

## Key content relevant to the vault

**AdGrok / Y Combinator / Twitter acquisition.** García Martínez founded AdGrok, got Y Combinator backing (mentored by Paul Graham), negotiated simultaneously with Twitter and Facebook. Twitter acquired AdGrok (paying ~$10M for the two developers; García Martínez was acqui-hired directly into Facebook at PM level). This is a granular account of how Silicon Valley deal-making and acqui-hiring works, with named people including Chris Sacca and Paul Graham.

**Facebook Exchange (FBX).** García Martínez led the team that built FBX, Facebook's first programmatic advertising exchange — the mechanism that allowed real-time bidding on Facebook ad placements by third-party advertisers. FBX was eventually killed internally (Zuckerberg decided the future was mobile), but while it operated it was a significant data infrastructure experiment.

**Custom Audiences and Lookalike Audiences.** The book provides an insider account of the construction of Custom Audiences (allowing advertisers to upload their own customer email or phone lists and match against Facebook's user graph) and Lookalike Audiences (Facebook's system to identify users statistically similar to an advertiser's seed list). These two products are the direct technical predecessors of the data-matching techniques that made Cambridge Analytica's psychographic targeting operable at scale on the platform. CA's ability to upload modeled psychographic scores and find matching Facebook users depended on this infrastructure.

**Facebook's data environment circa 2011–2013.** The book describes what data Facebook had on users, how it was internally classified, and how it flowed to the advertising system. This includes behavioral data (likes, check-ins, link shares, comments) fed into targeting. García Martínez notes that the initial approach of using behavioral signals did not dramatically improve click-through rates over simple demographic targeting — a finding relevant to the vault's disputed-claims thread about CA's effectiveness.

**Sheryl Sandberg's role.** The book describes Sandberg's operation of Facebook's revenue side, her management style, and her positioning of advertising as the company's core strategic product. García Martínez portrays the Sandberg operation as a high-pressure, metrics-driven sales machine.

**Key named figures.** [[Mark Zuckerberg]] (depicted in design and strategy decisions); [[Sheryl Sandberg]] (revenue operations); Gokul Rajaram (Facebook ads product director, García Martínez's direct superior); Paul Graham (Y Combinator); Chris Sacca (Twitter advisor); David Fischer (Facebook VP of Advertising).

**Silicon Valley VC culture.** The book is a primary source on Y Combinator culture, startup acquisition dynamics, and the financial engineering behind acqui-hires — relevant to understanding how the Tech Right ecosystem's companies were built.

## How it maps to the vault
- Critical technical background for [[Psychographic Targeting]], [[Dark Ads]], [[Facebook Graph API v1]], [[Microtargeting]]
- Custom Audiences and Lookalike Audiences are the direct technical substrate for [[CA-SCL-Group\Cambridge Analytica]]'s Facebook-based targeting
- [[Mark Zuckerberg]] and [[Sheryl Sandberg]] nodes can cite this for internal corporate culture detail
- Connects to the vault's disputed-claims thread on whether CA's psychographic model added value over basic demographic targeting on Facebook

## GAPS — what this book raises that the vault appears to miss

1. **Facebook Exchange (FBX)** — The first programmatic advertising exchange built on Facebook; not in the vault as a named technical infrastructure entry. [verified-absent]

2. **Custom Audiences (Facebook product)** — The named Facebook advertising product that enabled advertiser customer-list matching against user graph; vault has generic microtargeting entries but not this specific named product that is the direct CA substrate. [verified-absent]

3. **Lookalike Audiences (Facebook product)** — Same gap as above; the statistical-twin targeting product. [verified-absent]

4. **Y Combinator** — Referenced repeatedly as the startup accelerator that shaped Silicon Valley culture; no organization entry in inventory. [verified-absent]

5. **Paul Graham** — Y Combinator founder; named in the book's AdGrok narrative; not found in inventory. [verified-absent]

6. **Gokul Rajaram** — Facebook ads product director during the FBX period; not in inventory. [verified-absent]

7. **Acqui-hire as a named mechanism** — The practice of buying a startup primarily to absorb its talent, paying compensation to individuals while the company shell is absorbed; not found as a concept entry. [candidate]

8. **Real-time bidding (RTB) / programmatic advertising as a concept** — The vault addresses dark ads and microtargeting but not the underlying programmatic infrastructure that makes these possible at scale. [verified-absent]

## Evidence tier
Tier-2. First-person memoir by a named insider with verifiable employment history; technical claims about FBX, Custom Audiences, and Lookalike Audiences are corroborated by independent reporting and Facebook's own product announcements. Some interpersonal narratives are contested (Twitter disputed elements of the acquisition account). Apple briefly hired then fired García Martínez in 2021 following backlash over misogynistic passages in the book — this reputational note does not affect the technical accuracy of the advertising infrastructure claims.

## Related
- [[Psychographic Targeting]]
- [[Dark Ads]]
- [[Microtargeting]]
- [[Cambridge Analytica]]
- [[Mark Zuckerberg]]
- [[Sheryl Sandberg]]
- [[Source Zuboff 2019 Age of Surveillance Capitalism]]
- [[Source McNamee 2019 Zucked]]
