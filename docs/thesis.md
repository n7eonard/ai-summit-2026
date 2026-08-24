# The thesis

> Execution went up. Our ability to judge our own output went down.
> That combination is the whole talk.

## The causal chain

The argument is a chain, and each link is doing real work. If any one of them breaks, the
conclusion doesn't hold — which is why they're written out separately here rather than
compressed into a slogan.

### 1. Output per engineer has genuinely exploded

This is not a projection. It is measured, and the people measuring it have every incentive
to be careful because they are measuring themselves.

Anthropic reports the typical engineer merging **8× as much code per quarter** as in the
2021–2025 baseline, with **more than 80% of merged production code authored by the model**,
and **74 product releases in 52 days**.

→ [`evidence/anthropic-internal.md`](../evidence/anthropic-internal.md)

### 2. This is structurally new, not just "faster"

For fifty years, more output meant more people, and more people meant more communication
overhead. That's Brooks' Law and it has held.

An agent breaks the relationship. It adds capacity **without joining the conversation**.
It doesn't need to be onboarded, doesn't attend the kickoff, doesn't have an opinion in
the Slack thread. So the usual brake on output — coordination cost — stops applying to
the building half of the work.

It keeps applying, at full strength, to the deciding half.

*This is the load-bearing link of the whole talk.* Everything after it is a consequence.

### 3. Meanwhile, our judgement of our own output got worse

METR ran a randomised controlled trial with experienced open-source developers on their own
repositories. They forecast a **24% speed-up**. Afterwards they reported a **20% speed-up**.
Measured, they were **19% slower**.

The interesting number is not −19%. It's the ~39-point gap between what they experienced
and what happened. The tooling didn't just change the output; it broke the instrument people
use to assess the output — their own sense of progress.

→ [`evidence/metr-rct.md`](../evidence/metr-rct.md)

**The strongest version of this point comes from the optimists.** Anthropic, publishing its
own 8×, calls that figure *"almost certainly overstated"*, labels lines-of-code a vanity
metric, and notes that the bottleneck in its own software production shifted from *writing*
code to *reviewing* it. The most bullish available dataset says, in its own footnotes, that
it can no longer cleanly judge what it produced.

### 4. The deciding half did not compress — and structurally cannot

Getting six people in a room to agree on what "good" means has not gotten faster, because
there is nothing there for a model to automate.

Alignment lives in Slack threads, kickoff meetings and hallway conversations. It is
performed, not recorded. It evaporates. **There is no corpus to learn from** — so there is
no version of this that a model gets better at by scaling.

Andrew Ng, arriving from a different direction: he doesn't see product work speeding up at
the rate engineering has, and one of his teams asked for a ratio of **two PMs per engineer**
— a request he notes would have sounded absurd a year earlier.

→ [`evidence/andrew-ng-pm-ratio.md`](../evidence/andrew-ng-pm-ratio.md)

### 5. Therefore the bottleneck moved

The cost of building fell through the floor. **The cost of being wrong didn't move.**

When those two costs were comparable, "let's just build it and see" was sound advice —
building was itself a cheap way to find out. Now building is nearly free and finding out is
not, so the ratio inverted and the old advice quietly became expensive.

The constraint was never capacity. It was six people who disagreed on what a good deal was.
**There is no prompt for that.**

## What the talk is *not* claiming

Stated explicitly, because a talk with this title attracts these misreadings:

- **Not** that AI coding tools don't work. They do, enormously. Link 1 is the setup, not
  the villain.
- **Not** that engineers are now less valuable. The argument is about where the *constraint*
  sits, not where the *value* sits.
- **Not** that PMs are the heroes of the story. The shifts apply to whoever is doing the
  deciding — which in a small team is often the same person doing the building. That
  collapse is precisely the problem in [Shift 1](shifts/01-split-the-role.md).
- **Not** a prediction about the future. Every number here is already in the past.

## Known weak points

Kept here so they can be handled on stage rather than in the Q&A.

**The METR study is not about agents as they exist now.** It used early-2025 tooling
(Cursor Pro with Claude 3.5/3.7). Someone will say the models have moved on. The honest
answer: yes, and the finding that matters isn't the −19%, it's the perception gap — and
nothing about better models fixes a broken self-assessment instrument. Arguably it widens it.

**n=16 developers, 246 tasks.** Small. Say so before someone else does.

**"Alignment has no corpus" is the boldest claim in the talk** and the one most likely to be
challenged — meeting transcription tools are now recording exactly the conversations I say
aren't recorded. The distinction to hold: transcription produces a *record*, not a *decision*.
[`docs/llm-as-mirror.md`](llm-as-mirror.md) is where the talk concedes the strongest version
of this objection and turns it into the closing point.

**Sample size of one, on the field case.** One mission, one client, one domain. It's an
existence proof of a failure mode, not evidence of its frequency. Frame it that way.
