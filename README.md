# Hacker's Guides

*Travel writing for historic source code.*

This repository collects **Hacker's Guides**: close readings of landmark programs, written for the curious visitor rather than the specialist. Each guide takes one program — usually decades old, usually famous for what it did rather than how it did it — and walks through the actual source the way a good guidebook walks through a city: a map first, then the districts, then the things you'd never notice on your own.

The premise is that historic code is worth *reading*, not just running or citing. The source of a famous program records decisions, constraints, jokes, borrowings, and unfinished business that no retrospective summary preserves. These guides try to make that record legible to someone without the period machine, the period language, or a PhD in the field the program founded.

## Who these are for

- Programmers curious about how famous systems actually worked under the hood
- Students of computing history who want to go one level deeper than the standard accounts
- Researchers in software studies / critical code studies looking for technically grounded walkthroughs
- Anyone who has heard a program's legend and wants to see the artifact

No familiarity with the original language or hardware is assumed. Each guide includes a primer on whatever dialect, notation, or machine quirks are needed to read the excerpts.

## The format

Every guide follows roughly the same structure:

- **Before You Arrive** — what the program is, who wrote it, when, on what machine, and the provenance of the specific source file being read (original listing, reconstruction, transcription, etc.)
- **The Map** — the program's overall architecture at a glance
- **Districts** — a tour through the major subsystems or regions of the source, with short code excerpts and commentary
- **★ DON'T MISS** — callout boxes for the details worth the trip: revealing comments, clever hacks, period jokes, load-bearing oddities
- **A Day in the Life** — one input, request, or frame traced end-to-end through the whole system
- **Practical Notes** — the minimal language/machine primer needed to read the code yourself, plus pointers to runnable versions or emulators where they exist
- **What Makes It Worth Visiting** — why this program, beyond the legend
- **Provenance and Sources / References** — where the source file came from, which claims rest on the code itself versus historical accounts, and where interpretation was required

## Ground rules

These guides aim to be accurate, not just evocative:

1. **Claims about code behavior come from the code.** Excerpts are quoted from the actual source under discussion, and behavioral claims should be checkable against it.
2. **Provenance is stated up front.** Many famous programs survive only as reconstructions, disassemblies, or later transcriptions. Each guide says exactly which witness it reads and what that implies.
3. **History is attributed.** Authorship, dates, and anecdotes are sourced to primary or standard secondary accounts, and conflicts between sources are noted rather than silently resolved.
4. **Interpretation is flagged.** Dense or self-modifying code sometimes requires a judgment call about what it's doing; guides say so instead of presenting readings as fact.
5. **Modern analogies are labeled as analogies.** Saying a 1962 routine resembles JIT compilation is illuminating; implying lineage or identity is not.

## Reading and contributing

Each guide lives in its own directory alongside the source file(s) it reads (where licensing permits) and any supporting material. Guides are self-contained — start with whichever program interests you.

Corrections are especially welcome: factual errors, misread code, missing attributions, or better provenance for a source file. If proposing a new guide, the bar is a program that is (a) historically significant, (b) available as readable source with known provenance, and (c) small enough to tour honestly in a single document.

# Copyright

**Hacker's Guides** — guide texts, commentary, and supporting material.

Copyright © 2026 Jeff Shrager (<jshrager@gmail.com>). All rights reserved.

Permission requests, corrections, and questions: <jshrager@gmail.com>.

## Scope

This copyright covers the original text of the guides and the README — the prose, structure, commentary, and annotations written for this repository: https://github.com/jeffshrager/HackersGuides

It does **not** cover:

- **The historic source code being read.** Quoted program source (and any complete source files included in this repository) remains the property of its respective authors and rights holders, or is in the public domain, as the case may be. Excerpts appear here for purposes of commentary, criticism, and scholarship. Provenance for each program's source is stated in the corresponding guide.
- **Quoted third-party material.** Brief quotations from cited historical accounts and documentation remain the property of their respective rights holders and are used for the same purposes.

## Attribution

If you quote or reference a guide, please credit "Hacker's Guides, Jeff Shrager" and link to this repository: https://github.com/jeffshrager/HackersGuides
