---
name: executing-pm-plans
description: Use when executing a written PM plan, implementing initiative tasks with checkpoints, or resuming work on a planned PM initiative.
---

# Executing PM Plans

## Overview

Load plan, review critically, execute tasks with strategic checkpoints.

**Core principle:** Checkpoint at strategic moments, not after every micro-task.

**Announce at start:** "Using executing-pm-plans to implement this initiative."

---

## The Process

### Step 1: Load and Review Plan

1. Read plan file from `outputs/plans/`
2. Review critically:
   - Are success criteria clear?
   - Are inputs available?
   - Any missing context?
3. Check foundation status (vision/strategy/roadmap)
4. If concerns: Raise before starting
5. If no concerns: Create TodoWrite and proceed

### Step 2: Execute Task

For each task:

1. **Check dependencies:** If `Requires: Task N`, verify that task is complete first
2. **Announce:** "Starting Task N: [name]"
3. **Check inputs:** Verify context files exist
4. **Follow steps:** Execute exactly as written
5. **Verify:** Check success criteria
6. **Confirm evidence:** Check the Evidence field - does the concrete proof exist?
7. **Save:** Deliverable to specified location
8. **Mark complete:** Update todo list

**Parallel execution:** Tasks with `Requires: None` or whose dependencies are met can run simultaneously. Use subagents for independent tasks when appropriate.

### Step 3: Checkpoint

At each checkpoint specified in plan:

```
## Checkpoint: [Task Name] Complete

**Completed:** [What was done]
**Deliverable:** [Link to file]
**Verified:** [Success criteria status]

Ready for feedback. Continue to next task, or review first?
```

### Step 4: Handle Blockers

**STOP executing immediately when:**
- Missing input (context file doesn't exist)
- Success criteria unclear
- Stakeholder input needed but not available
- Task depends on external action
- **Dependency not met** (`Requires: Task N` but Task N incomplete)

**Don't guess.** State the blocker and wait.

### Step 4b: Parallel Execution (Optional)

When multiple tasks have dependencies satisfied:

1. **Identify ready tasks:** All tasks where `Requires` is met
2. **Check independence:** Tasks don't share output files
3. **Execute in parallel:** Use subagents or work simultaneously
4. **Sync at checkpoints:** Gather results before dependent tasks

**Example:**
```
Tasks 1, 2 both have Requires: None → Execute in parallel
Task 3 has Requires: Tasks 1, 2 → Wait for both, then execute
```

### Step 5: Complete Initiative

After all tasks verified:

1. Announce: "Using verification-before-completion to finalize."
2. Run full verification against plan success criteria
3. Report completion status with evidence

---

## PM-Specific Execution Patterns

### Red Mode (Committed Bet)
- Scope and timeline defined, execute the plan
- Move faster through tasks
- Checkpoints at deliverable boundaries
- Focus on completion

### Blue Mode (Figuring Out)
- Still exploring what to build
- Pause more for validation
- Checkpoints include "what did we learn?"
- Be willing to abandon tasks if learning invalidates them

**Note:** Red/Blue is about decision certainty, not company stage. Pre-PMF teams building to validate are in Red mode.

---

## Resuming Work

When returning to an in-progress plan:

1. Read plan file
2. Check deliverables created so far (scan `outputs/`)
3. Identify last completed task
4. State: "Resuming at Task N. Last completed: [task name]"
5. Continue execution

---

## Invoking Other Skills

Plans often reference other skills. When plan says:
- "Use prioritization skill" → Invoke that skill
- "Apply DHM framework" → Check knowledge/resources.md first
- "Create one-pager" → Follow style-guide.md

Stay within the plan structure while using referenced skills.

---

## Remember

- Review plan critically before starting
- **Check dependencies** before starting each task
- **Verify evidence** after each task, not just success criteria
- **Run parallel tasks** when dependencies allow
- Follow plan steps exactly
- Don't skip checkpoints
- Save deliverables to specified locations
- Stop when blocked, don't guess
- Reference other skills when plan says to
