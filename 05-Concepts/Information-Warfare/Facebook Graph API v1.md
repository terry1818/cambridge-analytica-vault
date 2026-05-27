---
date: 2026-05-16
description: Facebook API permission (2010-2015) that allowed third-party apps to harvest friends data without consent
tags: [concept, topic/facebook-data, era/pre-2014, era/2014-2016]
type: concept
domain: tech
first-documented: 2010
---

# Facebook Graph API v1.0

## Definition

First major version of Facebooks developer API, in use 2010-2015. The critical feature relevant to the CA scandal: the **friends_data permission** â€” when a Facebook user installed a third-party app and granted it permission, the app could collect not only the users profile data but also the **full profile data of every Facebook friend**, *without those friends knowledge or consent*. Average user had ~300 friends.

## How CA exploited it

- [[Aleksandr Kogan]] / [[Global Science Research (GSR)]] built "This Is Your Digital Life" app
- ~270,000 users downloaded and consented
- Friends_data permission expanded data collection to ~87 million profiles
- Data sold to [[Cambridge Analytica]] in 2014

## Closure

- 2014-04 â€” Facebook deprecated friends_data API (Graph API v2.0)
- 2015-04 â€” API fully shut down
- But data already harvested by third-party apps remained in their possession

## Why Facebook designed it this way

The friends-data API was not a security accident â€” it was a deliberate design decision to maximize the social-graph network effect of third-party apps. Facebook saw third-party developers as growth drivers; granting them access to friends data made their apps more useful (social games could see your friends; quizzes could compare you to friends; etc.). The privacy implications were understood internally but treated as secondary to growth.

By 2014, Facebook had recognized the abuse potential and started shutting it down â€” but two years of unrestricted harvest had already produced datasets like CAs.

## Related

- [[Facebook]] / [[Meta]]
- [[Global Science Research (GSR)]]
- [[Aleksandr Kogan]]
- [[Facebook-CA Data Scandal]]

## Sources

- [[Source Wikipedia - Facebook-CA scandal]]
- [[Source Constine TechCrunch 2015-04-28 API shutdown]]
