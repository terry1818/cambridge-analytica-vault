---
date: 2026-05-22
description: Former hedge-fund quant catalogues opaque, unaccountable, and scalable algorithms across criminal justice, education, hiring, insurance, and credit — arguing they systematically amplify inequality and undermine democracy.
tags: [source, book, algorithmic-harm, big-data, inequality]
type: source
tier: Tier-2
aliases: ["Source: O'Neil 2016", "Source: O'Neil 2016 - Weapons of Math Destruction"]
---

# Source — Weapons of Math Destruction: How Big Data Increases Inequality and Threatens Democracy (Cathy O'Neil, 2016)

## Bibliographic
- **Author:** Cathy O'Neil (mathematician; formerly D.E. Shaw hedge fund quant; data scientist)
- **Publisher:** Crown/Random House, 2016
- **ISBN:** 9780553418811
- **Context:** Written while O'Neil was running the blog mathbabe.org and after she left the finance industry; informed by her experience building models at D.E. Shaw

## Thesis & scope
O'Neil defines a "Weapon of Math Destruction" (WMD) by three criteria: opacity (the scored person cannot see or contest the model), scale (the model operates on millions simultaneously, compounding any bias), and damage (consequential outcomes in housing, employment, credit, liberty, education). The book argues that algorithmic models masquerade as objective while encoding and amplifying the biases of their training data and designers. Unlike fair human judgment, WMDs cannot be appealed, are rarely audited, and improve the lives of those who already score well while degrading the prospects of those who score poorly. The combined effect is not random inequality — it is systematic downward pressure on the already disadvantaged, creating feedback loops that reproduce themselves.

## Key content relevant to the vault

**COMPAS recidivism algorithm.** Used by courts in multiple US states to score defendants' recidivism risk. O'Neil documents (pre-dating and anticipating ProPublica's 2016 COMPAS investigation) that proxy variables — zip code, family criminal history, employment history — stand in for race in a formally race-neutral model, producing discriminatory outcomes. The scored person typically cannot see the model's logic or contest a score.

**LSI-R (Level of Service Inventory-Revised).** A 54-question offender assessment instrument used in pretrial and sentencing decisions. O'Neil shows that it asks questions whose answers correlate strongly with class and race (prior contact with police, educational attainment, employment history) while framing its outputs as individual risk assessments.

**Teacher Value-Added Models (VAMs).** O'Neil covers New York City's Teacher Data Reports, introduced under Bloomberg, which used a value-added statistical model to assess teacher performance. She documents the case of teacher Sarah Wysocki, rated an "excellent" teacher by principal observation and fired after a VAM score — a score she could not review or challenge. The case illustrates the damage caused when opaque models are given authority over transparent human judgment.

**US News & World Report college rankings.** O'Neil argues this is a paradigmatic WMD because it defines what it claims to measure: schools optimise for the ranking criteria (acceptance rate, alumni giving, SAT scores) rather than underlying educational quality, distorting resource allocation and student choices across the entire higher education market.

**Credit scoring and insurance pricing.** Auto-insurance algorithms use FICO scores and zip codes as proxies for risk, encoding economic disadvantage into premium pricing regardless of actual driving behaviour. This creates a compounding feedback loop: poverty increases insurance cost, which constrains mobility, which limits employment options, which deepens poverty.

**Hiring algorithms.** O'Neil covers personality screening tests and automated resume-rejection tools that consistently disadvantage neurodivergent, immigrant, and working-class applicants. Employers using these systems have no visibility into rejection rates by demographic group.

**The feedback loop as central mechanism.** Across all domains, O'Neil identifies the same structure: data from a biased world is used to train a model, the model's outputs create downstream conditions that feed into future training data, and the cycle tightens. This is the algorithmic analog to the CA psychographic targeting loop — garbage-in-garbage-out at civilisational scale.

## How it maps to the vault
O'Neil's WMD framework provides a theoretical vocabulary for what the vault covers empirically. [[Cambridge Analytica]]'s OCEAN/psychographic model meets WMD criteria (opaque to targets, scalable across millions of voters, consequential). The vault's [[Palantir Gotham]] coverage in law enforcement context maps to WMD criminal-justice examples. The vault's [[Embedding-based Audience Modeling]] and [[Psychographic Targeting]] concepts are downstream of the same algorithmic-bias dynamics O'Neil analyses. O'Neil is also relevant to the [[DOGE]] thread: DOGE's mass-data integration project has the structural features of a WMD — opaque, unaccountable, scalable.

## GAPS — what this book raises that the vault appears to miss

1. **Cathy O'Neil** — no person node in vault. [verified-absent] Vault thread: investigators / academics
2. **COMPAS algorithm** — the specific recidivism-scoring tool used in Florida and other states, its racial disparity (documented by ProPublica in 2016), and its role in sentencing — no vault concept or event node. [verified-absent] Vault thread: algorithmic harm / criminal justice
3. **LSI-R (Level of Service Inventory-Revised)** — the 54-question offender instrument; structurally similar to psychographic profiling tools but in criminal justice — no vault node. [verified-absent] Vault thread: algorithmic harm
4. **Teacher Value-Added Models / NYC Teacher Data Reports** — the Bloomberg-era NYC programme, the Sarah Wysocki case, and the broader use of VAMs in teacher evaluation — not in vault. [verified-absent] Vault thread: education / algorithmic governance
5. **US News college rankings as algorithmic harm** — O'Neil's specific named WMD case for how a ranking system distorts the thing it measures — no vault concept node. [verified-absent] Vault thread: information manipulation / algorithmic harm
6. **"Weapons of Math Destruction" as a named analytical framework** — the three-criteria definition (opaque, scalable, damaging) is a useful classification tool for vault entities that are not yet explicitly characterised this way — no vault concept node for the framework itself. [verified-absent] Vault thread: concepts / methodology
7. **D.E. Shaw & Co.** — the hedge fund at which O'Neil worked before writing the book; a significant player in quantitative finance whose modelling culture she critiques from the inside — not in vault. [verified-absent] (Low priority — background)

## Evidence tier
**Tier-2.** Accessible trade book with strong empirical grounding; all named algorithms are independently documented. The COMPAS analysis predates but aligns with ProPublica's peer-reviewed 2016 investigation. The NYC teacher VAM case is a matter of public record. O'Neil's interpretive claims (models "weaponise" data, feedback loops are structural) are sociological argument, clearly labelled. Some chapters are more illustrative than systematic; should not be cited for specific quantitative claims without independent verification.

## Related
- [[Cambridge Analytica]], [[Psychographic Targeting]], [[OCEAN Model]]
- [[Palantir Gotham]], [[DOGE]], [[ImmigrationOS]]
- [[Source - Eubanks 2018 - Automating Inequality]] (parallel: algorithmic harm to poor)
- [[Source - Brayne 2020 - Predict and Surveil]] (parallel: feedback loops in policing)
- [[Source - Zuboff 2019 - Age of Surveillance Capitalism]]
