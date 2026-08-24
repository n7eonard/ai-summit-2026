# The origin — 7 April 2026

The full record of the conversation the talk started from, recovered 2026-08-24.

Names are withheld here as everywhere in this repository: the client, the freelancer, and
the Anthropic staffer whose second-hand remarks seeded the early framing.

Read this before proposing a structural change. Most obvious ideas were had in April, and
several were tried and dropped for reasons worth knowing.

---

## The raw material brought to the table

The speaker arrived with an already-formed thesis and a set of second-hand observations about
Anthropic's growth team:

- **5 engineers now produce the output of 15–20.** PM and design productivity did not scale
  proportionally, so the ratio compressed.
- **Two organisational responses**: hire *more* PMs, and formally deputise product-minded
  engineers as mini-PMs for any project under two weeks of engineering time.
- **60–80% of that team's projects ship with no PRD.** Small work is kicked off in a Slack
  back-and-forth with engineers who push back; large work gets a 30-minute cross-functional
  kickoff (legal, safeguards, stakeholders) — to surface concerns early, not to produce a doc.
- **The joke that became the thesis**: even with AGI, aligning six stakeholders will still be
  impossible.
- And the line the whole talk grew from:

> *"alignment is the part llms can't automate because there's nowhere for alignment to
> actually live. It happens in slack threads and kickoff meetings and then evaporates."*

**All of this material was later cut**, because it was second-hand and traceable to a named
individual rather than a citable source. The published Anthropic and METR figures replaced it.
That was the right call — but note that the *thesis itself* came from here, not from the
figures. The figures were found afterwards to support a conclusion already reached.

## The four angles the speaker proposed

Written in his own words, before any framing:

1. **"Le PM builder : quand tu arrêtes de spécer et que tu livres."** The field credential —
   in 3 months, solo: an OSINT reputation agent, a property-valuation agent, a track-record
   agent, a business-rules engine, a scoring system. Built with Claude Code and Cursor, not a
   dev team. *A PM who ships production code is no longer a curiosity — it's an advantage.*
2. **"Le coût de build est à zéro. Le coût de build le bon truc est infini."** The counter to
   "the PM is dead". Lived directly: **90% of the time building, 10% thinking**, until the
   client said *that's not what I need from you.*
3. **"Le PM comme chef d'orchestre d'une équipe d'agents IA + freelances."** The Q1→Q2 pivot:
   from building personally to supervising extraction agents, iterating with a freelancer on
   data extraction, and holding the vision. Not coding, not speccing — orchestrating hybrid
   human/AI systems.
4. **"Brian Chesky avait tort et raison en même temps."** The 40-page-spec, Jira-grooming PM
   is over; the discipline matters more than ever. When build cost hits zero, *everyone* makes
   product decisions by default, and most do it badly.

**Survivors:** #2 is now the spine (slide 18). #1 survives as the cold open credential, with
the agents reduced to a count. **#3 and #4 were cut entirely.**

## Three framing choices made on the spot

| Question | Answer given |
|---|---|
| Which angle leads? | **The compression thesis** — engineering scaled, alignment didn't |
| What should the audience walk away *doing*? | **All four** of the proposed shifts |
| Who's in the room? | **Mixed / not sure** |

"Mixed" is the constraint that shaped everything after it: the talk has to land for an
engineer and a CPO in the same sentence. It still does.

## The original structure — 7 parts, ~20 min

| # | Part | Time |
|---|---|---|
| 1 | The hook — *"I built 14 agents alone. My client told me I was doing it wrong."* | 2 min |
| 2 | The compression — what's happening to teams | 4 min |
| 3 | Why alignment is the unautomatable layer | 3 min |
| 4 | What I got wrong — the builder-PM trap, and the Q1→Q2 pivot | 4 min |
| 5 | Brian Chesky was half right | 2 min |
| 6 | Four shifts for builders | 4 min |
| 7 | Closing line | — |

Candidate closing line, never used:

> *"The best builders I know in 2026 spend less time building than they did in 2024.
> That's not a paradox. That's the job."*

## The four original shifts

1. **Rethink your ratios.** If your engineers use Claude Code seriously, your PM coverage is
   already underwater. Either hire, or formally deputise. Don't pretend.
2. **PMs: ship code — or hire PMs who do.** Not because PMs should become engineers, but
   because *you can't challenge what you can't read.*
3. **Invest in alignment rituals as the real moat.** The 30-minute kickoff. The Slack thread
   with a product-minded engineer. Not overhead — the only place the unautomatable work
   happens. Treat them like infrastructure.
4. **Audit the gap between what you're building and what you should be.** Once a quarter, ask
   the client question: *is this what you actually need from me?*

Comparison with the current set and what the replacement accomplished:
[`history.md`](history.md#the-four-shifts-were-completely-replaced).

## Three warnings given in April — and what happened to them

**1. "Decide whether to name the Anthropic source."** ✅ Resolved by cutting the material
entirely and sourcing the claims from published figures. The sourcing rule in
[`../evidence/README.md`](../evidence/README.md) is the descendant of this warning.

**2. "Keep the field story to ~30% of stage time, or the talk becomes a case study instead of
an industry thesis."** ⚠️ **Not followed.** In the current deck the cold open, Act 2 and Act 4
are all first-person — roughly 60% of the slides. → **Q17**

**3. "Mixed audience means one concrete moment per persona. You have one for PMs. You need one
for engineers and one for founders."** ⚠️ **Never done.** The abstract still promises to
address "a PM, an engineer, or a founder", and the deck still has only the one moment.
→ **Q16**

## What the record shows about the title

Four options were generated. The final title is none of them — it states the thesis in full
and moves the credential to slide 2.

The recommendation at the time was: use *"I Shipped 14 AI Agents Alone. That's Not the
Interesting Part."* as the title, **and keep *"alignment has nowhere to live"* as the quotable
moment in the middle of the talk.** The first half was overtaken; the second half was simply
never done. The line is nowhere in the deck. → **Q14**
