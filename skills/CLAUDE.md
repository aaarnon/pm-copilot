# Skills

Skills are discrete tools that produce specific outputs. Unlike agents (extended conversations), skills run once and return a result - a prioritized list, an OKR draft, an opportunity tree, etc.

Skills can be invoked by users directly or called by agents during coaching sessions.

---

## Invocation Modes

| Mode | Meaning | Example |
|------|---------|---------|
| **Hybrid** | User or agent can invoke | "Help me prioritize" triggers prioritization skill |
| **Agent-called** | Only agents invoke | OKR builder called by Metrics agent |

---

## File Format

Each skill file uses YAML frontmatter + markdown content:

```yaml
---
name: skill-name
description: What it does + when to use it. Third person. Include trigger terms.
---
```

**Required sections:**
- Purpose (one line)
- Invocation (hybrid or agent-called)
- When to Use (trigger scenarios)
- Process/Template
- Output Format

→ Use `skill-creator.md` as reference when creating new skills.
