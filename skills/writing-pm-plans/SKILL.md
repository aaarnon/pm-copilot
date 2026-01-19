---
name: writing-pm-plans
description: Use when breaking down PM initiatives into tasks, planning complex product work, or creating execution plans before starting work.
---

# Writing PM Plans

## Overview

Write comprehensive execution plans for PM initiatives. Plans assume the executor may return days later with limited context.

**Announce at start:** "Using writing-pm-plans to create the execution plan."

**Save plans to:** `outputs/plans/YYYY-MM-DD-[initiative-name].md`

---

## When to Use

- Initiative spans multiple deliverables
- Cross-functional coordination needed
- Work will span multiple sessions
- Complex stakeholder alignment required

---

## Plan Document Header

Every plan MUST start with:

```markdown
# [Initiative Name] Execution Plan

> **For Claude:** Use productkit:executing-pm-plans to implement this plan.

**Goal:** [One sentence - what this produces]

**Success Criteria:** [How we know it's done]

**Foundation Status:**
- Vision: [Exists/Missing]
- Strategy: [Exists/Missing]
- Roadmap: [Exists/Missing]

**Dependency Map:**
[ASCII diagram showing task dependencies - which tasks can run in parallel, which block others]

---
```

---

## Task Granularity

Each task = one focused work session (30-60 min equivalent).

**Good task:**
- "Draft problem definition section of alignment doc"
- "Synthesize 3 customer interviews into opportunity tree"
- "Create prioritized initiative list using VEUC framework"

**Bad task (too big):**
- "Create full product strategy"
- "Do discovery research"
- "Build complete roadmap"

**Bad task (too small):**
- "Write one bullet point"
- "Add header to document"
- "Fix typo"

---

## Dependencies & Parallelization

Mark each task's dependency status. This enables:
- Parallel execution when tasks are independent
- Clear blocking relationships
- Resumption without re-reading entire plan

### Dependency Markers

| Marker | Meaning |
|--------|---------|
| `Requires: None` | Can start immediately, independent |
| `Requires: Task 1` | Blocked until Task 1 completes |
| `Requires: Tasks 1, 2` | Blocked until both complete |
| `Requires: External - [description]` | Blocked on stakeholder/external input |

### Identifying Parallel Tasks

Tasks are parallel-capable when they:
- Don't share output files
- Don't depend on each other's deliverables
- Can be reviewed independently

**Example:**
```
Task 2: Draft problem definition     Requires: Task 1
Task 3: Research competitor pricing  Requires: None ← parallel with Task 2
Task 4: Synthesize into strategy     Requires: Tasks 2, 3
```

### Why This Matters

- **For agents:** Independent tasks can run as subagents simultaneously
- **For humans:** Shows which work can be delegated or done out of order
- **For resumption:** Know exactly what's blocked and what's ready

---

## Task Structure

```markdown
### Task N: [Task Name]

**Deliverable:** [What gets created/updated]

**Location:** `outputs/[filename]` or `context/[filename]`

**Requires:** [Task dependencies, or "None - can start immediately"]

**Inputs needed:**
- [Existing context files]
- [Information to gather]

**Steps:**
1. [Specific action]
2. [Specific action]
3. [Verification step]

**Success criteria:**
- [ ] [Measurable outcome 1]
- [ ] [Measurable outcome 2]

**Evidence:** [How to verify completion - file exists, section contains X, stakeholder confirmed]

**Checkpoint:** [When to pause for review, or "None - continue to next"]
```

---

## PM-Specific Checkpoints

Unlike code (commit after each task), PM work uses strategic checkpoints:

| After... | Checkpoint |
|----------|------------|
| Foundation work (vision/strategy) | Review before building on it |
| Problem definition | Validate before solution design |
| Draft deliverable | Review before finalizing |
| Cross-functional impact | Stakeholder alignment |

---

## Example Plan Skeleton

```markdown
# Q1 Roadmap Creation Plan

> **For Claude:** Use productkit:executing-pm-plans to implement.

**Goal:** Create Q1 roadmap with initiative one-pagers

**Success Criteria:**
- Roadmap in Now-Next-Later format
- Top 3 initiatives have alignment docs
- Stakeholder review scheduled

**Foundation Status:**
- Vision: Exists (context/vision.md)
- Strategy: Exists (context/strategy.md)
- Roadmap: Creating

**Dependency Map:**
```
Task 1 (Audit) ──┬──→ Task 3 (Draft Roadmap)
                 │
Task 2 (Research) ┘    ↓
                      Task 4 (Alignment Docs)
```

---

### Task 1: Audit Current State

**Deliverable:** Gap analysis summary
**Location:** outputs/q1-gap-analysis.md

**Requires:** None - can start immediately

**Inputs needed:**
- context/strategy.md
- Current initiative list (if exists)

**Steps:**
1. Read context/strategy.md for strategic priorities
2. List initiatives already in progress
3. Identify gaps between strategy and current work
4. Document findings in gap analysis file

**Success criteria:**
- [ ] Strategic themes identified
- [ ] In-progress initiatives listed
- [ ] Gaps articulated

**Evidence:** outputs/q1-gap-analysis.md exists with all three sections populated

**Checkpoint:** Review gaps before prioritization

---

### Task 2: Research Competitor Initiatives

**Deliverable:** Competitor landscape summary
**Location:** outputs/q1-competitor-landscape.md

**Requires:** None - can start immediately (parallel with Task 1)

**Inputs needed:**
- Competitor websites/product pages
- context/company-profile.md for market context

**Steps:**
1. Identify top 3 competitors from company profile
2. Document their recent launches/focus areas
3. Note gaps in our positioning

**Success criteria:**
- [ ] 3 competitors analyzed
- [ ] Recent initiatives documented
- [ ] Positioning gaps identified

**Evidence:** outputs/q1-competitor-landscape.md exists with competitor table

**Checkpoint:** None - continue to next

---

### Task 3: Draft Roadmap Structure

**Deliverable:** Q1 roadmap draft
**Location:** outputs/q1-roadmap-draft.md

**Requires:** Tasks 1, 2 (needs gap analysis + competitor context)

**Inputs needed:**
- outputs/q1-gap-analysis.md
- outputs/q1-competitor-landscape.md
- context/strategy.md

**Steps:**
1. Invoke prioritization skill with gap analysis as input
2. Apply VEUC or DHM framework
3. Create Now-Next-Later structure
4. Document trade-offs for each placement

**Success criteria:**
- [ ] Now: 2-3 committed initiatives
- [ ] Next: 3-5 candidate initiatives
- [ ] Later: Backlog items listed
- [ ] Trade-offs documented per initiative

**Evidence:** outputs/q1-roadmap-draft.md has Now/Next/Later sections, each with at least one item

**Checkpoint:** Stakeholder review of priorities before alignment docs

---

[Continue with Task 4: Create Alignment Docs for Top 3...]
```

---

## Execution Handoff

After saving the plan:

"Plan saved to `outputs/plans/[filename].md`. Ready to execute?

**Options:**
1. **Continue now** - Use executing-pm-plans skill
2. **Pause for review** - Review plan first, execute later
3. **Share plan** - Get stakeholder input before executing

Which approach?"

---

## Remember

- Task = one session of focused work
- Include success criteria for every task
- **Add Evidence field** - How to verify completion concretely
- **Mark dependencies** - `Requires: None` or `Requires: Task N`
- **Identify parallel tasks** - Independent tasks can run simultaneously
- Specify checkpoint moments (or "None - continue")
- Reference other skills when needed (prioritization, metrics, etc.)
- Use `[Needs input: ...]` for information gaps
