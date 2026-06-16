---
title: Future Builds
description: Architecture sketches for the most impactful accessibility upgrades to the vault. Reference document for design decisions before committing to a build.
date: 2026-06-16
tags: [home, planning, internal]
aliases: ['Future Builds','Build Sketches']
---

# Future Builds

Architecture sketches for the most impactful accessibility upgrades. Each section is a design sketch, not a commitment.

## Option A -- Ask the Vault (Q&A chatbot)

**Highest accessibility impact for the effort.**

Someone asks a plain-English question. They get a 2-paragraph answer with citations to specific vault notes.

### Architecture

`
User question
    |
    v
Embedding model (OpenAI text-embedding-3-small or local)
    |
    v
Vector search across all ~3,500 vault notes (top 8-12 matches)
    |
    v
LLM (Claude Sonnet or GPT-4) given matches + system prompt
    |  -- enforces evidence-tier labels in output
    |  -- requires citation links back to notes
    |  -- refuses to invent claims not in source material
    v
Answer + citation links rendered in chat UI
`

### Stack options

**Cheapest / fastest (~weekend build, ~``/mo to run):**
- Frontend: Next.js + Vercel free tier
- Vector DB: Pinecone free tier (5M vectors) or pgvector on Supabase free tier
- Embeddings: OpenAI `text-embedding-3-small` (about `$`0.02 per 1M tokens, `$`0.50 to embed entire vault once)
- LLM: Claude Haiku (cheap) or Sonnet (quality), about `$`5-30/mo at moderate use
- Auth: None initially (public chatbot)

**Higher quality (~1 week build, ~`$`50/mo):**
- All of the above plus:
- Re-ranking step (Cohere rerank API)
- Conversation memory
- Citation deeplinking back to Quartz site

### Key design rules

1. **Never invent claims.** If retrieval returns nothing relevant, the bot says so.
2. **Always cite.** Every claim in the answer must link to a vault note.
3. **Preserve evidence tiers.** If a vault note labels something Tier 3, the bot must too.
4. **Refuse off-topic.** If asked about something not in the vault, decline rather than guess.

### MVP scope

- Single-turn Q&A only (no conversation history)
- Public, no auth, simple chat UI
- Hosted at chat.terry1818.github.io or similar
- "Ask the Vault" button on the Quartz site landing page

## Option B -- Curated long-form articles

Turn the master theses + reading lists into polished long-form pieces, like an Atlantic feature.

### Stack

- Next.js or Astro for the site
- MDX rendering for the article bodies
- Each article pulls quotes/citations from vault notes via API
- Twitter-thread / Substack-style readable formatting

### Effort

- ~1 week to build the framework
- Then ~1 day per article to adapt vault MOCs into long-form

## Option C -- Interactive timeline

A drag-through timeline of every documented event from 1980-2026.

### Stack

- D3.js or vis.js timeline component
- Each event clickable, expands to show the vault note inline
- Filterable by category (Trump cases, Russia, Epstein, etc.)
- Embeds in the Quartz site as a single page

### Effort

- ~1 week build
- All event data already exists in the `10-Timeline/` folder

## Option D -- Visual graph explorer

Standalone web app showing the full vault graph as an interactive visualization. Better than the built-in Quartz graph.

### Stack

- Cytoscape.js or Sigma.js
- Pre-rendered node positions for performance
- Click any node, side panel shows the note
- Filterable by cluster (Religious right, Tech right, etc.)

### Effort

- ~1 week build
- Could be embedded into the Quartz site

## Option E -- Mobile PWA

The Quartz site works on mobile but is not installable. A PWA wrapper would let people add it to their home screen, get offline access, and feel like a real app.

### Stack

- PWA manifest + service worker added to the Quartz output
- 1-2 days

## Recommendation order

1. **Card-style landing page** (done in Phase 32)
2. **Q&A chatbot** (Option A) -- biggest single accessibility win
3. **Interactive timeline** (Option C) -- visual entry point for non-readers
4. **PWA wrapper** (Option E) -- mobile install with low effort
5. Long-form articles (Option B) -- when there's writing time
6. Visual graph explorer (Option D) -- nice-to-have polish

## See also

[[Start Here]] | [[Master Theses MOC]] | [[How to Use the Vault]] | [[Frequently Asked Questions]]