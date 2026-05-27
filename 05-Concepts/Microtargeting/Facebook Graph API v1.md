---
date: 2026-05-16
description: Facebook API version that allowed apps to access not just user data but full data of all friends
tags: [concept, topic/facebook-data, era/pre-2014, era/2014-2016]
type: concept
domain: tech
aliases: ["Facebook Graph API v1.0"]
---

# Facebook Graph API v1.0

## Definition

The first major version of Facebook's Graph API. Crucially permitted any third-party app to access **not only the app user's data, but also the full profile data of all of that user's Facebook friends** â€” without those friends' knowledge or consent. This permission ("friends-data") was used by tens of thousands of apps, including [[Aleksandr Kogan]]'s "This Is Your Digital Life".

## Timeline

- **April 2014:** Facebook deprecates the friends-data API (Graph API v1.0 â†’ v2.0)
- **April 2015:** Facebook shuts the v1.0 API entirely
- **Effect:** Data already collected by apps **remained in developers' possession** â€” including the 87M-profile dataset that ended up at [[Cambridge Analytica]]

## Significance

The single technical decision that enabled the entire CA harvest. ~300 friends per average user Ã— 270,000 app users = up to 87M profiles. [[Mark Zuckerberg]] later testified to Congress that Facebook was auditing "tens of thousands" of apps that had had similar access.

## Sources

- [[Source Wikipedia - Facebook-CA scandal]]
- [[Source Constine TechCrunch 2015-04-28 API shutdown]]
- [[Source An Update on Our Plans to Restrict Data Access 2018-04]]

## Vault context and open research threads

This concept is in the vault because it is one of the operational primitives the CA-to-present information warfare stack relies on. Concepts here are not academic curiosities. Each one corresponds to a real deployed tactic, a documented capability, or an analytical frame used to interpret deployments.

Use this node to anchor: a clear working definition, the methodological origin (academic paper, military doctrine, commercial product, hacker community), the documented deployments tied to this concept inside the vault, and the difference between the academic claim and the operational reality.

## Open research threads

- Origin trace: who first formalized this concept, in what paper, doctrine, or product? Add the primary source.
- Deployment trace: in which vault events was this concept demonstrably used? Cross-link the events.
- Effect-size evidence: what does the strongest peer-reviewed evidence say about how well this concept actually works on real populations? Where the literature has retracted or weakened a claim, note it.
- Adjacent concepts: which other vault concepts are confused with this one, and what is the clean distinction?

## See also

- [[Concepts MOC]]
- [[Methodology MOC]]
- [[Vault MOC]]
