# How this talk got here

Recovered 2026-08-24 from the preparation conversations. They were in Claude Chat
(claude.ai), not Claude Code — which is why the first search of local transcripts came up
empty. The source conversations are private; what matters from them is below.

This file exists because the talk changed shape substantially between April and August, and
the reasoning behind those changes was about to be lost. Knowing what was tried and dropped
is what stops it being re-tried.

---

## Timeline

| When | What happened |
|---|---|
| **Dec 2025** | Earliest thinking on PM workflow under AI. Pre-dates the talk |
| **7 Apr 2026** | Origin. Framing for the AI for Builders track, title options, first structure, **first set of four shifts** |
| **30 Apr 2026** | Speaker profile and positioning rewritten for the conference |
| **2 May 2026** | **First deck built** — 26 slides, PPTX, 7 sections. Visual identity fixed here |
| **Jun 2026** | Design and role-archetype work continues around the deck |
| **~Jul–Aug 2026** | Rebuild into the current 36-slide, four-act Google Slides deck |
| **24 Aug 2026** | This repository |
| **24 Aug 2026 (later)** | Working sessions switch from Claude Code to Grok. Same library, same rules. |

---

## What changed, and why it matters

### The four shifts were completely replaced

This is the biggest single change, and nothing recorded the reasoning.

**April version — organisational advice, aimed at PMs:**
1. Rethink your ratios — if your engineers use Claude Code seriously, PM coverage is already underwater
2. PMs: ship code, or hire PMs who do — you can't challenge what you can't read
3. Invest in alignment rituals as the real moat — the 30-minute kickoff is infrastructure, not overhead
4. Audit the gap between what you're building and what you should be — ask the client question once a quarter

**Current version — failure modes, aimed at anyone building:**
1. Split the role before it splits itself
2. Instrument adoption on day one, not month six
3. Make the disagreement visible before you make the thing
4. Freeze the surface so people can build habits

**What the change accomplished.** The April set is advice about *org design* and only fully
lands for someone who controls headcount. The current set is *failure modes* anyone in the
room can recognise from their own week. Shift 3 is the only real survivor — April's
"alignment rituals" became "make the disagreement visible", which is the same idea stated as
a consequence instead of a ceremony.

It also stopped being a PM talk. April addressed PMs and told engineers they were being
deputised; the current version addresses whoever is doing the deciding, which is the more
honest framing given the speaker was both.

**Still worth revisiting:** April's shift 2 — *you can't challenge what you can't read* — is
sharp and has no equivalent in the current deck.

### The title moved twice

April generated four options. The recommendation at the time was
*"I Shipped 14 AI Agents Alone. That's Not the Interesting Part."* — chosen for making the
speaker unmistakable. The runner-up thesis line was *"Alignment Has Nowhere to Live"*.

The final title is neither. It states the thesis in full and drops the personal credential
into slide 2 instead — which keeps the hook while letting the title tell a passing CPO
whether to walk in.

*"Alignment has nowhere to live"* never made it onto a slide. It is arguably still the best
line the preparation produced. Slide 16 says the same thing in three sentences.

### Material that was dropped

Worth knowing about, because some of it is strong:

- **The client's actual feedback.** The April structure was built around a specific moment:
  the client saying, in substance, *that's not what I need from you.* The current deck states
  the failure abstractly ("I built the wrong thing at record speed") and never stages the
  moment. **The concrete version is better** and it belongs somewhere in Act 2.
- **The Q1→Q2 arc.** April had a resolution: stopped building, started orchestrating — a
  hybrid human/AI system, supervising extraction agents, working with freelancers, holding
  the vision. The current deck diagnoses the failure and never shows the recovery.
  → open question: does the talk need it, or is the unresolved version stronger?
- **The named agents.** OSINT reputation, valeur vénale, track record, rules engine, scoring.
  Concrete proof of the credential, currently reduced to a count.
- **Brian Chesky was half right.** A whole section arguing the spec-writing PM is over but the
  discipline matters more than ever. Cut — probably correctly, it's a different talk.
- **Market-signal slides.** Comp ceilings, share of open roles. Cut, and rightly: sourcing was
  shaky and the Anthropic/METR figures do the work better.
- **Anthropic growth-team anecdotes**, including "60–80% of projects ship with no PRD" and a
  second-hand line about six stakeholders being impossible to align even with AGI. Cut for
  sourcing reasons — they came via a named individual and were never traced to a citable
  source. Correct call; see the sourcing rule in [`../evidence/README.md`](../evidence/README.md).

### What was added late — and is the best part

Act 4 does not exist in any April or May version. The client's cold LLM readout, the
self-analysis of the prompt log, *my highest-output week was the week I pushed back least* —
all of it arrived after the mission ended in early August.

That's not incidental. Act 4 could only be written once the mission was over and the
post-mortem had been done. It's the newest material and the least rehearsed.

### The visual identity was fixed in May and still holds

Set during the first deck build, and the current deck still uses it:

| Token | Value |
|---|---|
| Background | near-black `#0E0E10` |
| Foreground | warm off-white `#F4F1EC` |
| Accent | burnt orange `#D94F2A` |
| Headers | Georgia (serif, opinionated) |
| Body | Calibri |

Stated intent: builder/editorial, not consultancy. Oversized numerals on section dividers,
heavy whitespace, one idea per slide, no decorative chrome. The current deck's numbered
dividers (01–04) descend directly from this.

### Delivery decisions already made in May

- **Presenter View, not single-screen.** The deck was built with speaker notes carrying the
  script; they only work in dual-screen mode. Confirm the AV setup on site.
- **Print an A4 backup.** One page: section timings, the four or five quotable lines,
  transitions. Ten minutes of work, saves the talk if Presenter View fails on stage.
  **Not yet done for the current 36-slide deck.**

---

## What is still not recovered

The rebuild itself — April/May's seven sections into the current four acts, and the shift
replacement — is not in any conversation found. It happened either directly in Google Slides
or somewhere not indexed by search. The reconstruction above is inferred from the before and
after, not from a record of the decision.
