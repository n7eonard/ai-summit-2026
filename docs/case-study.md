# The field case — judge and party

> Seven months as the person who built **and** the person who decided what to build.
> Not a mission report. Only the parts that bear on the talk's claim.

## The relevance filter

Everything below has to answer one question:

> **Does this illuminate what happens when deciding-what-to-build and building collapse into
> the same person — and what to do about it?**

The underlying mission produced plenty of good product work that fails that test: a pivot on
data quality, a convergence engine, evaluation systems, a handover. Real, and out of scope.
It lives in a private retrospective and it stays there. This page was over-stuffed with it on
2026-08-24 and cut back the same day. → [`meta/decisions.md`](../meta/decisions.md)

## The vantage

**Twelve years doing product management**, where deciding and building were separated by other
people, meetings, and time. Then **seven months (January–July 2026)** as a solo product
builder in an AI proptech startup: freelance, Claude Code as the working environment, 10+
production agents shipped alone.

The second is what makes the talk possible, but only because of the first. Anyone can describe
a role collapsing; describing what it collapsed *from* takes having worked the separated
version for a decade.

> ⚠️ **The twelve-year half is missing from this repository.** It's half the stated vantage and
> nothing here documents it. → [Q24](../meta/open-questions.md)

**Mandate:** automate the analysis of incoming financing projects, to clear a bottleneck
observed on the analysis step. Note the irony that the talk is built on: I was hired to remove
a bottleneck, and became one of a different kind.

> **On naming.** The company and the people are not named here. What follows is about a
> structural failure mode and about my own errors inside it.
> → [`meta/open-questions.md`](../meta/open-questions.md#naming)

---

## Situation 1 — I was the only person who could challenge the bet, and I was busy executing it

The brief was clean: there is an expert, the expert has rules, the queue is longer than his
hours. Encode the rules.

**That bet contained an unstated assumption** — that the rules existed in stable form, and
that the expert's job was applying them rather than producing them.

In a separated setup, someone would have questioned that assumption out loud, because
questioning it would have been their job and building would not. Here both jobs were mine, and
only one of them produced something by the end of the day. It took six to seven weeks to see
that the bet was wrong.

**What it looks like from inside:** not doubt suppressed, doubt never scheduled. I wasn't
ignoring the question. I was never in a mode where the question came up.

## Situation 2 — the decision I was automating did not exist in a stable form

He applied the same rule **differently** from one case to the next.

Not carelessly. He was weighing things that were real and that he had never had to name,
because the weighing had only ever needed to survive contact with himself. Asked to state the
rule, he stated a rule. Watched across cases, he was running something richer than the rule he
stated.

> **You cannot automate a decision your expert can't state twice the same way.**

**Why this belongs in this talk and not in a product post-mortem:** it is the precise point
where the deciding layer proves unautomatable. Not because the model is too weak — because
there is no stable artefact to learn from. And I was the only one positioned to notice, since
I was the one watching case after case go through.

I doubted for several weeks that we could ever align everyone behind one set of rules. **I did
not say so.** That is the mechanism, not a personality flaw: the person building has the worst
possible standing to announce that the thing being built may be wrong.

**Note for the deck:** the person who commissioned the work and the expert whose judgement was
being encoded were **two different people** — which is exactly why nobody was positioned to
notice the rule wasn't stable. Slide 11 merges them and loses the mechanism.
→ [Q22](../meta/open-questions.md)

## Situation 3 — being both roles means nobody contradicts you

On 1 April the expert said, in substance, *"what's been built is amazing."* He was not using
it. He was still doing the work by hand, on his own separate tool.

Praise and non-use, same person, same week.

**The judge-and-party version of this:** when the builder and the decider are one person,
there is nobody whose job is to disbelieve the enthusiasm. Feedback given in a weekly is cold,
reconstructed and public — so it gets softened out of regard for the person who has been
building for months. I ran six months on declared enthusiasm with nothing instrumented.

**The metric that lied:** coverage looked like progress. Fourteen active rules. Validated: zero.
Average relevance 35%. Coverage climbed while value stayed flat — and coverage was the number
a builder naturally watches.

> On an internal tool automating a decision process, **coverage is a fake metric. Trust is the
> real one.**

## Situation 4 — the highest-output week was the week I pushed back least

February. No deadline, no plan, record production.

Measured, not remembered: an **assertiveness ratio of ~10 in my private working sessions
against 0.14 in my messages to the client**, in the same month. Same person, same weeks,
seventy-fold gap.

**When legitimacy isn't secured on the ground of opinion, it goes looking for it on the ground
of output.** Building is measurable, immediate, and nobody argues with it — which is exactly
what makes it a good place to hide.

Across the seven months, value produced and relationship quality never moved together. There
was no phase before the sixth month where both were good at once.

**The distinction that keeps this from being a confession.** Later in the mission, choosing to
build rather than to sync was an explicit call taken jointly against a hard deadline — and it
was right. Early on it was avoidance. **The two produce exactly the same observable
behaviour.** Neither priced the cost of the isolation. Choosing to build is legitimate; not
attaching a review gate to that choice is not.

## Situation 5 — a machine said the thing neither of us would say

End of March. Weeks of unspoken tension. The client ran an LLM over the transcripts of our
recent syncs and sent me the readout.

It was cold, and that was the point. Two people who have spent weeks not saying something
cannot be the ones to say it — anything either says arrives carrying the accumulated tone. The
model had no stake and no interest in being liked.

**There is a before and an after.** Assertiveness recovered, convictions came back, the work
got better.

**This is not the epilogue of the story — it is the intervention that turned it around.**
The deck currently stages it as a late reflection. → [Q20](../meta/open-questions.md)

---

## What worked

Only the things that bear on the claim.

- **An outside instrument, applied to the relationship rather than the codebase.** It did not
  create alignment. It made the misalignment visible, which is the achievable version.
- **Holding "no iteration without measurement"** — including against a direct request from the
  CEO. The one place where the decider in me beat the builder in me, and it held.
- **Writing positions down.** Every time I shared a piece of a document, it produced a useful
  discussion. The artefact was never the problem.

## What didn't work

- **Waiting for the client to open the conversation.** The readout should have been my move,
  weeks earlier. I had the discomfort; I let someone else schedule it.
- **Leaving convictions in documents and never forcing them out loud.** For five months my
  positions lived in files I wrote but didn't defend in the room. What eventually unblocked my
  speech wasn't a decision of mine — a channel appeared, freelancers arrived, an end date made
  disagreement cheap. The conditions came to me. I never went looking for them.
- **Never asking the question directly:** *what am I actually expected to do here, and what am
  I not doing?* Seven months left ample time. A vague mandate is a normal freelance starting
  condition; clarifying it is part of the job.
- **Measuring adoption far too late.** Not a tooling failure — a consequence of being the only
  one watching, and watching the wrong number.

## The correction we landed on

Agreed with the client at the end: not "be more assertive" — **a pair rather than a single
role.** One clearly a builder, one on product and strategy. I would then have been expected on
a known perimeter, and could have taken the place he was actually hoping for.

He generalised it to the whole company: stop mixing roles, give squads distinct perimeters.
The mixing suited 0→1 and stops suiting what comes next.

> **A role you don't split splits itself** — by default, toward whatever the person is best at.

## Honesty notes

- **n=1.** One mission, one client, one domain. An existence proof of a failure mode, not a
  measure of how common it is. The twelve-year PM half is what generalises it, and it is not
  yet written down.
- **Not a complaint about anyone.** The client is the one who handled the misalignment better
  than I did — he ran the readout that unblocked it.
- **The failure is not "I built the wrong thing at record speed."** The client disputes that
  framing, and he has a case. The defensible sentence is *it took six to seven weeks to see
  that the bet was wrong, and I was the only one placed to see it.*
  → [Q21](../meta/open-questions.md)
