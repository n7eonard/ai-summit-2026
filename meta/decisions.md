# Decisions log

Choices made while building this library, and why. New entries go on top.

---

## 2026-08-24 (late) — Shift 4 dropped

*Freeze the surface so people can build habits* is out. It was the only one of the four that
would have sat just as well in a talk about something else — change management, not the
collapse of deciding into building. Applying the relevance filter to the talk's own contents,
not only to incoming material.

The page is kept, marked retired; the deck loses slides 26–27 and gains ~70 seconds. The slot
is deliberately left open rather than backfilled in a hurry → Q26. The published abstract
promises four, which is now a decision to make rather than a fact.

**Three that all land beats four where one is off-topic.**

---

## 2026-08-24 (late) — A relevance filter, after importing the wrong thing

**What went wrong.** The mission retrospective was found and treated as a source to mine
rather than a source to filter. Its own criterion is *what happened on this mission*; the
talk's is *what does this say about deciding and building collapsing into one person*. A
large amount of product-operational detail — a data-quality pivot, a convergence engine,
evaluation systems, handover preparation — was written into the repo. All true. None of it
serves the claim.

**The filter is now stated in [`../AGENTS.md`](../AGENTS.md)** and applied. Test for anything
coming from that retrospective: *would this still be true and interesting if the mission had
been in a different industry solving a different problem?* If not, it is mission detail.

**[`../docs/case-study.md`](../docs/case-study.md) was rewritten** around the actual vantage —
judge and party — and organised as five situations plus what worked and what didn't, which is
the shape the talk delivers. The mission-operational material was cut, not moved: it already
exists in the private retrospective.

**A gap the import concealed:** the repo documents only the seven months. The twelve years of
product management — the separated version the talk is contrasting against — are nowhere.
That is half the vantage and only the speaker has it. → Q24.

**Also opened:** honest doubt about whether Shift 4 still belongs, since it is the one that
doesn't connect to the collapse. → Q25.

---

## 2026-08-24 — Working sessions continue in Grok

The library was bootstrapped in Claude Code. From this point, preparation continues in Grok
against the same remote (`n7eonard/ai-summit-2026`), with the same house rules.

**[`AGENTS.md`](../AGENTS.md) is the single source of the working notes**, and the only one.
It was briefly duplicated into a `CLAUDE.md` with a "keep them in sync" rule; that lasted less
than a day before the two drifted — one file gained a pointer, a stale line survived in the
other. Duplicated house rules drift silently, which is the worst way for a rule to fail, so
`CLAUDE.md` was deleted outright rather than kept as a stub.

**Known trade-off:** a Claude Code session opening this repo no longer auto-loads the house
rules, because `AGENTS.md` is not read automatically the way `CLAUDE.md` was. Anyone starting
a Claude session here should be pointed at `AGENTS.md` explicitly. Accepted deliberately —
Grok owns this repo.

Same principle for anything added later: point at `AGENTS.md`, don't copy it.

Nothing about the argument, the evidence bar, or the anonymisation policy changes.

---

## 2026-08-24 — History recovered, timing fixed

**The preparation history is now a first-class file**, not a footnote.
[`history.md`](history.md) records what the talk used to be: a different set of four shifts,
a different title, a 26-slide deck, and a body of material that was cut. Kept because the
talk changed shape substantially and none of the reasoning was written down — knowing what
was already tried and dropped is what stops it being re-tried.

**Timing built around 20 + 5.** [`docs/narrative.md`](../docs/narrative.md#timing) now carries
a per-act allocation, an explicit *cut order* for overrunning, a list of five slides that must
never be cut, and two beats that need silence. A talk plan without a cut order isn't a plan —
it just fails at whichever slide the clock happens to run out on.

---

## 2026-08-24 — Anonymisation, and the agent count

**The client company, its CEO and the domain expert are not named in this repository.**
The field material is critical — an expert who couldn't state his own rule twice the same
way, six weeks of unspoken tension — and a public, indexed repo attaching that to a named
company and a findable person is a different act from saying it once from a stage. The
argument loses nothing: "an AI proptech startup, real-estate financing" carries the whole
story. Residual exposure via the published abstract is flagged as a speaker decision.
→ [Q3](open-questions.md#naming)

**Agent count settled at 10+**, matching the submitted abstract; the deck still says 14 and
needs the edit. Under-claiming against your own abstract costs nothing; being caught
over-claiming in the first ninety seconds of a talk about intellectual honesty would cost the
whole room. → [Q1](open-questions.md#agent-count)

*Correction, later the same day:* the recovered history shows **14 was the original working
figure**, used consistently from April — including in a candidate title. The deck did not
round up; the submitted abstract was deliberately conservative. The 10+ decision stands, and
the reason is now the better one: it's the number that was published.

---

## 2026-08-24 — Repository bootstrapped

**Structured as a tool's documentation, not as a blog.** Requested explicitly. The consequence
that matters: nothing is written to be read front to back, everything is written to be
arrived at from a link, and each file states its own context. Costs some repetition. Worth it.

**Written in English.** The talk is in English at an international conference and the repo is
public for that audience. *(Assumption — flag if wrong; working conversation stays in French.)*

**Evidence separated from argument.** `evidence/` holds sources with their caveats;
`docs/` holds the argument. A talk claiming *we've lost the ability to judge our own output*
cannot have loose sourcing — the form has to match the argument. Hence the claims ledger, and
hence writing down the objections before anyone raises them.

**Shifts written failure-mode-first.** Each of the four opens with what breaks, not with the
advice. Readers recognise a failure they're living faster than they recognise advice they
should take, and the talk's audience is specifically people who *are* living this.

**Weak points documented, not hidden.** `docs/thesis.md` ends with the arguments against the
talk. In a public repo attached to a talk about intellectual honesty, hiding them would be
the actual credibility risk.

**CC BY 4.0.** Content meant to be reused and cited.

---

## Content findings from the bootstrap pass

**Anthropic undercuts its own 8×.** The June 2026 report calls the figure "almost certainly
overstated," calls lines-of-code a vanity metric, and names *review* as the new bottleneck.
This was not in the deck. It is probably the strongest evidence in the talk for the thesis:
the most bullish dataset available says in its own footnotes that it can't cleanly judge its
own output. → open question Q6.

**Deck and abstract disagreed on the agent count** (14 vs 10+). Resolved same day in favour
of 10+; the live deck still needs the edit.

**The Andrew Ng quotation lacks a primary source.** Substance is well attested; the exact
wording, on a slide, attributed by name, is not yet traced to the original. → Q4.

**Earlier preparation conversations were not in Claude Code.** Searched all transcripts in
`~/.claude/projects/` — no session mentions the talk. **Later recovered from Claude Chat
(claude.ai)** and written up in [`history.md`](history.md). → Q11, resolved.
