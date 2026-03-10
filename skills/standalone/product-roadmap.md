---
name: product-roadmap
description: Use when planning what to build and when, sequencing initiatives, or when the team has a backlog of ideas but no clear order of operations
---

# Product Roadmap

Build a roadmap through structured co-creation. A roadmap is not a feature list with dates. It's a strategic communication tool that shows what you're betting on, what you're learning, and why in this order.

A single company or product often has multiple roadmaps at different levels: a company-level roadmap across products, a product-level roadmap across squads, or a squad-level roadmap for a single team. This skill produces one roadmap at whatever level fits your need. Be clear about which level you're working at before starting.

## Soft Prerequisites

A roadmap without strategy is a feature list. A roadmap without metrics is wishful thinking. A roadmap without discovery is guesswork. If you don't have clarity on what you're optimizing for (strategy, OKRs) and what problems are worth solving (discovery), consider building those first. You can proceed without them, but the roadmap will lack strategic grounding.

## Co-Creation Flow

Three sections, each with a checkpoint:

```
Foundations (2 elements)
    ↓ checkpoint
Now-Next-Later (5 elements)
    ↓ checkpoint
Sequencing & Capacity (2 elements)
    ↓ assemble
```

Work through each element one at a time. For each: explain the concept, ask one question, reflect back what you heard, confirm before moving on.

---

### Section 1: Foundations

#### Element 1: Prerequisites Check

**Explain:** Before structuring a roadmap, quick inventory: do we have a strategy (how we win), metrics (what outcomes matter), and identified opportunities (what problems to solve)? If not, the roadmap will be a prioritized wish list rather than a strategic plan. That might be OK for a first pass, but name the gap.

**Ask:** "What strategic context exists? Can you state: what we're optimizing for this quarter, and what opportunities/problems we've identified?"

**Reflect/Confirm:** If solid, proceed. If missing, note the gap and recommend addressing it. Don't block, but name what the roadmap will lack.

#### Element 2: Narrative Mode

**Explain:** Roadmaps serve different audiences and tell different stories. Pick the mode that fits:
- **Vision-driven:** "Here's where we're going." Best for all-hands, team alignment, new hires.
- **KPI-driven:** "Here's how we move the needle." Best for quarterly planning, OKR alignment.
- **Executive pitch:** "Here's why these bets matter." Best for leadership, board, investors.

The mode shapes how you frame every initiative on the roadmap.

**Ask:** "Who is the primary audience for this roadmap, and what mode fits: vision-driven, KPI-driven, or executive pitch?"

**Reflect/Confirm:** Confirm the mode. Also confirm the scope: is this a product-level roadmap, a squad-level roadmap, or something else?

**Checkpoint:** Foundations set. Move to structuring the roadmap.

---

### Section 2: Now-Next-Later

#### Element 3: Now: Discovery

**Explain:** "Now: Discovery" is work you're actively investigating but haven't committed to building. These are opportunities being validated, not delivery promises. This is the most important distinction in the roadmap: making uncertainty visible. Discovery has three possible outcomes: dropping (the opportunity isn't worth pursuing), splitting (breaking into sub-opportunities or versions), or pivoting (finding something more promising). Limit to 1-2 items. You can't discover everything at once.

**Ask:** "What are you actively investigating right now? What opportunities are in discovery, and what are you trying to learn about each?"

**Reflect/Confirm:** Check: are these stated as questions to answer, not features to build? "Can we reduce onboarding drop-off by 30%?" is discovery. "Build new onboarding flow" is delivery.

#### Element 4: Now: Delivery

**Explain:** "Now: Delivery" is committed work. High confidence, clear scope, team assigned. These are active bets with defined outcomes. Each item needs a "why" tied to strategy or OKRs, not just a feature name. Limit to 1-3 items. If everything is "Now," nothing is.

**Ask:** "What is the team actively building right now? For each: what outcome does it serve, and how will you measure success?"

**Reflect/Confirm:** Check: does each item have an outcome, not just a feature name? "Ship dashboard v2" needs a "so that [metric] improves."

#### Element 5: Next

**Explain:** "Next" is shaped work planned for 1-3 months out. Medium confidence: the direction is clear but scope isn't fully defined. These are validated opportunities waiting for capacity. Sequenced based on what you learn from current Discovery and what ships from current Delivery. Next items can change based on discovery outcomes.

**Ask:** "What's planned after current work completes? What opportunities are shaped and waiting for capacity?"

**Reflect/Confirm:** Check: are these dependent on current Discovery outcomes? If so, note the dependency explicitly ("if discovery confirms X, then this moves to Now").

#### Element 6: Later

**Explain:** "Later" is directional, 3-6 months out. Lower confidence. These signal where thinking is heading without promising delivery. It's OK for these to change. They exist to show stakeholders you're thinking ahead, not to commit resources. Never put dates on Later items: that's false precision.

**Ask:** "What's on the horizon? What direction is the team headed in 3-6 months, knowing it might change?"

**Reflect/Confirm:** Check: are we comfortable that these might change? If anyone treats Later as commitments, the roadmap will create more problems than it solves.

#### Element 7: Trade-offs

**Explain:** What you're explicitly NOT doing and why. A roadmap that tries to do everything communicates nothing. Include a "Not in next X months" parking lot: these aren't bad ideas, they just don't align with current objectives. Stakeholders can bring new data or wait for objective changes to revisit them. Every "no" should reference what you're saying "yes" to instead.

**Ask:** "What are you choosing NOT to do? What good ideas are parked, and what would change that decision?"

**Reflect/Confirm:** Check: is the "revisit when" trigger clear? "When we hire more engineers" is vague. "When activation rate exceeds 40% and we shift focus to retention" is actionable.

**Checkpoint:** Review the full Now-Next-Later. Does the story make sense? Does Discovery feed Next? Does the narrative mode come through?

---

### Section 3: Sequencing & Capacity

#### Element 8: Sequencing Rationale

**Explain:** Why this order? Not just priority, but logic. Good sequencing front-loads learning: do the uncertain thing first so you learn before committing to the expensive thing. Look for dependencies (B requires A), risk reduction (validate before scaling), and value delivery (quick wins build momentum and trust).

**Ask:** "Why this order? What logic drives the sequence: dependencies, risk reduction, learning loops, or something else?"

**Reflect/Confirm:** Check: does the sequence front-load learning? If the highest-uncertainty item is in Later, you're optimizing for comfort, not information.

#### Element 9: Capacity Reality Check

**Explain:** Three engineers don't equal thirty. Is this roadmap realistic given the team? How many parallel streams can you actually run? If everything is in "Now," be honest: can the team deliver all of it simultaneously? Add a disclaimer: this is a best guess from today's date. Prioritize flexibility over predictability.

**Ask:** "What's the team size and structure? How many things can realistically be in-flight at once?"

**Reflect/Confirm:** If the roadmap exceeds capacity, something needs to move from Now to Next, or from Next to Later. Which items move?

---

### Assembly

Combine all elements into a roadmap. Add the narrative framing based on the chosen mode.

## Output Template

```markdown
# Product Roadmap: [Product/Team] - [Period]

> Disclaimer: Best guess from [date]. We prioritize flexibility over predictability.

## Narrative
[1-2 sentences: what story does this roadmap tell?]
**Mode:** [Vision-driven / KPI-driven / Executive pitch]
**Scope:** [Product-level / Squad-level / Other]

## Now: Discovery
| Opportunity | What We're Validating | OKR Link | Status |
|------------|----------------------|----------|--------|
| [name] | [question we're answering] | [which OKR] | [early/mid/late] |

## Now: Delivery
| Initiative | Expected Outcome | Metric | Confidence |
|-----------|-----------------|--------|------------|
| [name] | [why, tied to strategy] | [how we measure] | High |

## Next (1-3 months)
| Initiative | Expected Outcome | Metric | Confidence |
|-----------|-----------------|--------|------------|
| [name] | [why] | [how we measure] | Medium |

## Later (3-6 months)
| Initiative | Direction | Confidence |
|-----------|-----------|------------|
| [name] | [where thinking is heading] | Low-Medium |

## Not Doing / Not in Next X Months
| Initiative | Reason | Revisit When |
|-----------|--------|-------------|
| [name] | [why not now] | [what trigger would change this] |

## Sequencing Rationale
[Why this order: dependencies, risk reduction, learning loops]

## Capacity
- **Team:** [size and structure]
- **Parallel streams:** [how many in-flight at once]
- **Realistic throughput:** [what can actually ship per quarter]
```

## Verification Criteria

After drafting, run these checks. For failures: fix silently if you have the context, ask if you need input. Max 3 attempts per check.

### Structural (6 checks)
- [ ] Narrative mode stated
- [ ] Roadmap scope stated (product/squad/other)
- [ ] Now split into Discovery and Delivery
- [ ] Now/Next/Later all present
- [ ] Trade-offs/"Not Doing" section present
- [ ] Capacity stated with team size

### Quality (7 checks)
- [ ] Now: Discovery has 1-2 items max (not overloaded)
- [ ] Now: Delivery has 1-3 items max
- [ ] Discovery items state what's being validated, not what's being built
- [ ] Every Delivery/Next initiative has an outcome, not just a feature name
- [ ] Confidence decreases from Now → Next → Later
- [ ] Later items have no dates (no false precision)
- [ ] Capacity is realistic for team size (roadmap doesn't exceed throughput)

## Common Pitfalls

- **Feature lists disguised as roadmaps.** No "why" per item. Just a list of things to build. Every initiative needs an outcome.
- **Everything in "Now."** If you have 8 items in Now, you have no priorities. Force the hard conversation.
- **Later items with deadlines.** Putting dates on low-confidence items creates false promises. Use timeframes (3-6 months), not dates.
- **No Discovery column.** If everything goes straight from idea to Delivery, you're skipping validation. Make uncertainty visible.
- **Ignoring capacity.** A beautiful roadmap for a team that doesn't exist. Always check: can we actually do this with the people we have?
- **Missing trade-offs.** The roadmap shows what you'll do but not what you won't. Without trade-offs, stakeholders assume everything will happen eventually.
