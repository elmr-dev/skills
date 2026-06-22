---
name: copy-voice
description: >-
  Use when writing or reviewing any elmr-facing copy — site text, READMEs,
  Discord messages, deploy/CI messages, release notes, commit messages meant
  to be read, or social posts. Keeps the ham-native, dry, low-ego voice and
  catches overclaiming before it ships. Load this before drafting copy, not
  after.
---

# elmr copy voice

Copy for elmr reads like it comes from someone inside the hobby — a ham talking
to other hams. Dry, plain, low-ego. The work earns attention; the copy doesn't
ask for it.

The rule under all the other rules: **earn it, don't announce it.** If a line is
telling the reader how good the thing is, cut it and let the thing be good.

## The voice in one line

Ham radio software, rebuilt for everywhere — said by someone who'd rather show
you than sell you.

## Hard nos

These don't ship. No exceptions waiting to be argued:

- **"the future of"** — fast-dates, overclaims, and every project says it.
- **"AI"** as a selling point. The tools may use ML; that's an implementation
  detail, not a headline. Never lead with it.
- **Hype adjectives**: revolutionary, seamless, effortless, game-changing,
  next-generation, cutting-edge. If a word would feel at home in a SaaS landing
  page, it's wrong here.
- **Implicit insults to the hobby.** This one's subtle and the easiest to miss.
  "Software worth using" implies the existing software isn't — that's a swipe at
  decades of work by people we respect. The bet is that good amateur-radio
  software got *stranded*, not that it was bad. Copy never punches at the hobby
  to flatter elmr.
- **Manufactured urgency or fanfare** — "launching now," "don't miss," exclamation
  stacks. The door's open; you don't have to shout through it.

## The canonical line

The tagline is:

> **ham radio software, rebuilt for everywhere.**

That is the line. The older formulation — "the future of ham software, built with
AI, in the open, and taught to anyone who wants in" — is **retired.** It violates
two hard nos ("the future of," "AI") in a single breath. If you find it lingering
anywhere — old notes, a brain, a draft — it's dead. Replace it.

## Phrases that have passed the bar

These aren't just approved — they're the tuning fork. When a new line is in
question, check it against the register these set. They're ham-native, they carry
warmth without gushing, and they assume the reader is one of us:

- **the door to the shack is open** — invitation, no pressure.
- **more on the bench** — what's coming, said like a workbench, not a roadmap.
- **works on my rig** — honest scope; it runs, here, now.
- **gonna like it here** — welcome, dry.
- **on the air** — deploy succeeded.
- **didn't make it** — deploy failed. Plain. No "oops," no alarm.

The throughline: shack, bench, rig, on the air. Borrow from the hobby's own
language before reaching for software's.

## Brand rendering

- **elmr** — lowercase, set in Azeret Mono when it's the brand/wordmark in copy.
  Never "Elmr," never "ELMR," never capitalized at sentence start (rework the
  sentence instead).
- **Elmer** — the ham term for a mentor. Stays plain prose, capitalized like the
  ordinary word it is. It is *not* the brand. The brand is named *after* it; don't
  collapse the two. (e.g. "find an Elmer" is prose; "elmr decodes CW" is brand.)
- The mentor meaning is the point of the name — when it's natural to note that
  elmr comes from Elmer, that's a feature, not a gloss to hide.

## Naming, structurally

Name things by **function, not people.** `#maintainers`, not `#founders`.
Person-named things age badly, and "founders" cuts against working in the open —
it draws a line where the ethos says there isn't one. This applies to channels,
roles, repos, docs: the name should describe what the thing *does* or *is for*,
and still be right in two years when the people have changed.

## Worked examples

Before → after, to show the judgment, not just assert it.

**Overclaiming headline**

> ✗ The future of ham radio software is here — AI-powered, blazing fast, and
>   built for the modern operator.
> ✓ Ham radio software, rebuilt for everywhere.

What changed: killed "the future of," "AI-powered," "blazing fast," "modern" —
every one of them was the copy patting itself on the back. What's left states
what it is and stops.

**Swipe at the hobby**

> ✗ Finally, logging software that's actually worth using.
> ✓ A logger that installs in seconds and runs anywhere.
>   <!-- when there's a real claim, make a concrete one, not a comparative jab -->

What changed: "finally" and "actually worth using" both say *the old stuff
wasn't* — a swipe at people we respect. The fix makes a specific, checkable claim
instead of a comparative sneer.

**Deploy message**

> ✗ 🎉 Deployment successful! Your changes are now LIVE! 🚀
> ✓ on the air.

What changed: the fanfare went. "on the air" is shorter, dryer, and speaks the
hobby's own language. A ham knows exactly what it means.

## When in doubt

Read it back as if someone inside the hobby — skeptical of marketing, allergic to
hype — is on the other end. If any line would make them roll their eyes, it's not
ready. Cut toward plainer and shorter, almost always.
