---
date: 2026-05-23
description: The classification of individuals by personality traits, values, attitudes and lifestyle rather than by demographics — the analytic foundation Cambridge Analytica used to claim it could profile and target voters by psychological type.
tags:
  - concept
  - topic/psychographics
  - topic/cambridge-analytica
  - topic/data-broker
  - era/pre-2014
  - era/2014-2016
  - era/2016-2018
  - jurisdiction/us
  - jurisdiction/uk
type: concept
domain: psychology / market research / political-strategy
first-documented: "1960s–1970s (consumer market research); 2012–2016 (digital-footprint form popularized by Kosinski/Stillwell and Cambridge Analytica)"
aliases:
  - Psychographic profiling
  - Psychographic segmentation
---

# Psychographics

## Definition

Psychographics is the practice of describing and grouping people by *psychological* attributes — personality traits, values, attitudes, interests, opinions and lifestyle — rather than by *demographic* attributes such as age, income, race, or postcode. Where demographics answer "who is this person on paper," psychographics claims to answer "what kind of person are they, and what moves them." In its modern, data-driven form it pairs personality psychology with large behavioral datasets to assign individuals scores on standardized trait dimensions, most commonly the [[Big Five personality model]] (the OCEAN model: Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism).

## Origin / history

Psychographics emerged in commercial market research in the 1960s and 1970s as advertisers sought segmentation richer than census categories. Frameworks such as SRI International's VALS ("Values, Attitudes and Lifestyles," 1978) sorted consumers into lifestyle types for product marketing. For decades psychographic data had to be gathered through surveys — expensive, slow, and small-sample.

The transformative shift came from academic work at the University of Cambridge Psychometrics Centre. Michal Kosinski, David Stillwell and Thore Graepel showed (notably in a 2013 PNAS paper) that Facebook "Likes" alone could predict sensitive personal traits — sexual orientation, political views, intelligence, and Big Five personality scores — with significant accuracy. This established that psychographic profiles could be inferred at scale from digital footprints, without asking the subject anything. That insight is the technical premise on which [[Cambridge Analytica]] built its commercial pitch.

## How it works

In the survey-based tradition, respondents answer validated personality questionnaires; statistical clustering then sorts them into types. In the digital-footprint tradition, a model is trained on a "seed" population for whom both personality scores (from a quiz) and behavioral data (Likes, posts, app usage, purchases) are known. The model learns correlations between behavior and traits, and is then applied to a much larger population for whom only behavioral data exists — producing inferred trait scores for people who never took any test. Cambridge Analytica's pipeline did exactly this: [[Aleksandr Kogan]]'s "This Is Your Digital Life" quiz produced the seed personality data; harvested Facebook profiles supplied the behavioral data; the model projected OCEAN scores onto tens of millions of [[Facebook-CA Data Scandal|harvested profiles]].

## Application in this domain

In the political sphere, psychographics is the predicate for [[psychographic microtargeting]]: once voters carry inferred personality scores, campaigns can craft message variants tuned to each psychological type — fear-framed messaging for high-Neuroticism voters, tradition-and-order framing for high-Conscientiousness voters, and so on. [[Cambridge Analytica]] and its parent [[SCL Group]] marketed this as their core differentiator to the [[Ted Cruz]] and [[Donald Trump]] campaigns. After CA's 2018 collapse the *technique* did not disappear: psychographic-style audience modeling has been absorbed into platform ad systems and into commercial data-broker products, which is central to this vault's argument about institutional continuity.

## Examples

- [[Cambridge Analytica]] — built its entire brand on psychographic voter profiling
- [[Facebook-CA Data Scandal]] — the harvested data was the raw material for psychographic models
- [[psychographic microtargeting]] — the operational use of psychographic profiles
- VALS / SRI International — the pre-digital commercial precursor

## Effectiveness / critique

- **Claimed effectiveness:** CA and SCL claimed psychographics gave them a decisive, near-magical persuasive edge over conventional targeting.
- **Empirical evidence:** The Kosinski/Stillwell finding that traits are *predictable* from digital data is well-supported and replicated. Whether psychographically *targeted* messaging actually changes votes is far weaker. `#claim/disputed`
- **Academic critique:** Political scientists including Eitan Hersh and David Karpf, and reporting by *The New York Times* (March 2017), found CA's psychographic claims oversold; CA executives themselves reportedly conceded psychographics was not actually used in the Trump general-election effort. Predicting a personality trait is not the same as reliably moving behavior. The vault treats psychographics' predictive validity as documented and its persuasive efficacy as contested.

## Related concepts

- [[psychographic microtargeting]]
- [[Big Five personality model]]
- [[surveillance capitalism]]
- [[data brokers]]
- [[behavioral surplus]]

## Sources

- [[Source - Tau 2024 - Means of Control]] — Tier-2 (corroborated; situates psychographic modeling within the commercial-data pipeline)
- Kosinski, Stillwell & Graepel, "Private traits and attributes are predictable from digital records of human behavior," PNAS (2013): https://www.pnas.org/doi/10.1073/pnas.1218772110 — Tier-1 (peer-reviewed)
- The Conversation, "Psychographics: the behavioural analysis that helped Cambridge Analytica know voters' minds": https://theconversation.com/psychographics-the-behavioural-analysis-that-helped-cambridge-analytica-know-voters-minds-93675 — Tier-2
- NBC News, "Cambridge Analytica's effectiveness called into question": https://www.nbcnews.com/politics/politics-news/cambridge-analytica-s-effectiveness-called-question-despite-alleged-facebook-data-n858256 — Tier-2

## See also

- [[psychographic microtargeting]]
- [[Cambridge Analytica]]
- [[SCL Group]]
- [[Facebook-CA Data Scandal]]
- [[Aleksandr Kogan]]
- [[surveillance capitalism]]
- [[data brokers]]
- [[Hypothesis - Federal database supersedes CA model]]
