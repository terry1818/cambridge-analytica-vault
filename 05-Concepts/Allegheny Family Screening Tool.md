---
date: 2026-05-22
description: Predictive risk-scoring algorithm deployed by Allegheny County (Pennsylvania) since 2016 to assist child-welfare call screeners in assessing maltreatment referrals; documented by Eubanks as a case study in the digital poorhouse.
tags:
  - concept
  - topic/algorithmic-governance
  - topic/child-welfare
  - topic/predictive-risk
type: concept
domain: Child welfare / algorithmic governance
first-documented: Allegheny County DHS launch, August 2016; Eubanks, V. (2018). *Automating Inequality*.
---

## Definition

The Allegheny Family Screening Tool (AFST) is a machine-learning predictive risk model deployed by the Allegheny County (Pennsylvania) Department of Human Services (DHS) to assist call-center screeners in evaluating referrals about potential child maltreatment. The model outputs a risk score (1–20) estimating the probability that a child referred for a general protective service investigation will be placed in out-of-home care within two years. The score is presented to screeners alongside a case narrative; screeners are not required to follow the score but cannot investigate a case rated below 14 without supervisory approval, and cannot decline to investigate a case rated 18 or higher.

## Origin / history

Allegheny County DHS issued a request for proposals in 2014 to design a data-driven screening system. The AFST was built by a county analytics team in partnership with academics. It was launched in August 2016. [[Virginia Eubanks]] documented the AFST in *Automating Inequality* (2018) as her second major case study — following the [[Indiana welfare automation]] failure — in her argument that algorithmic systems applied to poverty create a [[Digital poorhouse]]. Eubanks focused on the AFST's potential for encoding and amplifying existing racial and economic biases embedded in historical child-welfare records.

## How it works

1. A call is received at the Allegheny County child-welfare hotline alleging maltreatment.
2. The screener enters information about the referral into the system.
3. The AFST queries the county's integrated data warehouse — drawing on child welfare history, criminal justice records, behavioral health treatment records, public assistance history, and other administrative data for the child, caretakers, and alleged perpetrators.
4. The model outputs a risk score (1–20).
5. Screeners see the score alongside other case information and make an investigation decision.
6. Screeners rated 14+ must actively justify a non-investigation; screeners rated 18+ cannot decline.

## Application in this domain

The AFST illustrates a key mechanism of the [[Digital poorhouse]]: the algorithm is trained on historical data from families who interacted with Allegheny County's public services — but these interactions are themselves a function of poverty and race (wealthy families experiencing equivalent home conditions are far less likely to come to official attention). The model therefore predicts involvement with the child-welfare system partly by detecting poverty and non-white racial composition, without those variables appearing explicitly in the model. Eubanks documented how AFST scores could flag families for investigation based on behaviors that are legal but associated with poverty (using public services, receiving public assistance).

## Examples

- A family receiving behavioral health services for a parent would have that treatment history entered into the data warehouse, potentially elevating an AFST risk score — penalizing help-seeking behavior.
- Families without documented child-welfare history but living in public housing (housing status is a data-warehouse variable) may score higher than equivalent families in private housing.
- A 2024 Allegheny County analytics evaluation found the AFST reduced some racial gaps in investigation rates among high-risk referrals — a finding disputed by critics who argue the definition of "high risk" is itself circular.

## Effectiveness / critique

**Proponents** (Allegheny County, some academics): The AFST improved consistency in screening decisions, reduced subjective bias by individual screeners, and may have reduced racial disparities within the high-risk tier.

**Critics** (Eubanks, Logic Magazine, civil liberties advocates): The model encodes structural racism by treating poverty-correlated behaviors as risk factors; the feedback loop between investigation, removal, and model training means the system reinforces historical patterns; no consent process exists for families whose data is used; the "can't decline 18+" rule effectively removes screener discretion for high-scoring cases.

**Key uncertainty**: The causal direction of the racial-disparity finding is contested. Evidence tier: Tier 2 (peer-reviewed evaluation exists, but methodology dispute is active).

## Related concepts

- [[Digital poorhouse]]
- [[Indiana welfare automation]]
- [[COMPAS]]
- [[Weapons of math destruction]]
- [[Third-party doctrine]]

## Sources

- [[Source - Eubanks 2018 - Automating Inequality]] — primary source; evidence tier: Tier 1
- Allegheny County DHS official page: https://www.alleghenycounty.us/Services/Human-Services-DHS/DHS-News-and-Events/Accomplishments-and-Innovations/Allegheny-Family-Screening-Tool
- 2024 county evaluation: https://alleghenycountyanalytics.us/2024/05/31/predictive-risk-models-in-child-welfare/
- Logic Magazine critique: https://logicmag.io/policy/allegheny-family-screening-tools-overestimation-of-utility-and-risk/
- Medium / Neil Ballantyne analysis: https://medium.com/@neilballantyne/the-harm-that-data-do-the-case-of-the-allegheny-family-screening-tool-5f9fca22e0b2

## See also

- [[Digital poorhouse]]
- [[Virginia Eubanks]]
- [[Indiana welfare automation]]
- [[COMPAS]]
- [[Weapons of math destruction]]
- [[Third-party doctrine]]
