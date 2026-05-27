---
date: 2026-05-17
description: Index of all timeline notes — the master timeline and per-entity / per-era chronological views
tags: [moc, timelines]
type: moc
---

# Timelines MOC

Timeline notes provide **chronological views** over the facts that live in entity / event / connection notes. A timeline is **not a fact store** — it's a sorted index of facts that are documented elsewhere. The canonical source for any specific fact is the relevant entity / event note; the timeline is the **chronological projection**.

For routing rules on timeline vs. event vs. entity content, see [[Categorization Architecture]].

## Master timeline

- [[Master Timeline]] — the cross-domain chronological spine; pre-2014 through 2024-present AI-era

## Per-entity timelines (`10-Timeline/`)

### CA / SCL operational core
- [[Timeline - Cambridge Analytica]]
- [[Timeline - SCL Group]]
- [[Timeline - Alexander Nix]]
- [[Timeline - Aleksandr Kogan]]

### Whistleblowers
- [[Timeline - Christopher Wylie]]
- [[Timeline - Brittany Kaiser]]

### Funders / political infrastructure
- [[Timeline - Robert Mercer]]
- [[Timeline - Rebekah Mercer]]
- [[Timeline - Steve Bannon]]

### State / private-intel
- [[Timeline - Erik Prince]]

### Journalists
- [[Timeline - Carole Cadwalladr]]

### Cross-entity threads
- [[Timeline - Russia data triangle]]

## When to split the master timeline

The [[Master Timeline]] currently maintains a single-file view across all eras. When that file becomes unwieldy (currently <100 lines, not yet at the threshold), it can split into:

- `Timeline - Pre-2014 SCL era`
- `Timeline - 2014-2018 CA era`
- `Timeline - 2018-2024 successor era`
- `Timeline - 2024-present AI / federal-database era`

Each era timeline would include cross-references to the per-entity timelines for that period.

## How timelines integrate with hypotheses

Each hypothesis in `08-Hypotheses/` implicitly invokes a chronological argument — that events occurred in a specific order that supports the claim. When a hypothesis's chronological claim is contested, the relevant timeline note is the **shared chronological surface** where evidence converges.

Example: [[Hypothesis - Successor entities preserve operational capability]] relies on the timing of:
- [[Emerdata Limited]] incorporation (2017-08-11)
- [[Alexander Nix]] suspension (2018-03-20)
- [[Alexander Tayler]] Emerdata appointment (2018-03-28)
- [[Cambridge Analytica]] insolvency (May 2018)
- [[Auspex International]] launch (July 2018)
- [[Data Propria]] launch (May 29, 2018)

The chronology is the load-bearing argument. The [[Master Timeline]] and per-entity timelines are where that chronology is verifiable in one place.

## Related

- [[Categorization Architecture]] — timeline vs. event routing
- [[Events MOC]] — discrete events that timelines organize chronologically
- [[Vault MOC]] — top-level navigation
