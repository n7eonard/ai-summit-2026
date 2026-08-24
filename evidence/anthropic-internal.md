# Anthropic — internal engineering metrics

**Supports:** C1, C2, C3 · **Slide:** 6 · **Verified:** 2026-08-24

## The claims

| Figure | Detail |
|---|---|
| **8×** | Typical engineer merging 8× as much code per quarter as in the 2021–2025 baseline |
| **80%+** | Share of code merged into production authored by Claude, as of ~May 2026 |
| **74 in 52** | Product releases shipped in 52 days (≈1.4/day) |

## Primary source

**"When AI Builds Itself"**, Anthropic, published June 2026.

Reported detail: lines merged per engineer per day were **flat from 2021 through 2024**, then
began rising in 2025 after the Claude Code research preview in February. The 80% figure is up
**from low single digits** before that preview. The described change is in *kind*, not only
degree — from suggesting snippets a human copies, to running code, proposing and executing
experiments, and applying findings to the codebase directly.

## The caveat — and why it strengthens the talk

**Anthropic calls its own 8× figure "almost certainly overstated" and labels lines-of-code a
vanity metric.** It also notes that the bottleneck in its own software production shifted
from *writing* code to *reviewing* it.

Do not bury this. It is the best evidence in the talk for
[thesis §3](../docs/thesis.md#3-meanwhile-our-judgement-of-our-own-output-got-worse):

> The most bullish dataset available on AI engineering output says, in its own footnotes,
> that it can no longer cleanly judge what it produced. And it names the new bottleneck as
> *review* — which is judgement, which is the thing that didn't scale.

Presenting the caveat yourself also inoculates against the obvious heckle ("that's a vendor
marketing its own product"), and it models the intellectual honesty the talk is arguing for.

## Sourcing status

- C1, C2 — reported consistently across independent outlets citing the June 2026 report,
  including the self-critical framing. Solid.
- C3 (74 releases / 52 days) — **secondary only so far.** Widely reported, attributed to a
  window of roughly 3 February – 24 March 2026, with a breakdown circulating as: developer
  tools 28, desktop automation 15, API and infrastructure 18, models and core platform 13.
  Treat the breakdown as unverified colour; do not put it on a slide. Finding Anthropic's own
  statement of the headline figure is an open task.

## Links

- [Anthropic says 80% of its new production code is now authored by Claude — VentureBeat](https://venturebeat.com/technology/anthropic-says-80-of-its-new-production-code-is-now-authored-by-claude-how-your-enterprise-can-keep-up)
- [Anthropic says Claude now writes more than 80% of its merged code — Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/anthropic-says-claude-now-writes-more-than-80-percent-of-its-merged-code)
- [Anthropic engineers ship 8X more code than last year — Crypto Briefing](https://cryptobriefing.com/anthropic-engineers-8x-code-claude/)
- [Claude Team is Shipping Like Crazy: 74 Releases in 52 Days — Product Compass](https://www.productcompass.pm/p/claude-shipping-calendar)
