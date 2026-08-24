# Open questions

What still has to be decided or done before 22 September. Numbers are stable and never reused.

**🔴 6 blocking · 🟠 10 to resolve · 🟡 3 minor · ✅ 8 settled** *(one line each, at the bottom)*

---

## 🔴 Blocking

### Q19 — "Six people who disagreed" is not from the field

**The most serious item in the deck.** Slide 15 presents it as first-hand. It traces to
second-hand material gathered in April — an anecdote about aligning six stakeholders — and the
mission it's attributed to describes something different: one expert applying his own rule
inconsistently, and an unspoken mismatch about the speaker's role.

In a talk arguing for honesty about your own output, a borrowed anecdote wearing the clothes of
testimony is what costs the room if anyone pulls the thread.

**Fix:** state it as the general claim it is, or replace it with the field's actual finding —
*the expert could not state his own rule twice the same way, and nobody had noticed.* The
second is stronger and it's true.

### Q24 — Half the vantage is undocumented: the twelve years of product management

The talk's authority rests on two experiences: twelve years where deciding and building were
separated by other people, meetings and time — then seven months where they collapsed into one
person. **Only the seven months exist anywhere.**

Nothing documents what the role collapsed *from*, which is the half that turns a personal story
into a claim about the industry, and the half that answers "n=1".

Only the speaker has it. Not a CV — the contrast, concretely:

- What used to *force* the deciding to happen? Which meetings, artefacts or people made it
  unskippable, and which still exist?
- A situation where the separation **saved** a project — someone whose job wasn't building said
  "this is wrong" and was heard.
- The PM-to-engineering ratio in a team you actually ran.
- The thing you did routinely in 2018 that nobody has time for now.

Blocks Q26. Softens Q17.

### Q26 — What fills the fourth slot?

Shift 4 was dropped; the slot is open and the published abstract promises four. Three
candidates in [`spare-parts.md`](spare-parts.md). The strongest — *rebuild what used to force
the deciding to happen* — depends on Q24.

Delivering three is also a valid answer. Three that all land beats four where one is off-topic.

### Q20 — Act 4 is mis-sequenced: the readout was the pivot, not the epilogue

The deck stages the client's cold LLM readout as a late reflection. It happened **at the end of
March, mid-mission**, and it was the turning point — there is a before and an after.

**This makes the talk better.** As staged, Act 4 is a lesson learned too late. In reality it's
the intervention that turned the mission around, which lets the talk end on something that
*worked* and turns the shifts from regrets into what fixed it.

### Q21 — "For six weeks I built the wrong thing" is harsher than the client's own account

He disputes it: the rules work was the equivalent of a discovery, perhaps over-extended, and
the consolidated data model exists because it was done.

Self-deprecation the other party disputes isn't humility, it's a different inaccuracy. The
defensible sentence is sharper anyway: **it took six to seven weeks to see that the bet was
wrong, and I was the only one placed to see it.**

### Q18 — Seven months, not three

The mission ran January–July 2026. Deck and abstract both say "3 months" — presumably the
agent-shipping window inside it. Say which window it refers to, or say seven and put the agents
inside.

---

## 🟠 To resolve

### Q23 — The talk under-uses its best asset: the measurement was real

Act 4 says "I analysed every prompt I sent." What that actually was:

- **2,194 prompts** and **793 messages** across 10 channels, Feb–Jul
- Two independent readings produced separately then crossed — the factual against the felt.
  *The places where they contradicted each other were the most instructive.*
- An **assertiveness ratio**: **~10 in private working sessions against 0.14 in messages to the
  client**, in the same month
- Stated limits: a purged retention window, local history ending before the mission did, a
  written-only corpus blind to what moved to video

That gap is the whole talk in one number. **Put one of these on a slide** — it turns Act 4 from
an anecdote into a method the audience can run on themselves, which is what the closing line
asks of them. The stated limits are what make it credible.

### Q16 — The engineer moment and the founder moment were never written

Flagged in April, never done. The abstract promises to address "a PM, an engineer, or a
founder"; the deck has one concrete human moment and it's the PM one.

April said what they should be: for **engineers**, they're being asked to do product work
whether they signed up or not. For **founders**, the ratio math — your org chart is already
wrong. The *chimera role* framing in [`spare-parts.md`](spare-parts.md) is a strong candidate
for the engineer moment.

### Q22 — Slide 11 merges two different people

The lead who commissioned the work, and the domain expert whose decisions were being encoded,
are two people. Merging them loses the mechanism: **the person whose judgement was being
encoded wasn't the person who commissioned the encoding**, so nobody was positioned to notice
the rule wasn't stable.

### Q13 — Stage the client's feedback instead of summarising it

The story was originally built around a specific moment — the client saying, in substance,
*that's not what I need from you.* The deck states the failure abstractly and gives up the
strongest beat in Act 2.

### Q17 — The talk is ~60% first-person; April said keep it to 30%

Cold open, Act 2 and Act 4 are all first-person. Not necessarily wrong — Act 4 is the best
material precisely because it's personal — but the ratio drifted by a factor of two without
anyone deciding to let it. Q24 is the real fix.

### Q6 — Put the "overstated" caveat on slide 6

Anthropic calls its own 8× *"almost certainly overstated"*, calls lines-of-code a vanity metric,
and names **review** as its new bottleneck. Probably the strongest evidence in the talk, and
it's on no slide. **Recommendation: add it.** It makes Act 1 land harder and pre-empts the
"vendor marketing" heckle.

### Q14 — Does "alignment has nowhere to live" belong on a slide?

Runner-up title in April, never used. Slide 16 takes three sentences to say it.

### Q15 — Does the talk need the recovery, not just the failure?

The original structure had a resolution: stopped building, started orchestrating a hybrid
human/AI system. The deck diagnoses and never shows what came after. Defensible — the shifts
*are* the resolution — but it should be a choice.

### Q4 — Primary source for the Andrew Ng quote

Slide 17 puts a direct quotation on screen, attributed by name, sourced from commentary rather
than the original. Find it, or paraphrase and attribute the substance.
→ [`../evidence/andrew-ng-pm-ratio.md`](../evidence/andrew-ng-pm-ratio.md)

### Q5 — Primary source for "74 releases in 52 days"

Consistent with the other figures, but every source found is secondary.
→ [`../evidence/anthropic-internal.md`](../evidence/anthropic-internal.md)

---

## 🟡 Minor

### Q9 — Link this repository from slide 36

The last slide ends on contact details. It should end on where to find everything.

### Q10 — Rehearse the Q&A

Five minutes, realistically three questions. The predictable ones are already answered; the job
is saying them out loud, not researching them.

- *"Isn't METR outdated?"* → [`../evidence/metr-rct.md`](../evidence/metr-rct.md)
- *"Transcription tools already record alignment"* → [`../docs/llm-as-mirror.md`](../docs/llm-as-mirror.md)
- *"Isn't this just doing product properly?"* → [`../docs/shifts/01-split-the-role.md`](../docs/shifts/01-split-the-role.md)
- *"n=1"* → Q24 is the answer, once it exists

Have a closing line ready for being cut off mid-answer.

### Q27 — Print the A4 backup sheet

Decided in May, never done for the current deck. One page: section timings, the must-land
lines, transitions. Ten minutes; saves the talk if Presenter View fails on stage.

---

## ✅ Settled

- **Q1 — Agent count: 10+.** ⚠️ the live deck still shows 14 on slide 2.
- **Q2 — Slot: 20 min + 5 min Q&A.** Allocation and cut order in [`../docs/narrative.md`](../docs/narrative.md#timing).
- **Q3 — Anonymisation: yes, in this repo.** ⚠️ two speaker actions remain — the published
  abstract still names the company, and the client and the expert should hear the story from
  you before Barcelona.
- **Q7 — Mission timeline** — dated; only Q18 remains.
- **Q8 — Is "six people" literal?** Superseded by Q19: it isn't from the field at all.
- **Q11 — Earlier preparation conversations** — found, mined, reusable residue in
  [`spare-parts.md`](spare-parts.md). ⚠️ one organisation was unreachable (HTTP 403); if
  preparation happened there, it hasn't been seen.
- **Q12 — Visual identity** — fixed since May, still in force. See [`spare-parts.md`](spare-parts.md).
- **Q25 — Shift 4** — dropped. See [`decisions.md`](decisions.md) and Q26.
