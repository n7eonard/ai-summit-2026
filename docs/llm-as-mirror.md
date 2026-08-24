# One more thing — point it at your transcripts, not your codebase

**Slides:** 28–35 · **Evidence:** field

This is the closing act, and it does something specific: it takes the strongest objection to
the talk and turns it into the last idea.

## The objection it answers

Through the whole talk I claim alignment can't be automated — it lives in Slack threads and
hallway conversations, it's never written down, there's no corpus. Someone in the room is
already thinking: *transcription tools record exactly those conversations now.*

They're right about the recording. The claim survives anyway, and here's the seam:
**an LLM will not create alignment. It is very good at making your misalignment visible.**

Those are different jobs. The first one is what people hope for and won't get. The second is
available today, undersold, and uncomfortable enough that almost nobody does it.

## What happened

Six weeks of tension between me and my client. Neither of us said it out loud.

He fed our transcripts to an LLM and sent me the readout.

**It was cold. That is exactly what we needed.** The coldness was the feature. Two people who
have spent six weeks not saying a thing to each other cannot be the ones to say it — anything
either of us said would have arrived carrying six weeks of accumulated tone. The model had no
stake, no history, and no interest in being liked. It just described what was in the record.

That is the whole mechanism: not intelligence, *disinterest*. A mirror that doesn't flinch.

## Then I did it to myself

To write my own post-mortem, I didn't trust my memory. I analysed every prompt I sent and
every message I wrote.

Memory is not a neutral record of a project — it is a story you have been rehearsing, and it
was written by the person who most needs to come out of it well. The prompt log wasn't. It's
a timestamped, un-curated trace of what I actually thought was worth doing, hour by hour, and
it does not know it's being read.

What it gave me was the sentence I would never have retrieved on my own:

> **My highest-output week was also the week I pushed back on my client the least.**

I could not have remembered that. I'd have remembered the good week as a good week. The
correlation only exists in the data, and it's the finding that made the rest of the talk
make sense — it turns [Shift 1](shifts/01-split-the-role.md) from advice into a mechanism.

## What to actually do with this

- **Your prompt history is a behavioural log.** Everyone treats it as disposable. It's the
  most honest record you have of what you believed was worth building, without the benefit
  of hindsight and without anyone performing for it.
- **Run the analysis on the pair, not just on yourself.** The client-side readout worked
  because it covered both of us. A one-sided version is just a better-organised way to be
  defensive.
- **Ask for the cold version explicitly.** The default register of these tools is
  encouraging, and encouraging is the exact wrong setting here. You are not asking for
  feedback, you are asking for a description.
- **Do it while the project is running, not after.** Mine was a post-mortem. Every finding in
  it was available in week two.

## The last line

> Anyone can build now.
> The scarce thing is saying it out loud: **I think we're building the wrong thing.**

The talk is not asking people to do that alone. It's pointing out that the tool everyone is
using to build faster is also, if you point it somewhere unusual, the thing that makes the
sentence sayable.
