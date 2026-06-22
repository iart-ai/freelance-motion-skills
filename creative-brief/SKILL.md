---
name: creative-brief
description: This skill should be used when the user asks to "write a creative brief", "build a motion brief", "the client doesn't know what they want", "turn this vague client request into a brief", "what questions should I ask the client", or "make a brief I can get sign-off on". It turns a fuzzy client ask into a structured, sign-off-ready motion design brief and the exact clarifying questions to send back.
version: 0.1.0
---

# Creative Brief

Convert a vague client ask ("we need a cool animated explainer") into a structured, sign-off-ready creative brief, and generate the exact clarifying questions to send when the client cannot articulate what they want.

## When to use

Use when starting any motion project, when a client request lacks the detail needed to scope or quote, when a brief needs to be drafted for client approval, or when a "make it cool" request must be translated into concrete direction. A locked brief is the contract for creative intent; everything downstream (estimate, scope, revisions, delivery) depends on it.

## Core principle

A brief is not a wish list — it is a decision document. Every project decision should trace back to one line in the brief. The job is to interrogate eleven dimensions until each has a concrete, written answer, then lock it with a sign-off line. Vague answers are not acceptable; convert each one into a specific, testable statement.

## The 11 interrogation dimensions

Capture a concrete answer for each. If the client cannot answer, send the matching clarifying question (see references/clarifying-questions.md).

1. **Business goal** — what the business needs to change (awareness, sign-ups, sales, comprehension). Must be measurable, not "engagement."
2. **Audience** — who watches, where their head is at, their objection. Specific persona, not "everyone."
3. **Core message** — the ONE thing a viewer must remember. One sentence. If there are three, the brief is not done.
4. **Tone / feel** — 3-5 adjectives plus a "but not" (e.g. "playful but not childish"). Tie to reference frames.
5. **Mandatories** — brand assets, logo lockup rules, colour/font system, legal disclaimers, super/endcard, clearcast/regulatory needs.
6. **Deliverables** — exact count, durations, and versions (e.g. 1× 30s hero, 3× 6s cutdowns, 1× static endframe).
7. **Distribution** — exact placements (IG Reels, paid YouTube pre-roll, trade-show loop, broadcast). This drives spec and aspect ratios.
8. **References** — 2-4 links with a note on what to steal from each ("the pacing here, not the colour"). Also anti-references.
9. **Timeline** — final air date working backwards through delivery, revisions, animation, design, script/board, kickoff.
10. **Budget** — a real number or a band. "No budget yet" is a red flag to resolve before design starts.
11. **Success metric** — how success is judged 30 days post-launch. Defines "done well," not just "done."

## Workflow

1. **Intake.** Read the raw client ask. Extract whatever maps to the 11 dimensions; mark the rest as gaps.
2. **Triage gaps.** For each blank or vague dimension, pull the matching clarifying question. Group them into one consolidated email — never drip-feed questions across days.
3. **Draft the brief.** Fill the template below. Where the client was vague, write the best assumption and flag it `[ASSUMPTION — confirm]`.
4. **Pressure-test.** Check the message is singular, the tone has a "but not," deliverables have counts and durations, and distribution maps to real specs.
5. **Send for sign-off.** Include the sign-off block. No design work begins until it is returned approved.

## The brief template

```
PROJECT BRIEF — [Project name]                     Date: ___  Version: ___
Client: ___   Main contact (decision-maker): ___   Prepared by: ___

1. BUSINESS GOAL
   We are making this so that: [measurable change]

2. AUDIENCE
   Primary: [persona, context, mindset, key objection]

3. CORE MESSAGE (the one thing)
   After watching, the viewer thinks/does: [one sentence]

4. TONE / FEEL
   It feels: [adj, adj, adj] — but NOT [adj, adj]

5. MANDATORIES
   Logo: [lockup + rules]   Colour/Type: [system]
   Legal/super/endcard: [required text]   Regulatory: [Y/N — body]

6. DELIVERABLES
   [count × duration × ratio × format]  (full list in delivery section)

7. DISTRIBUTION
   Placements: [exact channels + paid/organic]

8. REFERENCES
   • [link] — take: [what to steal]
   • Anti-ref: [link] — avoid: [what]

9. TIMELINE (back from air date)
   Air: ___  Final delivery: ___  Rev rounds: ___  Animation: ___
   Design/boards: ___  Script: ___  Kickoff: ___

10. BUDGET
    [number or band] — covers: [scope]

11. SUCCESS METRIC
    30 days out, success = [metric + target]

ASSUMPTIONS TO CONFIRM
   • [ASSUMPTION] ...

SIGN-OFF
   This brief is the agreed creative intent. Changes after sign-off are
   handled as change requests.
   Approved by: __________  Title: ______  Date: ______
```

## Handling "I don't know what I want"

Do not ask the client to design. Offer bounded choices instead of open questions:
- Replace "What tone do you want?" with "Closer to A (calm, premium, slow) or B (punchy, bold, fast)?"
- Replace "Any references?" with "Of these three styles, which is nearest — and what's wrong with it?"
- Force a single message: "If the viewer forgets everything but one line, which line?"
- Anchor budget with a band: "Projects like this usually land between X and Y — which end are we?"

Convert every vague adjective using the translator in references/vague-translator.md ("clean" → which of: minimal layout / lots of negative space / limited palette / slow easing?).

## Quick reference

| Symptom | Move |
|---|---|
| "Make it pop / cool / modern" | Run the vague-translator; offer 2 bounded options |
| Three core messages | Force-rank; brief carries one, others become future assets |
| No budget given | Anchor with a band before any design |
| "Everyone" is the audience | Ask who must act first; that is the audience |
| No air date | Set delivery date first, schedule backwards |
| Endless references | Cap at 4 + require a "take" note + 1 anti-reference |
| Tone with no "but not" | Add the guardrail adjective; it prevents 80% of revisions |

## Reference files

- `references/clarifying-questions.md` — the full bank of send-ready clarifying questions, one set per dimension, plus the consolidated intake email template.
- `references/vague-translator.md` — vague-adjective → concrete-question lookup table and the bounded-choice question patterns.
- `references/worked-example.md` — a real vague ask turned into a completed brief, start to finish.
