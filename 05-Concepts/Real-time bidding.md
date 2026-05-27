---
date: 2026-05-22
description: The programmatic advertising auction model in which ad impressions are bought and sold individually in millisecond auctions as web pages load — the infrastructure underlying digital political microtargeting and data-broker-to-platform data flows.
tags:
  - concept
  - topic/microtargeting
  - topic/facebook-data
  - era/pre-2014
  - era/2014-2016
type: concept
domain: Digital advertising / programmatic media buying / data infrastructure
first-documented: "First RTB-enabled ad exchanges emerged ca. 2009 (Google DoubleClick Ad Exchange)"
---

## Definition

Real-time bidding (RTB) is a method for buying and selling digital advertising impressions on a per-impression basis via automated instantaneous auction. When a user loads a webpage that carries programmatic ad inventory, a signal is sent to an ad exchange containing information about the impression (the page, the user's cookie or device ID, inferred demographics, and behavioral data). Demand-side platforms (DSPs) representing advertisers submit bids within approximately 100 milliseconds; the highest bid wins and the ad is served. The entire process occurs before the page finishes loading. RTB is the technical infrastructure of the programmatic advertising industry and the mechanism that enabled cookie-based behavioral targeting to operate at internet scale.

## Origin / history

- **Pre-2009**: Digital advertising was bought and sold via direct deals, ad networks, and remnant inventory pools — largely non-automated.
- **2009**: Google launches the DoubleClick Ad Exchange, the first major RTB-enabled exchange. Yahoo's RightMedia had earlier versions of exchange mechanics.
- **2010**: RTB adoption accelerates; demand-side platform (DSP) ecosystem develops rapidly.
- **2012**: [[Facebook Exchange (FBX)]] launches — RTB's first major integration with a closed social platform; described in detail by Antonio García Martínez in *Chaos Monkeys*.
- **2013–2016**: RTB becomes the dominant buying mechanism for non-reserved digital display advertising.
- **2019–2023**: Third-party cookie deprecation plans (Apple ITP, Google's Privacy Sandbox initiative) begin to erode cookie-based RTB; identity graph alternatives (authenticated ID solutions) emerge.

## How it works

The RTB auction chain involves several actors:

1. **Publisher**: A website or app that has ad inventory to sell, typically represented by a **supply-side platform (SSP)**.
2. **SSP**: Aggregates publisher inventory and sends bid requests to ad exchanges.
3. **Ad exchange**: Manages the auction; receives bid requests from SSPs and bid responses from DSPs.
4. **DSP (demand-side platform)**: Software used by advertisers to participate in auctions; makes real-time bidding decisions based on audience targeting parameters.
5. **Data Management Platform (DMP)**: Aggregates and segments audience data; feeds audience signals to the DSP for targeting.
6. **Advertiser**: Sets targeting parameters and bids via DSP.

**Privacy implication**: Each bid request includes the user's cookie ID (or mobile device ID), the URL of the page being loaded, and often inferred demographic and behavioral data. This data is transmitted to potentially hundreds of DSPs per page load, even for losing bidders — creating a massive data leakage channel documented by researchers including Lukasz Olejnik.

## Application in this domain

RTB is the technical substrate connecting data brokers, voter file companies, and psychographic profilers (like [[Cambridge Analytica]]) to the audiences those companies sought to reach. The chain: CA builds a psychographic profile → that profile is expressed as a targeting segment → the segment is activated via a DSP bidding on RTB auctions → matched users see targeted content. The [[Facebook Exchange (FBX)]] was the RTB integration specifically within Facebook; [[Custom and Lookalike Audiences]] operate on a related but distinct mechanism (list-matching rather than cookie-matching, but conceptually parallel).

Antonio García Martínez (*Chaos Monkeys*) worked on FBX and provides the most detailed insider account of how RTB was integrated into Facebook's ad product. The programmatic infrastructure he describes is the same infrastructure that political data operations — including CA's — ran on top of.

## Examples

- A voter-targeting campaign: a campaign's DSP loads the campaign's voter file as a data segment; bids on RTB auctions only when a matched user's cookie appears; delivers targeted ad within 100ms.
- Behavioral retargeting: a user who visited a Trump campaign donation page is cookied; the campaign's DSP subsequently bids on every RTB auction where that cookie appears, regardless of which website the user is visiting.
- The Cambridge Analytica model: psychographic targeting segments derived from the Kogan dataset could be deployed via any DSP buying RTB inventory on the open web — not limited to Facebook.

## Effectiveness / critique

- RTB is highly effective for commercial retargeting; its effectiveness for political persuasion (versus mobilization) is more contested.
- The privacy critique is substantial and well-documented: each RTB bid request is a data broadcast that exposes user identity signals to hundreds of companies, creating surveillance infrastructure not visible to users.
- Regulatory scrutiny has increased: GDPR (2018) raised questions about the legal basis for RTB's data flows in Europe; multiple enforcement actions and academic studies have documented RTB's data leakage scale.

## Related concepts

- [[Facebook Exchange (FBX)]]
- [[Custom and Lookalike Audiences]]
- [[Microtargeting]]
- [[Psychographics]]
- [[Cambridge Analytica]]
- [[Facebook]]

## Sources

- [[Source - Garcia Martinez 2016 - Chaos Monkeys]] — primary cite. Evidence tier: **memoir / insider account**.
- Wikipedia, "Real-time bidding": https://en.wikipedia.org/wiki/Real-time_bidding
- Novatiq, "Programmatic advertising: Evolution, history and future": https://www.novatiq.com/the-evolution-of-programmatic-advertising-state-of-the-nation/
- Lukasz Olejnik, "Selling Off Privacy At Auction": https://lukaszolejnik.com/rtbdesc
- EPOM, "The Nuts and Bolts of Real-Time Bidding": https://epom.com/blog/programmatic/what-is-real-time-bidding

## See also

- [[Facebook Exchange (FBX)]]
- [[Custom and Lookalike Audiences]]
- [[Cambridge Analytica]]
- [[Microtargeting]]
- [[Facebook]]
- [[Psychographics]]
