---
date: 2026-05-16
description: $30M Palantir ICE surveillance platform for deportation targeting and self-deportation tracking
tags: [concept, topic/surveillance, topic/deportation, era/2024-2026]
type: concept
domain: tech
first-documented: 2025-04
---

# ImmigrationOS

## Definition

**ImmigrationOS** is a surveillance and deportation-targeting platform built by [[Palantir Technologies]] for **Immigration and Customs Enforcement (ICE)** under a **$30M modification to an existing ICE-Palantir contract**, awarded approximately April 2025. Prototype due September 2025. Operates as a product on top of the broader [[Federated Master Database]] enabled by [[Trump EO Eliminating Information Silos 2025-03-20]].

## Stated functions (per ICE / Palantir contract documents)

1. **Streamline identification and apprehension** of individuals prioritized for removal (defined by ICE as "violent criminals," gang members, visa overstays)
2. **Track and report self-deportations** with "near real-time visibility"
3. **Make deportation logistics more efficient** through improved identification and removal workflows

## Authorizing executive orders

- **EO 14159** ("Protecting the American People Against Invasion") -- Trump 2.0
- **EO 13773** (Transnational criminal organizations) -- originally Trump 1.0

## Data sources it pulls from

- ICE / DHS internal databases (TECS, EAGLE, EARM, etc.)
- **External federal data:** passport records, SSA files, IRS tax data
- **Surveillance feeds:** automated license plate reader (ALPR) data -- including [[Flock Safety]] "side door" lookups and CBP pilot data

## Related Palantir products

- **ELITE** (Enhanced Leads Identification & Targeting for Enforcement) -- companion tool that maps deportation targets, generates dossiers, scores addresses using HHS data
- **Foundry** -- underlying Palantir commercial platform
- **Gotham** -- Palantir intel/defense platform

## Critique / civil-liberties concerns

- **Accuracy of underlying databases** -- Palantir pulls from sources regardless of veracity; license-plate data has known false positives; HHS data can be stale
- **Mission creep** -- designed for criminal/gang targets, used at scale for non-criminal civil immigration cases
- **Privacy Act violations** -- cross-agency data sharing without notice/consent (12+ lawsuits)
- **Targeting children** -- via [[Flock Safety]] school-camera integration

## Sources

- [[Source ACLU Palantir Deportation]]
- [[Source American Immigration Council ImmigrationOS]]
- [[Source Immigration Policy Tracking Palantir ICE]]