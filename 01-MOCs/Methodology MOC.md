---
date: 2026-05-17
description: Index of the vault's research-methodology documents — verification workflow, evidence tiers, categorization architecture, conventions
tags: [moc, methodology, meta]
type: moc
---

# Methodology MOC

The vault's **research-methodology** documentation — how claims are verified, how evidence is graded, how content is routed into nodes, and what naming / linking conventions apply. Distinct from [[Methods MOC]] which catalogues **operational methods** used by influence operations.

## Core methodology documents

- [[Methodology - Verifying a CA claim]] — the explicit workflow for grading and verifying a claim
- [[Evidence Tiers]] — Tier-1 / Tier-2 / Tier-3 evidence-quality framework
- [[Categorization Architecture]] — how to route a claim into the right entity / event / concept / connection / hypothesis node
- [[Conventions]] — naming, linking, citation, confidence-label rules
- [[Tag Taxonomy]] — multi-axis tag schema (11 axes)

## Companion organizational MOCs

- [[Source Bibliography MOC]] — the catalogue of all source notes (Tier-1, 2, 3 mix)
- [[Open Questions]] — research backlog for un-verified claims
- [[Vault MOC]] — top-level navigation

## How these fit together

A new research item enters the vault via this flow:

1. **Capture** — what is the claim, fact, or document?
2. **Tier** — use [[Evidence Tiers]] to grade the source quality (Tier 1 / 2 / 3)
3. **Categorize** — use [[Categorization Architecture]] to identify which node type owns this content (entity / event / concept / connection / hypothesis)
4. **Cite** — link to the relevant [[Source Bibliography MOC|source note]]
5. **Verify** — if the claim is contested, walk [[Methodology - Verifying a CA claim]] to determine confidence
6. **Tag** — apply axis tags per [[Tag Taxonomy]] and confidence labels per [[Conventions]]
7. **Surface** — if research-incomplete, log in [[Open Questions]]

## Methodology in active use

The vault is not just an archive — it is a **methodology being used**. The eight hypotheses in `08-Hypotheses/` are all structured around the workflow above. Each hypothesis cites sources at their tier; uses categorized entity / event / connection wikilinks; applies confidence labels with explicit falsification criteria.

When the methodology breaks down — when an unverified claim drifts into hypothesis territory without being tiered, when a tertiary synthesis is cited as primary, when a concept is conflated with an entity — that's a methodology failure that surfaces in [[Open Questions]] for correction.

## Related

- [[Methods MOC]] — operational methods (microtargeting, persona management, etc.) — distinct from methodology
- [[Investigations MOC]] — formal investigations into CA-era operations
- [[Vault MOC]] — top-level navigation
