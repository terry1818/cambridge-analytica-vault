---
date: 2026-05-16
description: Practical guide to navigating and querying the vault from different perspectives
tags: [meta, guide]
---

# How to Use the Vault

This vault contains ~260 notes on Cambridge Analytica, SCL Group, their funders, successors, and the broader AI-era political-influence ecosystem. Here is how to ask different kinds of questions of it.

## Three navigational entry points

1. **Top-level MOC** — [[Vault MOC]] — every major entity and cluster, organized as a hand-curated outline
2. **Lens MOCs** — [[Lenses MOC]] — cross-cutting analytical views (operators, funders, money flows, etc.)
3. **Obsidian Bases** — [[People|People Base]], [[Organizations|Organizations Base]], [[Events|Events Base]], [[Sources|Sources Base]] — spreadsheet-style filterable tables

## The four thematic clusters

The vault's content interlocks in four major thematic clusters. Use these as mental orientation when reading or building:

1. **Defense pipeline** — origin story: BDI → SCL → MoD/DoD → CA. Tagged `#cluster/defense-pipeline`.
2. **Data pipeline** — operational: harvest → models → targeting. Tagged `#cluster/data-pipeline`.
3. **Capital pipeline** — money + ownership: Mercers → CA → Trump + ecosystem; Emerdata + FSG + Israeli intel. Tagged `#cluster/capital-pipeline`.
4. **Continuity / afterlife** — what's still operational. Tagged `#cluster/continuity`.

A given entity often belongs to multiple clusters. [[Robert Mercer]] is `#cluster/capital-pipeline` AND `#cluster/continuity`. [[Alexander Nix]] is in all four.

## Common questions, with how to answer them

### "Who funded what?"

Open [[Lens - Funders]] or [[Lens - Money Flows]]. For database-style: open `99-Bases/People.base` and select the "Funders" view.

### "What's still operational?"

Open [[Lens - Active Successor Operations]]. For database-style: `99-Bases/Organizations.base` → "Active Successors" view.

### "Who blew the whistle?"

Open [[Whistleblowers MOC]] or filter people by `#role/whistleblower`. Bases: People → Whistleblowers view.

### "What's actually contested vs. settled?"

Open [[Lens - Disputed Claims]]. Anything tagged `#claim/disputed` flags a contested fact.

### "What was the Russia connection?"

[[Lens - Data Flows]] (the data-pipeline view) and [[Russian IRA MOC]], plus [[Hypothesis - Defense-to-elections pipeline]]. Search tag `#topic/russia-investigation`.

### "How did CA's methods get exported to the West?"

Open [[Lens - Developing World Test Bed]]. This is the under-examined thread — methods refined in [[Trinidad 2010 Do So Campaign]], Kenya, Nigeria, India, Malta, etc. before [[Donald Trump]] / [[Brexit Referendum 2016]].

### "What's the timeline?"

Open [[Master Timeline]]. For database-style: `99-Bases/Events.base` → "All Events Chronological".

### "What's the bibliography?"

Open `99-Bases/Sources.base` for the full filterable list of 124 sources. Sub-views: Books, Court filings, Cadwalladr corpus, Academic, Whistleblower testimony.

## Tagging discipline

Every note carries tags from multiple axes (entity type, role, topic, era, jurisdiction, plus optional cluster/power/confidence axes). The full schema is in [[Tag Taxonomy]]. **Don't invent new tags** — extend the taxonomy file first.

## Graph view recommendations

In Obsidian's graph view, set color groups by tag:

- `#person` → blue
- `#org` → orange
- `#event` → red
- `#source` → grey
- `#concept` → purple
- `#hypothesis` → yellow

Then filter to one cluster at a time (`#cluster/data-pipeline`, etc.) to see how data flows through the network without other clusters overwhelming the view.

## Search examples

In Obsidian's search bar:
- `tag:#role/operative tag:#era/2014-2016` — operatives during CA's peak
- `tag:#org/private-intelligence` — every privatized-intel firm in the vault
- `tag:#claim/disputed` — every contested factual claim
- `path:02-People file:Mercer` — every Mercer family member node
- `path:06-Sources tag:#evidence/whistleblower-testimony` — every whistleblower source
- `tag:#jurisdiction/russia` — every Russia-tagged note
- `tag:#cluster/continuity` — everything in the afterlife story

## What the vault is NOT

- **Not a substitute for primary sources.** Every claim links to a source note; chase the URL when stakes are high.
- **Not a static snapshot.** The story is still unfolding. The [[Lens - Active Successor Operations]] node and `#status/in-progress` tags mark threads to keep watching.
- **Not court-admissible.** This is research, not litigation.

## What to add as the work continues

In priority order:

1. **More sources from the 119 in `06-Sources/`** — most are stubs with citation only; many need body content
2. **More HindsightFiles analysis** — 100K+ documents largely unanalyzed publicly
3. **2024+ AI-era cases** — Doppelganger, Spamouflage, Team Jorge details, OpenAI threat reports
4. **Per-country event nodes** — Australia, Brazil, Colombia, Argentina, etc. — still mostly stubs
5. **Connection notes** — only 3 written; many more pairwise relationships deserve their own notes

## Sources for the vault itself

This vault was built primarily from Wikipedia + chase-down of Wikipedia references. Every entity note cites Wikipedia and the primary references Wikipedia draws from. The methodology is documented in [[Conventions]].
