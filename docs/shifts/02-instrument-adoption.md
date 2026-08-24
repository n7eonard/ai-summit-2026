# Shift 2 — Instrument adoption on day one, not month six

**Slides:** 22–23 · **Evidence:** field

## The failure

Nobody complained, so you assumed it was working.

> **An internal user who complains is a good user. Silence is the failure signal.**

A complaint requires someone to have used the thing, formed an expectation, and had it
violated. That is three separate signs of life. Silence has none of them, and it looks
exactly like success from where you're sitting.

**From the field:** the agents were in production. The expert whose job they automated was
still doing it by hand, the same quarter. No alarm went off, because there was nothing
watching for the absence of use — only for errors, and there were none. A tool nobody runs
throws no exceptions.

## Why now specifically

This one is a direct arithmetic consequence of the compression.

When shipping took a quarter, the gap between "shipped" and "someone told us it's useless"
was small relative to the build. You could afford to learn late. Now the build is three days
and the feedback loop is still six weeks, so **almost all of the elapsed time in your project
is now the part you're not measuring.**

The measurement didn't get worse. The thing it's attached to got 8× faster and left it behind.

## What to do

- **Instrument before you ship, not after.** If "is this being used, by whom, how often" is
  not answerable on day one, you have shipped a thing you cannot evaluate. For internal tools
  this is usually a few lines, and it is always the few lines that get cut.
- **Watch non-use, not errors.** The dashboard that matters counts the people who *should*
  have used it and didn't. Error rates measure the health of the people already inside.
- **Go looking for the complaint.** Silence is not neutral data you can wait out. Someone has
  to go and ask, in person, and the answer will not arrive in a Slack channel.
- **Name the adoption number before you build.** "This works if the expert stops doing it by
  hand" is a falsifiable target. "This works if it's accurate" is not — mine was accurate.

## Objections

**"Internal tools don't deserve analytics."** They deserve them more. External users churn
visibly and you find out from revenue. Internal users just quietly keep doing it the old way
and are too polite to mention it.

**"We'd rather ship than instrument."** You are about to ship eight times as much. The
instrumentation is what tells you which of the eight mattered.

## Related

[Shift 4](04-freeze-the-surface.md) — often the reason adoption fails isn't the tool, it's
that the tool changed shape before anyone could learn it.
