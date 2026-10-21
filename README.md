# Everloom — App Business Plan (Phase 1)

**A voice-first AI biographer that turns a parent's stories into a finished memoir.**

Phase 1 deliverable for a *Mobile App Development* course: topic selection, product definition, positioning, market analysis, go-to-market plan, unit economics, and a pre-build validation programme — together with the presentation used to defend it.

![Everloom — Phase 1 cover](assets/cover.jpg)

---

## Overview

Everloom is a proposed mobile app that replaces the weekly writing prompt with a scheduled conversation. The storyteller — typically a parent or grandparent aged 65–85 — talks for fifteen minutes; an AI biographer listens, follows up, remembers what was said weeks earlier, and gradually assembles a private archive, a narrated audiobook, and an optional printed hardcover.

This repository contains the complete written plan (in English and Chinese) and the slide deck. Everything is self-contained: no code, no build step.

## Quick facts

| | |
|---|---|
| **Category** | Consumer mobile app — AI-assisted legacy storytelling |
| **Buyer / user** | Adult children (32–55) buy; their parents (65–85) tell the story |
| **Price** | $119 / year per family (one hardcover included) |
| **Market** | $6.2B TAM · $890M SAM · $62M SOM by 2030 |
| **Unit economics** | $142 first-year revenue · 76% gross margin · 3.3× LTV/CAC |
| **Path to profit** | Operating break-even in Q3 2029; $2.4M peak cash need |
| **Funding ask** | $3.0M seed, with $85K spent on validation first |
| **Decision gate** | 31 March 2027 — build only if the validation thresholds are met |

## The idea in three lines

- **Problem.** Every family has a story that is one hospital visit away from being lost, but prompt libraries cannot follow up, writing is a barrier for an 85-year-old, and memory only surfaces when someone asks again.
- **Product.** An AI biographer that runs the interview instead of sending a question: adaptive follow-ups, long-term memory across sessions, chapter drafts, consented voice narration, print on demand.
- **Proposition.** *The memoir app that interviews rather than prompts* — fifteen minutes of talking instead of a year of writing.

## Repository contents

| File | What it is |
|---|---|
| [Everloom App Business Plan.docx](Everloom%20App%20Business%20Plan.docx) | Full business plan, English, 31 pages, A4, 39 numbered tables and 3 figures |
| [Everloom App Business Plan.md](Everloom%20App%20Business%20Plan.md) | The same plan as GitHub-flavoured Markdown (figures resolve from `assets/`) |
| [Everloom - Phase 1 Presentation v4.pptx](Everloom%20-%20Phase%201%20Presentation%20v4.pptx) | 15-slide deck, 16:9, with bilingual speaker notes (English script + Chinese read-aloud) |
| [assets/](assets) | Cover image and the three charts used by the Markdown version |

## What the plan covers

| § | Section | Contents |
|---|---|---|
| 1 | Topic selection | Weighted criteria, four scored candidates, documented decision |
| 2 | App overview | Problem, five-step experience, three surfaces, architecture, scope, model, roadmap, team |
| 3 | Unique selling proposition | One-sentence USP, four proof layers, defensibility, positioning against seven alternatives, objection handling, proposition scorecard |
| 4 | Market analysis | Bottom-up TAM/SAM/SOM with visible arithmetic, five demand drivers, seven-competitor assessment, Porter's five forces, SWOT |
| 5 | Target personas | Two detailed personas plus a B2B buyer, jobs-to-be-done, buyer journey, anti-personas |
| 6 | Marketing channels | Seven-channel portfolio with budgets and target CACs, five playbooks, launch calendar, funnel targets, referral loop |
| 7 | Financial metrics | Unit economics, operating assumptions, four-year P&L, use of funds, KPI dashboard, three scenarios |
| 8 | Validation channels | Six experiments with pre-committed pass/kill thresholds, concierge MVP, go/no-go gate |
| 9 | Risks and ethics | Risk register, four product commitments |
| 10 | Conclusion | Ninety-day plan and the ask |
| A–B | Appendices | Assumptions and sources; requirement-to-section coverage matrix |

## Presentation

- **15 slides, roughly 14 minutes** at a comfortable pace.
- Each slide's notes open with a **Chinese read-aloud script** (timed per slide), followed by the English script and a Chinese summary for rehearsal.
- Presenter View shows the notes; *View → Notes Page* prints them as a bilingual speaking handout.

## How to use

**Read the plan in a browser.** Open the Markdown file on GitHub — the three figures load from `assets/`.

**Read the plan as a document.** The `.docx` files open in Word, WPS Office or Pages. Layout is A4 with headers, footers and page numbers.

**Present.** Open the `.pptx` in PowerPoint, WPS or Keynote and switch on Presenter View.

**Export a PDF.**

- Office: *File → Save as / Export → PDF*.
- LibreOffice, from the command line:

```
soffice --headless --convert-to pdf "Everloom - Phase 1 Presentation v4.pptx"
```

## Method and sources

Market sizing is built bottom-up rather than borrowed from a category report, because no published report defines this category precisely. The arithmetic is population × smartphone reach × annual purchase incidence × average spend, with every input listed.

External inputs include:

- World Health Organization, *Ageing and health* fact sheet (1 October 2025) — 1.4 billion people aged 60+ by 2030.
- United States Census Bureau, population estimates (2023) — approximately 61 million Americans aged 65+.
- Pew Research Center — roughly 10,000 Americans turn 65 every day.
- StoryWorth and Remento public pricing pages (accessed October 2026) — the $69–159 price anchor.
- Public product descriptions for HereAfter AI, StoryFile, Ancestry and MyHeritage.

Full assumptions and the source list are in Appendix A of the plan.

## Version history

| Version | Change |
|---|---|
| v1 | 14-slide deck |
| v2 | Added the technical feasibility slide; type sizes increased throughout |
| v3 | Chinese read-aloud scripts added to every slide's notes |
| **v4** | **Current** — custom backgrounds (navy cover, warm paper interior, gradient close) |

The plan has two editions: English (v1.0) and Chinese (same content, same figures).

## Academic use

This is coursework, not an investment document. The financial model is a structured projection built on stated assumptions, not a forecast; the validation programme exists precisely because several of those assumptions are unproven.

The assignment brief is course material and remains the property of its author; it is included only so that a reader can trace each section back to a requirement.

## Author

<!-- Replace with your name, student ID and course code before publishing. -->
**Prepared by:** _your name_
**Course:** Mobile App Development — Phase 1
**Date:** October 2026

## Acknowledgements

Thanks to the course instructors for the brief and the marking rubric that shaped the structure of this plan, and to the public pricing and product documentation of StoryWorth, Remento, HereAfter AI and StoryFile, which made a grounded competitive analysis possible.
