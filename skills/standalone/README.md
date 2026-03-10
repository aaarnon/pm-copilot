# ProductKit Standalone Skills

Standalone PM skills that work in any project. Each skill guides you through creating a proper deliverable using structured co-creation: one question at a time, building understanding before producing output.

## Installation

Copy the skill files you need into your project's skills directory, or reference them from your agent configuration.

**Claude Code:** Place in `~/.claude/skills/` or your project's skills folder.
**Cursor:** Reference in `.cursor/agents/AGENTS.md`.
**Other agents:** Follow your platform's skill loading mechanism.

## Skills

| Skill | Trigger | Produces |
|-------|---------|----------|
| `product-vision` | "I need to align the team on where we're going" | Vision statement with purpose, future state, impact |
| `product-strategy` | "I need to write a strategy doc" | Strategy doc with narrative, playing field, winning moves |
| `product-okrs` | "I need to set quarterly goals" | 2-3 Objectives with measurable Key Results |
| `discovery-plan` | "I need to validate an idea" | Discovery plan with risks, methods, confidence thresholds |
| `product-alignment-one-pager` | "I need to pitch an initiative" | Product Alignment Document (opportunity + solution framing) |
| `product-roadmap` | "I need to plan what we're building" | Now/Next/Later roadmap with Discovery and Delivery split |
| `product-prioritization` | "I need to decide what to work on next" | Strategy-tested prioritization with ICE alignment |

## Recommended Order

These skills build on each other. You can use any skill standalone, but the recommended foundation chain is:

```
Vision (why we exist)
    ↓
Strategy (how we win)
    ↓
OKRs (how we measure success)
    ↓
Discovery (what problems to solve) + Prioritization (what order)
    ↓
Roadmap (what to build when)
    ↓
Alignment One-Pager (per initiative)
```

Each skill has a "Soft Prerequisites" section that recommends (but doesn't require) prior work.

## How They Work

Every skill uses the same co-creation pattern:

1. **Explain** - The skill teaches you the concept (1-2 sentences)
2. **Ask** - One focused question to gather your input
3. **Reflect** - Restates what was heard to confirm understanding
4. **Confirm** - Gets explicit agreement before moving to the next element

This prevents misalignment and ensures you understand what you're building at each step.

## Verification

Each skill includes 10-15 verification checks that run automatically after drafting the deliverable. Failed checks trigger a conversation to fix the gap. This catches the most common quality issues without being exhaustive.

## Self-Contained

These skills are fully self-contained. All frameworks and best practices are embedded in the skill files themselves. No external knowledge base or reference material needed.
