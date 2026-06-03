---
date: 2026-05-16
description: 'Palantir ICE-deployment tool; "Enhanced Leads Identification and Targeting for Enforcement"; companion to ImmigrationOS; maps deportation targets via cross-agency data'
tags: [concept, topic/surveillance, topic/palantir, topic/ice, era/2025-2026]
type: concept
domain: tech
first-documented: 2025
---

# ELITE (Enhanced Leads Identification and Targeting for Enforcement)

## Definition

**Enhanced Leads Identification and Targeting for Enforcement (ELITE)** is a **[[Palantir Technologies]] tool deployed for [[ICE]]** alongside **[[ImmigrationOS]]**. ELITE specifically focuses on **target generation + dossier compilation + address-confidence scoring** for ICE deportation operations.

**Operational function:**
1. Pulls data from [[Federated Master Database]] (federal cross-agency integrated layer)
2. Identifies individuals matching ICE-defined removal-priority criteria
3. Generates individual dossiers with documented histories
4. Scores address-confidence (likelihood the individual is at a given address)
5. Provides target lists to ICE field operations

**Heavy reliance on HHS data** (medical, social-services records) is the most controversial element -- using government-provided assistance records to target individuals for deportation enforcement is operationally significant because it **chills access to public services for vulnerable populations**.

## Relationship to ImmigrationOS

- **ImmigrationOS** = broader Palantir-ICE platform (~$30M contract April 2025)
- **ELITE** = specific target-generation tool within / alongside ImmigrationOS
- Together provide end-to-end immigrant-targeting workflow

## Documented data sources

- ICE / DHS internal databases (TECS, EAGLE, EARM)
- IRS tax data
- SSA records
- **HHS data** (Medicaid, Medicare, ACA, refugee health programs) -- controversial
- Passport / visa records
- Automated license plate reader feeds (Flock Safety "side door")
- DOL employment records

## Why ELITE matters

ELITE represents the **operational integration of the [[Federated Master Database]]** with **immigration-enforcement targeting**. It is **the concrete deliverable** that demonstrates what cross-agency data integration is being used for in practice -- and shows the federated-database thesis is **not theoretical** but **operationally deployed**.

## Connection to vault entities

- [[Palantir Technologies]] - vendor
- [[ImmigrationOS]] - companion / parent platform
- [[Federated Master Database]] - underlying data integration layer
- [[Trump EO Eliminating Information Silos 2025-03-20]] - legal pretext
- [[Hypothesis - Federal database supersedes CA model]] - load-bearing claim ELITE exemplifies

## Sources

- [[Source ACLU Palantir Deportation]]
- [[Source American Immigration Council ImmigrationOS]]