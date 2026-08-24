# The field case

> The talk earns the right to its claim from one mission. This is that mission, in full.

**What:** an AI proptech startup, real-estate financing.
**Role:** freelance, solo build, Claude Code as the working environment.
**Duration:** ~3 months, ending early August 2026.
**Output:** 10+ production AI agents shipped, alone.

> **On naming.** The company, its CEO and the domain expert are not named in this
> repository, and the identifying detail has been kept out. What follows is about a
> structural failure mode and about my own errors in it — nothing here is a complaint about
> anyone I worked with. See [`meta/open-questions.md`](../meta/open-questions.md#naming).

## The setup

Real-estate financing. A CEO who decides. A queue of deals nobody has time to analyse.

The brief was clean and the kind of brief that makes you want to start immediately: automate
the decision. There is an expert, the expert has rules, the queue is longer than the expert's
hours. Encode the rules, clear the queue.

**The bet: encode the rules.**

That bet contains an assumption nobody stated, including me — that the rules existed in a
stable form, and that the expert's job was applying them rather than producing them.

## What actually happened

He applied the same rule **differently** from one deal to the next.

Not carelessly. Not wrongly. He was weighing things that were real and that he had never
had to name, because until then the weighing had only ever needed to survive contact with
himself. Asked to state the rule, he stated a rule. Watched across deals, he was running
something richer than the rule he stated.

This is the line the talk turns on:

> **You cannot automate a decision your expert can't state twice the same way.**

And behind the single expert, the wider version of the same thing: the constraint was never
capacity. It was **six people who disagreed on what a good deal was** — and mostly didn't
know they disagreed, because nothing had ever forced the disagreement into the open.
Automating the decision would have meant picking one of their six definitions and shipping
it silently under everyone's name.

## The failure, stated plainly

I shipped faster than I ever have. **And for six weeks I built the wrong thing at record
speed.**

The same quarter, the expert whose job I was automating **was still doing it by hand.**

Nothing was broken. The agents worked. Adoption was the thing that never happened, and
because output felt so good, adoption was not the thing I was watching.

## Timeline

| Phase | What I was doing | What was actually true |
|---|---|---|
| Start | Encoding the rules | The rules weren't stable |
| ~6 weeks in | Shipping at peak velocity | Building the wrong thing, fast |
| Same quarter | Agents in production | Expert still working by hand |
| Peak output week | Highest personal velocity of the mission | The week I pushed back on my client **the least** |
| End | Post-mortem from transcripts, not memory | See [`llm-as-mirror.md`](llm-as-mirror.md) |

*Dates and phase boundaries need tightening — see [`meta/open-questions.md`](../meta/open-questions.md).*

## What I'd extract from it

**The correlation that hurts.** The highest-output week was the week with the least
pushback. That's not a coincidence to mention in passing — it's the mechanism. Building is
measurable, immediate, and nobody argues with it. Disagreeing is slow, uncomfortable, and
has no artefact at the end of the day. Under any pressure at all, the first one crowds out
the second. → [Shift 1](shifts/01-split-the-role.md)

**Silence read as success.** No complaints came in, and I took that as the system working.
It was the system not being used. → [Shift 2](shifts/02-instrument-adoption.md)

**The disagreement existed the whole time.** It was available to be surfaced on day one,
for the cost of one uncomfortable meeting. Instead it was discovered six weeks later at the
cost of six weeks. → [Shift 3](shifts/03-surface-disagreement.md)

**Capability isn't adoption.** A tool that enables 100% of the job, that nobody knows how to
use, is worth zero. And a surface that keeps improving is a surface nobody can build a habit
on. → [Shift 4](shifts/04-freeze-the-surface.md)

## Honesty notes

- **n=1.** One mission, one client, one domain. This is an existence proof of a failure
  mode, not a measurement of how common it is.
- **The client is identifiable.** Everything here is about my own errors and the structural
  situation. Nothing here is a complaint about him — he is, in the closing act, the one who
  handled the misalignment better than I did.
- **I was the PM and the engineer.** The role collapse the talk describes is not something I
  observed from outside. It's the thing I did.
