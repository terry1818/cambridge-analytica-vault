---
title: How to Use the Vault
description: Practical guide to navigating the vault. Three ways to read it -- on GitHub, in Obsidian, or on the published Quartz site.
date: 2026-06-16
tags: [home, onboarding, howto]
aliases: ['How to Use the Vault']
---

# How to Use the Vault

## The three ways to read it

### 1. Browser on GitHub (easiest, no install)

- Click any folder above to read notes rendered as plain markdown
- Use GitHub's search box (top of repo) to find any name, organization, or term
- Wikilinks `[[like this]]` will not click on GitHub but you can search the name to find the linked note

**Best for:** Quick lookups, casual reading, first-time visitors.

### 2. Quartz published site (full graph view, no install)

- A static website with full search and visual graph view is auto-built from the repo
- Wikilinks click normally, backlinks work, the graph view renders

**Best for:** Serious reading with full navigation.

### 3. Obsidian (best experience, 5-minute setup)

1. Install [Obsidian](https://obsidian.md) -- free, no account needed
2. Clone: `git clone https://github.com/terry1818/cambridge-analytica-vault.git`
3. Open the cloned folder in Obsidian as a vault

You now have:
- Full graph view (filterable, zoomable)
- Full-text search with regex
- Wikilink click-through with backlinks
- Tag navigation
- Canvas (visual maps)

**Best for:** Researchers, journalists, regular users.

## Navigating once you are in

### Wikilinks

Anything in `[[double brackets]]` is a wikilink. Click it (in Obsidian or Quartz) to follow the connection.

### Backlinks

Every note has a "Linked mentions" or "Backlinks" panel showing every other note that links to it. This is how you find connections you did not know existed.

### Graph view

The visual graph shows every wikilink connection. Master Theses MOC is the dominant orange-highlighted node.

### Search

- Full-text search across every note
- Search inside YAML frontmatter (type, tags, aliases)
- Use `tag:#concept` to filter by tag
- Use `path:"02-People"` to filter by folder

### Tags

Every note carries tags in YAML frontmatter. Common tags include `person`, `organization`, `event`, `concept`, `source`, `moc`, plus topic tags like `religiousright`, `techright`, `j6`, `epstein`.

## Reading paths

| Time you have | Where to go |
|---|---|
| 2 minutes | [[Start Here]] |
| 5 minutes | [[Master Theses MOC]] |
| 30 minutes | [[Reading List - 30 Minutes]] |
| 2 hours | [[Reading List - 2 Hour Deep Dive]] |
| A weekend | [[Reading List - Weekend]] |

## When you find a claim you want to verify

1. Check the **Tier label** -- Tier 1 means citable directly, Tier 3 means cite as allegation
2. Follow any `[[Source: X]]` link -- those are the underlying primary sources
3. If the claim is unsourced or under-sourced, open a GitHub Issue

The [[Methodology - Verifying a CA claim]] note has the full verification protocol.

## When you find a missing connection

Open a GitHub Pull Request with the new connection. Use the templates in `_templates/` and follow [[Conventions]] for naming.

## When something is broken

Open a [GitHub Issue](https://github.com/terry1818/cambridge-analytica-vault/issues). Specify the file, the broken link or claim, and (if you have it) the correct information.

## See also

[[Start Here]] | [[Master Theses MOC]] | [[Plain English Glossary]] | [[Frequently Asked Questions]] | [[Evidence Tiers]] | [[Conventions]]