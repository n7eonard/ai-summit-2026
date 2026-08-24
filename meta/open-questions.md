# Open questions

Things this repository cannot resolve on its own. Ordered by how much damage they do if left
open until September.

**Legend:** 🔴 blocking · 🟠 should be resolved · 🟡 nice to have

---

## 🔴 Blocking

### <a id="agent-count"></a>Q1 — How many agents? ✅ Resolved 2026-08-24

**Answer: 10+.** The deck rounded up. Everything in this repository now says 10+.

**⚠️ One action remains:** the live deck still shows *14* on slide 2. Edit it.
→ [`deck/README.md`](../deck/README.md)

### Q2 — What is the slot length?

Not recorded anywhere. Everything about pacing depends on it, and 36 slides behaves very
differently at 15, 20 and 30 minutes. Also: is there a Q&A, and how long?

Act 4 is the first casualty of a short slot, and it's the part that shouldn't be cut. If the
slot is 15 minutes, Act 1 gets compressed instead — see
[`docs/narrative.md`](../docs/narrative.md#timing).

**Needed from:** the conference. **Blocks:** all timing work, rehearsal.

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

### Q11 — Recover the earlier preparation conversations

Prior talk-prep sessions exist but are **not** in local Claude Code history (searched
2026-08-24: no session in `~/.claude/projects/` mentions the talk). They were almost certainly
in claude.ai web chats, which are stored server-side and can't be searched from here.

If they're found, the reasoning behind choices already made — why these four shifts and not
others, what was cut — should be captured in [`decisions.md`](decisions.md). Right now that
file records only what was decided while building this repository.

### Q12 — Is the deck's visual design settled?

This repo covers content only. Typography, colour, and the section-divider treatment are
untouched here.
