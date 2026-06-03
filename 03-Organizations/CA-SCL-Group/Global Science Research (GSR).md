---
name: Global Science Research (GSR)
description: Aleksandr Kogan's company -- built the thisisyourdigitallife app that harvested ~87M Facebook profiles for Cambridge Analytica
type: org
tier: A-Entity
status: defunct
date_created: 2026-05-17
tags: [org, CA-SCL-Group, kogan, facebook-data, GSR, data-harvest]
aliases: [GSR, Global Science Research, GSR Limited]
---

# Global Science Research (GSR)

GSR was the **data-harvesting front company** that mechanically executed the Facebook data theft at the center of the Cambridge Analytica scandal. Run by [[Aleksandr Kogan]] -- a University of Cambridge psychometrics researcher -- GSR built and operated the **[[thisisyourdigitallife]]** app, which acquired data from ~87 million Facebook profiles and transferred that data to [[Cambridge Analytica]] in violation of Facebook's terms of service. GSR is the operational hinge between CA's psychographic-targeting ambition and the actual data substrate that made it possible.

## Founding and people

- **Founded:** 2014, Cambridge UK
- **Director:** [[Aleksandr Kogan]] (sometimes appearing as Aleksandr Spectre after his 2015 name change)
- **Co-founder:** [[Joseph Chancellor]] -- who later joined Facebook (a fact that became deeply awkward during the 2018 scandal coverage)
- **Status:** Effectively defunct post-2018; the company name is sometimes still cited in UK Companies House filings as a wound-down entity

Kogan held an academic affiliation with the **Cambridge Psychometrics Centre** -- the same research group whose [[Source Kosinski Stillwell Graepel 2013 PNAS]] paper demonstrated that Facebook Likes alone could predict personality traits with surprising accuracy. CA wanted access to the [[Cambridge Psychometrics Centre]]'s licensed dataset and methodology; when [[Michal Kosinski]] declined to license his work to CA, GSR was created as a parallel vehicle to replicate the methodology under contract to CA.

## The thisisyourdigitallife app

The technical mechanism:

1. GSR built **[[thisisyourdigitallife]]** as a Facebook personality-quiz app
2. ~270,000 users installed it after being paid small fees (~$1-$4) via Amazon Mechanical Turk and similar platforms
3. The app legally collected the personal data of each installing user -- under the **Facebook Graph API v1.0** permissions model
4. **Critically:** v1.0 of the Graph API also allowed the app to collect data on the *Facebook friends* of installing users -- without those friends' consent
5. From ~270,000 consenting installers, GSR thus harvested data on **~87 million people**
6. GSR then transferred this dataset to [[Cambridge Analytica]] -- in direct violation of Facebook's TOS, which prohibited transfer of platform-acquired data to third parties

This friend-graph harvest mechanism was the **architectural vulnerability** that made the entire scandal possible. Facebook closed the loophole in v2.0 of the Graph API in **April 2014-April 2015** -- but the harvest had already occurred during the v1 window.

## CA's use of the GSR data

CA fed the GSR dataset into its psychographic-profiling models -- combining Facebook Likes with OCEAN ([[OCEAN Model]]) personality dimensions to score US voters on the "Big Five" personality traits. The contested empirical question (see [[Source Sumpter interview with Kogan]]) is **how predictive these scores actually were** -- Kogan himself has publicly stated CA's psychographic targeting was "incredibly ineffective" and largely sales pitch. Wylie's account in [[Source Mindfck (Wylie 2019)]] is more bullish on the operational impact.

Regardless of whether psychographic micro-targeting "worked," the **legal and political** consequences were enormous:

- **2018 [[Facebook-Cambridge Analytica Scandal]]** broke when [[Christopher Wylie]] went on the record with [[Carole Cadwalladr]] / The Observer and [[Channel 4 News]]
- Facebook ultimately paid a **$5 billion FTC settlement** in 2019 ([[FTC Settlement Facebook 2019]])
- CA filed for insolvency in May 2018
- UK [[ICO]] imposed enforcement and fines

## Open questions

- **Where is the GSR-harvested dataset now?** Facebook claims it secured certifications of deletion. Wylie has consistently maintained no one can fully verify deletion across all copies (CA, AIQ, third-party recipients, individual researchers).
- **Did derived models built on the GSR data persist?** The raw data is one question; the trained predictive models built on it (which encode patterns from the data) is a separate, less-investigated question.
- **Joseph Chancellor's Facebook role:** Chancellor left Facebook in 2018 but the timing of his departure relative to internal Facebook awareness of the GSR transfer is murky.
- **Was the GSR-CA contract the actual transfer mechanism?** Public reporting summarizes the contract but the full text has not been published.

## Connections

- [[Aleksandr Kogan]] -- founder and operator
- [[Joseph Chancellor]] -- co-founder, later at Facebook
- [[Cambridge Analytica]] / [[SCL Group]] -- primary client
- [[thisisyourdigitallife]] -- the app itself
- [[Facebook Graph API v1.0]] -- the technical vulnerability that enabled the harvest
- [[Cambridge Psychometrics Centre]] / [[Michal Kosinski]] / [[David Stillwell]] -- academic origin of the methodology
- [[OCEAN Model]] -- psychographic framework
- [[Christopher Wylie]] -- whistleblower; previously worked alongside Kogan inside the SCL/CA network
- [[Facebook-Cambridge Analytica Scandal]]
- [[ICO Investigation into Political Campaigning]]

## Sources

- [[Source Kosinski Stillwell Graepel 2013 PNAS]]
- [[Source Matz Kosinski Nave Stillwell 2017 PNAS]]
- [[Source Wikipedia - Aleksandr Kogan]] (to create)
- [[Source Mindfck (Wylie 2019)]]
- [[Source The Conversation Sumpter Kogan interview]] (to create)
- [[Source CBS News 2018-04-21 Who is Kogan]] (to create)
- [[Source CNBC 2018-04-24 Kogan unlikely Trump campaign]] (to create)
- [[Source Cambridge University statement on Kogan]] (to create)
- [[Source Varsity Kogan Facebook messages]] (to create)
- [[Source Parliament DCMS Briant essays]]
