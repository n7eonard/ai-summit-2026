# Working notes for AI sessions

Context for anyone — human or model — picking up work on this repository.

From **2026-08-24**, live working sessions continue in **Grok**. Keep this file in sync with
[`AGENTS.md`](AGENTS.md).

## What this repo is

The companion library for Nicolas Léonard's talk *When anyone can build, the person who
decides what to build becomes the bottleneck*, AI Summit Barcelona, 22 September 2026.

Two audiences, both real:
1. **Preparation** — the working context for building the talk.
2. **Public** — what the audience is pointed to afterwards.

Write everything so it serves both. In practice that means: no private shorthand, no
half-finished thoughts left unmarked, and unresolved items go in
[`meta/open-questions.md`](meta/open-questions.md) rather than sitting as TODOs in prose.

## Start here

- [`docs/thesis.md`](docs/thesis.md) — the argument and its weak points
- [`meta/open-questions.md`](meta/open-questions.md) — what's unresolved, **read before
  proposing anything**; three items are blocking
- [`meta/decisions.md`](meta/decisions.md) — what was already decided and why
- [`meta/history.md`](meta/history.md) — what the talk used to be. **Read before proposing a
  structural change**: a different set of four shifts was already tried and replaced
- [`meta/origin-april-2026.md`](meta/origin-april-2026.md) — the origin conversation in full.
  Most obvious ideas were already had in April; several were tried and dropped for reasons
  worth knowing before re-proposing them

## House rules

**Never put a number on a slide without a row in the claims ledger.**
[`evidence/README.md`](evidence/README.md) holds the ledger; each claim gets a file with its
source *and its caveats*. This is the one non-negotiable rule here: the talk argues that we've
lost the ability to judge our own output, so sloppy sourcing would refute it by demonstration.

**Write objections down.** Every doc that makes a claim carries the arguments against it. Not
defensive hedging — the objections are load-bearing, because the talk's credibility comes from
the speaker having got things wrong and said so.

**Keep the deck mirror in sync.** [`deck/slide-by-slide.md`](deck/slide-by-slide.md) is a
transcription of the live Google Slides. When the deck moves, re-sync it, and update the
transcription date.

**Don't invent field detail.** The field material is first-hand testimony. If a date, a
count, or a sequence isn't already recorded, it goes to `meta/open-questions.md` as a question
for the speaker — never gets filled in plausibly.

**Language:** repo content in English (international audience). Working conversation with
Nicolas in French.

## Related context outside this repo

- Live deck: [Google Slides](https://docs.google.com/presentation/d/1LzHwT3HQxIEUMPMVrdSHSM9IEgZSnEJbucncsGTUwKc/edit)
- `~/Code/whoami/WHO-ME.md` — private self-portrait work by the same author. Contains
  independent material on that same mission (notably: peak flow came from a six-week
  objective with a shared checkpoint; motivation collapsed in phases without a clear goal).
  Corroborates Shift 1. **Private — do not copy content from it into this public repo.**
