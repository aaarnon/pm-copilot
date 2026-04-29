# The Playbook to Fix Your Product Roadmap

**Author:** Markus Muller
**Source:** [Medium](https://medium.com/@markusmuller89/the-playbook-to-fix-your-product-roadmap-1bd8da1ae344)

---

## Core Thesis

Roadmaps should be continuous, not quarterly. The Roadmap Pipeline approach combines a Kanban board with structured triage routines to balance intuition and data-driven decision-making while connecting every opportunity to company objectives.

---

## Key Frameworks

### Roadmap Pipeline

A Kanban board with specific columns for triaging opportunities:

```
[New] → [Initial Assessment] → [Later] → [Next] → [Now Discovery] → [Now Delivery] → [Done]
                                    ↓
                         [Not in next X months]
```

**Key principles:**
- New topics can come from anyone
- Only PMs make changes to the board (except creating requests)
- [New] and [Initial Assessment] columns should be empty by end of each week
- Limit [Next] to 3-5 impactful opportunities
- Split [Now] into Discovery and Delivery (different uncertainty levels)

### ICE Score (Impact, Confidence, Ease)

Simple prioritization framework covering three key questions:

| Parameter | Scale | Description |
|-----------|-------|-------------|
| Impact | 1-4 | Impact on current objectives (not generic user/business impact) |
| Confidence | 1-4 | How confident are we? Focus on generating evidence to increase this |
| Ease | 1-4 | Complexity estimate (prefer complexity over time estimates) |

**Key insight:** We are often overconfident. Focus on finding evidence to increase confidence scores.

### Three Routines

1. **Weekly Triage** (required)
   - Initial opportunity assessment
   - Clear [New] and [Initial Assessment] columns weekly
   - Build habit first, add team members over time

2. **Roadmap Alignment** (every 2-3 weeks)
   - PM-led meeting with key stakeholders
   - Structure: OKR status → Discovery/Delivery updates → New requests → Changes → Input needed → Q&A
   - Focus on "What opportunities should we prioritize to achieve our OKRs?"
   - 45-90 minutes depending on group size

3. **OKR Sync** (quarterly)
   - Reflect updated OKRs in the pipeline
   - Review [Later] and [Not...] columns for relevant opportunities
   - Block 1-3 hours at quarter start

---

## Discovery vs Delivery Split

Splitting [Now] into Discovery and Delivery highlights three common discovery outcomes:

1. **Dropping:** Learn the opportunity isn't worth pursuing
2. **Splitting:** Break into sub-opportunities or versions
3. **New Opportunities:** Discovery reveals different, more promising opportunities

---

## Outcome Over Output

| Output-focused (bad) | Outcome-focused (good) |
|---------------------|------------------------|
| Release tutorial feature | Increase activation rate to X% |
| Build referral system | Grow organic signups by Y% |
| Ship dashboard v2 | Improve dashboard satisfaction by Z% |

Outcomes remain stable over a quarter; outputs (features) stay flexible.

---

## Practical Guidance

### Saying No Effectively

Use [Not in next X months] column:
- Not saying it's a bad idea
- Saying it doesn't align with current objectives
- Invite stakeholders to bring new data or wait for objective changes

### 80/20 Rule

Not everything goes on the pipeline. Set a minimum threshold (e.g., 2+ days engineering work). For smaller requests:
1. **Group** similar small requests under one improvement opportunity
2. **Build right away** (10-20% of team capacity for fast-lane items)
3. **Ignore** (remove entirely, revisit if it keeps coming up)

### Scaling Across Teams

- One roadmap pipeline per tribe/group, not one central roadmap
- Decentralize to maintain speed and relevance
- Quarterly reassess resource allocation across groups

### Tool Selection

Use whatever Kanban tool is most adopted in your company (Trello, Asana, Jira, Notion). Adoption matters more than features.

---

## Other Roadmap Forms

| Type | Use Case | Update Frequency |
|------|----------|------------------|
| Roadmap Pipeline | Day-to-day prioritization | Continuous |
| Strategic Roadmap | Executive/investor communication | Monthly |
| Gantt Chart | Complex projects with dependencies | As needed |

**Always add disclaimer:** "This is our best guess from [Date]. We prioritize flexibility over predictability, so don't read it as a delivery commitment."

---

## Implementation Steps

1. Set up Kanban board
2. Fill with current Discovery and Delivery topics
3. Add topics from idea lists, backlogs, feedback to [New]
4. Do initial assessment and clear first two columns
5. Introduce team and stakeholders (call it "an experiment")
6. Run first alignment session (allow extra time)
7. Schedule recurring routines
8. Share approach company-wide (video format works well)
9. Retrospective at 4-6 weeks, adjust as needed

---

## Key Concepts

| Concept | Description |
|---------|-------------|
| Roadmap Pipeline | Kanban-based continuous roadmapping with triage columns |
| ICE Score | Impact/Confidence/Ease prioritization framework |
| Three Routines | Weekly triage, bi-weekly alignment, quarterly OKR sync |
| Discovery vs Delivery | Split [Now] column to highlight uncertainty differences |
| Outcome over Output | Focus objectives on metrics, not features |
| Adaptability over Predictability | Embrace change rather than promise fixed timelines |

---

## Diagrams

### Strategy Hierarchy & Roadmap Pipeline Overview

```
                    ┌─────────────────────┐
                    │       Vision        │ ←── 5-10 years
                    └─────────────────────┘
                              │
                    ┌─────────────────────────────┐
                    │ Mission (OKR) and/or       │ ←── 1-5 years
                    │      North Star            │
                    └─────────────────────────────┘
                              │
        ┌─────────────────────────────────────────────┐
        │                 Strategy                    │ ←── 6-24 months
        └─────────────────────────────────────────────┘
                    /                  \
       ┌────────────────┐        ┌────────────────┐
       │   Objectives   │        │      ...       │ ←── 1-6 months
       └────────────────┘        └────────────────┘
          /     |     \
   ┌─────────┐ ┌─────────┐ ┌─────────┐
   │Key      │ │Key      │ │Key      │
   │Result   │ │Result   │ │Result   │
   └─────────┘ └─────────┘ └─────────┘
       \          |          /
        \         |         /
  ┌ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┐
  │                    Roadmap Pipeline                         │
  │ ┌─────────┐┌─────────┐┌──────────┐┌───────────┐┌──────────┐┌──────┐
  │ │Problem  ││Feature  ││Experiment││Improvement││New       ││Idea  │
  │ └─────────┘└─────────┘└──────────┘└───────────┘│Product   │└──────┘
  │  ┌──────┐   ═══════    ═══════     ═══════    └──────────┘ ═══════
  │  │user  │   ═══════    ═══════     ═══════      ═══════    ═══════
  │  │story │   ═══════    ═══════     ═══════      ═══════    ═══════
  └ ─└──────┘─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┘
  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
  :                        Dev Backlog                            :
  . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
```

### Roadmap Pipeline Kanban Board

```
┌──────────────┬──────────────┬──────────────┬──────────────┬──────────────┬──────────────┬──────────────┐
│ New requests,│   Initial    │    Later     │     Next     │  Discovery   │   Delivery   │ Not in the   │
│ problems,    │  assessment  │ (3-6 months) │ (1-3 months) │    (Now)     │    (Now)     │ next 6 months│
│ ideas        │              │              │              │              │              │              │
├──────────────┼──────────────┼──────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │
│ └──────────┘ │ └──────────┘ │ └──────────┘ │ └──────────┘ │ └──────────┘ │ └──────────┘ │ └──────────┘ │
│ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │ ┌──────────┐ │
│ └──────────┘ │ └──────────┘ │ └──────────┘ │ └──────────┘ │ └──────────┘ │ └──────────┘ │ └──────────┘ │
└──────────────┴──────────────┴──────────────┴──────────────┴──────────────┴──────────────┴──────────────┘
```

### Triage Flow

```
                                    ↗  ↗  ↗
┌──────────────┬──────────────┬──────────────┬──────────────┬──────────────┬──────────────┬──────────────┐
│ New requests │   Initial    │    Later     │     Next     │  Discovery   │   Delivery   │ Not in the   │
│              │  assessment  │              │              │    (Now)     │    (Now)     │ next 6 months│
└──────────────┴──────────────┴──────────────┴──────────────┴──────────────┴──────────────┴──────────────┘
       │                             ↑             ↑              ↑              ↑              ↑
       └─────────────────────────────┴─────────────┴──────────────┴──────────────┴──────────────┘
                                (Items flow from New → to appropriate column)
```

### Example Opportunity Card (Initial)

```
┌─────────────────────────────────────────────────────────────────────────┐
│  Pay with PayPal                                                        │
├─────────────────┬───────────────────────────────────────────────────────┤
│ Opportunity     │ Users without credit cards can't use our service.    │
│                 │ PayPal would allow a larger share of users to sign up.│
├─────────────────┼───────────────────────────────────────────────────────┤
│ Expected Outcome│ >20% drop-off reduction on payment screen            │
│                 │ +5% activation rate (download to first ride)         │
├─────────────────┼───────────────────────────────────────────────────────┤
│ Available Proof │ - Most requested improvement via Customer Service    │
│                 │ - #1 drop-off reason on payment step is lack of      │
│                 │   credit card. 70% of these users have PayPal.       │
│                 │ - PayPal has significant market share in all         │
│                 │   core markets.                                      │
├─────────────────┼───────────────────────────────────────────────────────┤
│ Status          │ —                                                     │
│ OKRs Impacted   │ —                                                     │
│ Impact-Level    │ —                                                     │
│ Confidence Level│ —                                                     │
│ Ease            │ —                                                     │
│ Priority-Score  │ —                                                     │
└─────────────────┴───────────────────────────────────────────────────────┘
```

### Example Opportunity Card (Triaged)

```
┌─────────────────────────────────────────────────────────────────────────┐
│  Shared bank account                                                    │
├─────────────────┬───────────────────────────────────────────────────────┤
│ Opportunity     │ Customers want to share their bank account with      │
│                 │ partner or friends.                                   │
├─────────────────┼───────────────────────────────────────────────────────┤
│ Expected Outcome│ - Increased retention & satisfaction                 │
│                 │ - Boost organic growth, expand customer segments     │
│                 │ - Additional value for premium customers             │
├─────────────────┼───────────────────────────────────────────────────────┤
│ Available Proof │ Top request over 12 months. Early research shows     │
│                 │ shared account customers have higher loyalty.        │
├─────────────────┼───────────────────────────────────────────────────────┤
│ Status          │ [Next]                                                │
│ OKRs Impacted   │ [OKR 2: Increase Customer Satisfaction]              │
│ Impact-Level    │ [Massive (x4)]                                        │
│ Confidence Level│ [Some Confidence (x2)]                                │
│ Ease            │ [Complex (x2)]                                        │
│ Priority-Score  │ 16                                                    │
└─────────────────┴───────────────────────────────────────────────────────┘
```

### ICE Score Formula

```
╔═══════════════════════════════════════════════════════════════╗
║                                                               ║
║   ICE Score = Impact  ×  Confidence  ×  Ease                  ║
║                                                               ║
╚═══════════════════════════════════════════════════════════════╝
```

### ICE Scoring Scale

```
┌────────────┬─────────────────┬─────────────────────────────┬─────────────────────┐
│ Multiplier │ Impact on       │ Confidence to deliver       │ Ease                │
│            │ Objectives      │ the impact                  │                     │
├────────────┼─────────────────┼─────────────────────────────┼─────────────────────┤
│     x1     │ Low             │ Educated guess              │ Very Complex        │
│            │                 │ Based on experience         │ Many weeks          │
├────────────┼─────────────────┼─────────────────────────────┼─────────────────────┤
│     x2     │ Medium          │ Some confidence             │ Complex             │
│            │                 │ Market & secondary research │ A few weeks         │
├────────────┼─────────────────┼─────────────────────────────┼─────────────────────┤
│     x3     │ High            │ Confident                   │ Medium Complexity   │
│            │                 │ Based on primary research   │ Around one week     │
├────────────┼─────────────────┼─────────────────────────────┼─────────────────────┤
│     x4     │ Massive         │ Very confident              │ Low Complexity      │
│            │                 │ Based on quantitative &     │ Less than 3 days    │
│            │                 │ qualitative experiments     │                     │
└────────────┴─────────────────┴─────────────────────────────┴─────────────────────┘
```

### Output vs Outcome

```
         Output                    vs.                 Outcome
    ═══════════════                              ═══════════════════
    Activities you do                            Result of what you do

    Call a customer ─────────────────────────> Make a customer sign
    Build a new tutorial ────────────────────> Improve the activation rate
    Launch a new feature ────────────────────> Increase 4-week retention
    Change the copy ─────────────────────────> Decrease the drop-off rate
    Implement a new tool ────────────────────> Improve the time to deploy
```

### Other Roadmap Forms

```
                    ┌─────────────────────┐
                    │       Vision        │
                    └─────────────────────┘
                              │
                    ┌─────────────────────────────┐
                    │ Mission (OKR) and/or       │
                    │      North Star            │
                    └─────────────────────────────┘
                              │
  ┌ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┐
  │            Strategic Roadmap                     │
  │     ┌─────────────────────────────────────┐     │
  │     │              Strategy               │     │
  │     └─────────────────────────────────────┘     │
  │            /                  \                 │
  │   ┌────────────────┐    ┌────────────────┐     │
  │   │   Objectives   │    │      ...       │     │
  │   └────────────────┘    └────────────────┘     │
  │      /     |     \                              │
  │ ┌───────┐┌───────┐┌───────┐                    │
  │ │Key    ││Key    ││Key    │                    │
  │ │Result ││Result ││Result │                    │
  │ └───────┘└───────┘└───────┘                    │
  └ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┘
                     │
  ┌ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ┐
  │                  Roadmap Pipeline                           │
  │ ┌─────────┐┌─────────┐┌──────────┐┌─────────────┐┌────────┐┌──────┐
  │ │Problem  ││Feature  ││Experiment││Special      ││New     ││Idea  │
  │ │         ││         ││          ││Project      ││Product ││      │
  │ └─────────┘└─────────┘└──────────┘└─────────────┘└────────┘└──────┘
  │    ═══       ═══        ═══         ┌────────┐    ┌────────┐ ═══
  │    ═══       ═══        ═══         │Gantt   │    │Story   │ ═══
  │    ═══       ═══        ═══         │Chart   │    │Map     │ ═══
  └ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ └────────┘─ ─ └────────┘─ ─ ─ ┘
```

### Filled Kanban Board Example

```
┌──────────────┬──────────────┬──────────────┬──────────────┬──────────────┬──────────────┬──────────────┐
│ New requests │   Initial    │    Later     │     Next     │  Discovery   │   Delivery   │ Not in the   │
│              │  assessment  │ (3-6 months) │ (1-3 months) │    (Now)     │    (Now)     │ next 6 months│
├──────────────┼──────────────┼──────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│              │              │Reduce unlock │Public API v2 │Pausing a ride│Public API v1 │     ...      │
│    Empty     │    Empty     │error rate    │              │              │              │              │
│              │              ├──────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│              │              │Enable launch │Increase      │Subscriptions │Reserve a     │     ...      │
│              │              │of country X  │payment       │              │scooter       │              │
│              │              │              │conversion    │              │              │              │
│              │              ├──────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│              │              │Advanced in-  │Referral      │              │% based       │     ...      │
│              │              │app feedback  │system        │              │discounts     │              │
│              │              ├──────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│              │              │Location based│              │              │Improved error│     ...      │
│              │              │discounting   │              │              │messages      │              │
│              │              ├──────────────┤              │              │              ├──────────────┤
│              │              │Public API v3 │              │              │              │     ...      │
└──────────────┴──────────────┴──────────────┴──────────────┴──────────────┴──────────────┴──────────────┘
```

### Strategic Roadmap Example (by Segment)

```
                    │ Quarter 1          │ Quarter 2          │ Quarter 3           │ Quarter 4          │
┌───────────────────┼────────────────────┼────────────────────┼─────────────────────┼────────────────────┤
│                   │Sign up & user      │Basic promotions    │Advance promotion    │Subscription        │
│ Customer          │onboarding          │and growth support  │and marketing system │experiments         │
│                   ├────────────────────┼────────────────────┼─────────────────────┼────────────────────┤
│                   │Take a ride and     │Basic localization  │Additional payment   │First deep partner  │
│                   │pay for it          │for multi country   │options              │integration         │
├───────────────────┼────────────────────┼────────────────────┼─────────────────────┼────────────────────┤
│                   │Fleet management    │Advanced operations │Optimize deployment  │100% system-based   │
│ Operations        │tool to handle      │tools & permission  │based on user demand │deployment and      │
│                   │critical cases      │management          │and efficient routing│collection          │
├───────────────────┼────────────────────┼────────────────────┼─────────────────────┼────────────────────┤
│                   │Integration of IOT  │      ...           │       ...           │       ...          │
│ Platform          │to lock/unlock      │                    │                     │                    │
│                   │scooter             │                    │                     │                    │
└───────────────────┴────────────────────┴────────────────────┴─────────────────────┴────────────────────┘

Disclaimer: This is the best guess from [Date]. We prioritize flexibility over predictability.
```

### Outcome-Focused Strategic Roadmap

```
                    │ Quarter 1 (Launch)                       │ Quarter 2                    │
┌───────────────────┼───────────────────────┬──────────────────┼──────────────┬───────────────┤
│ Retention &       │Strong customer        │Majority of 1st   │Referral...   │Ellis Score... │
│ Satisfaction      │satisfaction after     │time customers    │              │               │
│                   │first use              │return            │NPS...        │X-week         │
│                   │                       │                  │              │retention...   │
├───────────────────┼───────────────────────┼──────────────────┼──────────────┼───────────────┤
│ Growth &          │Build a basic customer │Understand        │Installs...   │Funnel         │
│ Activation        │base                   │activation funnel │              │conversion...  │
│                   │                       │opportunities     │CAC...        │Share          │
│                   │                       │                  │              │organic/paid   │
├───────────────────┼───────────────────────┼──────────────────┼──────────────┼───────────────┤
│ Monetization      │Test paying intent     │                  │Average       │Share of paying│
│                   │                       │                  │revenue/user  │customer...    │
└───────────────────┴───────────────────────┴──────────────────┴──────────────┴───────────────┘
```

### Gantt Chart Example (Migration Project)

```
                        February        March           April           May
                            │              │               │              │
Beta Launch of new   ══════════════◆      │               │              │
system in DE                │     5th of   │               │              │
                            │     March    │               │              │
                            │              │               │              │
Full Launch in DE           │        ══════════◆          │              │
                            │              Last week      │              │
                            │              of March       │              │
                            │              │               │              │
Migration of 1st            │              │    ══════════════◆          │
country                     │              │               Mid of        │
                            │              │               April         │
                            │              │               │              │
Migration of                │              │               │              ◆
remaining countries         │              │               │             May
                            │              │               │              │
```
