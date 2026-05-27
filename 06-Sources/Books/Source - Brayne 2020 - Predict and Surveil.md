---
date: 2026-05-22
description: Five-year LAPD ethnography documenting how Palantir and predictive policing systems expanded surveillance, discretion, and racialized control at the street level.
tags: [source, book, surveillance, predictive-policing, palantir]
type: source
tier: Tier-2
aliases: ["Source: Brayne 2020"]
---

# Source — Predict and Surveil: Data, Discretion, and the Future of Policing (Sarah Brayne, 2020)

## Bibliographic
- **Author:** Sarah Brayne (sociologist, UT Austin)
- **Publisher:** Oxford University Press, 2020
- **Method:** Ethnographic fieldwork with the LAPD and surrounding agencies, 2013–2015, with annual follow-up visits 2016–2018
- **ISBN:** 9780190684099

## Thesis & scope
Brayne argues that data-driven policing does not simply predict crime — it actively produces it. The feedback loop is structural: biased enforcement creates biased training data, which directs enforcement back at the same communities. The book documents two novel surveillance effects: (1) expansion of the surveilled population far beyond prior-contact individuals through "secondary surveillance networks," and (2) a legal work-around dynamic where officers can run commercial data aggregators without triggering Fourth Amendment disclosure requirements that would attach to traditional law-enforcement queries.

## Key content relevant to the vault

**LAPD / Palantir operational specifics.** LAPD deployed [[Palantir Gotham]] as its core integration platform, merging crime and arrest reports, automated license plate reader (ALPR) data, rap sheets, field interview (FI) cards, gang database entries, outstanding warrants, vehicle registrations, foreclosure records, and noise complaints into a single queryable environment. Brayne observed this in live use, not via document review alone.

**Operation LASER.** A federally funded pilot that used Palantir data to generate a "chronic offender" list — primarily suspected gang members — and directed patrol resources toward those individuals. Officers accrued points for each contact with a listed person; listed persons accrued points for each officer contact. The scoring loop is the clearest empirical demonstration of the feedback mechanism Brayne theorizes.

**CalGang / gang database.** Individuals could be placed in gang-related databases on officer discretion, with minimal due process. Brayne documents how database entry fed directly into Palantir query results, so database errors propagated into patrol decisions.

**Secondary surveillance networks.** [[Palantir Gotham]] allowed officers to map social ties of contact subjects — a person never individually stopped could be surveilled as an associate of someone who had been. Brayne names this the "secondary surveillance network" effect and argues it extends dragnet logic to previously uncovered populations.

**Vendor dependence and audit gap.** Brayne found that LAPD officers and supervisors had virtually no recollection of independent audits of the Palantir system. Accuracy, model logic, and output validity were outsourced to the vendor — a pattern she frames as a structural accountability deficit rather than individual negligence.

**Avoidance behavior.** Some community members began avoiding hospitals, schools, and social services to stay out of data systems — a chilling effect not traceable to overt coercion. Brayne calls this "system avoidance" and argues it is a material harm of surveillance independent of arrest outcomes.

**Officer ambivalence.** Not all LAPD officers embraced the systems. Brayne records instances of officers bypassing or ignoring Palantir outputs, raising questions about implementation fidelity and the gap between vendor claims and street reality.

## How it maps to the vault
The vault has nodes on [[Palantir Technologies]], [[Palantir Gotham]], [[Palantir Foundry]], the [[ICE Palantir Flock CSPOA 287g enforcement stack]], and the [[Federal database supersedes CA model]] hypothesis. Brayne provides the only published first-hand ethnographic record of Palantir in day-to-day police use, making her work the strongest empirical grounding for the vault's surveillance-tech thread. The secondary surveillance network concept maps directly to the vault's data-flow concern about non-consenting third parties swept in by CA-style graph traversal.

## GAPS — what this book raises that the vault appears to miss

1. **Operation LASER (LAPD)** — the specific federally funded Palantir pilot by that name, its scoring mechanism, and its 2019 cancellation after community pressure — not found in inventory. [verified-absent] Vault thread: Palantir + predictive policing
2. **ALPR (Automated License Plate Reader) data as Palantir feed layer** — the specific integration of ALPR into Palantir Gotham at scale in a named US city — not a distinct vault concept node. [verified-absent] Vault thread: surveillance / data flows
3. **CalGang database** — California's statewide gang database (or its structural role as a Palantir data source) — not found in inventory. [verified-absent] Vault thread: law enforcement data infrastructure
4. **"Secondary surveillance network" concept** — Brayne's named mechanism for surveilling social-graph neighbors of direct contacts — not in vault as a concept. [verified-absent] Vault thread: data flows / graph traversal
5. **"System avoidance" as surveillance harm** — the empirically documented behavior of vulnerable populations avoiding health/social services to escape data capture — no vault concept node. [verified-absent] Vault thread: surveillance harms / civil liberties
6. **Sarah Brayne** — no person node in vault. [verified-absent] Vault thread: investigators/journalists/academics
7. **PredPol** — the second predictive policing software vendor Brayne observed alongside Palantir; documented in the same fieldwork — not found in inventory. [verified-absent] Vault thread: predictive policing vendors

## Evidence tier
**Tier-2.** Peer-reviewed academic book based on five years of direct ethnographic observation and follow-up. Brayne had sustained embedded access to LAPD operations. Findings are specific and documented rather than speculative. Some interpretive claims (e.g., causal feedback loop) are sociological argument rather than proved fact — flag accordingly.

## Related
- [[Palantir Technologies]], [[Palantir Gotham]], [[Flock Safety]], [[ICE Palantir Flock CSPOA 287g enforcement stack]]
- [[Hypothesis - Federal database supersedes CA model]]
- [[Source - Tau 2024 - Means of Control]] (Byron Tau on commercial data broker ecosystem)
- [[Source - Zuboff 2019 - Age of Surveillance Capitalism]]
