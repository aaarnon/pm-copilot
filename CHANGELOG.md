# Changelog

All notable changes to ProductKit will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.1.0] - 2025-01-16

Initial public release.

### Added

**Core System**
- Foundation chain: Vision → Strategy → Metrics → Discovery → Roadmap
- 22 composable skills for product management workflows
- Context-aware profiles (user, company, product)
- Session memory for multi-conversation continuity
- Auto-save progress after completing skill stages

**Main Skills (with Co-Creation Flows)**
- Vision: Purpose, future state, impact
- Strategy: Narrative, playing field, winning moves (14 elements)
- Metrics: Success metrics, leading/lagging indicators (6 elements)
- Discovery: Opportunity framing, risk assessment (8 elements)
- Roadmap: Now-Next-Later, sequencing, trade-offs (6 elements)

**Utility Skills**
- Positioning, OKR Builder, Metric Selector, AARRR Analyzer
- Impact Model Builder, Leading-Lagging Mapper
- Opportunity Tree, Interview Summary
- Initiative Alignment Doc, Prioritization

**Execution Skills**
- Writing PM Plans (with dependency tracking and parallel execution)
- Executing PM Plans (with checkpoints and blocker handling)
- Verification Before Completion

**Knowledge Base**
- 67 articles from product thought leaders
- resources.md as single source of truth
- authors.md with 22 thought leader profiles and links
- Compound term attribution (e.g., "Teresa Torres' OST")

**Quality System**
- Verification criteria for main skills (111 total checks)
- Eval Summary appended to deliverables
- 3-attempt regeneration for failed checks
- Sources & Attribution tables in outputs

**Multi-Tool Support**
- Claude Code (full auto-discovery)
- Cursor (via AGENTS.md)
- Codex (via config.toml)
- Gemini CLI (via settings.json)

### Documentation

- README with architecture diagrams
- Style guide for deliverable quality
- Onboarding flow for first-time users
- Red/Blue awareness for decision certainty

---

## [Unreleased]

### Changed
- Enhanced writing-pm-plans with dependency markers and evidence fields
- Enhanced executing-pm-plans with parallel execution support

### Added
- CHANGELOG.md for version tracking
- Documented skill structure patterns by type in skills/CLAUDE.md
