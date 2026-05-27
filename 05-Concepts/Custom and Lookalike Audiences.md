---
date: 2026-05-22
description: Facebook's core ad-targeting tools that allow advertisers to upload first-party data lists (Custom Audiences) and then find statistically similar Facebook users (Lookalike Audiences) — the mechanism that enabled Cambridge Analytica-style psychographic microtargeting at scale.
tags:
  - concept
  - topic/facebook-data
  - topic/microtargeting
  - topic/psychographics
  - era/2014-2016
  - era/2016-2018
type: concept
domain: Digital advertising / political microtargeting / data-driven political campaigns
first-documented: "Custom Audiences launched 2012; Lookalike Audiences launched 2013"
---

## Definition

**Custom Audiences** is a Facebook advertising feature, launched in 2012, that allows advertisers to upload a list of contact identifiers (email addresses, phone numbers, device IDs) from their own customer or voter databases; Facebook matches those identifiers against its user graph to create a targetable audience of matched Facebook accounts.

**Lookalike Audiences** is an extension launched in 2013: the advertiser selects a Custom Audience as a "seed," and Facebook's machine learning models identify Facebook users who do not appear in the seed list but who exhibit statistically similar behavioral and demographic profiles, scaling the targeting to a much larger population.

Together they constitute Facebook's core first-party-data targeting infrastructure and represent the mechanism by which voter files, supporter lists, and psychographic profiles derived from external data — including the Aleksandr Kogan / [[Cambridge Analytica]] dataset — could be matched to and deployed against specific Facebook user populations.

## Origin / history

- **2012**: Custom Audiences launched as Facebook moved toward more sophisticated ad targeting post-IPO. Addressed advertiser demand to bring their own customer data into Facebook rather than relying solely on Facebook's demographic categories.
- **2013**: Lookalike Audiences added, dramatically expanding the scalable reach of first-party data targeting.
- **2014–2016**: Political campaigns discover the tools. The 2012 Obama campaign had pioneered digital voter targeting; by 2016, both parties and third parties (including [[Cambridge Analytica]]) were using Custom Audiences extensively.
- **2016**: The Trump campaign's digital operation, led by Brad Parscale and working alongside CA, used Custom Audiences heavily for voter suppression messaging and persuasion targeting.
- **2022**: Meta removed political topic targeting attributes, increasing campaigns' dependence on Custom Audiences as the primary political targeting mechanism.

## How it works

**Custom Audiences workflow**:
1. Advertiser prepares a CSV of email addresses (or phone numbers, device IDs).
2. List uploaded to Facebook Ads Manager via hashed format.
3. Facebook matches hashes against its own user graph.
4. Matched users constitute the Custom Audience; ad can be delivered to them, or they can be excluded.

**Lookalike Audiences workflow**:
1. Advertiser selects a Custom Audience as the seed (minimum ~100 matched users; works best with 1,000+).
2. Advertiser selects a target country and a percentage of that country's Facebook users (1%–10%).
3. Facebook's ML models find users with similar behavioral and demographic signals to the seed.
4. The Lookalike Audience — potentially millions of users — becomes the targeting universe.

**Political application**:
- A campaign uploads its registered-voter support list → Custom Audience of known supporters.
- From that seed, Lookalike Audience identifies persuadable non-supporters with similar profiles.
- Psychographic profiles (from OCEAN surveys, behavioral inference, or Cambridge Analytica's dataset) could be attached to the seed list, in principle producing a Lookalike Audience of users matching a target psychological profile.

## Application in this domain

Custom and Lookalike Audiences are the delivery mechanism that made [[Cambridge Analytica]]'s psychographic model actionable on [[Facebook]]. CA's process was: (1) build psychographic profiles from the [[GSR Data Harvest]] dataset; (2) identify target OCEAN profiles for specific persuasion messages; (3) match those profiles to Facebook users via Custom Audiences; (4) find scale via Lookalike Audiences. The tool converts offline psychographic data into online ad delivery.

Antonio García Martínez (*Chaos Monkeys*) describes the development of these tools from the inside, understanding their commercial logic; the political application by CA and the Trump campaign is documented in the broader [[Cambridge Analytica]] investigation record.

## Examples

- **Cambridge Analytica (2016)**: Used voter file data matched to psychographic profiles uploaded as Custom Audiences to deliver tailored messages to specific OCEAN-profile segments.
- **Trump 2016 digital operation**: Brad Parscale's team used Custom Audiences for "dark post" voter suppression targeting — ads shown only to specific audiences that never appeared publicly.
- **Obama 2012**: Pioneered similar first-party voter file targeting on Facebook, though without the psychographic overlay CA claimed.

## Effectiveness / critique

- The Custom / Lookalike Audience system is technically highly effective for commercial targeting; its political effectiveness is well-documented in the targeting literature but causally difficult to isolate.
- Privacy critique: the tool operationalizes the import of external databases — voter files, loyalty programs, health data brokers — into Facebook's identity graph, creating cross-context data linkage without user awareness or consent.
- Post-Cambridge Analytica scandal (2018), Facebook implemented restrictions on what data categories could be used in Custom Audiences for political advertising, but the core mechanism remains operative.

## Related concepts

- [[Facebook Exchange (FBX)]]
- [[Real-time bidding]]
- [[Psychographics]]
- [[Microtargeting]]
- [[Cambridge Analytica]]
- [[GSR Data Harvest]]

## Sources

- [[Source - Garcia Martinez 2016 - Chaos Monkeys]] — primary cite. Evidence tier: **memoir / insider account**.
- Mozilla Foundation, "The basics on microtargeting and political ads on Facebook": https://www.mozillafoundation.org/en/blog/basics-microtargeting-and-political-ads-facebook/
- Aristotle, "Lookalike Audiences and Their Impact on Political Campaigns" (2023): https://www.aristotle.com/blog/2023/08/lookalike-audiences-and-their-impact-on-political-campaigns/
- ProPublica, "How Political Advertisers Target You on Facebook": https://projects.propublica.org/facebook-ads/
- Facebook Business Help, Custom Audiences: https://www.facebook.com/business/help/572787736078838

## See also

- [[Facebook Exchange (FBX)]]
- [[Real-time bidding]]
- [[Cambridge Analytica]]
- [[Psychographics]]
- [[Microtargeting]]
- [[Facebook]]
- [[GSR Data Harvest]]
