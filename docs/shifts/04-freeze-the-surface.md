# ~~Shift 4~~ — Freeze the surface so people can build habits

> ⛔ **RETIRED 2026-08-24. Not in the talk.**
>
> Dropped because it fails the relevance filter: it is change management — about users
> absorbing change — not about deciding and building collapsing into one person. It would sit
> just as well in a talk about something else, and that is the test it failed.
>
> Kept because nothing in it is wrong, and some of it may be reusable in whatever fills the
> fourth slot. → [`README.md`](README.md)

**Former slides:** 26–27 · **Evidence:** field

## The failure

> **A tool that enables 100% of the job, that nobody knows how to use, is worth zero.**

Capability and value are not the same axis, and the compression pulls them apart. You can now
extend what a tool *can* do faster than any human can update what they *know* it does. Past a
certain rate of change, every improvement is also a small act of destruction: it invalidates
the mental model the user had just finished building.

A surface that keeps improving is a surface nobody can form a habit on. And an internal tool
without habits is not a tool, it's a demo that happens to be in production.

## Why now specifically

This is the shift that is *purely* a creature of the compression. It did not exist as a
problem when shipping a change took a quarter, because the change rate was naturally below
the human learning rate. Nobody needed a policy for it.

Ship 74 times in 52 days and you cross that line. The constraint is no longer engineering
throughput; it's the number of new things a person can absorb per week, which is small,
fixed, and not improving.

## What to do

- **Version the surface separately from the internals.** Improve the engine continuously;
  change the thing the user touches on a slow, announced cadence. Most of your 8× can go into
  the half nobody has to relearn.
- **Declare the freeze out loud.** "This screen will not change for six weeks" is a promise
  that lets someone invest in learning it. Unannounced stability delivers none of the benefit,
  because the user doesn't know they can rely on it.
- **Budget teaching as part of shipping.** If a change needs explaining and nobody has been
  assigned to explain it, it isn't finished. This is a real cost that the compression did not
  reduce at all.
- **Count habits, not features.** "How many people use this weekly without being reminded" is
  the number. Ties directly to [Shift 2](02-instrument-adoption.md).

## Objections

**"This is just change management."** Yes. The point is that change management used to be a
big-company concern and is now a three-person-team concern, because a three-person team can
now generate change at a rate that used to require a department.

**"Freezing means shipping slower."** It means shipping the same amount into a different
place. The freeze applies to the surface, not the product.

## Related

[Shift 2](02-instrument-adoption.md) — instrumentation is how you find out the freeze is
needed before the tool is already abandoned.
