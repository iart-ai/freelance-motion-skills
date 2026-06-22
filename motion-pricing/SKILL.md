---
name: motion-pricing
description: This skill should be used when the user asks to "quote a motion project", "estimate this animation job", "how much should I charge for this video", "what's my day rate", "build a quote", "price a 30-second explainer", or "is this estimate fair". It explains motion-design pricing models, the day-rate math, the cost drivers, and outputs a line-itemed quote with a worked example.
version: 0.1.0
---

# Motion Pricing

Produce a defensible quote for a motion design project: choose a pricing model, run the day-rate math, account for the real cost drivers, and output a clean line-itemed estimate the client can approve.

## When to use

Use when pricing any motion/animation project, sanity-checking an existing number, setting or revisiting a day rate, or explaining to a client why a price is what it is. The output is a structured quote plus the reasoning behind each line.

## Step 1 — Pick a pricing model

| Model | Bill on | Best for | Watch out |
|---|---|---|---|
| **Day rate** | Days of work | Open-ended, exploratory, or retainer work | Penalises speed; client may haggle days |
| **Per-project (fixed)** | Whole deliverable | Well-scoped jobs with a locked brief | Scope creep eats margin — needs a revision cap |
| **Per-finished-minute** | Final runtime | Explainers, series, repeatable style | Ignores complexity differences minute-to-minute |
| **Value-based** | Outcome/usage to client | High-leverage brand/ad work | Requires knowing the client's stakes |

Default approach: estimate internally in **days** (the only honest unit of effort), then present to the client as a **fixed per-project** price with a revision cap. Use per-finished-minute only as a cross-check or for series work, and value-based when the deliverable is tied to a large campaign or broadcast spend.

## Step 2 — Set the day rate

Day rate is derived, not guessed:

```
Target annual income (incl. salary you want + profit)
+ Annual business costs (software, hardware, rent, insurance, tax set-aside, pension)
= Total revenue needed
÷ Billable days per year
= DAY RATE
```

Billable days reality check: a year has ~260 weekdays. Subtract holiday, sick, admin, marketing, and unsold gaps. Most solo motion designers bill **120-150 days/year**, not 260. Dividing by 260 produces a rate that loses money.

Worked rate example:
- Target income £55,000 + costs £20,000 = £75,000 needed.
- Billable days: 130.
- Day rate = 75,000 ÷ 130 = **£577 → round to £600/day**.

## Step 3 — Apply the cost drivers

Estimate days by walking the drivers. Each pushes the day count up:

1. **Duration** — more finished seconds = more animation days (non-linear; a 60s film is more than 2× a 30s).
2. **Complexity / style** — flat 2D < detailed 2D < character animation < 3D < 3D with simulation. Style sets the per-second day cost.
3. **Asset creation** — design/illustration, 3D modelling, rigging, sound design, voiceover, music licensing. Each is a separate line, not "included."
4. **Revision rounds** — price in a fixed number (e.g. 2). Each extra round is roughly 10-20% of the animation effort.
5. **Rush** — compressed timeline or weekend work adds a 25-50% surcharge.
6. **Usage / licensing rights** — broadcast, paid media, perpetual, or exclusive usage multiplies the base. Organic social is cheapest; national TV/OOH and buyouts are highest.

## Step 4 — Build the line-itemed quote

```
QUOTE — [Project]                          Date: ___  Valid 30 days
Studio/Freelancer: ___        Client: ___

SCOPE
  Deliverables: [count × duration × format]
  Style: [flat 2D / character / 3D ...]
  Revisions included: [N rounds]
  Usage: [organic social / paid / broadcast / buyout]

LINE ITEMS                                  Days     Amount
  Concept & creative direction              __       ____
  Script / storyboard / animatic            __       ____
  Design & illustration (asset creation)    __       ____
  3D modelling / rigging (if any)           __       ____
  Animation                                 __       ____
  Sound design / music / VO                 __       ____
  Revisions (N rounds, included)            __       ____
  Project management                        __       ____
                                          --------  --------
  SUBTOTAL (production)                     __       ____

  Rush surcharge (if applicable)   +__%             ____
  Usage / licensing uplift         +__%             ____
                                          --------  --------
  TOTAL                                              ____
  (+ tax as applicable)

PAYMENT
  [50% to book / 50% on delivery]  — kill fee: __% of total
EXCLUSIONS
  Stock/music licences billed at cost · extra revision rounds at [rate]
  · additional cutdowns at [rate each] · scope changes via change order
```

## Step 5 — Cross-check and sanity-test

- Divide total by finished minutes — is the per-minute figure sane for the style? (See ranges below.)
- Is every asset a line, or did "design" get absorbed into "animation"?
- Are revisions capped and priced? Unlimited revisions = unlimited cost.
- Does usage match price? National broadcast at organic-social pricing is a money loser.
- Add 10-15% contingency for ambitious or vaguely-briefed jobs.

## 2026 ballpark ranges (localize before quoting)

These are rough Western-market starting points; rates vary widely by region, seniority, and client tier. Always adjust to local market and your own day rate.

| Item | Ballpark (2026, USD/GBP/EUR similar order) |
|---|---|
| Freelance mid day rate | 400-750 / day |
| Senior / specialist day rate | 750-1,500 / day |
| Simple flat 2D explainer | 1,000-3,000 / finished minute |
| Detailed / character 2D | 3,000-8,000 / finished minute |
| 3D motion | 8,000-20,000+ / finished minute |
| 6s social bumper (simple) | 500-2,000 each |
| Rush surcharge | +25-50% |
| Broadcast/paid usage uplift | +25-200% over organic base |

Caveat: treat every number as a starting anchor, not a fixed price. Localize to currency, region, and the client's tier, and reconcile against the day-rate math in Step 2.

## Quick reference

| Question | Answer |
|---|---|
| What unit do I estimate in? | Days of effort, always |
| What do I show the client? | Fixed per-project price + revision cap |
| How do I get my day rate? | (income + costs) ÷ billable days (~130) |
| Is design "included" in animation? | No — separate line |
| How many revisions to include? | 2, then charge per extra round |
| Client wants it in half the time? | +25-50% rush |
| It's running on national TV? | Add usage uplift over the base |

## Reference files

- `references/quote-template.md` — full quote template, payment-terms language, exclusions, and a kill-fee clause.
- `references/worked-example.md` — a complete worked estimate from brief to total, showing the day math and driver reasoning.
- `references/rate-card.md` — expanded 2026 ranges by deliverable type and the day-rate worksheet.
