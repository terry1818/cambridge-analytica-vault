---
date: 2026-05-15
description: Vault home and orientation for the Cambridge Analytica / AI political warfare research project
tags: [home, index, meta]
---

# Cambridge Analytica & AI Political Warfare — Research Vault

A living evidence base for tracing Cambridge Analytica, its successor organizations, and the broader evolution of AI-driven political influence and cognitive warfare.

## What this vault is for

Four overlapping purposes:

1. **Research archive** — primary sources, court filings, leaked documents, books, articles, videos. Everything tagged, dated, and cited.
2. **Investigative analysis** — connect dots between people, money, data flows, and events. Use canvases and connection notes to surface non-obvious links.
3. **Writing prep** — narrative threads that can be pulled out as articles, explainers, or longer-form work.
4. **App content backend** — structured entity notes that can later be exported to feed the Political app project.

## Start here

- [[Vault MOC|Vault Map of Content]] — the top-level index of every MOC
- [[Master Timeline|Master Timeline]] — chronological spine
- [[Tag Taxonomy|Tag Taxonomy]] — how tags are used in this vault
- [[Conventions|Conventions]] — naming, linking, citation rules
- [[Open Questions|Open Questions]] — the live research backlog

## Folder structure

```
00-Home/              Vault meta: README, taxonomy, conventions, dashboard
01-MOCs/              Maps of Content (topic indexes)
02-People/            Individuals — split by role
03-Organizations/     Companies, agencies, fronts
04-Events/            Campaigns, hearings, leaks, scandals
05-Concepts/          Doctrines, methods, technologies
06-Sources/           Primary evidence: documents, filings, leaks, books, articles
07-Connections/       Relationship notes (money, personnel, data, influence)
08-Hypotheses/        Working theories — labeled by confidence
09-Threads/           Narrative drafts and open question threads
10-Timeline/          Master timeline + per-event timelines
11-Canvases/          Visual relationship maps (.canvas files)
12-App-Backend/       Structured exports for the Political app
_templates/           Note templates (Person, Org, Event, Source, etc.)
_attachments/         Images, PDFs, screenshots
```

## How to use it

- **Adding evidence?** Create a note in `06-Sources/` using the Source template. Cite it from any claim with `[[Source Title]]`.
- **Adding a person/org?** Use the Person or Organization template. Link them to events, sources, and other entities.
- **Found a connection?** Create a note in `07-Connections/` using the Connection template — describe the link, evidence, and confidence.
- **Have a theory?** Drop it in `08-Hypotheses/` with a confidence label. Update as evidence comes in.
- **Drafting an article?** Use `09-Threads/Article-Drafts/`.

## Conventions in brief

- Every note has YAML frontmatter (`date`, `description`, `tags`).
- Dates are absolute (`2018-03-17`), never relative.
- Claims need a `[[source]]` link or a `#claim/unverified` tag.
- Confidence: `#confidence/high`, `#confidence/medium`, `#confidence/low`, `#confidence/speculative`.
- See [[Conventions]] for the full rules.
