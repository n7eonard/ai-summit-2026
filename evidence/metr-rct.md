# METR — randomised controlled trial on developer productivity

**Supports:** C4 · **Slide:** 8 · **Verified:** 2026-08-24

## The claim

Experienced developers **forecast +24%**, **self-reported +20%**, and were **measured 19%
slower** when allowed to use AI tools.

## Primary source

**"Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity"**
— METR, 10 July 2025. arXiv: [2507.09089](https://arxiv.org/abs/2507.09089)

## Method

- **16 experienced open-source developers**, working in **their own repositories**
  (averaging 22k+ stars, 1M+ lines of code), with ~5 years of contribution history on them.
- **246 real tasks**, randomly assigned to *AI allowed* or *AI disallowed*.
- Typical tooling in the AI-allowed condition: **Cursor Pro with Claude 3.5 / 3.7**.
- Outcome measured as **actual task completion time**, not self-report.

The design is what makes it worth putting on a slide: randomised, on real work, in codebases
the participants already knew deeply — the conditions most favourable to a genuine measurement
and least favourable to a flattering one.

## What to say about it on stage

**The −19% is not the point.** The point is the **~39-point gap** between the +20% they
experienced and the −19% that happened. Tooling that changes your output while simultaneously
breaking your ability to perceive your output is a different kind of problem from tooling
that's merely slower, and it is the one the talk is about.

## Limits — say these before someone else does

- **n=16.** Small. The effect is significant in the study's own analysis, but this is one
  trial, not a literature.
- **Early-2025 tooling.** Claude 3.5/3.7-era Cursor, not 2026 agents. The expected objection
  is "the models moved on," and it's fair on the −19%.
  **The perception gap is the part that doesn't age**: nothing about a better model repairs a
  broken self-assessment instrument, and a more capable, more autonomous tool plausibly widens
  the gap rather than closing it. That's the line to hold.
- **Experienced developers in familiar codebases** — arguably the population *least* likely
  to be sped up, since their baseline is highest. Generalising to junior developers or
  unfamiliar code is not supported.

## Links

- [Paper — arXiv:2507.09089](https://arxiv.org/abs/2507.09089)
- [METR blog post](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/)
- [METR announcement thread](https://x.com/METR_Evals/status/1943360399220388093)
