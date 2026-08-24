# Open questions

Things this repository cannot resolve on its own. Ordered by how much damage they do if left
open until September.

**Legend:** 🔴 blocking · 🟠 should be resolved · 🟡 nice to have

**Status 2026-08-24:** Q1, Q2, Q11, Q12 resolved · Q3 policy set, two speaker actions remain ·
Q13–Q17 opened by the recovered history · **Q18–Q23 opened by the REX, and they are the
serious ones — several things currently on slides are contradicted by the speaker's own
retrospective.** Start there.

---

## 🔴 Blocking

### Q18 — The mission was seven months, not three

The REX covers **January to July 2026**. The deck and the submitted abstract both say
"3 months".

Three months is presumably the agent-shipping window inside a seven-month mission — which is
fine, and arguably more impressive stated that way. But as written, slide 2 invites a listener
who knows the engagement to hear a longer mission compressed into a better-sounding number.

Say which window "3 months" refers to, or say seven months and put the agents inside it.

### Q19 — Slide 15's "six people who disagreed" is not supported by the field

This is the most serious one.

The REX describes a different problem: **data quality and trust in the tool**, one expert
applying rules inconsistently, and an unspoken mismatch about the speaker's own role. It does
not describe six stakeholders disagreeing about what a good deal was.

"Six people in a room" traces back to the **April inputs** — a second-hand Anthropic anecdote,
the joke that even with AGI you cannot align six stakeholders. It was never a field finding.

The deck presents it as one. In a talk arguing for intellectual honesty about your own output,
a borrowed anecdote wearing the clothes of first-hand testimony is the single most damaging
thing in the deck if anyone pulls the thread.

**Fix options:** state it as the general claim it is (and attribute it), or replace it with the
field's actual finding — *the expert could not state his own rule twice the same way, and
nobody had noticed.* The second is stronger, and it is true.

### Q20 — Act 4 is mis-sequenced: the readout was the pivot, not the epilogue

The deck implies the client's cold LLM readout came after the mission, as the reflective
coda. **It happened at the end of March**, mid-mission, and the REX calls it the turning point
— "il y a un avant et un après". Everything good in the mission came after it.

The self-analysis of the prompt log is the genuinely post-mission piece; the readout is not.

**This makes the story better, not worse.** As staged, Act 4 is a lesson learned too late. In
reality it is the intervention that rescued the mission — which means the talk can end on
something that *worked*, and the four shifts stop being regrets and become the things that
turned it around.

### Q21 — "For six weeks I built the wrong thing" is harsher than the client's own account

The client explicitly contests it. His position in the REX: the rules work was the equivalent
of a discovery, perhaps over-extended — nobody could state what data was needed to finance a
project, and the consolidated data table exists because that work was done. Without it, he
could not have briefed the extraction work at all.

Self-deprecation that the other party disputes is not humility, it is a different inaccuracy.
And the real finding is sharper anyway: **it took six to seven weeks to see that the problem
was data quality, not analysis speed.** That is a better sentence and it is defensible.

### <a id="agent-count"></a>Q1 — How many agents? ✅ Resolved 2026-08-24

**Answer: 10+.** The deck rounded up. Everything in this repository now says 10+.

**⚠️ One action remains:** the live deck still shows *14* on slide 2. Edit it.
→ [`deck/README.md`](../deck/README.md)

*Note: the REX gives a different countable — 14 active business rules, 0 validated. If the
"14" in the deck ever drifted from rules to agents, that is worth checking before the talk.*

### Q2 — What is the slot length? ✅ Resolved 2026-08-24

**20 minutes on stage + 5 minutes Q&A.**

Full allocation, the order things get cut in if you overrun, the five slides that must never
be cut, and the two beats that need silence rather than speed:
[`docs/narrative.md`](../docs/narrative.md#timing).

### <a id="naming"></a>Q3 — What can be said publicly about the client? ✅ Policy set 2026-08-24

**Decision: anonymise in this repository.** The company, its CEO and the domain expert are
not named here. The material stays — the failure mode is the point and it loses nothing by
being told about "an AI proptech startup".

Why: Act 4 describes six weeks of unspoken tension with a real person, and slide 13 says a
real expert applied his own rule inconsistently. On stage, delivered as observation, that is
respectful. In a public repository, indexed, attached to a named company and a findable
person, it is a different act — and an irreversible one.

**⚠️ Two actions remain, and they are the speaker's:**

1. **The published abstract names the company.** That text is already public on the
   conference site and this repo doesn't change it. Anyone can therefore join the dots.
   The redaction here reduces exposure; it does not eliminate it. Decide whether that's
   acceptable, or ask the conference to adjust the abstract.
2. **Tell the client and the expert.** Anonymised or not, the story is being told from a
   stage in Barcelona. They should hear it from you first — and the Act 4 story in
   particular is *his* story as much as yours. He comes out of it well; he should still get
   to know it's being told.

**Also decide:** whether the company is named *out loud on stage* even though it isn't named
here. That's a defensible split — a room of 200 is not a search index — but it should be a
choice, not an accident.

## 🟠 Should be resolved

### Q4 — Primary source for the Andrew Ng quote

Slide 17 puts a direct quotation on screen, attributed by name. Currently sourced from
commentary about his remarks, not the original. Find the issue of *The Batch* or the
talk/interview — or paraphrase and attribute the substance instead.
→ [`evidence/andrew-ng-pm-ratio.md`](../evidence/andrew-ng-pm-ratio.md)

### Q5 — Primary source for "74 releases in 52 days"

Widely reported, consistent with the other two Anthropic figures, but every source found is
secondary. → [`evidence/anthropic-internal.md`](../evidence/anthropic-internal.md)

### Q6 — Put the "overstated" caveat on slide 6?

Anthropic calls its own 8× *"almost certainly overstated"* and names review as the new
bottleneck. This is arguably the strongest single piece of evidence in the talk and it is
currently not on any slide. Adding it costs a beat in Act 1 and buys a great deal of
credibility — and it pre-empts the "that's vendor marketing" heckle.

**Recommendation: add it.** It makes Act 1 land harder, not softer.

### Q7 — Tighten the mission timeline

`docs/case-study.md` has the shape but the phase boundaries are approximate. When did the
six weeks start? When did the "still doing it by hand" discovery land? When was the readout?
Precision here is cheap and makes the story much harder to wave away.

### Q8 — Is "six people" literal?

Slide 15 and the abstract both say six. If the real number is five or seven, use the real
number. If "six" is a stand-in for "the stakeholders," say "the room" instead. Don't invent
precision in a talk about intellectual honesty.

---

## 🟡 Nice to have

### Q9 — Link this repository from slide 36

The last slide currently ends on contact details. It should end on where to find everything —
that's this repo's whole reason for existing. Consider a short URL or a QR code.

### Q10 — Q&A preparation

The predictable questions are already answered in the docs but not rehearsed:
- "Isn't METR outdated?" → [`evidence/metr-rct.md`](../evidence/metr-rct.md#limits--say-these-before-someone-else-does)
- "Meeting transcription already records alignment" → [`docs/llm-as-mirror.md`](../docs/llm-as-mirror.md#the-objection-it-answers)
- "Isn't this just doing product properly?" → [`docs/shifts/01-split-the-role.md`](../docs/shifts/01-split-the-role.md#objections)
- "n=1 on your case study" → [`docs/thesis.md`](../docs/thesis.md#known-weak-points)

### Q11 — Recover the earlier preparation conversations ✅ Resolved 2026-08-24

Found. They were in **Claude Chat (claude.ai)**, not Claude Code — which is why the local
transcript search came up empty. Recovered and written up in [`history.md`](history.md):
the timeline, the four shifts that were replaced, what was cut and why, and the visual
identity fixed in May.

Three things came back that are worth acting on → **Q13**, **Q14**, **Q15** below.

Still missing: the rebuild itself — seven sections into four acts, and the shift replacement
— is in none of the recovered conversations. If you remember why, it belongs in
[`history.md`](history.md).

### Q12 — Is the deck's visual design settled? ✅ Largely, since May 2026

Palette and type were fixed during the first deck build and the current deck still uses them
(`#0E0E10` / `#F4F1EC` / `#D94F2A`, Georgia + Calibri). Recorded in
[`history.md`](history.md).

**One delivery item is genuinely open:** print the A4 backup sheet — section timings, the
five must-land lines, transitions. Decided in May, never done for the current 36-slide deck.
Ten minutes of work; it saves the talk if Presenter View fails on stage.

### Q13 — Stage the client's feedback instead of summarising it

Recovered from the April structure: the story was originally built around a specific moment,
the client saying in substance *that's not what I need from you.* The current deck says "I
built the wrong thing at record speed" — true, abstract, and it gives up the strongest beat
available in Act 2. Consider restoring the moment.

### Q14 — Does *"alignment has nowhere to live"* belong on a slide?

It was the runner-up title in April and never made it into the deck. Slide 16 currently takes
three sentences to say it. If the line is as good as it looked in April, it's a slide by
itself.

### Q23 — 🟠 The talk under-uses its best asset: the measurement was real

Act 4 says "I analysed every prompt I sent and every message I wrote." The REX shows what that
actually was, and it is far more substantial than the deck lets on:

- **2,194 prompts** (2 Feb → 9 Jul) and **793 messages** across 10 channels (3 Jan → 26 Jul)
- Two independent readings produced separately then crossed: **the factual** (3 git repos,
  tickets, ~30 written pages) against **the felt** (prompts and messages). *The places where
  they contradicted each other were the most instructive.*
- An **assertiveness ratio** — phrasings that commit versus phrasings that solicit. In
  February it measured **~10 in private working sessions and 0.14 in messages to the client
  the same month.**
- Documented limits: one month missing to a purged retention window, local history ending
  before the mission did, and a written-only corpus that cannot see what moved to video.

That February gap is the whole talk in one number: the same person, the same week, assertive
alone and deferential in front of the client. It is a better slide than "I analysed my
prompts", and the stated limits are what make it credible.

**Recommendation: put one of these numbers on a slide.** It turns Act 4 from an anecdote into
a method the audience could run on themselves on Monday — which is what the closing line is
asking of them.

### Q22 — 🟠 Slide 11 merges two different people

Slide 11 says *"A CEO who decides"*. In the field there were two distinct roles: the client
lead who commissioned and steered the work, and the **domain expert** whose financing
decisions were being automated — the one who applied the same rule differently from case to
case.

Merging them costs the story its mechanism. The interesting thing is not that a CEO was
inconsistent; it is that **the person whose judgement was being encoded was not the person who
had commissioned the encoding**, so nobody was positioned to notice the rule wasn't stable.

### Q16 — 🟠 The engineer moment and the founder moment were never written

Flagged in April, never done. The abstract promises to address "a PM, an engineer, or a
founder"; the deck has exactly one concrete human moment, and it's the PM one (the client's
feedback). An engineer sitting in that room has nothing to recognise themselves in.

The April note said what they should be: for **engineers**, that they're being asked to do
product work whether they signed up for it or not. For **founders**, the ratio math — your
org chart is already wrong.

Cheapest fix: one slide each in Act 3, attached to Shift 1 (which is where the role collapse
already lives). → [`origin-april-2026.md`](origin-april-2026.md)

### Q17 — 🟠 The talk is ~60% first-person. April said keep it to 30%

The April warning: over-index on the field story and the talk becomes a case study instead of
an industry thesis. The cold open, Act 2 and Act 4 are all first-person — roughly 60% of the
slides.

**Not necessarily wrong.** The external evidence in Act 1 carries the general claim, and Act 4
is the best material in the talk precisely because it's personal. But the ratio drifted by a
factor of two without anyone deciding to let it, and a room expecting an industry thesis can
feel a case study coming. Worth one deliberate look. → [`origin-april-2026.md`](origin-april-2026.md)

### Q15 — Does the talk need the recovery, not just the failure?

The April structure had a Q1→Q2 arc: stopped building, started orchestrating a hybrid
human/AI system. The current deck diagnoses the failure and never shows what came after.
Defensible — an unresolved failure is more honest, and the four shifts *are* the resolution —
but it should be a deliberate choice rather than an omission.
