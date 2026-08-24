# Open questions

Things this repository cannot resolve on its own. Ordered by how much damage they do if left
open until September.

**Legend:** 🔴 blocking · 🟠 should be resolved · 🟡 nice to have

---

## 🔴 Blocking

### <a id="agent-count"></a>Q1 — How many agents? 14 or 10+?

The deck (slide 2) says **14**. The submitted abstract says **10+**.

The number is the credential the entire cold open rests on, and someone in the room will have
read the abstract. Pick one and make it true everywhere. A specific number is stronger than a
floor, provided it's defensible — so if 14 is right, the abstract's "10+" is merely
conservative and there's no contradiction to worry about. If the deck rounded up, fix the deck.

**Needed from:** the speaker. **Blocks:** slide 2, `docs/case-bricks.md`, `talk/abstract.md`.

### Q2 — What is the slot length?

Not recorded anywhere. Everything about pacing depends on it, and 36 slides behaves very
differently at 15, 20 and 30 minutes. Also: is there a Q&A, and how long?

Act 4 is the first casualty of a short slot, and it's the part that shouldn't be cut. If the
slot is 15 minutes, Act 1 gets compressed instead — see
[`docs/narrative.md`](../docs/narrative.md#timing).

**Needed from:** the conference. **Blocks:** all timing work, rehearsal.

### Q3 — What can be said publicly about the client?

Act 4 tells a story about six weeks of unspoken tension with a named client, and about him
running an LLM over our private conversations. It's the best material in the talk and it is
about a real, identifiable person, on a public stage, in a public repository.

- Is "Bricks" nameable, or does it become "an AI proptech startup"?
- Has he been told the story is being told? Has he agreed?
- Same question for the expert in Act 2 — slide 13 says he applied his own rule
  inconsistently. Delivered as observation it's respectful. In a public repo with the company
  named, it's more exposed than that.

This is the one that can't be fixed the week before.

**Needed from:** the speaker, and probably a conversation with the client.
**Blocks:** Act 2, Act 4, `docs/case-bricks.md`, whether this repo stays public as written.

---

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

### Q7 — Tighten the Bricks timeline

`docs/case-bricks.md` has the shape but the phase boundaries are approximate. When did the
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
