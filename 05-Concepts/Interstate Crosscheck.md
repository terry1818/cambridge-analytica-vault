---
date: 2026-05-22
description: Multi-state voter-roll cross-matching program that flagged voters allegedly registered in more than one state; suspended in 2019 after documented racial disparities and a >99% false-positive rate.
tags:
  - concept
  - topic/voter-suppression
  - era/2014-2016
  - era/2016-2018
  - era/2018-2020
  - jurisdiction/us
type: concept
domain: Electoral administration / voter-roll management
first-documented: "2005 (program inception); Carol Anderson 2018 analysis"
---

## Definition

The Interstate Voter Registration Crosscheck Program (commonly "Crosscheck") was a multi-state data-sharing arrangement that aggregated voter registration records to identify voters who appeared to be registered — and potentially to have voted — in more than one state simultaneously. Participating states submitted their full voter-registration files; the program returned a list of names flagged as potential duplicate registrants, which state officials could then use to challenge or remove voters from rolls.

## Origin / history

Crosscheck was developed in 2005 by Kansas Secretary of State Ron Thornburgh in conjunction with Iowa, Missouri, and Nebraska. The program remained small until Kris Kobach became Kansas Secretary of State in 2011 and dramatically expanded it: the participating state count grew from roughly 13 in 2010 to a peak of 29 in 2014. Kobach administered the program from Kansas and it operated without meaningful federal oversight, as a voluntary state-to-state arrangement.

The program's scale made it significant: at its height it was processing voter files covering an estimated 100+ million registrations and returning lists of millions of potential double-registrants for action by state election officials.

## How it works

1. Participating states submit full voter-registration databases to Kansas.
2. The program compares records across state files, matching on **first name, last name, and date of birth**. Social Security Number last-four digits (SSN4) were nominally part of the process but matching proceeded even when SSN4s did not match or were absent.
3. States receive a "Crosscheck list" of flagged names — potential double registrants — and may initiate removal proceedings.
4. No independent verification of actual double voting was required before a state could purge a flagged voter.

## Application in this domain

Crosscheck was deployed by Republican-controlled secretaries of state as a tool to clean voter rolls, framed publicly as anti-fraud enforcement. Critics documented that it functioned as voter suppression because:

- The matching algorithm is primitively weak: common names like "Jose Garcia" or "James Williams" generate massive false matches across states.
- Analytical firm ID Analytics found that matching on first name + last name + date of birth "fails for practically all common American names" when applied at scale.
- One report found that of all flagged voters, **more than 99%** were false positives; fewer than four individuals were ultimately charged with deliberate double registration.

## Examples

- **Georgia**: used Crosscheck-derived lists as part of broader voter-roll management alongside [[Exact match voter verification]].
- **Kansas**: Kobach used Crosscheck lists to challenge registrations; state ultimately suspended under 2019 ACLU settlement.
- **Michigan, North Carolina, Virginia, Florida**: major states that participated at Crosscheck's peak and received flagged lists affecting millions of registrations.

## Effectiveness / critique

**Documented racial disparity**: Analysis of Crosscheck flagged lists showed white voters underrepresented by 8%, while African Americans were overrepresented by 45%, Hispanic voters by 24%, and Asian-American voters by 31%. The built-in bias derives from the limited pool of given names common in non-white communities — a voter named "Jose Garcia" is far more likely to be flagged as a double registrant than "Brett Thompson."

**Investigation**: Investigative journalist Greg Palast documented Crosscheck's racial skew in a major 2016 Rolling Stone investigation, estimating it could have affected the outcome of close 2016 states.

**Shutdown**: In December 2019, a settlement of an ACLU of Kansas lawsuit suspended Crosscheck indefinitely. Prior to suspension, more than a dozen states had withdrawn, citing inaccurate data and privacy-law concerns.

## Related concepts

- [[Exact match voter verification]]
- [[Voter Roll Purge Operations]]
- [[Felon disenfranchisement]]
- [[Shelby County v Holder 2013]] — removal of Section 5 preclearance enabled states to act without DOJ review
- [[Kris Kobach]]

## Sources

- [[Source - Anderson 2018 - One Person No Vote]] — primary source; evidence tier: **published scholarly/journalistic**, well-corroborated
- Wikipedia, "Interstate Voter Registration Crosscheck Program": https://en.wikipedia.org/wiki/Interstate_Voter_Registration_Crosscheck_Program
- Brennan Center for Justice (Kobach anti-voting history): https://www.brennancenter.org/our-work/analysis-opinion/uncovering-kris-kobachs-anti-voting-history
- Greg Palast, Rolling Stone/gregpalast.com archive: https://www.gregpalast.com/tag/interstate-crosscheck/
- Facing South, racial bias report (2016): https://www.facingsouth.org/2016/09/controversial-anti-voter-fraud-program-risks-disenfranchising-voters-through-racial-bias

## See also

- [[Brian Kemp]]
- [[Husted v APRI 2018]]
- [[Voting Rights Act of 1965]]
- [[Counter-majoritarian institutions]]
