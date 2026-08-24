# Open questions

Things this repository cannot resolve on its own. Ordered by how much damage they do if left
open until September.

**Legend:** 🔴 blocking · 🟠 should be resolved · 🟡 nice to have

**Status 2026-08-24:** Q1, Q2, Q11, Q12 resolved · Q3 policy set, two speaker actions remain ·
Q13–Q17 opened by the recovered history. **Q16 is the most actionable of them.**

---

## 🔴 Blocking

### <a id="agent-count"></a>Q1 — How many agents? ✅ Resolved 2026-08-24

**Answer: 10+.** The deck rounded up. Everything in this repository now says 10+.

**⚠️ One action remains:** the live deck still shows *14* on slide 2. Edit it.
→ [`deck/README.md`](../deck/README.md)

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
