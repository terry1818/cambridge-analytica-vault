---
date: 2026-05-22
description: Use of randomized controlled trials (RCTs) to measure the causal effects of voter contact, persuasion, and mobilization interventions in political campaigns; the methodological foundation of modern evidence-based electoral strategy.
tags:
  - concept
  - topic/data-driven-campaigning
  - topic/microtargeting
  - era/pre-2014
  - era/2014-2016
  - era/2016-2018
  - era/2018-2020
type: concept
aliases: ["Randomized controlled trials in political campaigns"]
domain: Political science / campaign strategy / experimental methods
first-documented: "1924 (Gosnell, Chicago); modern revival 1998 (Gerber and Green, New Haven)"
---

## Definition

Randomized controlled trials (RCTs) in political campaigns are experiments in which voters or precincts are randomly assigned to receive a campaign intervention (a phone call, a door knock, a piece of direct mail, a digital ad) or to a control group that receives nothing. Turnout or vote choice is measured after the election using public voter-roll records or exit surveys. The random assignment ensures that the only systematic difference between treatment and control groups is the intervention itself, enabling clean causal inference rather than correlation.

## Origin / History

The first known use of an RCT in political campaigning was [[Harold Gosnell]]'s 1924 Chicago experiment, in which households were randomly assigned to receive get-out-the-vote mailers. Gosnell's approach was ahead of its time and was not recognized as the founding of a tradition until the 2000s.

The modern revival began with [[Gerber and Green field experiments]] in 1998. Alan Gerber and Donald Green at Yale ran a large-scale randomized canvassing experiment in New Haven that proved face-to-face contact raised turnout substantially. Their 2000 *American Political Science Review* publication triggered a wave of replications and extensions. By the mid-2000s, dozens of academic and practitioner experiments were running each electoral cycle.

[[Source - Issenberg 2012 - The Victory Lab]] is the definitive journalistic account of how this methodology moved from Yale seminar rooms into campaign operations, primarily through the [[Analyst Institute]] on the Democratic side and through the [[Voter Vault and the 2004 72-Hour Task Force]] on the Republican side.

## How It Works

**Standard campaign RCT design**:
1. Obtain a voter file (see [[US voter file architecture]]) for a target jurisdiction
2. Randomly assign voters to treatment(s) and control; document assignments before any contact
3. Execute the intervention — canvassing, phone call, mail, digital ad, etc.
4. After Election Day, merge treatment records with public voter-roll turnout data (or with modeled vote-choice data)
5. Calculate treatment effect: (turnout rate in treatment) minus (turnout rate in control); test for statistical significance

**Key enabling infrastructure**:
- Public voter-roll data listing who voted (not how, in most US states) — enables outcome measurement without surveying respondents
- Party and commercial voter files (see [[US voter file architecture]]) — provide baseline covariates and targeting
- Randomization at the individual or precinct level — depends on scale of operation

**Variations**:
- Cluster-randomized designs (randomize precincts or streets rather than individuals) where contact spillover is a concern
- Factorial designs testing multiple message versions simultaneously
- Dose-response designs varying number of contacts
- Encouragement designs used when forcing contact is impossible

## Application in This Domain

Within the CA/political-data ecosystem documented in this vault, RCTs matter for two distinct reasons:

**Pre-CA genealogy**: The Democratic experimental tradition (Gerber-Green → Analyst Institute → Obama 2008/2012 ground game) demonstrates that data-driven voter contact with rigorous measurement predates Cambridge Analytica's psychographic claims by at least a decade. This undercuts CA's narrative of unique methodological innovation.

**CA's claimed methodology**: [[Cambridge Analytica]] claimed to use experimental testing of psychographic messaging — presenting their work as more sophisticated than prior RCT-based approaches because they targeted psychological profiles rather than demographic or behavioral segments. Independent assessments found little evidence that CA's psychographic targeting outperformed conventional approaches. The Gerber-Green literature provides the benchmark against which CA's claims should be evaluated.

**Post-CA landscape**: The federal voter-file database infrastructure [[DOGE]] and [[Palantir Technologies]] are assembling as of 2025–2026 would, if it includes turnout records, enable large-scale behavioral experiments of a kind far beyond what campaign-season RCTs produce.

## Examples

- **Gerber, Green, Larimer (2008)** — Social-pressure mailing showing neighbors' turnout records; ~8pp effect, the largest measured in GOTV literature
- **Analyst Institute meta-analysis** — Aggregated results from hundreds of member-organization experiments establishing that volunteer canvassing outperforms paid canvassing, which outperforms phone banking
- **Obama 2012 Analytics Team** — Ran hundreds of internal RCTs on digital ads, email subject lines, and fundraising appeals — documented by Issenberg and subsequent journalism
- **GOP 72-Hour Task Force (2001–2004)** — RNC poured $1M+ into field experiments to test GOTV methods; results fed into [[TargetPoint Consulting]] segmentation

## Effectiveness / Critique

**Methodological strengths**: RCTs in political campaigns are among the most rigorous social-science designs possible because the outcome (did the voter turn out?) is measured from public records rather than self-report.

**Limitations and critiques**:
- Most published experiments measure turnout, not persuasion (vote choice), because secret-ballot laws prevent individual-level vote-choice measurement
- Effect sizes are often small (1–3pp for most mail and phone interventions) — meaningful in close elections but modest in absolute terms
- Many practitioner experiments are never published, limiting cumulative scientific knowledge
- "Experimenter demand effects" — campaigns sometimes design tests to confirm preferred tactics rather than to learn genuinely
- Ethical concerns about using voter's social-graph data (e.g., publicizing neighbors' records) without consent

## Related Concepts

- [[Gerber and Green field experiments]] — foundational program
- [[Harold Gosnell]] — historical origin
- [[Analyst Institute]] — institutional clearinghouse
- [[microtargeting]] — downstream application
- [[US voter file architecture]] — enabling infrastructure
- [[Cambridge Analytica]] — claimed to use psychographic RCT-style testing; evidence disputed

## Sources

- [[Source - Issenberg 2012 - The Victory Lab]] — Tier-2: primary secondary narrative
- Gerber, A.S. and Green, D.P. (2000). APSR 94(3): https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1313713 — Tier-1
- Gerber, A.S. and Green, D.P. (2012). *Field Experiments*. W.W. Norton. — Tier-1
- EGAP Brief 22: https://egap.org/resource/brief-22-getting-out-the-vote/ — Tier-2
- Oxford Bibliographies, "Voter Turnout Field Experiments": https://www.oxfordbibliographies.com/view/document/obo-9780199756223/obo-9780199756223-0243.xml — Tier-2

## See Also

- [[Gerber and Green field experiments]]
- [[Harold Gosnell]]
- [[Analyst Institute]]
- [[US voter file architecture]]
- [[microtargeting]]
- [[TargetPoint Consulting]]
- [[Voter Vault and the 2004 72-Hour Task Force]]
- [[Cambridge Analytica]]
- [[Source - Issenberg 2012 - The Victory Lab]]
