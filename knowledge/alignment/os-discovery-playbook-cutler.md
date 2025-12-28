# The OS Discovery Playbook

**Author:** John Cutler (Dotwork)

**Source:** https://docs.google.com/document/d/1NJN5yc-yuIPHBNLlgFq3x2BanX179OQeJr3ZSrEM-rw/

**Version:** Draft 1.0 (November 2025)

**License:** CC BY 4.0

---

## Overview

A structured approach to discovering how an organization actually works today, including its cycles, rituals, artifacts, language, structures, systems, and decision patterns. The goal is to collect raw inputs needed to design, configure, and instrument your operating system.

**Core insight:** You are creating an internal platform, not buying and installing a vendor product. Your operating system has customers, objectives, and deserves intentional design.

---

## The Internal Platform Mindset

Your operating system is a multi-sided product:

| Side | What They Need |
|------|----------------|
| **Leaders** | High-level view, reliable way to broadcast context, ability to drill into details |
| **Managers & Teams** | Context for good decisions, way to share their own context, collaboration with partners |

**North Star:** Better decision making and more engaged team members.

**Key inputs:** Reduced friction, better data quality, improved collaboration, clearer insights, early detection of risks, healthier conversations.

> You want to encourage helpful behaviors, not zombie processes. Organizations are full of non-value-add processes that people simply march through.

---

## How Tools Can Help

| Intervention | Description | How Tools Help |
|--------------|-------------|----------------|
| Education | Build understanding, deliver relevant information | Structured visibility, embedded context, real-time access to strategic info |
| Training | Develop skills through guided practice | Templates, walkthroughs, embedded workflows |
| Enablement | Remove barriers or add support mechanisms | Reduces coordination friction, surfaces blockers, nudges and scaffolds |
| Persuasion | Influence attitudes through communication | Nudges, progress indicators, visible value pathways |
| Modeling | Demonstrate desired behavior through example | Makes good behaviors and patterns across teams visible |
| Environmental Restructuring | Change context to enable behavior | Shapes flow of work: rituals, dashboards, check-ins, new defaults |

---

## "The PDF"

Some companies enjoy documenting how they work. Others prefer organic evolution. Both can succeed.

**If documentation exists:** Find "The PDF", the document or set of documents explaining how things work. It helps make sense of everything else.

**If documentation is scattered or aspirational:** Don't worry. Start discovering what actually happens.

---

## Chapter 1: Ops-ortunities

Ops-ortunities surfaces the operational opportunity space. It highlights possibility rather than blame.

### Part 1: Opportunity Mad Libs

Two templates for articulating opportunities:

**Mad Lib A:**
> If we can figure out how to [increase/decrease] the [attribute or dynamic] of [process, system, or behavior] for [a specific person or group], we could unlock [meaningful benefit].

**Mad Lib B:**
> If we can figure out how to [increase/decrease] the [attribute or dynamic] of [a process, system, or behavior], we could unlock [a meaningful benefit].

**Examples:**
- If we can increase the visibility of impact for research teams, we could unlock stronger motivation and tighter collaboration with product.
- If we can decrease the cognitive load of onboarding for new team members, we could unlock faster ramp-up and earlier engagement.

### Part 2: Lifecycle Mapping

Place practices along a lifecycle curve:

```
Pilot         Hidden        Bright Spots    Manual Wins /    Optimize    Local      Zombie
Candidates    Strengths     to Scale        Tech Opps        & Tweak     Maxima     Practices
    |            |              |               |               |           |           |
    v            v              v               v               v           v           v
[Early ideas] [Quiet wins]  [Working in    [Fragile,       [Good but   [Plateau,   [Outlived
              [to surface]   one pocket]    manual]         not great]  needs shift] usefulness]
```

| Category | Anchoring Quote |
|----------|-----------------|
| Pilot Candidates | "Let's try this on a small scale and see what we learn." |
| Hidden Strengths | "If only more people saw how well this is working." |
| Bright Spots to Scale | "It's working over here, how do we help it work over there too?" |
| Manual Wins / Tech Opportunities | "It works, but only because someone is heroing it manually." |
| Optimize and Tweak | "It's working reliably, now let's sharpen it." |
| Local Maxima | "We've gotten as far as we can with this approach." |
| Zombie Practices | "Why are we still doing this?" |

### Capability Areas to Explore (from Marty Cagan's Transformed)

| Capability Area | Increase | Decrease |
|-----------------|----------|----------|
| Discovery Research | Generative/evaluative research, customer access, instrumentation | Shipping without validated insights |
| Aligned Autonomy | Clear problem ownership, stable missions, trust | Constant reorgs, top-down directives |
| Problem/Outcome Focus | Framing around problems, outcomes, hypotheses | Feature-factory output with no clarity on why |
| Strategic Context | Broad access to vision, competitive context, rationale | Siloed plans, stale decks |
| Transparency | Real-time visibility of roadmaps, experiments, learnings | Hidden backlogs, late-breaking surprises |
| Stakeholder Support | Leadership sponsorship, coaching, unblockers | Directives without context or follow-through |
| Alignment & Collaboration | Shared language, clear decision paths | Coordination tax, conflicting stories |
| Process Friction | Lean approval paths, efficient decision flows | Excessive gates, committees, slow cycles |
| Culture of Learning | Regular retros, experiment reviews, coaching | Blame, status-quo mindset |
| Funding Mentality | Outcome-based funding, flexible budgeting | Rigid forecasts forcing premature commitments |

---

## Chapter 2: Core Cycles

Organizations have interlocking rhythms: external (fiscal year, seasonality), calendar-based (quarters, months, weeks), and intentional choices (planning, budgeting, reviews).

### Cycle Definition Table

| Field | What to Capture |
|-------|-----------------|
| Cycle Name | What people actually call it |
| Start, End, Length | When it begins, closes, and overall duration |
| Purpose | Why this cycle exists |
| Key Inputs | Information or artifacts needed to kick off |
| Key Outputs | What emerges when the cycle closes |
| Who Runs It | Leaders or teams responsible for coordinating |
| Interactions | Where this cycle overlaps or collides with others |

### Common Cycles

| Cycle | Timing | Description |
|-------|--------|-------------|
| Long-Range Planning (LRP) | Apr-May | Multi-year strategic direction, investment themes |
| Mid-Year Refresh | Jun-Jul | Reality check, course-correct for rest of year |
| Annual Planning | Aug-Oct | Company-wide reset, direction, budgets, priorities |
| Budget Season | Sep-Nov | Financial constraints: spending, hiring, vendors |
| Quarterly Prioritization | End of each quarter | Deciding what gets worked on next |
| Monthly Initiative Review | First week each month | Progress, risks, sequencing adjustments |
| Weekly Release Window | Weekly | Predictable deployment rhythm |
| Daily Standups | Daily | Micro-alignment, blockers, handoffs |

> When rhythms work well, they complement each other. When they don't, people get bounced between competing cycles.

---

## Chapter 3: Rituals

A ritual is any intentional, repeating set of interactions designed to output decisions, actions, or outcomes.

### Ritual Definition Table

| Area | Description |
|------|-------------|
| Name | How team members actually refer to the ritual |
| Ownership | Who owns outputs, sponsors it, organizes it |
| Attendees | Who participates and in what role |
| Frequency/Cadence | Fixed schedule or event-triggered |
| Inputs | Information collected, prep work, analysis |
| Outputs | Decisions, insights, documents, action items |
| Artifacts | Decks, docs, spreadsheets, dashboards used |
| Health | Mature but heavy prep? Work in progress? Needs redesign? |
| Areas for Improvement | What's working, what's not, where is friction |

### Example: Monthly Initiative Review

**Ownership:** VP of Product sponsors, PMs prepare content, Product Ops organizes

**Attendees:** PMs, Engineering Leads, Design Leads, VP Product, Finance Partner

**Cadence:** Monthly on second Tuesday, plus ad-hoc when initiatives enter/exit quarter slate

**Inputs:** 10-12 slide deck with KPIs, Jira exports, customer insights, PM narratives

**Outputs:** Alignment on sequencing, refreshed priority list, follow-up owners

**Pain points:** Heavy prep burden (many hours), stale data from manual copying, unclear ownership of follow-ups

---

## Chapter 4: Artifact Safari

Artifacts are the real operating system. They reveal how information is stitched together, who needs to be convinced, and what evidence matters.

### Artifact Catalog Questions

| Question | What You Capture |
|----------|------------------|
| What is the artifact? | Name, type, short description |
| Who creates it? | Role or team responsible |
| Who consumes it? | Decision makers, reviewers |
| When is it used? | The ritual, cadence, or trigger |
| What decisions depend on it? | What gets approved, aligned, prioritized |
| What information does it combine? | Data sources, systems it pulls from |
| Where does it live today? | Where people go to find it |
| How stable or repeatable is it? | Template vs. reinvented each time |
| What pain points exist? | Prep burden, duplication, manual steps |
| How could tools help? | Opportunities to reduce prep, connect data |

### Anchor Artifacts: Horizon + Cadence

Two questions reveal hidden friction:

1. **What horizon does this artifact represent?** (2 weeks, 30 days, quarter, year, multi-year)
2. **How often is it meant to be updated?** (Daily, weekly, monthly, quarterly, ad-hoc)

> Teams often treat short-horizon artifacts as if they should be stable for months, or expect long-horizon artifacts to update weekly. These mismatches create confusion and rework.

---

## Chapter 5: Noun Farming

Extracting the actual language used in your organization. The goal is "minimally viable consistency", not a big glossary everyone uses.

### Approach

1. **Rapid brainstorming:** Generate unfiltered list of common nouns (Initiatives, Pillars, Epics, Tasks, Tribes, etc.)
2. **Combine duplicates:** Merge obviously identical concepts
3. **Clarify each item:**

| Area | Description |
|------|-------------|
| Name | The actual term people use |
| Meaning | Different perspectives on what it refers to (squishiness expected) |
| Usage | Actual examples of how people use the term |
| Lifecycle | How it comes to be, who owns it, stages, when it stops mattering |
| Relationships | How it relates to other items |
| Health and Usage | Core and up to date? Rarely used? Politically sensitive? |

### The 4 Graphs Model

Consider nouns and relationships across four categories:

```
           CONTEXT                    INTENT
    ┌──────────────────┐      ┌──────────────────┐
    │ - Opportunities  │      │ - Focus Areas    │
    │ - Insights       │      │ - Objectives     │
    │ - Value Models   │      │ - Work           │
    └──────────────────┘      └──────────────────┘

        COLLABORATION              INVESTMENT
    ┌──────────────────┐      ┌──────────────────┐
    │ - Team Structure │      │ - Unit of Funding│
    │ - Collaboration  │      │ - Horizons/Cycles│
    │ - Skills/Caps    │      │ - ROI            │
    └──────────────────┘      └──────────────────┘
```

---

## Chapter 6: Organizational Structure

### Step 1: Containment and Grouping

Select a team. Work up the org chart:
> "[Team] is a part of [Group] which is a part of [Department] which is part of [Division]"

Repeat for teams across different parts of the organization.

### Step 2: Domain Context

Classify teams by primary paradigm:

| Approach | Description | Example |
|----------|-------------|---------|
| Customer Journey Stages | Aligned to journey steps (awareness, onboarding, retention) | Onboarding team owns first-time user flow |
| Customer Segment | Aligned to customer groups (SMB vs Enterprise) | SMB team tailors for small businesses |
| Surface/Channel | Aligned to customer-facing surfaces (mobile, web, API) | Mobile App team owns iOS/Android |
| Customer Job-to-Be-Done | Organized around core jobs customers need | Payments team enables checkout |
| Product Area/Module | Bounded parts of product needing ongoing ownership | Notifications team owns email, SMS, in-app |
| Geography/Region | Aligned to specific regions | Europe team handles GDPR compliance |
| Architecture Layers | Aligned to technical stack layers | Backend Services team manages APIs |
| Internal Capability/Platform | Shared capabilities other teams consume | Developer Tooling provides CI/CD |
| Specialized Discipline | Deep expertise supporting multiple teams | ML team builds recommendation models |
| Initiative-Based | Temporary teams for specific initiatives | Growth Experiment team for 3 months |

### Step 3: Build Team Spreadsheet

Columns: Team Name, Containment Levels 1-4, Primary Paradigm, Primary Domain, Secondary Paradigm(s), Secondary Domain(s), Notes/Conflicts

---

## Chapter 7: Clarifying Your Intent Graph

Most companies present intent as a tidy pyramid. Reality is more fractal: company has strategy, teams have strategy, company has goals, teams have goals.

```
                         ┌─────────────┐
                         │   Mission   │  10 years
                         └──────┬──────┘
                         ┌──────┴──────┐
                         │   Strategy  │  3-5 years
                         └──────┬──────┘
                    ┌───────────┼───────────┐
              ┌─────┴─────┐          ┌──────┴─────┐
              │  Pillar   │          │   Pillar   │  12-24 months
              └─────┬─────┘          └──────┬─────┘
                    │                       │
              ┌─────┴─────┐          ┌──────┴─────┐
              │ Objective │          │  Objective │  1 quarter
              └─────┬─────┘          └──────┬─────┘
                    │                       │
              ┌─────┴─────┐          ┌──────┴─────┐
              │ Initiative│          │ Initiative │  1-2 quarters
              └─────┬─────┘          └──────┬─────┘
                    │                       │
              ┌─────┴─────┐          ┌──────┴─────┐
              │   Epic    │          │    Epic    │  2-4 weeks
              └─────┬─────┘          └──────┬─────┘
                    │                       │
              ┌─────┴─────┐          ┌──────┴─────┐
              │   Task    │          │    Task    │  1-3 days
              └───────────┘          └────────────┘
```

### Exercise 1: Walk Up the Intent Graph

Pick a real task. For each hop upward, identify: Name, Typical timeframe, What it describes.

Keep going until you reach abstract strategy.

### Exercise 2: Trace the Flow

Pick something currently in flight. Walk backward (where did it come from?) and forward (where is it supposed to lead?).

**Flow stages:**

```
Insight → Opportunity → Options → Bet → Workstream → Releases → Impacts → Drivers → North Star → Business Outcomes
```

### Exercise 3: Work Categorization Schemes

| Category Type | What It Describes | Examples |
|---------------|-------------------|----------|
| Time Allocation | How capacity is spent | Feature work, maintenance, tech debt, experiments |
| Initiative Shape | Nature of the work | Quick win, spike, platform pillar, multi-quarter bet |
| Outcome Type | Expected impact | Revenue, adoption, retention, efficiency |
| Horizon/Timing | When outcomes materialize | Near-term (1-3 months), mid-term (1-3 quarters), long-term |
| Risk Profile | Inherent risk | Low-risk, high-risk, irreversible |
| Team Involvement | Teams required | Single-team, multi-team, cross-org |

---

## Chapter 8: Cataloging Core Information Systems

### System Catalog Fields

| Field | Description |
|-------|-------------|
| System Name | Name of system/tool/product |
| Purpose | What it does, why it exists |
| Information That Lives There | Types of information stored |
| How Information Is Structured | Organization: objects, records, workflows |
| Who Uses It | Teams or roles that interact |
| What Information Is Used For | Decisions, reporting, planning |
| Who Owns the System | Responsible for uptime, schema, permissions |
| Who Updates the Information | Who updates which parts |
| Copy/Paste Behavior | Does info get copied into decks, spreadsheets? |
| Native Views as Artifacts | Any dashboards/reports that serve as artifacts directly |

### Exploratory Questions

Where would you go right now to:
- Reacquaint yourself with high-level strategy?
- View details about a particular team's mission, roadmap, metrics?
- Learn about background and rationale for a specific initiative?
- See goals and progress for a team this quarter?
- Find what shipped last week that customers are using?
- See current blockers affecting the business?
- Learn about recent customer research and insights?

---

## Chapter 9: Budgeting, Funding, and Investment Mentality

### Key Questions

- When are budgets finalized?
- What funding models are used across the organization?
- What is the relationship between Finance and the technology organization?
- How do teams pitch for increased investment, and when?
- How does the org report on return on investment?
- What dimensions describe investment? ("We split investments across __, __, and __")
- What is the currency of investment? (Time, story points, percent, "major focus"?)

### Funding Models

| Context | Expand Approach | Protect Approach |
|---------|-----------------|------------------|
| Company-in-a-Company | Show capacity-constrained growth | Show run-rate at risk + SLA breach cost |
| Service/Internal Vendor | Demand > capacity with unit economics | Risk + continuity framed in cost terms |
| Platform/Capability | Tie to portfolio velocity + shared cost avoidance | Show maintenance debt creating portfolio drag |
| Blurry/Long-Horizon | Use leading indicators + learning milestones | Frame option value + prevention of bad bets |
| Ad-Hoc Cross-Org Program | Tranche the ask with critical-path math | Contain sunk cost, finish viable slice |
| Value-Stream/Team-of-Teams | Link flow metrics to bottlenecks | Emphasize throughput stability + quality cost |

---

## Chapter 10: Understanding Current Prioritization Frameworks

### Common Frameworks

| Framework | Where Typically Used | What It Prioritizes |
|-----------|----------------------|---------------------|
| WSJF | Quarterly planning | Cost of delay vs duration |
| RICE | Product teams, early-stage | Reach, Impact, Confidence, Effort |
| Impact vs Effort | Ideation, shaping | Quick wins vs big bets |
| MoSCoW | Design, requirements | Must/Should/Could/Won't |
| Theme-Based | Leadership, roadmapping | Strategic alignment |
| Financial Lens (ROI) | Executive, annual planning | Expected ROI, budget impact |
| "Leadership Top 5" | Executive direction | What leadership wants now |
| "What Sales Needs" | Revenue-driven orgs | Customer commitments |

### Catalog Fields

| Field | What to Capture |
|-------|-----------------|
| Framework Name | What people call it |
| Where It's Used | Teams, decisions, artifacts |
| What It Prioritizes | Types of work |
| How It Works in Practice | Formal/informal, when applied, when ignored |
| Notes | Conflicts, gaps, overrides |

---

## Appendix: Good Games vs. Barriers to Behavior Change

### What Good Games Get Right

- Clear, attainable goals people understand
- Good balance of difficulty
- Timely feedback for adjustment
- Engaging mechanics
- Visible signs of small progress
- Meaningful choices creating agency
- Calibrated learning curve promoting mastery
- Social interactions making experience richer

### What Blocks Behavior Change (Julie Dirksen)

- Lack of feedback
- Unclear goals
- Unlearning existing behavior
- Unawareness of consequences
- Lack of environment/process support
- Anxiety, fear, discomfort
- Lack of confidence
- Mistrust
- Social proof working wrong direction
- Lack of autonomy
- Learned helplessness
- Misaligned incentives
- Lack of identity/value alignment

---

## Summary: Done When Checklist

| Section | You're Done When |
|---------|------------------|
| Ops-ortunities | Generated opportunity statements, placed practices on lifecycle, spotted leverage points |
| Core Cycles | Listed cycles with real names, documented inputs/outputs/owners, mapped interactions |
| Rituals | Listed rituals performed, captured purpose/cadence/ownership, gathered artifact examples |
| Artifact Safari | Collected real artifacts, documented creators/consumers/dependencies, mapped horizons/cadences |
| Noun Farming | Created noun list, merged duplicates, captured meaning/usage/lifecycle/relationships |
| Org Structure | Captured containment, mapped paradigms, assembled team spreadsheet |
| Intent Graph | Walked task upward, traced work backward/forward, captured categorization schemes |
| Information Systems | Listed systems, documented info/users/owners, answered exploratory questions |
| Budgeting/Funding | Documented timing/flow, identified models, captured currencies/constraints |
| Prioritization | Listed frameworks, documented where applied, surfaced conflicts |

---

## Key Takeaways

1. **You're building a platform, not installing a tool** - Your operating system has customers and deserves intentional design
2. **Discovery over aspiration** - Surface what actually happens, not what the documentation says should happen
3. **Minimally viable consistency** - Don't aim for a unified glossary; aim for enough shared understanding to coordinate
4. **Intent is fractal** - Strategy exists at every level, not just the top
5. **Cycles create rhythm** - When cycles align, they complement each other; when they don't, they create friction
6. **Artifacts are evidence** - They show how information actually flows, not how it's supposed to flow
7. **Go deep enough to illuminate what's getting in the way** - You don't need to document everything, just enough to see the friction
8. **Tools enable behavior change** - Through education, enablement, modeling, and environmental restructuring
9. **Avoid zombie processes** - Encourage helpful behaviors, not marching through non-value-add rituals
10. **Continuous improvement** - This is not a one-time implementation but ongoing adaptation
