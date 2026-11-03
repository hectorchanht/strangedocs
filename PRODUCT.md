# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS served at strangedocs.com (inline `<style>` per page, no framework, no build step in this repo). The HTML was produced by Muse AI; how it is generated is unknown. Treat the files in this repo as the source of truth and edit them directly. Cloudflare Web Analytics beacon is installed.

## Users

Two audiences, served by the same pages:

- **Curious general readers** who met a viral claim (social media, news, a friend) and want to know what is actually true. They usually land on a single file from search or a shared link.
- **Researchers and journalists** who need the primary source: the original document, its date, and a citable link.

Every file must work for the first reader and hold up when the second one checks it.

## Product Purpose

An evidence-first archive of declassified documents, court records, FBI Vault releases and FOIA tranches on subjects heavy with conspiracy lore (Epstein, 9/11, JFK, MKUltra, COINTELPRO, Watergate, banking dynasties, satanic panic and more). It separates what the paper trail proves from what the internet claims. Success: a reader leaves knowing exactly where the documented record ends and folklore begins, with a link to the primary source.

## Positioning

Documents, not rumors. Unlike conspiracy sites, nothing is filed as fact without a primary source. Unlike generic fact-checkers, it is organized around the documents themselves, and popular claims sit beside them as separate entries with an explicit evidence status, so the reader sees the gap rather than being told a verdict.

## Operating Context

- Entry is mostly deep links to a single `/doc/<slug>/` file; index, topics, search and about pages support browsing.
- A watcher monitors FBI Vault, NARA, DOJ and House Oversight release feeds; new official releases are filed automatically (`watch-*` slugs).
- Each file carries an AI DOCUMENT REVIEW generated from the primary source, noting what it verified and what it could not verify from that source.
- Distribution surfaces: `feed.xml`, `sitemap.xml`, `llms.txt`, PWA manifest and icons.
- Sibling project: realufo.

## Capabilities and Constraints

- Content types: DOCUMENT and CLAIM entries. Claims carry a status: CLAIM: DISPUTED (actively contradicted by primary sources) or CLAIM: UNPROVEN (no primary-source evidence either way).
- 13 topic hubs under `/topics/<slug>/`; ~60 files under `/doc/<slug>/`; client-side search page; 404 page.
- Each file shows date, topic, file slug, TL;DR, AI review, and PRIMARY SOURCES links.
- Features already built (current behavior, not formal promises): AI review disclosure on each file; NEW — PENDING REVIEW marking for auto-filed releases until checked; the three-level evidence key.
- Adding a file means updating index LATEST FILES, `sitemap.xml`, `feed.xml` and `llms.txt` by hand.

## Brand Commitments

- Name: Strange Docs. Tagline: "EVIDENCE-FIRST ARCHIVE · DOCUMENTS, NOT RUMORS". Footer line: "EVERY FILE CITES ITS PRIMARY SOURCE".
- Logo: flat violet document mark with redaction bars (`logo.svg`, `favicon.svg`, PWA icons).
- Voice: plain, sober, evidence-led; states what is and is not verifiable. Does not sensationalize.

## Evidence on Hand

- Real content: all files in `doc/`, topic pages in `topics/`, and the cited primary sources (NARA, FBI Vault, NIST, Senate/House reports, court filings).
- No testimonials, readership numbers, press coverage or partnerships exist. Do not invent them.

## Product Principles

1. The primary source is the product. Every surface leads the reader to the document and its citation.
2. Status before story. A reader should see whether something is a document or a claim, and its evidence status, before reading the narrative.
3. Show the boundary. Say plainly what a source does not support, including the AI review's own limits.
4. Serve the skeptic and the researcher at once: readable for a newcomer, precise enough to cite.
5. Sober over sensational. The subject matter is lurid; the presentation should not be.

## Accessibility & Inclusion

No product-specific requirement established. Long-form reading pages, so legibility and contrast for extended reading matter.
