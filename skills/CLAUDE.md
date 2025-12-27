# Skills

All capabilities live here as `SKILL_NAME/SKILL.md` files with YAML frontmatter.

---

## Skill Hierarchy

```
MAIN SKILLS              UTILITY SKILLS
───────────────────────────────────────────────────────
vision              →    (none)
    ↓
strategy            →    positioning
    ↓
    ├── discovery   →    opportunity-tree, interview-summary
    │
    └── metrics     →    okr-builder, metric-selector,
                         impact-model-builder, leading-lagging-mapper,
                         aarrr-analyzer
    ↓
roadmap             →    initiative-alignment-doc, prioritization
stakeholder         →    initiative-alignment-doc

skill-creator       →    (meta: for building new skills)
```

**Foundation chain:** `context/vision.md` → `context/strategy.md` → `context/roadmap.md`

**Notes:**
- discovery and metrics are parallel (both need strategy, independent of each other)
- prioritization requires roadmap context to be meaningful
- Check earlier foundations exist before building later ones.

---

## Skill Index

| Skill | When to Use |
|-------|-------------|
| **MAIN SKILLS** | |
| `vision` | Vision, purpose, mission, long-term direction (3-5+ years) |
| `strategy` | Strategy, positioning, differentiation, "how to win" |
| `discovery` | Problem validation, user research, "is this worth building" |
| `metrics` | OKRs, KPIs, success measurement, leading indicators |
| `roadmap` | Roadmap, initiative planning, "what to build when" |
| `stakeholder` | Stakeholder alignment, getting buy-in, cross-team coordination |
| **UTILITY SKILLS** | |
| `positioning` | Positioning product, differentiation, crafting messaging |
| `opportunity-tree` | Structuring opportunities, building OST |
| `interview-summary` | Synthesizing interviews into snapshots |
| `okr-builder` | Setting OKRs, defining quarterly goals |
| `metric-selector` | Choosing KPIs, "what should we measure" |
| `impact-model-builder` | Building driver trees, connecting metrics to goals |
| `leading-lagging-mapper` | Indicator relationships, "what predicts outcomes" |
| `aarrr-analyzer` | Analyzing funnels, "where is funnel breaking" |
| `initiative-alignment-doc` | Documenting initiatives, alignment docs |
| `prioritization` | Comparing roadmap options, ranking features, "what should we focus on" |
| **META** | |
| `skill-creator` | Building new skills, creating SKILL.md files |

---

## Tool Compatibility

**Claude Code:** Auto-discovers skills from YAML frontmatter. No manual loading needed.

**Cursor, Codex, Gemini CLI:** Read this index, then:
1. Match user intent to the right skill based on descriptions above
2. Load the relevant `SKILL_NAME/SKILL.md` file
3. Follow its instructions

---

## File Format

Each SKILL.md uses YAML frontmatter:

```yaml
---
name: skill-name
description: Use when [triggers only]. Never summarize workflow.
---
```

---

## Output Quality

Before finalizing any output, verify it follows `style-guide.md` structure:
1. **Overview** - 2-3 sentences: what, why now, what decision
2. **Main content** - Document-specific sections
3. **FAQ** - Strategic questions with `[Suggested answer - Please review]` prefix
