---
name: client-revisions
description: This skill should be used when the user asks to "stop scope creep", "limit revision rounds", "write SOW revision language", "the client keeps asking for changes", "how do I say this is out of scope", "translate vague feedback", "client said make it pop", or "write a change-order email". It provides revision-cap contract language, a consolidated-feedback request, a vague-feedback translator, and a polite out-of-scope email.
version: 0.1.0
---

# Client Revisions

Control revision rounds and scope creep on motion projects: define what a revision is, cap rounds in the SOW, collect feedback the right way, translate vague notes into actionable changes, and decline out-of-scope work politely as a change order.

## When to use

Use when feedback is mounting, when a client keeps adding "small tweaks," when the SOW needs revision language, when a vague note ("make it pop") needs decoding before touching the file, or when a request has clearly crossed into new work and needs a change-order reply.

## The core distinction: revision vs new request

This single line prevents most disputes — put it in the SOW and the feedback request:

- **A revision** = a change to something that was already in the approved brief/board (adjusting timing, colour from the palette, swapping an approved word, fixing a glitch).
- **A new request** = anything not in the approved brief/board (a new scene, added second of runtime, a different concept, a new aspect ratio, a logo not previously supplied, "let's also try…").

Revisions are included up to the cap. New requests are change orders, quoted and scheduled separately. State this before round 1, not after the dispute.

## SOW revision-cap language

Drop this into the contract/quote:

```
REVISIONS
This project includes [2] rounds of revisions. A "round" is one
consolidated set of feedback, collected from all stakeholders and
delivered in a single document, then addressed in full.

Included (a revision): changes to elements already approved in the
brief and storyboard — timing, pacing, colours from the agreed
palette, approved copy edits, and fixes.

Not included (a new request / change order): new scenes, added
runtime, new concepts or directions, additional formats or aspect
ratios, new assets not previously supplied, or feedback that
reverses a previously approved decision.

New requests are quoted as a change order before work proceeds and
may affect the timeline. Additional revision rounds beyond those
included are billed at [day rate]. Feedback split across multiple
messages may be treated as separate rounds.
```

## Workflow when feedback arrives

1. **Stop.** Do not open the project file yet.
2. **Consolidate.** If feedback is scattered or per-person, send the consolidated-feedback request (below). One document, all stakeholders, deduped and de-conflicted.
3. **Classify each note** as revision or new request using the distinction above.
4. **Translate vague notes** into targeted questions before executing (see translator).
5. **For new requests**, send the change-order email — do not silently absorb them.
6. **Log the round.** Record which round this is so the cap is visible to both sides.

## Consolidated-feedback request template

```
Subject: Feedback on [project] — Round [N]

Hi [name],

Ready for your notes on V[n]. To turn these around fast and cleanly,
could you send everything in one go:

• Gather feedback from everyone who needs to weigh in and merge it
  into a single list (if two notes conflict, tell me which wins).
• Use timestamps where you can — "at 0:08 the logo feels slow."
• Tell me the problem, not the fix — "the intro drags" is more useful
  than "make it faster," because it lets me solve it properly.
• Flag any must-have vs nice-to-have.

Send it all together and I'll address the full set in this round.
Notes that arrive after, or in separate messages, may roll into the
next round. Thanks!
```

## Vague-feedback translator

Never act on a vague note. Convert it to targeted questions first:

| Client says | Ask back |
|---|---|
| "Make it pop" | "More saturated colour, faster pacing, bigger scale moves, or stronger sound? Point to a second that already pops." |
| "It feels off" | "Off in pacing, colour, type, or message? Which 2 seconds feel most wrong?" |
| "Make it more premium" | "Slower easing, more space, restrained palette, or refined type — which one?" |
| "Can it be more dynamic?" | "More camera movement, faster cuts, or more elements in motion?" |
| "I don't love it" | "What specifically — and what would 'loving it' look like? A reference helps." |
| "Make it bigger / stronger" | "Larger scale, bolder type, higher contrast, or more screen time?" |
| "Something's missing" | "A scene, a message, a brand element, or energy? Where in the timeline?" |
| "Can we punch it up?" | "Pacing, colour, or sound? Show me a moment that already has the energy you want." |

Rule: turn every feeling into a choice between concrete, decidable options, and ask for a timestamp.

## Out-of-scope / change-order email template

```
Subject: [project] — quick note on the new request

Hi [name],

Happy to help with [the new request] — flagging that it sits outside
the approved brief/storyboard, so it's a change rather than a revision
under our current scope.

Here's what it takes:
  • Work: [what's involved]
  • Cost: [amount / day estimate]
  • Timeline impact: [+X days / new delivery date]

If you'd like to go ahead, reply "approved" and I'll add it and update
the schedule. If you'd rather keep to the original scope and budget,
no problem — we'll proceed as planned and can revisit this later.

Either way works for me; just let me know which you prefer.
```

Tone notes: collaborative, never accusatory. Offer the choice (proceed or park), give a number, and state the timeline impact. The goal is to make the trade-off visible, not to say "no."

## Quick reference

| Situation | Move |
|---|---|
| Feedback dribbling in per-person | Send consolidated-feedback request; restart the round |
| "Make it pop" | Translate to concrete options + ask for a timestamp |
| Client requests a 4th round | Cite SOW cap; quote extra round at day rate |
| "Just one tiny new scene" | Change-order email; it's new work |
| Reversing an approved decision | New request, not a revision |
| New aspect ratio added late | Change order — separate format = separate deliverable |
| Two stakeholders conflict | Require client to pick the winning note before work |

## Reference files

- `references/sow-clauses.md` — full SOW revision section, approval-gate language, and "round" definition variants.
- `references/email-templates.md` — consolidated-feedback, change-order, extra-round, and stalled-approval email templates.
- `references/feedback-translator.md` — expanded vague-to-targeted feedback lookup and the "problem not fix" coaching note for clients.
