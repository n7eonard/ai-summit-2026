# Decisions log

Choices made while building this library, and why. New entries go on top.

---

## 2026-08-24 — Anonymisation, and the agent count

**The client company, its CEO and the domain expert are not named in this repository.**
The field material is critical — an expert who couldn't state his own rule twice the same
way, six weeks of unspoken tension — and a public, indexed repo attaching that to a named
company and a findable person is a different act from saying it once from a stage. The
argument loses nothing: "an AI proptech startup, real-estate financing" carries the whole
story. Residual exposure via the published abstract is flagged as a speaker decision.
→ [Q3](open-questions.md#naming)

**Agent count settled at 10+**, matching the submitted abstract. The deck rounded up to 14
and needs correcting. Under-claiming against your own abstract costs nothing; being caught
over-claiming in the first ninety seconds of a talk about intellectual honesty would cost
the whole room. → [Q1](open-questions.md#agent-count)

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

**Earlier preparation conversations are not locally recoverable.** Searched all Claude Code
transcripts in `~/.claude/projects/` — no session mentions the talk. They were almost
certainly claude.ai web chats, stored server-side. The deck itself is the surviving artefact
of that work, and this repository reconstructs the reasoning around it rather than recovering
it. → Q11.
