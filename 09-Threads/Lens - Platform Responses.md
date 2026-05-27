---
date: 2026-05-23
description: An analytical thread examining how social-media platforms responded to the Cambridge Analytica scandal and to disinformation more broadly — the policy changes, transparency tools, and takedowns, and what they did and did not change.
tags:
  - thread
  - status/in-progress
  - topic/cambridge-analytica
  - topic/disinformation
  - topic/info-warfare
  - era/2018-2020
  - era/2020-2024
type: thread
target_audience: policy
target_length: ~500 words
target_publication: internal vault analysis
---

# Lens - Platform Responses

## Pitch (one paragraph)

After the [[Facebook-CA Data Scandal]] broke in March 2018, the major platforms responded with a visible burst of reform — shutting data pipes, building ad-transparency archives, and removing coordinated networks. But the responses were uneven across companies, mostly addressed the *specific* vector Cambridge Analytica exploited rather than the underlying capability, and shifted targeting power inward to the platforms themselves. The honest analytical verdict: platform self-regulation closed one door and quietly kept the building.

## Working outline

1. The immediate post-CA reforms (2018) and what each company chose.
2. Ad-transparency tools as the centerpiece response.
3. Coordinated-inauthentic-behavior takedowns as the disinformation answer.
4. What the responses did not change.

## Key entities

- [[Facebook]] / [[Meta]]
- [[Cambridge Analytica]]
- [[Mark Zuckerberg]]
- [[Twitter]]
- [[Google]]

## Key sources

- [[Source Wikipedia - Facebook-CA scandal]]
- Bipartisan Policy Center, "History of the Cambridge Analytica Controversy"

## Hypotheses being argued

- [[Hypothesis - Federal database supersedes CA model]] — that the capability migrated rather than disappeared.

## Counter-arguments to address

- That the reforms were substantive and the targeting environment is genuinely safer now.

## Draft

The platform response to Cambridge Analytica came in three forms.

**Closing the data pipe.** Facebook's most direct action targeted the exact vector CA exploited — third-party developer access to friend data. It had already deprecated the Graph API v1 friends-data permission in 2014–2015; after 2018 it accelerated the lockdown, requiring app review for most data scopes, and in March 2018 announced it would shut down "Partner Categories," ending the use of third-party data-broker data for ad targeting. This genuinely eliminated the GSR/Kogan pathway.

**Ad-transparency tools.** The signature response was transparency infrastructure. In 2019 Facebook launched its Ad Library, where political and "issue" ads are retained and searchable for seven years; Google built a comparable political-ads archive and reduced microtargeting options for political advertisers; Twitter took the most absolute route and banned political ads outright in 2019. These tools made "dark ads" — ads visible only to their targets — partially visible, addressing a core CA-era complaint.

**Coordinated-inauthentic-behavior takedowns.** For disinformation more broadly, platforms converged on a "coordinated inauthentic behavior" (CIB) enforcement model — periodically removing networks of fake accounts and pages and publishing takedown reports, often in cooperation with outside researchers.

**What the responses did not change.** The reforms shared a common limit: they closed the *specific* CA vector while leaving the underlying capability intact. Individual-level targeting at scale did not end — it moved inside the platforms, into Facebook's own Custom Audiences and Lookalike Audiences tools, which give advertisers comparable precision without third-party data exposure. Psychographic-style audience modeling was largely absorbed into the platforms' own machine learning. Transparency archives made deployment visible but did not stop it, and platforms themselves decide what counts as a political ad. Self-regulation, not law, set the terms — and in the 2020s several platforms rolled back content-moderation and transparency commitments. The capability migrated to a more centralized, less externally auditable form.

## Open questions before publishing

- [ ] Verify current (2025-2026) status of Meta and Google ad-library retention policies.
- [ ] Confirm which platforms have rolled back post-2018 transparency or CIB programs.
- [ ] Get a current figure for political-ad-archive coverage gaps.

## See also

- [[Facebook-CA Data Scandal]]
- [[Cambridge Analytica]]
- [[disinformation]]
- [[Mark Zuckerberg]]
- [[Mueller Report]]
- [[Election Denial Infrastructure]]
