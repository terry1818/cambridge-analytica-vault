---
date: 2026-05-16
description: 'Cambridge University psychologist who built "This Is Your Digital Life" app for GSR; data harvester'
tags: [person, role/academic, role/researcher, topic/cambridge-analytica, topic/facebook-data, era/2014-2016]
type: person
full_name: Aleksandr Kogan
aliases: [Aleksandr Spectre, Dr. Spectre]
nationality: Moldovan-American (educated UK/US)
roles: [academic, app developer]
affiliations: [University of Cambridge, Global Science Research, Saint Petersburg State University]
notable_for: 'Built "This Is Your Digital Life" app that harvested up to 87M Facebook profiles for CA'
status: active
wikipedia_url: https://en.wikipedia.org/wiki/Aleksandr_Kogan_(psychologist)
---

# Aleksandr Kogan

## Summary

Psychologist and lecturer at the University of Cambridge (2012-2018); founder of [[Global Science Research (GSR)]]. Built the **"This Is Your Digital Life"** Facebook app in 2013 that harvested data from up to **87 million Facebook profiles** via Facebook's friends-data API permission. Sold the dataset to [[Cambridge Analytica]] in 2014, breaching Facebook's ToS. Later changed name to **Aleksandr Spectre** (which Wikipedia notes added to the story's "ominous" appeal as "Dr. Spectre"). Settled with FTC in 2019 with 20-year restrictions on business practices. ([[Source Wikipedia - Facebook-CA scandal]])

## Key facts

- **University role:** Lecturer at University of Cambridge, 2012â€“2018
- **Company:** [[Global Science Research (GSR)]] â€” built the harvest app
- **Russia ties:** named on a grant at Saint Petersburg State University (cyberbullying research, post-2013 visit); maintains role was limited to occasional lectures
- **App user count:** ~270,000 downloaded; harvested data on up to 87M friends
- **2016-01:** signed Facebook certification that data was deleted (later proven false)
- **FTC 2019:** consent order, 20-year restrictions, required to delete all data and derived models
- **Testimony 2018-04:** before UK Parliament re GSR's data collection

## Disputed facts

- Read_stream Facebook permission: Facebook claimed Kogan's app didn't get this (would have permitted message access); Kogan's testimony contradicted Facebook's position; ICO noted the discrepancy `#claim/disputed`

## Connections

- **Built data tool for:** [[Cambridge Analytica]] / [[SCL Group]]
- **Cambridge colleagues:** [[Michal Kosinski]] (separate, parallel work at Cambridge Psychometrics Centre)
- **Whistleblower exposing him:** [[Christopher Wylie]]

## Timeline

- `2012-2018` â€” Lecturer, University of Cambridge
- `~2013` â€” Visits Saint Petersburg State University; later named on grant
- `2013` â€” Founds GSR; builds "This Is Your Digital Life" app
- `2014` â€” Sells dataset to [[Cambridge Analytica]]
- `2014-04` â€” Facebook deprecates friends-data API
- `2015-04` â€” Facebook shuts API entirely
- `2016-01` â€” Signs Facebook certification of data deletion
- `2018-03` â€” Exposed in Wylie disclosures
- `2018-04` â€” Testifies before UK Parliament
- `2019` â€” FTC consent order; renamed to Aleksandr Spectre by this time

## Open questions

- [ ] Full nature of Saint Petersburg State University grant and any continuing relationship
- [ ] Whether any harvested data remains accessible

## Sources

- [[Source Wikipedia - Facebook-CA scandal]]
- [[Source Wikipedia - Cambridge Analytica]]
- [[Source FTC Complaint Cambridge Analytica 2019]]
- [[Source DCMS Final Report 2019]]

## Role at CA and the GSR data-harvesting pipeline

[[Aleksandr Kogan]] is the Moldovan-born University of Cambridge social psychologist (Department of Psychology) who built the thisisyourdigitallife Facebook app via his consultancy [[Global Science Research]] (GSR). The app paid roughly 270,000 Facebook users via Amazon Mechanical Turk to take a personality quiz; under Facebook's [[Facebook Graph API v1]] permissions, the app then ingested data on those users' friends without the friends' direct consent. The friend-graph expansion produced data on an estimated 87 million Facebook users (Facebook's own final disclosed figure; earlier estimates were 50 million).

GSR licensed this dataset to SCL Elections / [[Cambridge Analytica]] under contract. CA in turn used it (with subsequent enrichment from US voter files, commercial data brokers, and proprietary survey work) to build the psychographic targeting models it deployed in [[Ted Cruz Campaign]] and the Trump general-election operation.

## Position relative to other Cambridge psychometrics researchers

Kogan's position was operationally adjacent to but distinct from the foundational academic work by [[Michal Kosinski]] and David Stillwell at the Cambridge Psychometrics Centre, which had earlier demonstrated that Facebook Like data could predict personality traits at meaningful accuracy. Kosinski and Stillwell declined to commercialise their methodology directly for CA-style use; Kogan did. The vault distinguishes carefully between the underlying academic work (Kosinski/Stillwell) and the operational deployment (Kogan/GSR/SCL), because conflating them has been a common error in CA reporting.

## Legal and reputational consequences

Kogan was named throughout the [[ICO Investigation]], the [[FTC v Facebook 2019]] action, and the various civil suits; he settled with the FTC in 2019. His academic position at Cambridge was untenable post-2018 and he eventually moved out of UK academia. He has given a number of media interviews (including 60 Minutes) characterising his role as commercially routine at the time and arguing that the responsibility for the data exposure lies more with Facebook's API design than with GSR's commercial exploitation of it. The vault treats his self-characterisation as a primary source on its own terms (Tier-2) while noting that the regulatory record reached a less exculpatory conclusion.

## See also

- [[Cambridge Analytica]]
- [[SCL Group]]
- [[GSR to CA data flow]]
- [[Facebook Graph API v1]]
- [[Facebook-Cambridge Analytica Scandal]]
- [[Michal Kosinski]]
- [[David Stillwell]]
- [[Christopher Wylie]]
- [[ICO Investigation]]
- [[FTC v Facebook 2019]]
- [[Timeline - Aleksandr Kogan]]

## Academic background and the Cambridge psychometric ecosystem

Aleksandr Kogan (born 1985 in Moldova, then Soviet Union; moved to US at age 7) was a University of Cambridge social-psychology faculty member at the Department of Psychology and an affiliate of the Cambridge Psychometrics Centre during the 2013-2016 period when his GSR / thisisyourdigitallife operation produced the [[Facebook-Cambridge Analytica Scandal]] data exposure. His academic specialisations included positive psychology, social attachment, and Russia / former-Soviet-state social-psychology research (which would become operationally relevant to subsequent commentary about his Russian-state contacts).

The Cambridge Psychometrics Centre (CPC, led by David Stillwell with [[Michal Kosinski]] as a founding research figure) had pioneered the Facebook-Likes-predict-personality methodology that Kogan would commercialise. Kosinski and Stillwell's research, principally the myPersonality app and the 2013 PNAS paper showing prediction accuracy from Facebook Likes, was foundational academic infrastructure. Kogan's distinctive contribution was the commercial-deployment step that Kosinski and Stillwell explicitly declined.

## Global Science Research (GSR) and the SCL/CA contract

Kogan formed GSR (Global Science Research Ltd, UK-domiciled) in early 2014 with two co-founders, with the explicit purpose of providing commercial data-collection-and-analysis services to political and commercial clients. SCL Group signed a services contract with GSR in June 2014. The contract specifically authorised GSR to use Facebook Graph API access to collect personality-prediction data on US voters, with the data licensed to SCL for political-targeting purposes.

The thisisyourdigitallife Facebook app was the operational mechanism. The app was a personality quiz that paid Mechanical Turk workers a small fee to take the quiz; under Facebook Graph API v1, the app then ingested data on those users' Facebook friends without the friends' direct consent. Approximately 270,000 users took the quiz; the friend-graph expansion produced data on an estimated 87 million Facebook users (Facebook's final disclosed figure; earlier estimates were 30-50 million).

The 87 million figure is significant because it dwarfs the consent population. The data exposure was structurally enabled by the Facebook Graph API v1 design (which exposed friend data without friend consent); GSR/CA's commercial exploitation of that exposure was operationally novel; Facebook's enforcement of its developer terms of service (which prohibited the commercial use of friend-data) was operationally absent until the 2015 deprecation of v1 and the public 2018 reckoning that followed Wylie's disclosure.

## The Russian-state-contact question

Kogan's academic work included collaboration with Russian universities (specifically St. Petersburg State University, where he held a position concurrent with Cambridge) and research on Russian topics. His funding for some of this work came from Russian-state-affiliated sources. The relationship between his Russian academic work and his GSR commercial work has been investigated by the [[Mueller Investigation]], by the [[Senate Intel Vol 5 2020]] inquiry, and by various other authorities; the public-record finding is that the academic and commercial threads were operationally separate, with no documented transfer of CA-derived data to Russian state actors via Kogan.

The vault treats this finding as Tier-2 settled (multiple investigative bodies converged on the same conclusion based on independent evidence). It does not foreclose the possibility that subsequent disclosures could change the picture; the public-record state as of 2026 is what the various investigations established.

## The Facebook policy violations in detail

The GSR / Facebook violations were several. First, the explicit Facebook developer terms of service prohibited the commercial transfer of Graph-API-derived data to third parties; GSR's contract with SCL was a direct violation. Second, the terms required app developers to obtain explicit user consent for the specific uses of data collected; thisisyourdigitallife's consent flow did not adequately disclose the SCL transfer or the friend-data scope. Third, Facebook's post-disclosure enforcement (which involved instructing GSR and CA to delete the data, accepting their certifications that the data had been deleted, but conducting no audit to verify deletion) was the second-order policy failure that the FTC eventually sanctioned.

## Regulatory consequences for Kogan personally

Kogan was named throughout the [[ICO Investigation]] (he was investigated as a UK data controller), the [[FTC v Facebook 2019]] action (he was named as the principal third-party operator of the thisisyourdigitallife app), and the various civil suits that followed the 2018 disclosure cycle. He settled with the FTC in 2019 (no financial penalty assessed against Kogan personally; the settlement included compliance obligations). His academic position at Cambridge became untenable in the immediate post-2018 period; he eventually departed UK academia.

He has given a number of post-2018 media interviews (60 Minutes US, Channel 4 UK, the Cambridge Analytica documentary contributions, various long-form podcast appearances) characterising his role as commercially routine within the broader Facebook-developer ecosystem and arguing that the principal responsibility for the data exposure lies with Facebook's API design rather than with GSR's commercial exploitation. The vault treats his self-characterisation as a primary source on his own account; the regulatory record reached a less exculpatory conclusion.

## Distinctive contribution to vault analysis

Kogan is the operational hinge between the academic [[OCEAN Model]] / Facebook-Likes research (Kosinski-Stillwell, 2008-2014) and the commercial CA-era deployment (SCL/CA, 2014-2018). The vault carefully distinguishes between the underlying academic work (which is real, peer-reviewed, and replicated) and the commercial operationalisation (which is documented but whose specific effect size in field deployment is contested).

He is also the technical-source-of-record for what the GSR data pipeline actually produced. His subsequent testimony, the regulatory findings against him, and the FTC settlement together establish the documentary backbone for the CA-data-side narrative that Wylie's testimony complements.

## Open research threads

- The full GSR-SCL contract text has been partially disclosed via regulatory filings but should be inventoried in the vault as a primary source.
- The Russian-state-contact thread, while regulatorily settled, deserves continuing monitoring as new disclosures emerge.
- Kogan's post-2018 commercial activity (where he has worked, what consulting he has done) is poorly documented in vault terms.

## See also

- [[Cambridge Analytica]]
- [[SCL Group]]
- [[GSR to CA data flow]]
- [[Facebook Graph API v1]]
- [[Facebook-Cambridge Analytica Scandal]]
- [[Michal Kosinski]]
- [[David Stillwell]]
- [[Christopher Wylie]]
- [[ICO Investigation]]
- [[FTC v Facebook 2019]]
- [[Mueller Investigation]]
- [[Timeline - Aleksandr Kogan]]

---

## Master synthesis

This node is one of the structural anchors of [[Master Theses MOC]] - the vault's top-level synthesis of the three converging theses (Structural Capture / Demographic Defensiveness / Post-Liberal Constitutional Replacement) that tie the vault clusters together.
