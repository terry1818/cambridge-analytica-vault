---
date: 2026-05-16
description: Practical guide for verifying any factual claim about CA, SCL, or related entities
tags: [meta, guide, methodology]
---

# Methodology: Verifying a CA-Related Claim

When evaluating any claim about Cambridge Analytica, SCL Group, their personnel, or successor operations â€” apply this verification hierarchy.

## Step 1 â€” Identify the claim type

- **Factual existence claim** ("CA worked for X")
- **Quantitative claim** ("CA had 5,000 data points on 230M Americans")
- **Causal claim** ("CA decided the 2016 election")
- **Attribution claim** ("Russia/Israel/state X was behind this")
- **Methodological claim** ("CA's psychographics work / don't work")

## Step 2 â€” Find at least one primary source

Best to worst:
1. **Court filing / official government document** (FTC complaint, DCMS report, Senate Intel Vol 5)
2. **Companies House / FEC primary records** (corporate filings)
3. **Whistleblower testimony under oath** (parliamentary or congressional)
4. **Whistleblower public statements** (Wylie/Kaiser memoirs)
5. **Investigative journalism with named sources** (Cadwalladr, NYT)
6. **Investigative journalism with anonymous sources** (early Cadwalladr)
7. **Secondary analysis citing primary sources** (Wikipedia, retrospectives)
8. **CA's own marketing claims** (treat as inherently self-serving)

## Step 3 â€” Check for contradictory sources

For any factual claim, search for explicit contradiction:
- Did CA itself deny or contradict the claim?
- Did the relevant regulator find differently?
- Do other whistleblowers say differently?
- Does academic research contradict the claim?

## Step 4 â€” Apply confidence label

- `#confidence/high` â€” multiple independent primary sources confirm
- `#confidence/medium` â€” one strong primary source, or several secondary, with no significant contradiction
- `#confidence/low` â€” circumstantial, single secondary source, or some contradiction
- `#confidence/speculative` â€” pattern recognition, no direct evidence

## Step 5 â€” Apply claim-status label

- `#claim/verified` â€” fact well-established
- `#claim/disputed` â€” sources actively disagree
- `#claim/unverified` â€” pending verification
- `#claim/debunked` â€” disproven

## Common pitfalls

1. **CA's marketing claims** (e.g., "5,000 data points on 230M Americans") were largely fabricated for client acquisition. Treat all CA self-claims as suspect.
2. **Effectiveness claims** are contested across the field. The most rigorous academic work ([[Eitan Hersh]], [[Brendan Nyhan]]) is skeptical.
3. **Russia attribution** in Brexit is unsettled. The ICO's "no significant breach" is the official UK position; Wylie/Kaiser/Cadwalladr dispute.
4. **Causal claims about election outcomes** are unprovable. CA's contribution to Trump's win, or Brexit's outcome, cannot be empirically isolated.
5. **Numeric scale claims** vary by source. 50M / 87M Facebook profiles is the documented range.

## Worked example

**Claim:** "Cambridge Analytica decided the 2016 US election."

- Type: causal claim
- Primary sources: NONE (no source can prove this causally)
- CA's marketing: yes (Tayler quote on electoral college)
- Trump campaign: denies (Parscale, Kushner)
- NYT March 2017 (Confessore-Hakim): CA executives conceded psychographics not actually used in Trump
- Academic skepticism: strong (Hersh, Nyhan)
- **Verdict:** `#claim/disputed` with `#confidence/low` for the strong causal version; `#claim/verified` for the weaker "CA was a paid contractor whose contribution is unprovable"

## Use this in the vault

Any new claim added to a note should pass through these steps. The confidence and claim-status tags are the vault's way of recording the result.

## Methodology in vault use

The Verifying a CA Claim methodology is the explicit workflow that the vault uses to move a journalistic claim from Tier-3 (reporting) to Tier-2 (corroborated testimony) to Tier-1 (primary record). It cross-references the [[Evidence Tiers]] note (which defines the tiers), the [[Categorization Architecture]] (which routes claims into the right entity, event, or hypothesis node), the [[Open Questions]] backlog (where unverified claims are staged), and the [[Hypotheses MOC]] (where verified claims with explicit falsification conditions live).

It is also referenced by [[Source Bibliography MOC]] (which catalogues the primary sources the methodology walks toward) and by the individual hypothesis notes (which document specific verification chains for specific claims).

## See also

- [[Evidence Tiers]]
- [[Categorization Architecture]]
- [[Open Questions]]
- [[Hypotheses MOC]]
- [[Source Bibliography MOC]]
- [[Vault MOC]]