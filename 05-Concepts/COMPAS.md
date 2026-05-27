---
date: 2026-05-22
description: Commercial criminal risk-assessment algorithm used in pre-trial, sentencing, and parole decisions across the US; documented by ProPublica (2016) to produce racially disparate false-positive rates despite equal overall accuracy claims.
tags:
  - concept
  - topic/algorithmic-governance
  - topic/criminal-justice
  - topic/predictive-policing
type: concept
domain: Criminal justice / algorithmic decision systems
first-documented: Northpointe, Inc. (developer, c.2000s); O'Neil, C. (2016). *Weapons of Math Destruction*; ProPublica (2016) investigation.
---

## Definition

COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) is a proprietary risk-assessment algorithm developed by Northpointe, Inc. (later Equivant) and sold to courts, probation departments, and corrections agencies across the United States. The system generates risk scores — typically on a 1–10 scale — estimating an individual's likelihood of recidivating, either generally or violently, within a specified period. These scores are used at pre-trial bail hearings, in sentencing, and in parole decisions, in some jurisdictions carrying significant weight in judicial determinations.

## Origin / history

COMPAS was developed by Northpointe, Inc. (later renamed Equivant) in the early 2000s. It became widely adopted as part of the "evidence-based" criminal justice reform movement, which sought to reduce incarceration through structured, ostensibly objective risk classification. By the mid-2010s it was in use in jurisdictions including Florida, Wisconsin, New York, and elsewhere. [[Cathy O'Neil]] analyzed COMPAS as a case study in *Weapons of Math Destruction* (2016), arguing it exemplified the WMD pattern: opaque (proprietary model not subject to public scrutiny), large-scale, and damaging. ProPublica's landmark "Machine Bias" investigation (May 2016) provided the most cited empirical critique.

## How it works

1. Defendants complete a questionnaire covering criminal history, demographic factors, and self-reported attitudes, social networks, and substance use.
2. Responses are weighted according to a proprietary formula to generate numerical risk scores in categories including General Recidivism, Violent Recidivism, and Pre-trial Failure.
3. Scores are presented to judges, parole boards, or probation officers as risk indicators.
4. In most jurisdictions, COMPAS scores are advisory, not binding — but empirical research suggests they carry significant practical weight in judicial decision-making.
5. Individuals subject to COMPAS scores typically have no right to see the formula or challenge its output.

## Application in this domain

COMPAS is the central case study for [[Cathy O'Neil]]'s [[Weapons of math destruction]] framework and a key example in the broader literature on algorithmic governance. For the vault's research purposes, COMPAS represents the prototype of how algorithmic tools acquire legitimacy through claims of scientific objectivity while encoding and amplifying racial inequities, and how opacity makes accountability impossible. The structural parallel to political microtargeting algorithms and immigration risk-assessment systems is direct.

## Examples

- ProPublica (2016): Analyzed 10,000+ defendants in Broward County, Florida. Found Black defendants were 77% more likely than white defendants to be scored higher risk for violent crime without reoffending; white defendants were more likely to be scored low risk but subsequently reoffend.
- Northpointe's defense: The algorithm was equally accurate for Black and white defendants (~60% accuracy). The mathematical incompatibility between equal accuracy and equal false-positive rates was demonstrated by subsequent researchers (Chouldechova 2017).
- Wisconsin Supreme Court (*State v. Loomis*, 2016): Ruled COMPAS scores could be used in sentencing but warned they could not be the determinative factor; defendant's challenge to the proprietary opacity of the formula was rejected.

## Effectiveness / critique

**ProPublica findings** (Tier 2 evidence — investigative journalism with disclosed methodology): COMPAS produced racially disparate false-positive rates (high risk, did not reoffend) at the expense of Black defendants and racially disparate false-negative rates (low risk, did reoffend) at the expense of white defendants.

**Northpointe/Equivant response**: The algorithm is equally accurate across racial groups; the ProPublica analysis conflated accuracy with fairness.

**Academic resolution**: Multiple researchers (Chouldechova 2017; Kleinberg et al. 2016) demonstrated mathematically that equal predictive accuracy across groups is generally incompatible with equal false-positive rates when base rates differ — meaning the controversy reflects an irresolvable structural tension in the definition of algorithmic fairness, not a methodological error by either ProPublica or Northpointe.

## Related concepts

- [[Weapons of math destruction]]
- [[Allegheny Family Screening Tool]]
- [[Digital poorhouse]]
- [[Teacher value-added models]]
- [[Third-party doctrine]]

## Sources

- [[Source - O'Neil 2016 - Weapons of Math Destruction]] — primary source; evidence tier: Tier 1
- ProPublica "Machine Bias" (May 2016): https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
- ProPublica methodology: https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm
- ProPublica mathematical inevitability: https://www.propublica.org/article/bias-in-criminal-risk-scores-is-mathematically-inevitable-researchers-say
- UCLA Law Review: https://www.uclalawreview.org/injustice-ex-machina-predictive-algorithms-in-criminal-sentencing/

## See also

- [[Weapons of math destruction]]
- [[Cathy O'Neil]]
- [[Allegheny Family Screening Tool]]
- [[Digital poorhouse]]
- [[Teacher value-added models]]
- [[Third-party doctrine]]
