---
date: 2026-05-16
description: Multi-axis tag schema for slicing the vault from different analytical angles
tags: [meta, taxonomy]
---

# Tag Taxonomy (v2 -- multi-axis)

Tags are **hierarchical** (`#axis/value` or `#axis/subaxis/value`) and **orthogonal** -- most notes will carry tags from multiple axes. The point is to be able to filter the vault by any combination ("show me all #role/operative people active in the #era/2014-2016 period in #jurisdiction/uk").

Always tag at least: type, era, and at least one topic. Add as many additional axis tags as fit.

---

## AXIS 1 -- Entity type (one)

What KIND of note is this?

- `#person`
- `#org`
- `#event`
- `#source`
- `#concept`
- `#connection`
- `#hypothesis`
- `#moc` · `#lens`

---

## AXIS 2 -- Functional role (for people and orgs)

What did the entity DO in the system?

### People

- `#role/operative` -- built or ran the work (Nix, Kogan, Turnbull, Tayler, Zamel, Hanan, Chmieliauskas)
- `#role/executive` -- formal leadership (Nix, Wheatland, Mercers, Bannon)
- `#role/founder` -- created the firms (Oakes, Nix, Zamel)
- `#role/donor-funder` -- paid for it (Mercers, Bannon, Tchenguiz, Marland, Gabb, Banks)
- `#role/whistleblower` -- broke their silence (Wylie, Kaiser, Sanni)
- `#role/journalist` -- investigative reporting (Cadwalladr, Rosenberg, Confessore)
- `#role/investigator` -- outside academic / civil-society investigators (Briant, Carroll)
- `#role/academic` -- research / analysis (Kosinski, Stillwell, Briant, Hersh, Nyhan)
- `#role/researcher` -- applied research role inside a firm (Wylie, Kogan, Tayler)
- `#role/politician` -- beneficiary or actor (Trump, Cruz, Johnson, Duterte, Kenyatta)
- `#role/regulator` -- official enforcement (Denham, FTC commissioners)
- `#role/prosecutor` -- criminal prosecution (Mueller)
- `#role/lawyer` -- legal counsel (Laurence Levy)
- `#role/lobbyist`
- `#role/backchannel` -- intermediary in influence operation (Nader, Mifsud, Kilimnik, Patten)

### Organizations

- `#org/data-firm` -- CA, GSR, AIQ, Data Propria, Emerdata, Palantir
- `#org/political-consultancy` -- CA, SCL Elections, Auspex
- `#org/military-contractor` -- SCL Defence, Emic, HBGary Federal, FSG
- `#org/private-intelligence` -- Psy-Group, Black Cube, Wikistrat, Team Jorge
- `#org/state-actor` -- IRA, JTRIG, GRU
- `#org/tech-platform` -- Facebook, X, YouTube, TikTok
- `#org/media` -- Breitbart, Channel 4 News, The Observer, NYT
- `#org/research-institute` -- GAI, Mercer Family Foundation, Cambridge Psychometrics Centre
- `#org/shell-front` -- Emerdata, Firecrest, Crow Trading
- `#org/government` -- UK Cabinet Office, US DoD, FCO
- `#org/regulator` -- ICO, FTC, SEC, UK Electoral Commission
- `#org/campaign` -- Trump 2016, Cruz 2016, Leave.EU, Vote Leave, PRI

---

## AXIS 3 -- Topic (multiple)

Subject-matter areas.

- `#topic/cambridge-analytica`
- `#topic/scl-group`
- `#topic/facebook-data`
- `#topic/psychographics`
- `#topic/microtargeting`
- `#topic/disinformation`
- `#topic/deepfakes`
- `#topic/llm-propaganda`
- `#topic/info-warfare`
- `#topic/cognitive-warfare`
- `#topic/psyops`
- `#topic/election-interference`
- `#topic/voter-suppression`
- `#topic/2016-us-election`
- `#topic/brexit`
- `#topic/russia-investigation`
- `#topic/data-broker`
- `#topic/persona-management`

---

## AXIS 4 -- Era (one or range)

When this entity was operational / relevant.

- `#era/pre-2014` -- SCL origins, defense contracting
- `#era/2014-2016` -- CA buildout, Facebook harvesting
- `#era/2016-2018` -- peak operations, elections, exposé
- `#era/2018-2020` -- collapse, investigations, successor formation
- `#era/2020-2024` -- AI-era successor influence ops
- `#era/2024-present` -- generative AI mainstreaming

---

## AXIS 5 -- Jurisdiction (one or more)

Where the entity operated / where the action took place.

- `#jurisdiction/us`
- `#jurisdiction/uk`
- `#jurisdiction/eu`
- `#jurisdiction/russia`
- `#jurisdiction/china`
- `#jurisdiction/israel`
- `#jurisdiction/uae`
- `#jurisdiction/canada`
- `#jurisdiction/kenya`
- `#jurisdiction/india`
- `#jurisdiction/malta`
- `#jurisdiction/mexico`
- `#jurisdiction/trinidad`
- `#jurisdiction/philippines`
- `#jurisdiction/malaysia`
- `#jurisdiction/nigeria`
- `#jurisdiction/argentina`
- `#jurisdiction/australia`
- `#jurisdiction/global` -- multi-country

---

## AXIS 6 -- Evidence type (for sources only)

- `#evidence/primary-document` -- Companies House filings, court filings, official correspondence
- `#evidence/court-filing` -- formal legal documents
- `#evidence/leak` -- unauthorized disclosure (HindsightFiles, Snowden, Anonymous-HBGary)
- `#evidence/whistleblower-testimony` -- Wylie/Kaiser testimony and books
- `#evidence/investigation-report` -- DCMS, ICO, FTC, Mueller, Senate Intel
- `#evidence/journalism` -- published news reporting
- `#evidence/book` -- published book
- `#evidence/academic` -- peer-reviewed
- `#evidence/video-doc` -- broadcast / documentary
- `#evidence/social-media`

---

## AXIS 7 -- Confidence (for analytical claims)

How well-supported is the claim?

- `#confidence/high` -- multiple independent primary sources
- `#confidence/medium` -- one strong primary or several secondary
- `#confidence/low` -- circumstantial, single secondary
- `#confidence/speculative` -- pattern recognition, no direct evidence

---

## AXIS 8 -- Claim status (for assertions)

- `#claim/verified` -- fact, well-established
- `#claim/disputed` -- sources disagree
- `#claim/unverified` -- pending verification
- `#claim/debunked` -- disproven

---

## AXIS 9 -- Status (workflow)

- `#status/stub` -- placeholder
- `#status/in-progress` -- actively researching
- `#status/verified` -- facts cross-checked
- `#status/archived` -- superseded but kept

---

## AXIS 10 -- Cluster (which thematic story does this belong to)

NEW -- added v2. Lets you filter by the four major thematic clusters.

- `#cluster/defense-pipeline` -- origin story: SCL Defence → CA
- `#cluster/data-pipeline` -- operational: harvest → models → targeting
- `#cluster/capital-pipeline` -- money: Mercers → CA → Trump + ecosystem
- `#cluster/continuity` -- afterlife: successors, Israeli intel, AI-era

---

## AXIS 11 -- Power-relationship (NEW)

What is this entity's relationship to state-like power?

- `#power/state-intel` -- operated inside state intelligence agency (JTRIG, IRA, GRU)
- `#power/private-intel` -- privatized intelligence (Psy-Group, Black Cube, Wikistrat, Team Jorge)
- `#power/military-contractor` -- defense contracting (SCL Defence, HBGary Federal, FSG)
- `#power/political-vendor` -- commercial political services (CA, AIQ, Data Propria)
- `#power/political-finance` -- donor/funder/Super PAC (Mercers, Banks, Make America Number 1)
- `#power/platform` -- tech platform (Facebook/Meta, Twitter)
- `#power/regulator` -- official enforcement
- `#power/press` -- investigative journalism
- `#power/civil-society` -- academic / NGO / whistleblower-side

---

## How to use this in Obsidian

1. **Tag panel** -- Obsidian's tag panel lets you click any tag to see all notes with it
2. **Tag search** -- `tag:#role/operative tag:#era/2014-2016` shows operatives active in CA's peak
3. **Bases / dataview** -- for table views, see [[People.base]] and other base files (Obsidian Bases / Dataview required)
4. **Graph view** -- color nodes by tag for visual cluster identification

---

## Migration note

Existing notes in this vault were tagged with v1 schema (no #cluster, #power axes). Notes can be progressively re-tagged. The Tag Taxonomy itself is the source of truth -- if a tag isn't on this list, it shouldn't be in the vault.

## Tag taxonomy in vault use

The tag taxonomy is the axis system the [[Categorization Architecture]] note describes in narrative form. It is used by the [[Vault MOC]] and by the various [[Lens]] notes (e.g. [[Lens - 2024-2026 Power Map]], [[Lens - Money Flows]], [[Lens - Operators]], [[Lens - Funders]], [[Lens - Data Flows]]) as the underlying filter expressions for Obsidian Bases queries.

When adding a new tag, check whether the new tag is genuinely a new axis or whether it is a value on an existing axis. Adding values to existing axes is preferred over proliferating axes. The [[Conventions]] note in 00-Home governs the formatting and naming rules.

The 11-axis schema (entity type, role, topic, era, jurisdiction, evidence type, confidence, claim status, status, cluster, power-relationship) is intentionally over-specified for current needs: it anticipates future analytical questions the vault is not yet ready to ask.

## See also

- [[Categorization Architecture]]
- [[Vault MOC]]
- [[Conventions]]
- [[Evidence Tiers]]
- [[Lens - 2024-2026 Power Map]]
- [[Lens - Money Flows]]
- [[Lens - Operators]]
- [[Lens - Funders]]
- [[Lens - Data Flows]]

## Schema versioning and evolution

The current Tag Taxonomy (v3, established 2026-05-16) reflects three iterations of practical use:

**v1 (initial schema, 2026-05-16 early):** flat tag list with no axis system. Failed in practice because the same tag (e.g., "Russia") could mean entity (the country), topic (Russia-related content), evidence-jurisdiction (Russian-state-actor sources), or claim-status (Russia-related claim, unverified). The conflation produced unfilterable queries.

**v2 (axis-based, 2026-05-16 mid):** introduced explicit axes (entity-type, role, topic, etc.) with prefixed tags (e.g., entity/person, role/operator, topic/microtargeting). Failed in practice because the prefix overhead made tag-writing tedious and the axis count grew uncontrolled.

**v3 (current, 2026-05-16 late):** 11 explicit axes documented in this note, with conventions in [[Conventions]] governing how tags are formatted and applied. Each axis has explicit value-domain (the permitted values are documented), explicit applicability (which note types each axis applies to), and explicit query patterns (which Obsidian Bases queries each axis enables).

## How the taxonomy supports the lens MOCs

The taxonomy is the underlying mechanism that lets the lens MOCs ([[Lens - 2024-2026 Power Map]], [[Lens - Money Flows]], [[Lens - Operators]], [[Lens - Funders]], [[Lens - Data Flows]], [[Lens - COS as Constitutional Capture Vector]], [[Compare - CA era influence ops vs Tech Right government convergence]]) be computed dynamically rather than hand-curated.

A lens MOC's principal query is typically an intersection across multiple axes: "show all entities tagged role/operator AND era/2024-2026 AND cluster/tech-right" produces the Tech-Right-operators slice; "show all events tagged jurisdiction/uk AND topic/data-protection AND status/adjudicated" produces the UK-adjudicated-data-protection events slice; and so on. The taxonomy makes these queries possible; without the axis discipline, the same queries would either not work or would produce excessive noise.

## Common tagging mistakes and how to avoid them

Documented patterns the vault has encountered:

- **Tag-as-content.** Using tags to encode information that should be in the note body (e.g., tagging a note with topic/very-important when the note's substance establishes its importance). The fix: tags are for queryability, not for emphasis.

- **Axis confusion.** Applying an axis to the wrong note type (e.g., applying jurisdiction to a concept note where jurisdiction makes no sense). The fix: check the axis applicability documentation before applying.

- **Value proliferation.** Adding new values to existing axes for one-off notes (e.g., creating a new topic value for a single source that doesn't reuse). The fix: prefer the broadest existing applicable value over creating a new value; promote a value to canonical only when multiple notes need it.

- **Tag-without-link.** Tagging a note for a topic without also wikilinking to the canonical entity note for that topic. The fix: tags are an additional axis; they don't replace wikilinks. A note about CA should both link to [[Cambridge Analytica]] and carry the topic/ca tag.

## Maintenance workflow

The vault has not formalised a tag-maintenance workflow but periodic cleanup is expected. Specific cleanup tasks: identifying tag values that are used only once (candidates for elimination or for promotion to canonical); identifying notes that have axis-applicability mismatches; identifying notes that have wikilinks without corresponding tags; and identifying notes that have tags without corresponding wikilinks.

The maintenance is mostly orthogonal to the vault's substantive analytical work. Periodic batched maintenance (1-2x per year) is the realistic operational target.

## See also

- [[Conventions]]
- [[Categorization Architecture]]
- [[Vault MOC]]
- [[Evidence Tiers]]
- [[Lens - 2024-2026 Power Map]]
- [[Lens - Money Flows]]
- [[Lens - Operators]]
- [[Lens - Funders]]
- [[Lens - Data Flows]]