# How the talk is built

Four acts plus a coda, 36 slides. The structure is locked; the wording is in revision.

## Shape

```
   COLD OPEN (1–4)     credential, then immediately undercut it
        │
   ACT 1 (5–9)         the compression is real          ← external evidence
        │
   ACT 2 (10–18)       what didn't compress             ← the field case
        │
   ACT 3 (19–27)       four shifts                      ← the payload
        │
   ACT 4 (28–35)       one more thing                   ← the turn
        │
   CLOSE (36)
```

## Act by act

### Cold open — slides 1–4

Earn the right to speak, then spend it immediately.

Slide 2 is the credential: *N production AI agents. 3 months. One person.* Slides 3 and 4
take it back before the audience has finished being impressed — the expert was still doing
it by hand, and *for six weeks I built the wrong thing at record speed.*

**Why this order.** The self-deprecating opening is a weaker talk. The audience needs to
believe you actually did the thing before your admission of failure carries any information.
The credential is not bragging, it's the setup for the cost of the admission. The tension
between slides 2 and 3 is the engine of the whole talk and it fires in the first ninety
seconds.

### Act 1 — the compression is real (5–9)

External, verifiable, not about me. Anthropic's numbers (8× / 80% / 74-in-52), the Brooks'
Law break — *an agent adds capacity without joining the conversation* — then METR: forecast
+24%, felt +20%, measured −19%.

Closes on the hinge of the talk: *Execution went up. Our ability to judge our own output went
down. That combination is the whole talk.*

**Why this order.** Establish the good news at full strength first, from sources hostile to
my thesis in the sense that they're the optimists' own numbers. Then the METR reversal lands
as a genuine surprise instead of as a bias I brought with me.

### Act 2 — what didn't compress (10–18)

Back to the field. The setup, the bet (*encode the rules*), the discovery (*he applied the
same rule differently from one deal to the next*), the generalisation (*you cannot automate a
decision your expert can't state twice the same way*), then the structural claim — six people
who disagreed, alignment with no corpus to learn from — and Andrew Ng arriving independently
at the same place from the other direction.

Closes: *The cost of building fell through the floor. The cost of being wrong didn't move.*

**Why this order.** Story first, principle second, then outside validation. If Ng comes first
it's an argument from authority. Coming last, he's corroboration for something the audience
has already watched happen.

### Act 3 — four shifts (19–27)

The takeaway payload. Each shift is one claim slide plus one sharp line.
Full versions in [`shifts/`](shifts/).

1. Split the role before it splits itself — *building is a good place to hide*
2. Instrument adoption on day one — *silence is the failure signal*
3. Make the disagreement visible before you make the thing — *the middle is where work dies*
4. Freeze the surface so people can build habits — *enables 100% of the job, worth zero*

**Why this order.** They're ordered by when they bite in a project's life, not by importance.
1 and 3 carry the weight; 2 and 4 are the ones people can implement on Monday, which is why
they sit between and after the hard ones.

### Act 4 — one more thing (28–35)

The turn. The client's cold readout, the self-analysis of my own prompt log, the finding
(*highest-output week = least pushback*), and the reframe: *an LLM won't create alignment, it
is very good at making your misalignment visible.*

Full version: [`llm-as-mirror.md`](llm-as-mirror.md).

**Why this exists at all.** Without it the talk is a diagnosis with four pieces of advice
attached — true, useful, and slightly deflating for a room full of builders. Act 4 hands them
something to *do with the tool they already have*, and it does it by conceding the strongest
objection to Act 2 rather than dodging it.

### Close — slide 36

*Anyone can build now. The scarce thing is saying it out loud: I think we're building the
wrong thing.*

## Timing

**Not yet allocated — this is a blocking open question.** See
[`meta/open-questions.md`](../meta/open-questions.md#slot). 36 slides is comfortable for 20
minutes at this density (short, declarative, low word count), tight for 15, and would need
material added for 30.

Rough proportions to hold whatever the slot:

| Act | Share | Note |
|---|---|---|
| Cold open | ~10% | Must not run long — the whole point is speed |
| Act 1 | ~20% | Evidence, can be compressed if needed |
| Act 2 | ~30% | The story. Protect this one |
| Act 3 | ~25% | Four shifts, roughly equal |
| Act 4 + close | ~15% | Do not rush the readout beat |

## Craft notes

- **One idea per slide, no bullets.** The deck is a rhythm instrument, not a document.
  Density belongs in this repo, which is why this repo exists.
- **The two hardest beats to deliver:** slide 13 (*he applied the same rule differently*) —
  must land as observation, never as blame; and slide 30 (*it was cold, that is exactly what
  we needed*) — the room will laugh, and the next line has to survive that.
- **Numbers on screen, never spoken as a list.** Say what they mean, let the slide carry the
  digits.
