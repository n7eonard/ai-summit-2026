# Sources swept

An auditable answer to "have we got everything?". Swept **2026-08-24**.

Every source checked, what came out of it, and — as importantly — **what could not be
reached.** If a claim in this repo has no source here, it has no source.

---

## Method

Not a keyword hunt. The full conversation corpus was crawled and scored, so a relevant
conversation that never says "AI Summit" still surfaces.

| Source | Coverage | Result |
|---|---|---|
| Claude Code local transcripts | **100%** — all 4 files on disk | Nothing. The talk was never worked on in Claude Code |
| Claude Chat, personal org | **100% — 324/324 conversations**, full text, 2.9M chars, 0 failures | 201 scored non-zero; 15 genuinely relevant |
| Claude Chat, Experimenta org | **0% — HTTP 403** | ⚠️ **Unreachable.** See gaps below |
| Claude Chat projects | 5 projects, doc lists pulled | Nothing relevant. *Content Experimenta* holds no documents |
| Notion workspace | Searched | **The single richest source found.** See below |
| Google Drive | The deck only | Deck transcribed to [`../deck/slide-by-slide.md`](../deck/slide-by-slide.md) |

---

## The decisive find

**"REX 7 mois de mission"** (Notion) — a personal retrospective on the whole mission, written
before the client debrief of 28 July and completed after it with the client's own feedback.

It is more precise than anything in the deck, and it is **where the current four shifts
actually come from** — each one appears in it, nearly verbatim, as a learning. This closes the
question the repo could not previously answer.

It also **contradicts several things currently on slides.** All of it is recorded in
[`open-questions.md`](open-questions.md) as Q18–Q23.

**Not reproduced here.** The REX contains the client's candid self-assessment and a great deal
of relational detail about named people. The structural learnings, the corrected facts and the
method are carried into this repo; the personal and relational content is deliberately left out
of a public repository. It stays in Notion.

---

## Conversations that matter

Ranked by relevance. Dates are last-activity.

| Conversation | Date | Why it matters | Read |
|---|---|---|---|
| PM leverage in the age of AI engineering | 7 Apr | **The origin.** → [`origin-april-2026.md`](origin-april-2026.md) | ✅ full |
| I'm brainstorming around the t… | 2 May | First deck (26 slides, PPTX). Visual identity fixed here | ⚠️ partial |
| Former les équipes tech au product management | 19 Apr | Market evidence for the thesis; the *chimera role* framing | ✅ excerpts |
| Brief de réunion de fin de mission | 28 Jul | Preparation for the debrief that produced the REX | ✅ excerpts |
| Reframing speaker profile | 30 Apr | Speaker positioning and bio | ❌ |
| Reflecting on three years of experimental work | 3 Jun | Experimenta positioning | ❌ |
| Understanding harness engineering | 7 May | Harness quality as leverage | ❌ |
| *[client strategy conversation]* | 25 Jun | Client context and direction | ❌ |
| Architecture et plan d'exécution des agents IA | 16 Mar | The actual agent build | ❌ |
| Évolution du processus de réflexion en tant que PM builder | 16 Mar | On-theme | ❌ |
| Collaboration et charge mentale | 17 Apr | Adjacent | ❌ |
| Évaluation de la proposition freelance extraction | 27 Mar | The freelancer arrangement | ❌ |
| Product management in an agentic future | 19 Mar | Pre-dates the talk, same thesis | ❌ |
| Tech companies building coding agents | 6 May | Bottleneck-moves framing | ❌ |
| PM workflow transformation with AI | 20 Dec 2025 | Earliest trace of the thesis | ❌ |

The unread ones are **adjacent, not load-bearing**: no claim currently in this repo depends on
any of them. They were scored on full text, so their relevance is measured, not guessed.

---

## Gaps — the honest part

**1. The Experimenta organisation is unreachable.** `HTTP 403` from this session. If any talk
preparation happened under that org rather than the personal one, it has not been swept and
this document does not cover it. **This is the one real hole.** Worth ten minutes: switch org
in claude.ai and search there directly.

**2. The May 2 conversation is still only partly read.** It built the first deck. The visual
identity and the delivery decisions were recovered from it; its earlier half was not.

**3. Notion is searched, not swept.** The workspace was queried for the talk and the mission
and returned the REX. It was not enumerated. A page that names neither could still exist, and
the client database in particular holds more than the REX.

**4. Nothing outside these systems was touched.** Slack, Linear, the three git repos and email
were never opened. The REX itself was built from Slack and prompt logs, so their substance is
captured second-hand through it — but the primary sources are unread.

**5. The corpus is written only.** As the REX notes, part of the disagreement moved to video
calls. That is unmeasurable and always will be.

---

## Standing answer

**Within the personal Claude Chat org and the Notion pages that name the talk or the mission:
yes, this is complete.** Outside it — the Experimenta org above all — no, and the list above
says exactly where.
