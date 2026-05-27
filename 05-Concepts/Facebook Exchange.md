---
date: 2026-05-22
description: Facebook's real-time-bidding ad exchange, launched September 2012 and shut down November 2016, which allowed third-party advertisers to retarget Facebook users based on off-platform browsing data — Facebook's first integration with the programmatic advertising ecosystem.
tags:
  - concept
  - topic/facebook-data
  - topic/microtargeting
  - era/2014-2016
type: concept
aliases: ["Facebook Exchange (FBX)"]
domain: Digital advertising / programmatic advertising / platform monetization
first-documented: "Launched September 2012; shut down November 1, 2016"
---

## Definition

The Facebook Exchange (FBX) was Facebook's real-time-bidding (RTB) ad exchange, launched in September 2012, that allowed external demand-side platforms (DSPs) to bid in real time on Facebook display-ad inventory and retarget users based on their off-platform browsing behavior. It was the first major integration between Facebook's walled-garden user data and the broader programmatic advertising ecosystem, and social media's first mass-market RTB product. Antonio García Martínez, who was a product director at Facebook during the FBX era, provides a detailed inside account of FBX in *Chaos Monkeys* (2016).

## Origin / history

FBX was launched in September 2012 as Facebook responded to pressure to demonstrate post-IPO monetization capacity. The company had gone public in May 2012 with its ad revenue model questioned. FBX was framed internally as an answer to Google's DoubleClick Ad Exchange, and represented Facebook's first step toward the programmatic advertising market. García Martínez describes the product as driven by a period when Facebook was "desperate to boost revenue."

FBX allowed advertisers who had placed cookies on users' browsers (tracking off-Facebook browsing behavior) to bid in real time when those users appeared on Facebook — enabling retargeting: a user who visited a shoe retailer's website could be shown that retailer's ad in their Facebook feed within milliseconds. This was technically novel because it required matching anonymous cookie IDs from external ad networks to Facebook user identities.

## How it works

1. User visits an advertiser's website; advertiser's cookie is set.
2. User subsequently logs into Facebook.
3. Advertiser's DSP (via FBX) sends a bid request in real time (<100ms) when the user's impression becomes available.
4. Winning bidder's ad appears in the user's Facebook feed or right-rail.
5. Matching occurred via a cookie-sync mechanism between the external ad network and Facebook.

The key privacy implication: for the first time, Facebook allowed third parties to use behavioral data gathered outside Facebook to target users inside Facebook.

## Application in this domain

FBX is a structural link between the programmatic advertising ecosystem that García Martínez describes in *Chaos Monkeys* and the political targeting capabilities documented in the Cambridge Analytica / [[Cambridge Analytica]] story. FBX demonstrated that Facebook's user graph could be combined with external data to target individuals with high precision — the same architecture, at the ad-product level, that [[Custom and Lookalike Audiences]] subsequently perfected for political use. The data flows that made CA's model possible were enabled by the same infrastructure reasoning that created FBX.

Sheryl Sandberg told investors that FBX was "actually a very small part of our business" even within a year of launch — signaling Facebook's ambivalence about sharing control with outside bidders. This tension drove the shift to Custom Audiences, which kept data control within Facebook.

## Examples

- Retail retargeting: a user who browsed Amazon products sees those products in Facebook ads (the classic FBX use case).
- The political retargeting analog: a campaign could work with a data broker (e.g., a voter file vendor) whose data was synced with Facebook via FBX or Custom Audiences to reach identified voters.

## Effectiveness / critique

- FBX demonstrated effective retargeting performance but was limited to desktop (not mobile), which became a fatal limitation as mobile traffic surged.
- Facebook shut FBX on November 1, 2016, migrating advertisers to the Facebook Audience Network and Custom Audiences — products that gave Facebook more control over data and pricing.
- The privacy critique: FBX operationalized cross-context tracking on a massive scale, linking off-site behavioral data to Facebook's identity graph without clear user understanding or consent.

## Related concepts

- [[Real-time bidding]]
- [[Custom and Lookalike Audiences]]
- [[Facebook]]
- [[Cambridge Analytica]]
- [[Microtargeting]]
- [[Psychographics]]

## Sources

- [[Source - Garcia Martinez 2016 - Chaos Monkeys]] — primary cite. Evidence tier: **memoir / insider account**.
- Adweek, "Facebook Exchange Shutting Down": https://www.adweek.com/digital/facebook-exchange-shutting-down/
- Medium / Jounce Media, "FBX is Dead": https://medium.com/jounce-media-blog/fbx-is-dead-long-live-native-rtb-5355ad14f78a
- RetarGeter, "Facebook Ads API vs. Facebook Exchange": https://retargeter.com/blog/facebook-ads-api-vs-fbx/

## See also

- [[Real-time bidding]]
- [[Custom and Lookalike Audiences]]
- [[Facebook]]
- [[Cambridge Analytica]]
- [[Microtargeting]]
- [[Psychographics]]
