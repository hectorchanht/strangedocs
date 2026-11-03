---
name: Strange Docs
description: Evidence-first archive of declassified documents, court records and FOIA releases.
colors:
  violet: "#a78bfa"
  violet-deep: "#7c3aed"
  violet-light: "#c4b5fd"
  violet-tint: "rgba(139,92,246,.07)"
  violet-glow: "rgba(139,92,246,.4)"
  cyan: "#22d3ee"
  green: "#4ade80"
  red: "#fb7185"
  yellow: "#facc15"
  bg: "#08080f"
  panel: "#101019"
  panel2: "#151524"
  ink: "#f5f3ff"
  dim: "#a09abf"
  faint: "#837d9f"
typography:
  display:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(36px, 6.5vw, 62px)"
    fontWeight: 800
    lineHeight: 1.06
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(26px, 5vw, 42px)"
    fontWeight: 800
    lineHeight: 1.06
    letterSpacing: "-0.025em"
  topic-headline:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(28px, 5vw, 44px)"
    fontWeight: 800
    lineHeight: 1.06
    letterSpacing: "-0.025em"
  title:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "21px"
    fontWeight: 750
    letterSpacing: "-0.015em"
  lede:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: 1.65
  body:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.65
  stat:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "30px"
    fontWeight: 800
    letterSpacing: "-0.02em"
  summary:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.65
  small:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.65
  nav:
    fontFamily: "ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter, Helvetica Neue, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    letterSpacing: "0.1em"
  mono-body:
    fontFamily: "ui-monospace, SF Mono, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: "14px"
    fontWeight: 400
  label:
    fontFamily: "ui-monospace, SF Mono, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: "11px"
    fontWeight: 700
    letterSpacing: "0.18em"
  section-label:
    fontFamily: "ui-monospace, SF Mono, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: "12px"
    fontWeight: 700
    letterSpacing: "0.26em"
rounded:
  redact: "6px"
  md: "16px"
  lg: "18px"
  xl: "20px"
  pill: "999px"
spacing:
  gutter: "22px"
  grid-gap: "16px"
  card: "26px"
  section: "54px"
  footer: "72px"
components:
  card:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
    padding: "26px"
  file-item:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    padding: "22px 24px"
  badge-document:
    textColor: "{colors.green}"
    rounded: "{rounded.pill}"
    padding: "6px 14px"
    typography: "{typography.label}"
  badge-disputed:
    textColor: "{colors.red}"
    rounded: "{rounded.pill}"
    padding: "6px 14px"
    typography: "{typography.label}"
  badge-unproven:
    textColor: "{colors.yellow}"
    rounded: "{rounded.pill}"
    padding: "6px 14px"
    typography: "{typography.label}"
  badge-pending:
    textColor: "{colors.dim}"
    rounded: "{rounded.pill}"
    padding: "6px 14px"
    typography: "{typography.label}"
  search-input:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "16px 22px"
  nav-link:
    textColor: "{colors.dim}"
    padding: "6px 2px"
  nav-link-active:
    textColor: "{colors.violet}"
---

# Design System: Strange Docs

## Overview

**Creative North Star: "The Night Reading Room"**

A reading room after hours. The lights are low, the archive is open, and the documents glow faintly violet on a near-black desk. Strange Docs is read in the dark: one deep blue-black field, soft luminous panels, and a single violet voice that marks what can be clicked, filed or trusted. The atmosphere comes from depth and glow, not from props. There are no stamps, folders or typewriter faces.

Density is moderate and calm. Big sans headlines carry the subject, while small, widely tracked monospace labels carry the archive's bookkeeping: file codes, dates, topic names, evidence status. That split is the system: **the story speaks in sans, the record speaks in mono.** Evidence status gets its own three-color signal (green, red, yellow) that never doubles as decoration.

Rejected directions: spy-thriller / CIA cosplay (TOP SECRET stamps, typewriter type, manila folders) and the cold, purely functional government-portal look. The room is atmospheric, but it stays an archive.

**Key Characteristics:**
- Single dark theme on a near-black, faintly violet ground with a soft violet halo at the top of every page.
- Violet is the one interactive and brand accent; cyan is a rare secondary spark.
- Sans for narrative, uppercase tracked mono for every piece of metadata.
- Soft, generously rounded panels with hairline violet borders; they lift and glow on hover.
- Evidence status is always a colored pill, read before the headline.

## Colors

A near-monochrome violet night with one accent, one spark, and a reserved traffic-light set for evidence.

### Primary
- **Reading-Lamp Violet** (`violet`): links, active nav, the keyboard focus ring, card file codes, the emphasized word in the home headline, the source-list bullet (✦), the focus border on search, and the TL;DR label. Hover lifts it to **Pale Lavender** (`violet-light`).
- **Deep Ink Violet** (`violet-deep`): the folded corner of the logo. Its rgba sibling (139,92,246) drives every translucent tint (`violet-tint`, the TL;DR fill), border glow and hover shadow (`violet-glow`) on the site.

### Secondary
- **Signal Cyan** (`cyan`): a rare spark. File counts on topic cards and the last redaction bar in the logo.

### Tertiary (evidence key only)
- **Confirmed Green** (`green`): DOCUMENT badge. Confirmed by primary sources.
- **Contradicted Rose** (`red`): CLAIM: DISPUTED badge.
- **Unproven Amber** (`yellow`): CLAIM: UNPROVEN badge only. NEW — PENDING REVIEW is not an evidence status and uses the neutral dashed pending badge.

### Neutral
- **Midnight Desk** (`bg`): page background and `html` fill.
- **Panel Night** (`panel`): cards, file items, stat tiles, evidence key box, search field.
- **Raised Panel** (`panel2`): second surface step; defined but rarely used.
- **Paper White** (`ink`): headlines and primary text, a faintly violet white.
- **Lamplight Grey** (`dim`): body copy in cards, ledes, secondary text, inactive nav.
- **Shadow Grey** (`faint`): tagline, section labels, footer, metadata, placeholders. Tuned to clear 4.5:1 on every surface (5.1:1 on Midnight Desk, 4.6:1 on Raised Panel).
- **Hairline** (rgba(167,139,250,.14)): every border and divider.

### Named Rules
**The One Lamp Rule.** Violet is the only accent that means "act here." Cyan stays below a handful of touches per page; it never becomes a link color.

**The Evidence Colors Are Not Decoration Rule.** Green, rose and amber only appear as evidence-status signals; workflow states such as pending review stay neutral. Never use them for charts, highlights or branding.

## Typography

**Display Font:** system UI sans (ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Inter)
**Body Font:** same system sans
**Label/Mono Font:** system monospace (ui-monospace, SF Mono, Menlo, Consolas)

**Character:** Heavy, tightly tracked sans headlines feel present and modern. Small, uppercase, widely spaced mono labels read like archive catalogue entries. No web fonts are loaded, so pages render instantly in the platform's own faces.

### Hierarchy
- **Display** (800, clamp(36px, 6.5vw, 62px), 1.06): home and section heroes. May carry a solid violet emphasis span (`.grad`) or a dimmed span (`.soft`). Headings use `text-wrap: balance`; paragraphs use `text-wrap: pretty`.
- **Headline** (800, clamp(26px, 5vw, 42px), 1.06): the title of an individual file page (`.file-title`). Topic hub titles run one step larger (`topic-headline`, clamp(28px, 5vw, 44px), `.topic-title`).
- **Title** (750, 21px): card headings; file-list headings run at 700 / 19px.
- **Lede** (400, 19px, 1.65): hero intro and a file's main summary paragraph, max 640–700px.
- **Body** (400, 17px, 1.65): default text; supporting copy in cards runs at 15px in Lamplight Grey.
- **Label** (700, 11–12px, 0.08–0.26em tracking, uppercase mono): badges, file codes, dates, meta lines, tagline, footer, section headings (`h2.sec`: 12px, 0.26em, Shadow Grey).

### Named Rules
**The 11px Floor Rule.** No functional text renders below 11px.

**The Record Speaks in Mono Rule.** Every piece of archival bookkeeping (dates, file codes, topic names, statuses, counts, section headings) is uppercase tracked monospace. Narrative never is.

## Layout

A single centered column, max 1080px, with a 22px side gutter. Reading blocks on file pages are capped at 700px. Topic cards use an auto-fill grid of `minmax(min(300px, 100%), 1fr)` with a 16px gap, so the grid collapses to one column on phones without a breakpoint. Vertical rhythm is generous: heroes at 66px top / 46px bottom (36px / 10px on file pages), section labels at 54px above, footer at 72px. One breakpoint at 640px stacks the stat tiles, wraps the nav, and tightens hero and card padding. Long titles are protected with `overflow-wrap: break-word`.

## Elevation & Depth

Depth comes from light, not shadow. Surfaces are flat at rest: a panel fill (often a vertical gradient from Panel Night to transparent) plus a hairline violet border. The page itself has a soft violet radial halo at the top. Shadows appear only as a response: a violet glow under a hovered card and a focus ring on search. Hover lifts are dropped under `prefers-reduced-motion: reduce`; border and glow feedback stay.

### Shadow Vocabulary
- **Card hover glow** (`box-shadow: 0 16px 44px -14px rgba(139,92,246,.4)`): under a hovered topic card, paired with translateY(-3px).
- **Search focus ring** (`box-shadow: 0 0 0 4px rgba(139,92,246,.15)`): around the focused search field.

### Named Rules
**The Glow Is a Response Rule.** Nothing glows at rest except the page halo. Glow and lift are earned by hover or focus.

## Shapes

Soft and generous. Containers use 16–20px corners: 20px for cards and the evidence key, 18px for file items and stat tiles, 16px for the search field and TL;DR box. Every label-like element (status badges) is a full 999px capsule. The only small radius is the 6px redaction bar. Borders are always 1px hairlines in translucent violet; nothing uses a heavy stroke.

## Components

Soft and luminous: big rounded panels with faint violet edges that brighten and lift when touched.

### Chips (status badges)
- **Style:** 999px capsule, uppercase mono 10.5px / 700 / 0.14em, 6px 14px padding. Text in the status color, background at 10% of it, border at 32% of it.
- **Variants:** DOCUMENT (green), CLAIM: DISPUTED (rose), CLAIM: UNPROVEN (amber). NEW — PENDING REVIEW is neutral: Lamplight Grey text on an 8% grey fill with a dashed 45% grey border, so it reads as "not yet checked" rather than as a verdict.

### Cards / Containers
- **Corner Style:** 20px (topic card), 18px (file item).
- **Background:** Panel Night fading to transparent (card) or solid Panel Night (file item).
- **Shadow Strategy:** flat at rest; card hover adds the violet glow and lifts 3px; file item hover shifts 3px right instead.
- **Border:** 1px hairline violet, brightening to ~50% violet on hover.
- **Internal Padding:** 26px (22px under 640px) for cards, 22px 24px for file items.
- **Card anatomy:** violet mono file code, 21px title, 15px grey summary, cyan mono count.

### Inputs / Fields
- **Style:** full-width search field, Panel Night fill, hairline border, 16px corners, 17px sans, 16px 22px padding, Shadow Grey placeholder.
- **Focus:** border turns violet and a 4px soft violet ring appears; the browser outline is removed. Native search appearance is reset so Safari keeps the 16px corners.

### Focus
Every focusable element shows a 2px Reading-Lamp Violet outline, offset 3px, on `:focus-visible`. The page declares `color-scheme: dark` and themes text selection with a 40% violet fill.

### Navigation
- **Style:** brand lockup (32px decorative logo with empty alt, 800 / 19px / 0.14em "STRANGE DOCS" with DOCS in violet), mono tagline under it, then a row of uppercase 13px / 700 / 0.1em links with a 26px gap.
- **States:** Lamplight Grey at rest, Paper White on hover, violet with a 2px violet underline when active. Under 640px the gap shrinks to 16px and the row wraps.

### TL;DR Box (signature)
On file pages: max 700px, 16px corners, 18px 20px padding, violet tint background (7%) with a 35% violet border, a violet mono "TL;DR" label, then a 16px summary. It is the first thing read after the status badge and headline.

### Primary Sources List (signature)
A top-bordered list in 14px mono, each line led by a violet ✦. It closes every file page and backs the footer promise "EVERY FILE CITES ITS PRIMARY SOURCE."

### Redaction Bar
An inline span filled Lamplight Grey with transparent text and 6px corners, used as a typographic wink. It echoes the logo's redaction bars.

## Do's and Don'ts

### Do:
- **Do** lead every file with its status badge, then the mono meta line (date · topic · file code), then the headline.
- **Do** keep all metadata in uppercase tracked mono and all narrative in sans.
- **Do** use the hairline violet border (rgba(167,139,250,.14)) for every divider and container edge.
- **Do** keep reading blocks at or under 700px wide and body text at 1.65 line-height.
- **Do** reserve green, rose and amber for evidence status only.
- **Do** make hover and focus visible through border brightening, glow or a small lift (≤3px), and keep the violet `:focus-visible` outline on every interactive element.

### Don't:
- **Don't** add spy-thriller props: TOP SECRET stamps, typewriter fonts, manila folders, coffee-stained paper.
- **Don't** flatten the room into a cold government portal: keep the dark ground, the halo and the soft luminous panels.
- **Don't** introduce a second interactive accent; links and active states are violet.
- **Don't** use gradient text or an eyebrow pill above a headline; emphasis comes from solid violet, weight and size.
- **Don't** set long text in Shadow Grey (#6b6584); it is for short labels only.
- **Don't** use square corners or heavy borders on containers.
- **Don't** add inline styles. File and topic page blocks use the shared classes (`file-hero`, `file-meta`, `file-title`, `topic-title`, `topic-code`, `tldr`, `tldr-label`, `tldr-text`, `summary`, `status-note`, `review`, `review-note`, `review-body`, `flush`, `dim`).
