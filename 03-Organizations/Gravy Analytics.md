---
date: 2026-05-23
description: U.S. location-data broker that aggregated precise smartphone-location records from thousands of consumer apps, supplied government clients via its subsidiary Venntel, was barred by the FTC in late 2024, and suffered a massive data breach exposed in January 2025.
tags:
  - org
  - org/data-firm
  - topic/data-broker
  - topic/surveillance-state
  - topic/commercial-surveillance
  - era/2018-2020
  - era/2020-2024
  - era/2024-present
  - jurisdiction/us
type: organization
legal_name: Gravy Analytics, Inc.
aliases:
  - Gravy Analytics
  - Unacast
founded: "2012 (Unacast, Norway); Gravy Analytics founded c. 2014; merged 2023"
dissolved: ""
headquarters: Reston / Sterling, Virginia, USA
jurisdiction: US
parent_org: ""
subsidiaries:
  - Venntel
key_people:
  - Jeff White (founder, Gravy Analytics)
status: active
---

# Gravy Analytics

## Summary

Gravy Analytics is a U.S. location-data broker that built one of the largest commercial collections of precise smartphone-location records in the world. It aggregated location data harvested from thousands of ordinary consumer apps — games, dating, fitness, weather, transit apps — primarily by tapping the advertising-technology "bidstream," and resold derived location intelligence to commercial and government clients. Its subsidiary [[Venntel]] specialized in supplying location data to U.S. government agencies and law enforcement. In December 2024 the [[Federal Trade Commission]] proposed an order barring Gravy Analytics and Venntel from collecting and selling Americans' sensitive location data, finding the company had unlawfully tracked people to sensitive places such as healthcare clinics and military bases. Weeks later, in January 2025, a hacker posted samples of a multi-terabyte trove of Gravy location data on a Russian-language cybercrime forum — a breach that made the abstract scale of [[commercial surveillance]] concretely visible. Gravy is a central exhibit in the vault's argument that the [[data brokers|data-broker]] industry has built a population-scale tracking capability that any well-resourced actor — commercial or governmental — can simply buy.

## Identity

- **Legal name(s):** Gravy Analytics, Inc.
- **Other names / fronts:** Unacast (merged Norwegian-founded firm); [[Venntel]] (government-facing subsidiary)
- **Founded:** Gravy Analytics c. 2014; Unacast founded in Norway in 2012; the two merged in 2023 to create what the combined company called "one of the largest" location-data collections
- **Dissolved / restructured:** Still operating; under FTC restrictions and post-breach scrutiny
- **Parent / owner:** Private; backed by venture investment (specifics not reliably documented in reviewed public sources)
- **Subsidiaries:** [[Venntel]] — the unit that contracted with government and law-enforcement clients
- **Registered jurisdiction:** United States (Virginia)

## Leadership & key personnel

- **Jeff White** — founder of Gravy Analytics; built the company's location-intelligence product
- Post-merger leadership operated under the combined Unacast/Gravy entity; named executives are not consistently documented in reviewed sources

## Funding & money flows

Gravy Analytics' revenue came from licensing location intelligence to advertisers, retail and real-estate analytics clients, and — through [[Venntel]] — to government agencies. Venntel held contracts with components of the U.S. Department of Homeland Security and other agencies; the location data it sold has been tied in reporting and FTC findings to law-enforcement and immigration use. The 2023 Unacast merger consolidated two location-data businesses into a single large pool. Precise contract values and investor names are not consistently documented in reviewed public sources.

## Activities

**Bidstream harvesting.** Gravy's core method was acquiring location data emitted by the real-time-bidding advertising ecosystem. When an app requests an ad, device and (often) location data enters an auction "bidstream"; brokers monitoring those auctions can collect that data at scale without any direct relationship to the app or its users. The January 2025 breach indicated roughly 15,000 apps as sources — including Tinder, Grindr, Candy Crush, MyFitnessPal, Subway Surfers, period-tracking apps, and Microsoft and Yahoo apps.

**Location intelligence products.** Gravy packaged raw points into derived products — visit attribution, foot-traffic analytics, "points of interest" patterns showing where devices live, work, worship, and travel.

**Government supply via Venntel.** [[Venntel]] resold location data to government and law-enforcement customers, a channel that lets agencies obtain location histories by purchase rather than by warrant — the practice [[Byron Tau]] documents and that Senator Wyden's "Fourth Amendment Is Not For Sale Act" targets.

## Timeline

| Date | Event |
|---|---|
| 2012 | Unacast founded in Norway |
| ~2014 | Gravy Analytics founded in Virginia |
| ~2015–2023 | Gravy and Venntel build location-data products; Venntel contracts with U.S. government agencies |
| 2023 | Unacast and Gravy Analytics merge, consolidating location-data holdings |
| 2024-12 | FTC announces proposed order barring Gravy Analytics and Venntel from collecting/selling sensitive location data without consent |
| 2025-01-04 | Company (Unacast) identifies that a hacker acquired files from its Amazon cloud environment via a "misappropriated key" |
| 2025-01-10 to 13 | Hacker posts location-data samples on a Russian-language cybercrime forum; 404 Media and Hudson Rock publish app lists; breach reported globally |
| 2025 | Regulatory and litigation scrutiny intensifies; FTC order finalization process continues |

## Successor / related entities

- [[Venntel]] — subsidiary; the government-facing location-data reseller
- [[Babel Street]] — competitor/peer in the government location-data market (Locate X)
- X-Mode Social / Outlogic — peer location-data broker also subject to FTC action
- [[data brokers]] — the industry category Gravy exemplifies

## Controversies / investigations

**FTC action (December 2024).** The FTC found Gravy Analytics and Venntel unlawfully tracked and sold consumers' sensitive location data — including visits to health clinics and military installations — without consent, and proposed an order barring the practice. This was part of a wave of FTC location-data enforcement (alongside X-Mode/Outlogic and InMarket).

**The January 2025 breach.** A hacker claimed to have exfiltrated several terabytes of consumer location data. Unacast confirmed a breach traced to a misappropriated key in its Amazon cloud environment. Security researchers (Hudson Rock) and 404 Media analyzed the leaked sample and published lists of ~15,000 source apps. The breach is significant beyond Gravy itself: it demonstrated, with concrete data, that bidstream harvesting produces precise, re-identifiable location histories on millions of people from apps users never imagined were tracking them.

**Bidstream-consent question.** A core dispute is whether app users meaningfully consent to having location data sold onward. Generic ad-permission prompts and terms of service do not, critics argue, constitute consent to population-scale resale and government access. `#claim/disputed`

## Open questions

- [ ] What is the full list of Venntel's government customers and the contract values?
- [ ] How many distinct individuals' location histories were exposed in the 2025 breach, and where did the leaked data circulate?
- [ ] Did any government agency continue purchasing Gravy/Venntel data after the FTC order?
- [ ] What is the relationship between Gravy's holdings and those of peer brokers (potential overlap of the same bidstream data)?

## Sources

- TechCrunch, "Data broker Gravy Analytics confirms a data breach..." (Jan 2025): https://techcrunch.com/2025/01/13/gravy-analytics-data-broker-breach-trove-of-location-data-threatens-privacy-millions/ — Tier-2
- 404 Media, "Candy Crush, Tinder, MyFitnessPal: See the Thousands of Apps Hijacked to Spy on Your Location" (Jan 2025): https://www.404media.co/candy-crush-tinder-myfitnesspal-see-the-thousands-of-apps-hijacked-to-spy-on-your-location/ — Tier-2 (investigative)
- Malwarebytes, "Massive breach at location data seller" (Jan 2025): https://www.malwarebytes.com/blog/news/2025/01/massive-breach-at-location-data-seller-millions-of-users-affected — Tier-2
- FTC action on Gravy Analytics / Venntel (Dec 2024) — primary regulatory action; summarized in TechCrunch and Kaspersky coverage: https://www.kaspersky.com/blog/geolocation-data-broker-leak/53050/ — Tier-2
- [[Source - Tau 2024 - Means of Control]] — Tier-2 (frames the broker-to-government location-data pipeline)

## See also

- [[Venntel]]
- [[Babel Street]]
- [[data brokers]]
- [[commercial surveillance]]
- [[surveillance capitalism]]
- [[Byron Tau]]
- [[Federal-state data-sharing pipelines]]
- [[Hypothesis - Federal database supersedes CA model]]
