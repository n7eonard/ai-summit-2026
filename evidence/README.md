# Evidence

Every external claim made on stage, traced to a primary source, with its caveats.

If you're checking a number from the talk, it's in the ledger below.
Claims about the Bricks mission are first-hand and live in
[`docs/case-bricks.md`](../docs/case-bricks.md) instead — they're testimony, not citation.

**Last verified:** 2026-08-24

## Claims ledger

| # | Claim on stage | Slide | Source | Status |
|---|---|---|---|---|
| C1 | 8× more code shipped per engineer, per quarter | 6 | [Anthropic](anthropic-internal.md) | ✅ Verified — **with a caveat the talk should use** |
| C2 | 80% of merged code authored by the model | 6 | [Anthropic](anthropic-internal.md) | ✅ Verified |
| C3 | 74 product releases in 52 days | 6 | [Anthropic](anthropic-internal.md) | ⚠️ Verified, secondary sourcing — see file |
| C4 | Forecast +24%, self-reported +20%, measured −19% | 8 | [METR](metr-rct.md) | ✅ Verified, primary (peer-reviewable preprint) |
| C5 | "I don't see product management work becoming faster at the same speed as engineering" | 17 | [Andrew Ng](andrew-ng-pm-ratio.md) | ⚠️ Substance verified, **exact wording needs primary check** |
| C6 | One of Ng's teams asked for two PMs per engineer | 17 | [Andrew Ng](andrew-ng-pm-ratio.md) | ✅ Verified |
| C7 | For fifty years, more output meant more people | 7 | Brooks, *The Mythical Man-Month* (1975) | 📎 Framing, not a cited statistic — see below |

**Legend:** ✅ verified against a primary or near-primary source · ⚠️ verified in substance,
sourcing or wording needs one more pass · 📎 rhetorical framing, no citation claimed

## Note on C7

"For fifty years, more output meant more people; more people meant more communication" is
Brooks' Law as common ground, not a statistic being asserted. No slide puts a number on it.
It's listed here so that nobody in the Q&A can claim the talk smuggled in an unsourced
figure — it doesn't, and this line is the reason to be sure.

## Two open sourcing tasks

1. **C5 — get the Ng quote from the primary.** The substance is well attested across
   secondary coverage, but a direct quotation on a slide needs the original (*The Batch*
   issue, or the talk/interview it came from). Currently sourced from commentary about it.
   → [`meta/open-questions.md`](../meta/open-questions.md)
2. **C3 — find Anthropic's own statement of the 74/52 figure.** Widely reported and
   internally consistent with C1/C2, but every source found so far is secondary.

## Standing rule for this repo

If a number goes on a slide, it gets a row in this table and a file in this directory,
including the caveats that weaken it. A talk that argues *we've lost the ability to judge our
own output* cannot afford to be sloppy about its own evidence — the form has to match the
argument. Every objection is written down here before it's raised from the floor.
