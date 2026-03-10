---
name: product-prioritization
description: Use when deciding what to work on next, ranking competing initiatives, or when the team can't agree on priorities and everything feels equally important
---

# Product Prioritization

Prioritize initiatives through structured co-creation. This is not a vanilla scoring exercise. If you have a prioritization problem, you probably have a strategy problem. This skill starts by pressure-testing strategy clarity. Only if strategy doesn't make priorities obvious does it move to ICE scoring as an alignment tool.

## Soft Prerequisites

Strategy and goals should exist. If you can't state your strategy and current objectives in 2-3 sentences, start with `product-strategy` and `product-okrs`. You can proceed without them, but you'll be scoring initiatives against unclear criteria, which produces confident-looking nonsense.

## Co-Creation Flow

Three sections. Section 1 may resolve the problem entirely:

```
Strategy Pressure Test (3 elements)
    ↓ checkpoint: did strategy make it obvious?
    ↓ if yes → done
    ↓ if no → continue
ICE for Alignment (4 elements)
    ↓ checkpoint: review scores, discuss disagreements
The Decision (2 elements)
    ↓ assemble
```

Work through each element one at a time. For each: explain the concept, ask one question, reflect back what you heard, confirm before moving on.

---

### Section 1: Strategy Pressure Test

The goal: see if you actually need a scoring framework, or if the strategy already answers the question.

#### Element 1: Strategy Clarity Check

**Explain:** Before scoring anything, state the strategy and current objectives. What are we trying to achieve this quarter? What outcomes matter? If you can't state this in 2-3 sentences, that's the real problem. No scoring framework will compensate for unclear direction. In an early-stage startup, if you have a prioritization problem, you have a strategy problem.

**Ask:** "What's the strategy, and what are the current objectives/OKRs? Can you state them in 2-3 sentences?"

**Reflect/Confirm:** If unclear, recommend building strategy first. If clear, proceed to the test.

#### Element 2: "Does Strategy Make It Obvious?"

**Explain:** List the initiatives you're trying to prioritize. Now look at each one through the lens of your strategy. Does the strategy clearly say which matters most? If your strategy is sharp, most prioritization should be obvious: this initiative directly serves the primary objective, that one doesn't. If the order isn't clear, the strategy has gaps.

**Ask:** "List the initiatives you're choosing between. For each one: does the strategy make it obviously high, medium, or low priority?"

**Reflect/Confirm:** If strategy makes it obvious for all items, you're done. Write the stack rank and skip to Section 3. If some items are ambiguous, those are the ones that need scoring.

#### Element 3: Company Goals Alignment

**Explain:** Map each initiative to a specific company goal or OKR. If an initiative doesn't connect to a current objective, ask: why is it on the list? If multiple initiatives serve the same OKR, now you have a real prioritization question worth scoring. That's when ICE helps: comparing items within the same strategic bucket.

**Ask:** "For each initiative, which specific OKR or goal does it serve? Any initiatives that don't map to a current objective?"

**Reflect/Confirm:** Remove or park items that don't connect to objectives. Flag the items that need scoring (multiple initiatives serving the same goal).

**Checkpoint:** Did strategy make priorities obvious? If yes, skip to Section 3. If some items remain ambiguous, continue to ICE.

---

### Section 2: ICE for Alignment

ICE is a conversation tool, not a decision-maker. The value is in the disagreements it surfaces.

#### Element 4: Impact on Objectives

**Explain:** Score 1-4. Not generic "user impact" or "business value" but impact on *current objectives*. A feature can be great for users but irrelevant to this quarter's goals. 1 = low impact on objectives, 2 = medium, 3 = high, 4 = massive. Always ask: impact on which objective?

**Ask:** "For each ambiguous initiative, score impact on your current objectives (1-4). Be specific: which objective does it impact, and how much?"

**Reflect/Confirm:** Check: is impact scored against current objectives, or against a vague sense of "importance"? Push for specificity.

#### Element 5: Confidence

**Explain:** Score 1-4. How much evidence do we have that this will deliver the expected impact?
- 1 = educated guess, based on experience or intuition
- 2 = some confidence, secondary research or market data
- 3 = confident, based on primary research (interviews, tests)
- 4 = very confident, quantitative and qualitative experiments

Key insight: we are almost always overconfident. If everyone scores 3-4 on confidence, challenge it. What specific evidence supports that score?

**Ask:** "For each initiative, score confidence (1-4). What specific evidence do you have for each score? Not what you believe, but what you know."

**Reflect/Confirm:** Push back on high confidence scores without evidence. "We've heard from customers" is a 2. "We ran an experiment and saw 25% improvement" is a 4.

#### Element 6: Ease

**Explain:** Score 1-4. Complexity estimate, not a time estimate. Time estimates are fiction, but complexity is observable.
- 1 = very complex (many weeks, multiple teams, dependencies)
- 2 = complex (a few weeks, some dependencies)
- 3 = medium complexity (about a week, self-contained)
- 4 = low complexity (days, straightforward)

Prefer complexity thinking over duration thinking because it's more honest.

**Ask:** "For each initiative, score ease (1-4) based on complexity, not time. How many teams involved, how many unknowns, how many dependencies?"

**Reflect/Confirm:** Check: are complex items honestly scored, or are we being optimistic? If in doubt, score lower.

#### Element 7: Score and Discuss

**Explain:** ICE Score = Impact x Confidence x Ease. Calculate the scores, but don't stop there. The score is a conversation starter, not the answer. The real value is the disagreements. When two people score Impact differently, that's a strategy alignment gap. When Confidence scores diverge, someone has information the other doesn't. Surface those gaps.

**Ask:** "Calculate ICE scores. Now look at the ranking: does anything feel wrong? Where did scores surprise you? Where would two team members disagree?"

**Reflect/Confirm:** Discuss disagreements. Resolve or note them. The discussion matters more than the number.

**Checkpoint:** Review scores and disagreements before making decisions.

---

### Section 3: The Decision

#### Element 8: Low Confidence, High Impact Items

**Explain:** These are the most dangerous items on the list. High impact + low confidence = potential gold or fool's gold. The answer is not "build it and hope" or "kill it because uncertain." The answer is: run discovery first. What's the cheapest way to increase confidence before committing full resources?

**Ask:** "Are there any high-impact, low-confidence items? For each: what's the cheapest experiment or research that would increase confidence before building?"

**Reflect/Confirm:** For each: define a discovery action, not a build decision. Low confidence items go to "discover first," not "build now" or "kill."

#### Element 9: Final Recommendation

**Explain:** Combine strategy alignment, ICE scores, and the confidence discussion into a final decision per initiative. Four options for each: build now (high confidence, high impact, aligned), discover first (high impact but low confidence), park for later (aligned but lower priority or waiting for capacity), or kill (doesn't connect to objectives or evidence is against it). The output is a decision, not a spreadsheet.

**Ask:** "For each initiative, what's the call: build now, discover first, park for later, or kill? And why?"

**Reflect/Confirm:** Review the full recommendation. Check: did low-confidence items get discovery paths, not just "park"? Are we building the things with the most evidence, not just the most enthusiasm?

---

### Assembly

Combine into a prioritization document. Lead with the strategy test, show ICE only for ambiguous items, and end with clear decisions.

## Output Template

```markdown
# Prioritization: [Product/Team] - [Period]

## Strategy Context
**Strategy:** [2-sentence summary]
**Current Objectives/OKRs:**
- [OKR 1]
- [OKR 2]

## Strategy Clarity Test
| Initiative | Connects to OKR | Strategy Makes It Obvious? |
|-----------|-----------------|---------------------------|
| [name] | [which OKR] | [Yes: priority is clear / No: needs scoring] |

## ICE Assessment (ambiguous items only)
| Initiative | Impact (1-4) | Confidence (1-4) | Ease (1-4) | ICE Score | Key Disagreements |
|-----------|-------------|------------------|-----------|-----------|-------------------|
| [name] | [on objectives] | [evidence level] | [complexity] | [IxCxE] | [where people disagree] |

## Confidence Gaps
| Initiative | Confidence | What Would Increase It | Cost to Learn |
|-----------|-----------|----------------------|---------------|
| [high impact, low confidence items] | [1-2] | [specific evidence needed] | [time/effort] |

## Recommendation
| Initiative | Decision | Rationale |
|-----------|----------|-----------|
| [name] | Build now / Discover first / Park / Kill | [why] |

## Next Actions
[Specific actions for each decision: who does what by when]
```

## Verification Criteria

After drafting, run these checks. For failures: fix silently if you have the context, ask if you need input. Max 3 attempts per check.

### Structural (5 checks)
- [ ] Strategy stated with current OKRs
- [ ] Every initiative mapped to an OKR
- [ ] Strategy clarity test done before scoring
- [ ] Final recommendation present with decision per initiative
- [ ] Next actions defined

### Quality (7 checks)
- [ ] Impact scored against current objectives, not generic value
- [ ] Confidence scores are honest (not all 3-4 without evidence)
- [ ] Scoring disagreements noted and discussed
- [ ] Low-confidence/high-impact items have discovery paths (not just "park" or "build")
- [ ] Recommendations include "discover first" where appropriate
- [ ] Items not connected to OKRs are parked or killed (not scored anyway)
- [ ] Strategy test was genuinely attempted before jumping to ICE

## Common Pitfalls

- **Jumping straight to scoring.** ICE without the strategy test is theatre. If strategy makes priorities obvious, you don't need a framework. Use the framework only for genuinely ambiguous items.
- **Scoring impact generically.** "Good for users" is not a score. Impact must be against current objectives. A feature can delight users and score 1 on Impact if it doesn't serve this quarter's OKRs.
- **Overconfidence bias.** Everyone scores 3-4 on confidence. Challenge it: "What specific evidence supports that? Show me the data, the interview quotes, the experiment results."
- **Using the score as the decision.** ICE produces a number. Humans make decisions. The score is a starting point for conversation. If the ranking feels wrong, investigate why, don't just accept the math.
- **Treating low confidence as low priority.** Low confidence means uncertain, not unimportant. A low-confidence, high-impact item needs discovery, not dismissal. The worst thing you can do is ignore your most promising uncertain bets.
