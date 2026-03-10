---
name: discovery-plan
description: Use when validating a product idea, planning user research, or when the team is about to build something without evidence that the problem exists
---

# Discovery Plan

Build a discovery plan through structured co-creation. Discovery is about reducing risk before committing resources. If you're building without evidence the problem exists, you're gambling, not building product.

## Soft Prerequisites

Discovery works best when you know what outcomes matter (strategy, metrics) and what problems you're exploring. If you have no strategic context, the discovery might validate a problem that doesn't matter. Consider `product-strategy` first if direction is unclear.

## Co-Creation Flow

Three sections, each with a checkpoint:

```
Opportunity Framing (2 elements)
    ↓ checkpoint
Risk Assessment (4 elements)
    ↓ checkpoint
Discovery Design (2 elements)
    ↓ assemble
```

Work through each element one at a time. For each: explain the concept, ask one question, reflect back what you heard, confirm before moving on.

---

### Section 1: Opportunity Framing

#### Element 1: Problem Statement

**Explain:** Start with the problem, not the solution. "Users struggle to find relevant content" is a problem. "We should build a search feature" is a solution. Premature solutions are the #1 discovery killer: they narrow your thinking before you understand the space. State who has the problem, what the problem is, and how you know it exists.

**Ask:** "What problem are you exploring? State it from the user's perspective, without mentioning any solution. Who has this problem, and how do you know?"

**Reflect/Confirm:** Check: is this a problem or a solution in disguise? "Users need a dashboard" is a solution. "Users can't tell if their campaigns are working" is a problem.

#### Element 2: Desired Outcome

**Explain:** What does success look like if you solve this problem? An outcome, not a feature. This should connect to a metric the team cares about. It's your "why bother": the reason this problem is worth investigating at all.

**Ask:** "If you solved this problem completely, what would change? What metric would move, or what behavior would shift?"

**Reflect/Confirm:** Check: does this connect to something strategically important? If solving the problem wouldn't move a metric you care about, question whether it's worth discovery effort.

**Checkpoint:** Is this problem worth investigating? Is the potential impact clear?

---

### Section 2: Risk Assessment

Four types of risk. Assess each independently.

#### Element 3: Value Risk

**Explain:** Will anyone want this? This is the risk that the problem isn't real, isn't painful enough, or that users won't switch from their current approach. It's the most important risk because nothing else matters if value is zero.

**Ask:** "What evidence do you have that people actually have this problem and care enough to change their behavior? Rate your confidence: strong evidence, some evidence, weak evidence, or assumption only."

**Reflect/Confirm:** Be honest about confidence level. "Some customers mentioned it" is different from "40% of churned users cited it as the reason."

#### Element 4: Usability Risk

**Explain:** Can people figure out how to use it? Even if the problem is real and the solution is right, poor usability kills adoption. Is the interaction complex, novel, or does it follow patterns users already know?

**Ask:** "If you built a solution, how complex would the user interaction be? Would users need to learn something new, or does it fit their existing mental model?"

**Reflect/Confirm:** Rate: High (novel interaction, learning curve), Medium (some new patterns), Low (familiar patterns, obvious flow).

#### Element 5: Feasibility Risk

**Explain:** Can you build it? Technical constraints, dependencies, third-party integrations, data availability, performance requirements. Be honest about unknowns: "we think we can" is different from "we've prototyped it."

**Ask:** "What are the biggest technical unknowns or dependencies? Is there anything you're not sure you can build?"

**Reflect/Confirm:** Rate: High (unproven technology, major unknowns), Medium (some unknowns, manageable dependencies), Low (well-understood, similar to what we've built before).

#### Element 6: Business Viability Risk

**Explain:** Should you build it? Does it align with strategy? Can you support it long-term (maintenance, support, infrastructure)? Can you price it? Will it cannibalize existing revenue? A great product that doesn't fit your business model is still a bad bet.

**Ask:** "Does this align with your strategy? Can you sustain it operationally? Are there pricing, legal, or support implications?"

**Reflect/Confirm:** Rate: High (unclear strategic fit, significant operational burden), Medium (aligned but with considerations), Low (clear strategic fit, manageable operations).

**Checkpoint:** Review the risk profile. Which risks are highest? Those determine the discovery methods.

---

### Section 3: Discovery Design

#### Element 7: Methods Matched to Risks

**Explain:** Different risks need different methods. Value risk: talk to users (interviews, surveys, data analysis). Usability risk: show them something (prototypes, usability tests). Feasibility risk: try to build it (technical spikes, proof of concepts). Business viability risk: model it (financial analysis, operational planning). Don't run a survey when you need a conversation. Don't build a prototype when you need a spreadsheet.

**Ask:** "For your highest risk: what's the cheapest, fastest way to learn? What method would reduce that specific uncertainty?"

**Reflect/Confirm:** Map each high risk to a specific method. Check: does the method actually address the risk? An interview doesn't reduce feasibility risk. A technical spike doesn't reduce value risk.

#### Element 8: Confidence Threshold

**Explain:** How confident do you need to be before building? A reversible two-week experiment needs less confidence (60%) than a six-month platform rewrite (90%). Set the bar before you start, not after. Otherwise you'll keep discovering until you feel comfortable, which is never.

**Ask:** "How big and reversible is the investment if you proceed to build? Based on that: what confidence level (60-90%) do you need to reach before committing?"

**Reflect/Confirm:** Confirm the threshold. Also ask: "What would make you change your mind? What disconfirming evidence are you looking for?" This prevents confirmation bias.

---

### Assembly

Combine into a discovery plan that connects problem to risks to methods, with a clear confidence threshold.

## Output Template

```markdown
# Discovery Plan: [Opportunity Name]

## Problem Statement
- **Who:** [specific audience]
- **Problem:** [what they struggle with, in their words]
- **Evidence:** [how we know this is real]
- **Desired Outcome:** [what changes if we solve it, what metric moves]

## Risk Assessment
| Risk | Level | Key Question | Current Evidence |
|------|-------|-------------|-----------------|
| Value | [High/Med/Low] | [Will anyone want this?] | [What we know] |
| Usability | [High/Med/Low] | [Can they use it?] | [What we know] |
| Feasibility | [High/Med/Low] | [Can we build it?] | [What we know] |
| Viability | [High/Med/Low] | [Should we build it?] | [What we know] |

## Discovery Methods
| Risk to Address | Method | Timeline | What We'd Learn |
|----------------|--------|----------|----------------|
| [Highest risk first] | [Interview/Prototype/Spike/etc] | [Duration] | [Specific question answered] |

## Confidence Threshold
- **Required confidence before building:** [%]
- **Rationale:** [why this level, based on investment reversibility]

## What Would Change Our Mind
[Disconfirming evidence we're actively looking for. Not strawmen, real things that would make us stop.]
```

## Verification Criteria

After drafting, run these checks. For failures: fix silently if you have the context, ask if you need input. Max 3 attempts per check.

### Structural (5 checks)
- [ ] Problem statement present with who/what/evidence
- [ ] All four risks assessed with confidence levels
- [ ] At least one method per high-risk area
- [ ] Confidence threshold set with rationale
- [ ] "What would change our mind" section present

### Quality (7 checks)
- [ ] Problem is stated as a problem, not a solution
- [ ] Evidence field has actual data or observations, not just assumptions
- [ ] Methods match the risks they address (interviews for value, prototypes for usability, spikes for feasibility)
- [ ] Highest risks get the most attention and resources
- [ ] Confidence threshold is calibrated to investment reversibility
- [ ] Disconfirming evidence is genuinely sought (not strawmen easily dismissed)
- [ ] Timeline is realistic for the methods chosen

## Common Pitfalls

- **Solution masquerading as problem.** "Users need a dashboard" is a solution. "Users can't tell if their campaigns are working" is a problem. If the problem statement contains a feature name, rewrite it.
- **Discovery theatre.** Going through the motions with your mind already made up. If you already know what you'll build regardless of findings, skip the charade.
- **All risks rated "medium."** This is conflict avoidance, not assessment. Force honest ratings. At least one risk should be High, or the opportunity isn't uncertain enough to need discovery.
- **Only looking for confirmation.** If your discovery plan doesn't include "what would make us stop," you're seeking validation, not truth.
- **Over-engineering discovery for small bets.** A reversible two-week experiment doesn't need six weeks of discovery. Match the discovery effort to the investment size.
