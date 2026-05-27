---
date: 2026-05-22
description: Statistical algorithms that estimate individual teachers' contributions to student test-score gains, used in high-stakes evaluation and dismissal decisions in US school districts; documented by O'Neil as a paradigmatic weapon of math destruction.
tags:
  - concept
  - topic/algorithmic-governance
  - topic/education
type: concept
domain: Education policy / algorithmic decision systems
first-documented: Academic VAM literature from the 1980s; high-stakes use in DC (IMPACT) and New York (2008–2013); O'Neil, C. (2016). *Weapons of Math Destruction*.
---

## Definition

Teacher value-added models (VAMs) are statistical methods that attempt to isolate an individual teacher's contribution to student academic growth, measured through standardized test-score gains, by controlling for student background, prior performance, school-level effects, and other variables. VAMs were adopted as a core component of teacher evaluation systems in the 2000s and 2010s under the pressure of federal initiatives (No Child Left Behind, Race to the Top). When used in high-stakes contexts — employment, compensation, public ranking — they are among [[Cathy O'Neil]]'s primary examples of [[Weapons of math destruction]].

## Origin / history

VAMs originated in agricultural statistics (R.A. Fisher) and were adapted for education by economist William Sanders in the 1980s (Tennessee Value-Added Assessment System). Federal policy promoted high-stakes VAM use through the No Child Left Behind Act (2001) and, more forcefully, Race to the Top (2009), which required states to link teacher evaluation to student outcomes as a condition of grant funding. By 2012, dozens of major urban school districts — including Washington DC, New York City, Los Angeles, and Houston — used VAMs as components of formal teacher evaluation systems that could result in dismissal.

O'Neil analyzed VAMs in *Weapons of Math Destruction* as exhibiting all three WMD characteristics: opacity (models are proprietary or technically inaccessible to teachers), scale (affecting hundreds of thousands of teachers nationally), and damage (teachers dismissed on the basis of scores that have documented year-to-year instability).

## How it works

1. Student test scores from one year to the next are measured.
2. A statistical model attempts to control for factors outside the teacher's control — prior student performance, socioeconomic status, school-wide effects, class composition.
3. The residual gain (actual gain minus predicted gain) is attributed to the teacher as their "value-added."
4. Teachers are ranked and assigned scores; those below a threshold may be dismissed, denied tenure, or denied pay increases.
5. In some districts (e.g., New York City 2012), VAM rankings were published in newspapers, generating public reputational damage.

## Application in this domain

VAMs illustrate the central WMD mechanism: algorithmic outputs that appear objective (numerical scores from complex models) are used to make high-stakes personnel decisions, while the opacity of the models makes challenge nearly impossible. The same structural pattern applies to algorithmic hiring systems, credit-scoring models, and risk-assessment tools in criminal justice.

O'Neil highlighted the specific case of Washington DC's IMPACT system — introduced by Chancellor Michelle Rhee — which weighted 50% of teacher evaluations on VAM scores. In New York City, a similar system generated extreme year-to-year score volatility (the same teacher could rank in the 6th percentile one year and the 96th the next), which the American Educational Research Association and American Statistical Association noted made the scores statistically unreliable for individual evaluation purposes.

## Examples

- Washington DC IMPACT (2009): 50% of teacher evaluation weighted on VAM; teachers dismissed on basis of scores; system later reduced VAM weighting to 35% following teacher feedback.
- New York City (2010–2013): VAM scores published in newspapers; teachers documented with year-to-year score swings of 90+ percentile points; system abandoned 2013.
- Houston (2011): Teachers filed legal challenges to VAM-based dismissals; courts generally deferred to school district discretion.

## Effectiveness / critique

**AERA and ASA position** (Tier 1): Both major professional associations in education research and statistics released statements warning against using VAM scores as a primary factor in high-stakes individual teacher decisions, citing documented instability and measurement error.

**Proponent position**: Advocates argued that VAMs, however imperfect, were better than the prior system (near-universal satisfactory ratings regardless of teacher performance).

**O'Neil's critique**: The year-to-year instability is a WMD signature — the model does not actually measure what it claims to measure, but because it generates numbers it acquires authority it does not deserve.

## Related concepts

- [[Weapons of math destruction]]
- [[COMPAS]]
- [[Allegheny Family Screening Tool]]
- [[Digital poorhouse]]

## Sources

- [[Source - O'Neil 2016 - Weapons of Math Destruction]] — primary source; evidence tier: Tier 1
- AERA Statement on VAMs (2015): https://journals.sagepub.com/doi/10.3102/0013189X15618385
- EdWeek: https://www.edweek.org/education/opinion-disagreeing-about-the-use-of-value-added-measures/2014/04
- The Century Foundation (DC IMPACT): https://tcf.org/content/commentary/the-unfair-effects-of-impact-on-teachers-with-the-toughest-jobs/
- RAND VAM evaluation: https://www.rand.org/content/dam/rand/pubs/monographs/2004/RAND_MG158.pdf

## See also

- [[Weapons of math destruction]]
- [[Cathy O'Neil]]
- [[COMPAS]]
- [[Allegheny Family Screening Tool]]
- [[Digital poorhouse]]
