# Slide by slide

Verbatim transcription of the current draft (36 slides), mapped to the documentation.

> Transcribed 2026-08-24. If the deck has moved on, this file is stale — treat the
> [Slides file](https://docs.google.com/presentation/d/1LzHwT3HQxIEUMPMVrdSHSM9IEgZSnEJbucncsGTUwKc/edit)
> as the source of truth and re-sync.

---

## Cold open

**1** · *AI FOR BUILDERS*
**When anyone can build, the person who decides what to build becomes the bottleneck**
Nicolas Léonard · AI Summit Barcelona · 22 September 2026

**2** — 10+ production AI agents. 3 months. One person.
> ⚠️ **the live deck still says "14" — correct it.** Resolved 2026-08-24 in favour of the
> submitted abstract's "10+". See [`../meta/open-questions.md`](../meta/open-questions.md#agent-count)

**3** — The same quarter — the expert whose job I was automating was still doing it by hand.

**4** — I shipped faster than I ever have. And for six weeks I built the wrong thing at record speed.

---

## 01 — The compression is real
→ [`../docs/thesis.md`](../docs/thesis.md)

**5** · *01 The compression is real*

**6** · *ANTHROPIC, MEASURING ITSELF*
**8×** more code shipped per engineer, per quarter
**80%** of merged code authored by the model
**74** product releases in 52 days
→ [`../evidence/anthropic-internal.md`](../evidence/anthropic-internal.md)

**7** — For fifty years, more output meant more people. More people meant more communication.
An agent adds capacity without joining the conversation.

**8** · *METR — randomised controlled trial, experienced developers*
**19% slower. They felt 20% faster.**
Forecast +24% · Self-reported +20% · Measured −19%
→ [`../evidence/metr-rct.md`](../evidence/metr-rct.md)

**9** — Execution went up. Our ability to judge our own output went down.
That combination is the whole talk.

---

## 02 — What didn't compress
→ [`../docs/case-study.md`](../docs/case-study.md)

**10** · *02 What didn't compress*

**11** — Real-estate financing. A CEO who decides. A queue of deals nobody has time to
analyse. My job: automate the decision.

**12** — The bet: encode the rules.

**13** — He applied the same rule **differently** from one deal to the next.

**14** — You cannot automate a decision your expert can't state twice the same way.

**15** — The constraint was never capacity. It was six people who disagreed on what a good
deal was. There is no prompt for that.

**16** — Alignment lives in Slack threads and hallway conversations. It is never written
down. So there is no corpus to learn from.

**17** — *"I don't see product management work becoming faster at the same speed as
engineering."*
Andrew Ng — one of his teams asked for two PMs per engineer
→ [`../evidence/andrew-ng-pm-ratio.md`](../evidence/andrew-ng-pm-ratio.md)

**18** — The cost of building fell through the floor. The cost of being wrong didn't move.

---

## 03 — The shifts
→ [`../docs/shifts/`](../docs/shifts/)

**19** · *03 Four shifts* — ⚠️ retitle: only three shifts remain

**20** · **1** Split the role before it splits itself.
**21** — Building is measurable, immediate, and nobody argues with it.
That is exactly what makes it a good place to hide.
→ [Shift 1](../docs/shifts/01-split-the-role.md)

**22** · **2** Instrument adoption on day one. Not month six.
**23** — An internal user who complains is a good user. Silence is the failure signal.
→ [Shift 2](../docs/shifts/02-instrument-adoption.md)

**24** · **3** Make the disagreement visible before you make the thing.
**25** — Bring people in at genesis, or take it to autonomous impact.
The middle is where work dies.
→ [Shift 3](../docs/shifts/03-surface-disagreement.md)

~~**26** · **4** Freeze the surface so people can build habits.~~
~~**27** — A tool that enables 100% of the job, that nobody knows how to use, is worth zero.~~
> ⛔ **CUT 2026-08-24 — remove these two slides from the live deck.** Change management, not
> this talk's claim. ~70 seconds returns to the budget. The slot may be refilled later.
> → [Q25/Q26](../meta/open-questions.md)

---

## 04 — One more thing
→ [`../docs/llm-as-mirror.md`](../docs/llm-as-mirror.md)

**28** · *04 One more thing*

**29** — Six weeks of tension between me and my client. Neither of us said it.
He fed our transcripts to an LLM and sent me the readout.

**30** — It was cold. That is exactly what we needed.

**31** — To write my own post-mortem, I didn't trust my memory.
I analysed every prompt I sent and every message I wrote.

**32** — My highest-output week was also the week I pushed back on my client the least.

**33** — An LLM won't create alignment. It is very good at making your misalignment visible.

**34** — Point it at your transcripts. Not just your codebase.

---

## Close

**35** — Anyone can build now. The scarce thing is saying it out loud:
**I think we're building the wrong thing.**

**36** · *Thank you*
Nicolas Léonard — Experimenta Studio · [experimenta.work](https://experimenta.work)
> ⚠️ **two edits needed on the live deck:** the attribution still reads
> "Experimenta · AI Product Partners" — align it to **Experimenta Studio**. And this
> repository should appear here.
