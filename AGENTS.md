# Working notes for AI sessions

Context for anyone — human or model — picking up work on this repository.

From **2026-08-24**, live working sessions continue in **Grok**, and **this file is the single
source of the working notes.** Any other agent-facing file added later should point here rather
than copy it — two copies of house rules drift, and the drift is silent.

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
  proposing anything**; Q16 and Q17 are April warnings that were never acted on
- [`meta/decisions.md`](meta/decisions.md) — what was already decided and why
- [`meta/spare-parts.md`](meta/spare-parts.md) — good material not currently in the talk, and
  a list of things already tried and dropped. **Check it before proposing an idea** — several
  obvious ones have already been through here

## The relevance filter — apply before adding anything

The talk has one claim: **when anyone can build, the person who decides what to build becomes
the bottleneck.** The speaker's vantage is that he lived both halves at once — twelve years of
product management where deciding and building were separated, then seven months as a solo
product builder where they collapsed into one person. Judge and party.

Before anything enters this repository, it must answer:

> **Does this illuminate what happens when deciding and building collapse into the same
> person — and what to do about it?**

The talk delivers three things and nothing else: **the observation**, **concrete situations
the speaker was actually in**, and **paths forward — what he tried, what worked, what didn't.**

**What that rules out.** The underlying mission produced a great deal of good product work
that fails the test: data-quality pivots, evaluation systems, convergence engines, handover
plans. It is real and it is out of scope. A private mission retrospective exists and is far
richer than this repo — **most of it does not belong here.** On 2026-08-24 a large amount of
it was imported and then cut back the same day; don't repeat that.

The test for material from that retrospective: *would this still be true and interesting if
the mission had been in a different industry solving a different problem?* If not, it's mission
detail, not talk material.

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

**Never commit `assets/`.** Local working captures (screenshots, episode stills, third-party
slides) stay on disk for preparation. They do not belong in this public repo. `.gitignore`
enforces it.

**Language:** repo content in English (international audience). Working conversation with
Nicolas in French.

**Commit attribution.** From 2026-08-24, live working sessions are Grok. Commits carry
`Co-Authored-By: Grok 4.6 <noreply@x.ai>`. Do not add a GitHub user named `grok` as a
collaborator — that account is unrelated.

## Related context outside this repo

- Live deck: [Google Slides](https://docs.google.com/presentation/d/1LzHwT3HQxIEUMPMVrdSHSM9IEgZSnEJbucncsGTUwKc/edit)
- `~/Code/whoami/WHO-ME.md` — private self-portrait work by the same author. Contains
  independent material on that same mission (notably: peak flow came from a six-week
  objective with a shared checkpoint; motivation collapsed in phases without a clear goal).
  Corroborates Shift 1. **Private — do not copy content from it into this public repo.**
