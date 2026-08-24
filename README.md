# When anyone can build, the person who decides *what* to build becomes the bottleneck

Companion library for the talk of the same name, given by [Nicolas Léonard](https://experimenta.work)
at **AI Summit Barcelona**, 22 September 2026.

---

## What this is

A talk is 20 minutes and then it's gone. This repository is the part that stays.

It holds the full context behind the talk: the argument and how it was built, the field
case it comes from, every claim traced to its source, the four shifts in their long form
(with the objections that apply to them), and the working notes of the preparation itself.

It is organised like the documentation of a tool, not like a blog post. Nothing here asks
to be read front to back. Go to the piece you need.

## Who it's for

**You just watched the talk** and want the sources, or the version of a shift that didn't
fit on a slide → [`docs/thesis.md`](docs/thesis.md), then [`docs/shifts/`](docs/shifts/),
then [`evidence/`](evidence/).

**You're a PM, an engineer, or a founder** watching your own team hit this — the bottleneck
moved and nobody has said so out loud → go straight to
[`docs/shifts/`](docs/shifts/). Each shift is written as a failure mode first: what breaks
if you don't make it. Start with the one you recognise.

**You're helping prepare the talk** (including future AI sessions) → start with
[`AGENTS.md`](AGENTS.md) (or [`CLAUDE.md`](CLAUDE.md) — same notes) and
[`meta/open-questions.md`](meta/open-questions.md).

## The argument, in five lines

1. Engineering output has genuinely exploded. The numbers are real and they are large.
2. Our ability to judge that output did not grow with it — measurably, it fell.
3. The work that decides *whether you're building the right thing* did not compress at all,
   because it is made of human alignment and alignment has no corpus to learn from.
4. So the bottleneck moved. It is no longer "can we build it." It is
   "do we know what to build, and does everyone actually agree."
5. Four shifts follow from that. None of them are about tooling.

The long version: [`docs/thesis.md`](docs/thesis.md).

## Map

| Path | What's in it |
|---|---|
| [`docs/thesis.md`](docs/thesis.md) | The argument in full, with its causal chain and its weak points |
| [`docs/narrative.md`](docs/narrative.md) | How the talk is built: four acts, slide map, timing |
| [`docs/case-study.md`](docs/case-study.md) | The field case. What I shipped, what I got wrong, and when |
| [`docs/shifts/`](docs/shifts/) | The four shifts, one file each, long form |
| [`docs/llm-as-mirror.md`](docs/llm-as-mirror.md) | The closing move: pointing a model at your transcripts, not your codebase |
| [`evidence/`](evidence/) | Every external claim in the talk, traced, dated, and caveated |
| [`deck/`](deck/) | Slide-by-slide content and the link to the live deck |
| [`talk/abstract.md`](talk/abstract.md) | Official abstract, session metadata, speaker info |
| [`meta/history.md`](meta/history.md) | How the talk got here — what it used to be, and what was cut |
| [`meta/origin-april-2026.md`](meta/origin-april-2026.md) | The full record of the conversation it all started from |
| [`meta/`](meta/) | Open questions and the decisions log |

## Status

The talk is **in preparation**. This library is versioned alongside it.

- **Slot:** 20 minutes on stage, 5 minutes Q&A.
- **Deck:** draft, 36 slides, structure locked, wording in revision.
- **Evidence:** 3 external claims verified, with caveats — [`evidence/README.md`](evidence/README.md).
- **Open questions:** [`meta/open-questions.md`](meta/open-questions.md). Q1, Q2, Q11 and Q12
  resolved; the remainder need the speaker, not research.

## License

Content is [CC BY 4.0](LICENSE) — use it, adapt it, cite it. Attribution:
Nicolas Léonard, *When anyone can build*, AI Summit Barcelona 2026.
