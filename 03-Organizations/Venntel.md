---
date: 2026-05-22
description: U.S. government contractor and subsidiary of Gravy Analytics that sold commercial smartphone location data — harvested from the ad-bidstream ecosystem — to ICE, CBP, FBI, IRS, and the Secret Service, enabling warrantless geofencing and immigration enforcement.
tags:
  - org
  - org/data-broker
  - topic/data-broker
  - topic/surveillance-state
  - topic/info-warfare
  - era/2018-2020
  - era/2020-2024
  - era/2024-present
  - jurisdiction/us
  - cluster/continuity
type: organization
legal_name: Venntel, Inc.
aliases:
  - Venntel
founded: "~2017"
dissolved: ""
headquarters: Ashburn, Virginia, USA
jurisdiction: US
parent_org: Gravy Analytics (itself merged with Unacast in 2023)
subsidiaries: []
key_people:
  - Jeff White (founder/CEO of Gravy Analytics)
status: restructured
---

# Venntel

## Summary

Venntel is the government-facing subsidiary of [[Gravy Analytics]], a commercial location-data company founded around 2011 (as "TimeRazor") and headquartered in Ashburn, Virginia. Venntel acts as the conduit between the commercial advertising-data ecosystem and U.S. federal law-enforcement and intelligence agencies, selling subscription access to a dataset drawn from hundreds of millions of smartphone advertising impressions (the "bidstream"). Between roughly 2017 and 2024, documented government clients included [[ICE]], [[CBP]] (Customs and Border Protection), the FBI, the IRS Criminal Investigation division, and the Secret Service. The relationship is a textbook instantiation of the [[Hypothesis - Federal database supersedes CA model]]: agencies obtained persistent, high-resolution location data on virtually any U.S. phone without obtaining a warrant, by purchasing commercially available data rather than compelling disclosure from carriers. The FTC moved against Gravy/Venntel in late 2024, and a final order was issued in January 2025 barring the sale of sensitive location data — the most significant federal enforcement action on commercial location data to date.

## Identity

Venntel, Inc. is nominally a separate legal entity from its parent Gravy Analytics, structured to serve as the government-sales arm. Gravy Analytics itself traces to a 2011 consumer-events startup called TimeRazor, later renamed Gravy, then Gravy Analytics, reflecting a pivot from lifestyle-recommendation to enterprise location intelligence. In November 2023, Gravy Analytics merged with Norwegian firm Unacast (whose principals had previously sold a failed music-streaming platform to Jay-Z), creating a combined entity with offices in Ashburn VA, Oslo, and Pilsen. The combined company continued operating Venntel's government contracts through the FTC enforcement period.

## Leadership & Key Personnel

- **Jeff White** — founder and longtime CEO of Gravy Analytics; built the company from TimeRazor through successive pivots.
- Leadership of Venntel as a distinct subsidiary is not publicly identified in available sources; it appears to operate as a product/sales unit rather than a separately managed company.

## Funding & Money Flows

Gravy Analytics is a venture-backed private company; specific funding rounds and investors are not reliably documented in public sources consulted for this note. Government revenue is partially documented: CBP paid Venntel nearly $500,000 in a single contract circa August 2020 for access to its geolocation dataset. The IRS purchased an annual subscription granting 12,000 queries per year. Total government contract value across all agencies is not aggregated in public records reviewed.

## Activities

Venntel's core product is subscription access to a database of smartphone pings derived from the **advertising bidstream** — the real-time data generated when apps request ad bids, which includes device identifiers and precise GPS coordinates. This data is collected not through direct agreements with users but through the layered supply chain of ad-tech: apps embed SDKs, SDKs participate in programmatic auctions, auction data is harvested, and location records are retained and resold. Venntel aggregates this from multiple upstream providers and resells it with analytical tools.

Government use cases documented in journalism and congressional inquiries include:

- **Geofencing**: Drawing a virtual perimeter around an address or GPS coordinate and pulling all device identifiers (and therefore owner-linked identities) present in that area during a specified time window.
- **Immigration enforcement**: ICE and CBP used Venntel data to locate and arrest individuals near the U.S.–Mexico border without obtaining a judicial warrant.
- **Criminal investigation**: IRS Criminal Investigation subscribed to Venntel from 2017–2018 to track suspects; the Inspector General later opened a formal investigation into whether this use violated the Fourth Amendment.
- **Persistent tracking**: Agencies could query historical location trails for any device in the dataset — a capability the Supreme Court's 2018 *Carpenter v. United States* ruling held requires a warrant when government compels it from carriers. The commercial-purchase route was understood by agencies as a workaround to *Carpenter*.

## Timeline

| Date | Event |
|---|---|
| 2011 | Gravy Analytics founded as TimeRazor (consumer events app) |
| ~2017 | Venntel established as government-facing subsidiary; begins selling to federal agencies |
| 2017–2018 | IRS Criminal Investigation purchases annual Venntel subscription (12,000 queries/year) |
| Aug 2020 | CBP pays ~$500,000 for Venntel data access contract |
| 2020 | Vice/Motherboard reporting first widely exposes ICE/FBI/IRS use of Venntel |
| 2021 | Congressional letters from Senators Wyden, Warren, Brown, Markey, Schatz requesting DHS Inspector General investigation |
| Nov 2023 | Gravy Analytics merges with Unacast |
| Dec 2024 | FTC files complaint against Gravy Analytics and Venntel |
| Jan 14, 2025 | FTC finalizes consent order; Gravy/Venntel prohibited from selling sensitive location data (carve-out for national security/law enforcement under limited circumstances) |

## Successor / Related Entities

- **[[Gravy Analytics]]** — direct parent; subject to the same FTC order
- **Unacast** — merged into Gravy Analytics in 2023
- **[[Babel Street]]** — comparable government-facing location data vendor, also documented selling to DHS/ICE
- **[[X-Mode Social / Outlogic]]** — parallel competitor, subject to earlier FTC action in 2024
- The FTC's January 2025 final order does not dissolve the company; Gravy/Venntel may continue operating under the consent decree's restrictions.

## Controversies / Investigations

**FTC Enforcement (2024–2025):** The FTC's complaint (announced December 2024, finalized January 2025) alleged that Gravy Analytics and Venntel violated the FTC Act by: (1) unfairly selling sensitive consumer location data without verifiable user consent; (2) selling data revealing visits to health clinics, reproductive health facilities, domestic abuse shelters, and places of worship. The final order requires deletion of previously collected sensitive-location data and prohibits future sales except in narrowly defined circumstances. This is one of the most significant FTC enforcement actions on a commercial data broker to date.

**Warrantless Government Surveillance:** Multiple senators, the ACLU, and the EFF argued that agencies' use of purchased location data constitutes a Fourth Amendment violation under *Carpenter v. United States* (2018). DHS, CBP, and ICE declined to explain their legal justification for the warrantless use in congressional correspondence.

**IRS Inspector General Investigation:** Following press reporting, the Treasury IG formally investigated the IRS's use of Venntel data without a warrant.

**ACLU Litigation:** The ACLU filed FOIA requests and a lawsuit against DHS, CBP, and ICE seeking records of their location data purchases and use policies.

## Open Questions

- What volume of immigration-enforcement actions were directly enabled by Venntel geofencing queries between 2017 and 2024?
- Does the FTC consent order's "national security" carve-out in practice allow resumed government sales?
- Are there undisclosed contracts with other agencies (NSA, DEA, state-level law enforcement)?
- What happened to the historical Venntel datasets already purchased by government agencies — does the FTC order compel agencies to delete them?
- What is the post-merger operational status of the Venntel brand within the Gravy/Unacast entity?

## Sources

- [[Source - Tau 2024 - Means of Control]] — Tier-2 (corroborated journalism; Tau documents the commercial data-broker pipeline to government surveillance agencies)
- FTC press release and final order (Jan 14, 2025): https://www.ftc.gov/news-events/news/press-releases/2025/01/ftc-finalizes-order-prohibiting-gravy-analytics-venntel-selling-sensitive-location-data — Tier-1 (primary regulatory document)
- FTC complaint/case page: https://www.ftc.gov/legal-library/browse/cases-proceedings/212-3035-gravy-analytics-inc-matter — Tier-1
- Vice/Motherboard, "How an ICE Contractor Tracks Phones Around the World": https://www.vice.com/en/article/ice-dhs-fbi-location-data-venntel-apps/ — Tier-2 (investigative journalism, corroborated by congressional correspondence)
- Vice/Motherboard, "IRS Could Search Warrantless Location Database Over 10,000 Times": https://www.vice.com/en/article/irs-location-data-venntel-contract/ — Tier-2
- EFF, "How the Federal Government Buys Our Cell Phone Location Data": https://www.eff.org/deeplinks/2022/06/how-federal-government-buys-our-cell-phone-location-data — Tier-2
- ACLU, "DHS is Circumventing Constitution by Buying Data": https://www.aclu.org/news/privacy-technology/dhs-is-circumventing-constitution-by-buying-data-it-would-normally-need-a-warrant-to-access — Tier-2

## See Also

- [[Hypothesis - Federal database supersedes CA model]]
- [[Gravy Analytics]]
- [[X-Mode Social / Outlogic]]
- [[Babel Street]]
- [[ICE]]
- [[Palantir Technologies]]
- [[ImmigrationOS]]
- [[Flock Safety]]
- [[Cambridge Analytica]]
