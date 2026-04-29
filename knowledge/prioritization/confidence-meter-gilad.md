# The Tool That Will Help You Choose Better Product Ideas

**Author:** Itamar Gilad

**Source:** https://itamargilad.com/the-tool-that-will-help-you-choose-better-product-ideas/

**Framework:** Itamar Gilad's Confidence Meter (used inside ICE Score)

---

## Overview

Most product decisions are driven by opinions: HiPPOs, gut feel, industry buzz, manager preference. The Confidence Meter is Itamar Gilad's tool for converting "how sure are we?" into a calibrated number from 0 to 10, based on the **type and strength of evidence** behind an idea.

It's the **C in ICE Score**: Impact × Confidence × Ease. Without a calibrated Confidence value, ICE collapses into wishful thinking.

Core insight: **opinions barely move the needle**. Real confidence is earned through progressively stronger evidence, peaking with live launch data.

---

## The Confidence Meter Scale

The meter is a 0 to 10 scale. Each evidence type carries a weight (its contribution to overall confidence) and sits in a named tier with a Cap (the ceiling no amount of stacking within that tier can exceed). Stack evidence to raise the score; jump tiers by gathering stronger evidence.

| Tier | Evidence Type | Weight | Cap |
|------|---------------|-------:|----:|
| **Near-zero** | Self conviction | 0.01 | 0.1 |
| **Near-zero** | Pitch deck | 0.02 | 0.1 |
| **Near-zero** | Thematic support — vision/strategy alignment, current trends/buzzword, outside research, macro trends, product methodology | 0.05 | 0.1 |
| **Very Low** | Other's opinion — team / management / external expert / investor / press think it's a good idea | 0.1 | 0.5 |
| **Very Low** | Estimates & plans — back-of-envelope calculations, Eng/UX feasibility, project timeline, Business Model Canvas | 0.3 | 0.5 |
| **Low** | Anecdotal evidence — a few product data points, sales request, 1-3 interested customers, one competitor has it | 0.5 | 1.0 |
| **Med-Low** | Market data — surveys, smoke tests, all competitors have it | 1.0 | 3.0 |
| **Med-Low** | User/Customer evidence — lots of product data, top user request, interviews with 20+ users, usability study, MVP | 2.0 | 3.0 |
| **Medium** | Test results — longitudinal user studies, large-scale MVP, alpha/beta, A/B experiments | 3.0 | 5.0 |
| **High** | Launch data — real performance after full launch | 5.0 | 10.0 |

Source: confidence meter table reproduced from Itamar Gilad's article.

---

## How to Read the Table

**Weight** = how much that evidence type contributes when you accumulate confidence.

**Cap** = the ceiling for that tier. No matter how much evidence you stack within a tier, you cannot exceed its cap. To break past a tier, you need evidence from a higher tier.

**Stacking is cumulative within bounds.** Self conviction (0.01) + Pitch deck (0.02) + Thematic support (0.05) = 0.08 confidence, still inside the Near-zero tier (cap 0.1). Adding Other's opinion (0.1) lifts you into the Very Low tier (cap 0.5).

**The six tiers:** Near-zero (≤0.1) → Very Low (≤0.5) → Low (≤1.0) → Med-Low (≤3.0) → Medium (≤5.0) → High (≤10.0).

---

## Why Opinions Don't Count

The article opens with a chatbot vs dashboard example: stakeholders prefer the chatbot based on industry hype, manager opinion, and self-conviction. Plugging this into the meter:

- Self conviction (0.01) + Thematic support (0.05) → Near-zero tier, capped at 0.1
- Add Other's opinion (0.1) → Very Low tier, total ≈ 0.1 / 10

Despite consensus, the team has near-zero evidence. Building the chatbot is a guess dressed up as alignment.

The dashboard, by contrast, is backed by a usability study and product data, putting it at ~3 / 10 (Med-Low tier). Real evidence wins.

---

## Using the Meter with ICE

ICE = Impact × Confidence × Ease.

Without the Confidence Meter, "Confidence" defaults to gut-feel scores like 7 or 8 from people who have done no research. Plugging the meter into ICE forces honest grading:

- Opinions only: Confidence ≤ 0.1 (Near-zero)
- Estimates / endorsements: Confidence ≤ 0.5 (Very Low)
- A few anecdotes: Confidence ≤ 1.0 (Low)
- Surveys / customer interviews / MVP: Confidence ≤ 3.0 (Med-Low)
- A/B tests, alpha/beta: Confidence ≤ 5.0 (Medium)
- Post-launch performance: up to 10.0 (High)

This dramatically reshuffles roadmaps. Most "exciting" ideas drop in priority because they're untested.

---

## How to Increase Confidence

The meter is also a **roadmap for evidence-gathering**. To move an idea up tier by tier:

1. **Near-zero → Very Low:** Get team/expert endorsement, do back-of-envelope estimates.
2. **Very Low → Low:** Surface anecdotal evidence — sales requests, a few interested customers, scattered product data.
3. **Low → Med-Low:** Run surveys / smoke tests, interview 20+ users, run a usability study, build an MVP.
4. **Med-Low → Medium:** Run A/B experiments, alpha/beta releases, longitudinal user studies.
5. **Medium → High:** Ship and measure real-world performance.

Each tier requires a different research investment. The meter helps teams decide *which evidence to gather next* given the bet's size.

---

## When to Use This

- Prioritizing ideas in ICE or any value/confidence/effort framework
- Pushing back on HiPPO-driven roadmaps with a calibrated number
- Justifying discovery budget: "We're at 0.5, we need a 3 before we commit eng capacity"
- Aligning teams on what counts as "validated"

---

## Limitations

- The numerical weights are illustrative, not absolute. Different teams may calibrate differently.
- It assumes you can categorize evidence cleanly. Mixed evidence (e.g., one survey + one interview) requires judgment.
- It does not capture evidence quality within a tier (a great usability study and a sloppy one are both "user evidence").

The meter is best treated as a **shared mental model** for what counts as evidence, not a precise scoring engine.

---

## Related Frameworks

- **ICE Score** — Itamar Gilad popularized ICE (Impact, Confidence, Ease) as a lighter alternative to RICE. The Confidence Meter is the rigor that makes ICE work.
- **Evidence-Guided Product Development** — Itamar Gilad's broader methodology, expanded in his book *Evidence-Guided*.
- **Confidence-Based Prioritization** — Ant Murphy's `prioritization/confidence-not-value.md` argues a similar point: prioritize by confidence, not abstract value.
- **Discovery Confidence Scale** — Ed Biden's `discovery/how-much-discovery-is-enough.md` adapts this idea for discovery sizing.

---

## Key Takeaways

1. Confidence is a number, not a feeling. Calibrate it.
2. Opinions cap out at 0.1 / 10. They are not evidence.
3. Real confidence comes from cumulative evidence: anecdotes → market data → user testing → A/B tests → launch.
4. Use the meter inside ICE to stop overrating untested ideas.
5. The meter doubles as a roadmap for what evidence to gather next.
