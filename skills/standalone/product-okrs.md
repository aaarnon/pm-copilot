---
name: product-okrs
description: Use when setting quarterly goals, translating strategy into measurable outcomes, or when the team is tracking activity instead of impact
---

# Product OKRs

Build meaningful OKRs through structured co-creation. OKRs translate strategy into measurable quarterly outcomes. If your OKRs feel like a to-do list, they're not OKRs.

## Soft Prerequisites

OKRs without strategy are random targets. If you can't state your product strategy in 2-3 sentences, consider starting with `product-strategy` first. You can proceed without it, but the OKRs will lack strategic grounding.

## Co-Creation Flow

Three sections, each with a checkpoint:

```
OKR Readiness (2 elements)
    ↓ checkpoint
Objectives (3 elements)
    ↓ checkpoint
Key Results (3 elements)
    ↓ assemble
```

Work through each element one at a time. For each: explain the concept, ask one question, reflect back what you heard, confirm before moving on.

---

### Section 1: OKR Readiness

#### Element 1: Strategy Anchor

**Explain:** OKRs are how strategy becomes action each quarter. Without strategy, OKRs become a list of things people want to build. Quick check: what's the strategy these OKRs should serve? If it's unclear, the OKRs will be disconnected targets.

**Ask:** "What's the product strategy these OKRs need to advance? Can you summarize in 2-3 sentences?"

**Reflect/Confirm:** If strategy is unclear, recommend building one first. If it's clear enough, anchor the OKR work to it.

#### Element 2: Time Horizon

**Explain:** OKRs work best quarterly. Annual OKRs are too vague to act on. Monthly is too tactical, you'd be measuring activity not outcomes. A quarter gives enough time to move a meaningful metric while maintaining urgency.

**Ask:** "What time period are we setting OKRs for? Is there a specific quarter or cycle?"

**Reflect/Confirm:** Confirm the period and any constraints (team changes, launches, dependencies).

**Checkpoint:** Do we have enough strategic context to set meaningful OKRs?

---

### Section 2: Objectives

#### Element 3: Outcome vs Output Test

**Explain:** This is the most common OKR mistake. "Launch feature X" is an output: it describes work. "Reduce churn by 15%" is an outcome: it describes the change in the world. Objectives must be outcomes. The test: if you shipped the thing and the metric didn't move, was the OKR successful? If your answer is "yes, because we shipped it," that's an output OKR.

**Ask:** "What outcomes matter most this quarter? Not what you'll build, but what will change. Think: what should be different in the world at the end of the quarter?"

**Reflect/Confirm:** Apply the outcome vs output test to each. Rewrite any outputs as outcomes.

#### Element 4: Objective Drafting

**Explain:** A good objective is qualitative, inspirational, time-bound, and directly derived from strategy. Draft 2-3 max. More than 3 objectives means no focus. If everything is a priority, nothing is. Each objective should make someone think "yes, if we achieve that, it really matters."

**Ask:** "Given the strategy and outcomes you described, let's draft 2-3 objectives. For each, complete: 'By end of [quarter], we will have [qualitative outcome that matters].'"

**Reflect/Confirm:** Review each objective. Check: does it connect to strategy? Is it qualitative (not a metric)? Would achieving it matter?

#### Element 5: The "So What" Test

**Explain:** For each objective, ask: "If we achieve this, what changes for the business?" If the answer is unclear or requires mental gymnastics to explain, the objective is too tactical. It might be a good Key Result, but not an Objective.

**Ask:** "For each objective we drafted: so what? If you achieved it, what would you tell the CEO? What changes?"

**Reflect/Confirm:** Cut or merge any objectives that don't pass the test. Confirm the final set (2-3 max).

**Checkpoint:** Review objectives before defining Key Results.

---

### Section 3: Key Results

#### Element 6: Leading vs Lagging Indicators

**Explain:** Lagging indicators measure the outcome you want (revenue, retention, NPS). You can see them but you can't directly control them. Leading indicators measure the inputs you can control that predict the outcome (activation rate, time-to-value, feature adoption). Good KR sets have both: leading indicators to steer by, lagging indicators to confirm results.

**Ask:** "For your first objective, what's the lagging metric that tells you it worked? And what's the leading metric you can actually influence week-to-week?"

**Reflect/Confirm:** Check: is the leading indicator actually predictive of the lagging one? If activation rate goes up, does retention actually follow? If the link is unproven, note it as an assumption.

#### Element 7: Key Result Drafting

**Explain:** Each Key Result needs four things: a metric (what you measure), a baseline (where you are now), a target (where you want to be), and confidence that the team can influence it. Missing baselines are the #1 KR problem. "Improve retention" means nothing without "from 40% to 55%."

**Ask:** "For each objective, let's draft 2-4 Key Results. For each: what's the metric, where is it today (baseline), and where should it be by end of quarter (target)?"

**Reflect/Confirm:** Check: do we have real baselines? If not, flag getting them as the first action. Are targets ambitious but not fantasy? Can the team actually influence each metric?

#### Element 8: Ambition Calibration

**Explain:** OKR targets should stretch. 70% achievement should be the target for ambitious goals. If you're hitting 100% every quarter, targets are too safe and you're not learning how far you can push. If hitting 30%, they're demoralizing and the team stops caring. The sweet spot: uncomfortable but achievable with focused effort.

**Ask:** "For each Key Result: on a scale of 1-10, how confident are you the team can hit 100% of this target? Aim for 5-7 confidence. Lower means too ambitious, higher means too safe."

**Reflect/Confirm:** Adjust targets based on confidence. Push safe targets up, reign in demoralizing ones.

---

### Assembly

Combine into 2-3 Objectives with 2-4 Key Results each. Include a "What We're NOT Measuring" section to make focus explicit.

## Output Template

```markdown
# OKRs: [Team/Product] - [Quarter/Period]

## Strategic Context
[1-2 sentences linking these OKRs to the strategy]

## Objective 1: [Qualitative, inspirational statement]
- KR1: [Metric] from [baseline] to [target]
  - Type: Leading / Lagging
  - Confidence: [1-10 that team can hit 100%]
- KR2: [Metric] from [baseline] to [target]
  - Type: Leading / Lagging
  - Confidence: [1-10]

## Objective 2: [Qualitative, inspirational statement]
- KR1: [Metric] from [baseline] to [target]
  - Type: Leading / Lagging
  - Confidence: [1-10]
- KR2: [Metric] from [baseline] to [target]
  - Type: Leading / Lagging
  - Confidence: [1-10]

## What We're NOT Measuring This Quarter
[Explicit list of metrics we're deprioritizing and why]
```

## Verification Criteria

After drafting, run these checks. For failures: fix silently if you have the context, ask if you need input. Max 3 attempts per check.

### Structural (5 checks)
- [ ] Strategic context present (links OKRs to strategy)
- [ ] 2-3 objectives (not more)
- [ ] Each objective has 2-4 Key Results
- [ ] Baselines included for every Key Result
- [ ] Targets included for every Key Result

### Quality (7 checks)
- [ ] Every objective passes the outcome vs output test (no "launch X" or "build Y")
- [ ] At least one leading indicator per objective
- [ ] Targets have ambition calibration (confidence 5-7, not all 9-10)
- [ ] Key Results are measurable, not subjective ("improve experience" fails)
- [ ] "Not measuring" section present (makes focus explicit)
- [ ] No vanity metrics (pageviews without action, signups without activation)
- [ ] Objectives trace back to strategy (not random improvements)

## Common Pitfalls

- **Output disguised as outcome.** "Launch redesign" is output. "Improve activation from 20% to 35%" is outcome. Apply the test: if you shipped it and the metric didn't move, was it successful?
- **Too many objectives.** 5+ objectives means no priorities. If you can't cut to 2-3, the strategy isn't clear enough.
- **All lagging indicators.** If every KR is a lagging metric (revenue, retention), you can't course-correct mid-quarter. You'll only know you failed after it's too late.
- **Missing baselines.** "Improve retention" from what? Without a baseline, you can't tell if you moved the needle or if the target was unrealistic.
- **OKR theatre.** Perfect scores every quarter because targets are sandbagged. If you always hit 100%, you're not stretching. Raise the bar.
