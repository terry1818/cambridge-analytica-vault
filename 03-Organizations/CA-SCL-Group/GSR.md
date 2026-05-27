---
date: 2026-05-16
description: Aleksandr Kogan's data-harvesting firm; harvested 87M Facebook users via "thisisyourdigitallife" app; sold dataset to Cambridge Analytica
tags: [org, org/data-firm, topic/cambridge-analytica, era/2013-2015, jurisdiction/uk]
type: organization
legal_name: Global Science Research Ltd.
aliases: [GSR]
founded: 2014
dissolved: 2015 (operations wound down)
headquarters: Cambridge UK
jurisdiction: UK
parent_org: ""
key_people: [Aleksandr Kogan (founder + sole principal), Joseph Chancellor (collaborator; later Facebook)]
status: dissolved
wikipedia_url: https://en.wikipedia.org/wiki/Cambridge_Analytica
---

# GSR (Global Science Research)

## Summary

**Aleksandr Kogan's data-harvesting company**, founded 2014 in Cambridge, UK. **The operational entity that harvested approximately 87 million Facebook users' data** via the "**thisisyourdigitallife**" personality-quiz app (deployed via Facebook's Graph API v1.0 which allowed friend-network data harvesting from the ~270,000 app installers). **Sold the dataset to [[Cambridge Analytica]]** in 2014, in violation of Facebook ToS. **The single most operationally consequential single dataset in modern political-data history** measured by downstream impact.

**Kogan claimed academic-research framing** for the harvest while structuring GSR as a commercial entity allowing the CA sale. **Facebook's investigation post-2018** found Kogan + GSR had violated Platform Policy. **Both Kogan + [[Alexander Nix]] signed January 2016 certifications** that the GSR data had been destroyed; **NYT viewed surviving samples in March 2018** confirming the certifications were false (load-bearing evidence for [[Hypothesis - CA data survives]]).

## Identity

- **Founded:** 2014
- **HQ:** Cambridge, UK
- **Founder:** [[Aleksandr Kogan]] (Cambridge psychometrics researcher)
- **Collaborator:** Joseph Chancellor (co-author; later joined Facebook 2015)
- **Status:** Dissolved 2015 (operations wound down post-Facebook-investigation)

## The harvest

- **App:** "thisisyourdigitallife" (personality quiz)
- **App installers:** ~270,000 (~$3-4 paid per install via Mechanical Turk + Qualtrics)
- **Friend-network harvest:** ~87 million Facebook users (via Graph API v1.0)
- **Data captured:** demographics, likes, posts, friends, private messages (partial), location, photos
- **Cost:** ~$800K-$1M total

## The sale to Cambridge Analytica

- **2014:** Kogan via GSR sold dataset to [[SCL Group|SCL]] / [[Cambridge Analytica]]
- **Violated Facebook Platform Policy** (academic data could not be commercially sold)
- **Christopher Wylie** acquired the data + transferred to CA from SCL
- **CA paid ~$1M for the dataset** (per [[Christopher Wylie]] disclosures)
- **CA used it for psychographic profiling** of 2014-2018 political clients (Cruz 2016, Trump 2016, Brexit-adjacent operations)

## January 2016 deletion certifications

After Facebook learned of the violation December 2015:
- **Kogan signed deletion certification January 2016**
- **[[Alexander Nix]] signed deletion certification January 2016 for CA**
- **Both certifications proved false** when NYT viewed surviving data samples March 2018

This is **direct documented evidence** that the CA dataset survived deletion certifications - the foundational evidence for [[Hypothesis - CA data survives]].

## Connection to vault entities

- [[Aleksandr Kogan]] - founder
- [[Cambridge Analytica]] - dataset buyer
- [[SCL Group]] - parent of CA
- [[Christopher Wylie]] - transferred data CA-side
- [[Hypothesis - CA data survives]] - GSR data is the load-bearing piece
- [[Facebook Graph API v1]] - harvest mechanism
- [[Lens - Data Flows]]
- [[Federated Master Database]] - the post-CA architecture that supersedes this model

## Sources

- [[Source Wikipedia - Cambridge Analytica]]
- [[Source Cadwalladr 2018-03-17 Guardian]]
- [[Source Rosenberg et al 2018-03-17 NYT]]