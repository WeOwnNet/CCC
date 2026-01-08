# 📐 Contributor Code Convention (CCC.bot)
## ♾️ WeOwnNet 🌐 — Ecosystem Official Documentation

**Version:** 2.4.0  
**Established:** 2026-W02  
**Last Updated:** 2026-01-09 (GTM_2026-W02_017)  
**Repository:** [github.com/WeOwnNet/CCC](https://github.com/WeOwnNet/CCC)  
**Domain:** [ccc.bot](https://ccc.bot) *(coming soon)*

---

## 📖 Table of Contents

1. [Overview](#-overview)
2. [Governance & Adoption](#-governance--adoption)
3. [Entry ID Format Specification](#-entry-id-format-specification)
4. [Registered Contributor Codes](#-registered-contributor-codes)
5. [Timestamp Format Standards](#-timestamp-format-standards)
6. [Priority Matrix](#-priority-matrix)
7. [Status Icons](#-status-icons)
8. [Category Emojis](#-category-emojis)
9. [Entry Template](#-entry-template)
10. [Quick Reference Card](#-quick-reference-card)
11. [Contribution Workflow](#-contribution-workflow)
12. [Version History](#-version-history)
13. [Adoption Signatures](#-adoption-signatures)

---

## 📖 Overview

The **Contributor Code Convention (CCC)** is the official standard for tracking, organizing, and attributing contributions across the ♾️ WeOwnNet 🌐 ecosystem. This convention ensures:

- **Consistent Attribution** — Every contribution is properly credited
- **Traceability** — All entries can be traced back to their source
- **Collaboration** — Team members can easily reference and build upon each other's work
- **Automation-Ready** — Structured format enables tooling and automation

### Design Principles

| Principle | Description |
|-----------|-------------|
| **Human-Readable** | Entry IDs should be immediately understandable |
| **Machine-Parseable** | Format supports automated processing |
| **Chronologically Sortable** | Entries sort correctly by date |
| **Uniquely Identifiable** | No two entries share the same ID |
| **Context-Rich** | Each entry carries meaningful metadata |

### AI Collaboration

CCC entries may be created in collaboration with AI assistants. The primary AI collaboration environment for ♾️ WeOwnNet 🌐 is:

| Resource | Value |
|----------|-------|
| **AI Instance** | [AI.WeOwn.Agency](https://AI.WeOwn.Agency) |
| **AI Username** | AI:team-lfg |
| **Platform** | AnythingLLM |

### Onchain Cooperative

The CCC standard will be governed by an onchain cooperative at [ccc.bot](https://ccc.bot).

| Resource | Value |
|----------|-------|
| **Domain** | [ccc.bot](https://ccc.bot) |
| **Registrar** | Porkbun.com (Web3FreedomClub) |
| **Purpose** | Onchain cooperative for CCC governance |
| **Status** | 🔄 In Development |

---

## 🏛️ Governance & Adoption

### Formal Adoption Process

The CCC standard will be formally adopted through on-chain governance to ensure transparent, community-driven decision making.

#### Governance Proposal

| Field | Value |
|-------|-------|
| **Platform** | [snapshot.box](https://snapshot.box) |
| **Proposer** | yonks (GTM) |
| **Proposal** | CCC v2.4.0 Adoption |
| **Status** | 📋 Pending |

#### Voting Eligibility

| Team | Participation |
|------|---------------|
| ♾️ WeOwnNet 🌐 Core TEAM | ✅ Eligible |
| ♾️ WeOwn.Dev 💻 TEAM | ✅ Eligible |

### AMA / Q&A Event

An **Ask Me Anything (AMA)** session will be hosted to discuss the CCC standard, answer questions, and gather feedback before the governance vote.

| Field | Value |
|-------|-------|
| **Event** | CCC v2.4.0 AMA / Q&A |
| **Hosts** | yonks (GTM) + CoachLFG (LFG) |
| **Audience** | ♾️ WeOwnNet 🌐 Community |
| **Purpose** | Discuss CCC, answer questions, gather feedback |
| **Status** | 📋 Scheduled (TBD) |

#### AMA Agenda (Proposed)

| # | Topic | Duration |
|---|-------|----------|
| 1 | Introduction to CCC | 10 min |
| 2 | Entry ID Format Walkthrough | 10 min |
| 3 | Contributor Codes & Attribution | 10 min |
| 4 | Standards Overview (timestamps, priorities, statuses) | 10 min |
| 5 | Live Q&A | 20 min |
| 6 | Next Steps & Governance Vote | 10 min |

### Adoption Timeline

| Phase | Activity | Status |
|-------|----------|--------|
| 1 | CCC v2.4.0 Published to GitHub | ✅ Complete |
| 2 | ccc.bot Domain Registered | ✅ Complete |
| 3 | Share with Core TEAM (Signal) | 📋 Pending |
| 4 | AMA / Q&A Event | 📋 Scheduled |
| 5 | Governance Proposal on snapshot.box | 📋 Pending |
| 6 | Voting Period | ⬜ TBD |
| 7 | Formal Adoption (if approved) | ⬜ TBD |
| 8 | ccc.bot Cooperative Launch | ⬜ TBD |

---

## 🆔 Entry ID Format Specification

### Format Structure

```
<CCC>_<YYYY>-W<WW>_<NNN>
```

### Component Breakdown

| Component | Description | Format | Example |
|-----------|-------------|--------|---------|
| `<CCC>` | Contributor Code Convention identifier | 3 uppercase letters | `GTM` |
| `_` | Primary delimiter | Underscore | `_` |
| `<YYYY>` | 4-digit year | ISO 8601 | `2026` |
| `-` | Date separator | Hyphen | `-` |
| `W` | Week indicator | Literal "W" | `W` |
| `<WW>` | ISO week number | 01-53, zero-padded | `02` |
| `_` | Secondary delimiter | Underscore | `_` |
| `<NNN>` | Sequential number | 001-999, zero-padded | `017` |

### Complete Example

```
GTM_2026-W02_017
│   │    │   │
│   │    │   └── Sequential entry #017
│   │    └────── ISO Week 02
│   └─────────── Year 2026
└─────────────── Contributor: yonks (GTM)
```

### Validation Rules

| Rule | Requirement |
|------|-------------|
| CCC Length | Exactly 3 characters |
| CCC Characters | A-Z uppercase only |
| Year Range | 2024-2099 (current era) |
| Week Range | 01-53 (ISO 8601 compliant) |
| Sequence Range | 001-999 per contributor per week |
| Delimiters | Underscores and hyphens as specified |

### RegEx Pattern

```regex
^[A-Z]{3}_[0-9]{4}-W(0[1-9]|[1-4][0-9]|5[0-3])_[0-9]{3}$
```

---

## 👥 Registered Contributor Codes

### 🏛️ Founding OG ♾️ WeOwn.Agency Owners

**Established:** 2026-W02 (GTM_2026-W02_015)

> *"Forever OG"* 🫡

| CCC | Contributor | Handle | Role | Status |
|-----|-------------|--------|------|--------|
| `GTM` | yonks | yonks.box｜🤖🏛️🪙｜Jason Younker ♾️ | Host / Founder | 🏛️ Founding OG |
| `THY` | mrsyonks | Tyler Younker (mrsyonks) | Co-Founder | 🏛️ Founding OG |
| `ILO` | IamLotus | IamLotus.eth | Co-Founder | 🏛️ Founding OG |
| `RMN` | Roman | Roman Di Domizio (@LLMfeed) | AI Platform Engineer | 🏛️ Founding OG |
| `LFG` | CoachLFG | Mike LeMaire (Coach) | Co-Host / Coach | 🏛️ Founding OG |

### System Codes

| CCC | Purpose | Description |
|-----|---------|-------------|
| `ORG` | Organization-wide | Shared entries not attributed to individuals |
| `SYS` | System | Automated or system-generated entries |
| `TMP` | Temporary | Draft or temporary entries pending assignment |

### Code Assignment Rules

1. **Uniqueness** — Each CCC must be unique across the organization
2. **Permanence** — Once assigned, a CCC is never reassigned to another contributor
3. **Individual Attribution** — Each CCC represents an individual contributor
4. **AI Collaboration** — Entries created with AI assistance are still attributed to the human contributor's CCC

### Requesting a New CCC

New contributor codes are assigned by:
1. Request via Core TEAM channel (Signal: ♾️ WeOwn.Agency 👥)
2. Approval by existing Founding OG member
3. Registration in this document
4. Announcement in community channels

---

## ⏰ Timestamp Format Standards

### Primary Format

| Scenario | Pattern | Example |
|----------|---------|---------|
| Time known | `Dd HH:MM TZ` | `Th 14:30 EST` |
| Time unknown | `Fullday` | `Thursday` |

### Day Abbreviations

| Day | Abbreviation | ISO Number |
|-----|--------------|------------|
| Monday | `Mo` | 1 |
| Tuesday | `Tu` | 2 |
| Wednesday | `We` | 3 |
| Thursday | `Th` | 4 |
| Friday | `Fr` | 5 |
| Saturday | `Sa` | 6 |
| Sunday | `Su` | 7 |

### Time Zone Reference

| Abbreviation | Full Name | UTC Offset |
|--------------|-----------|------------|
| `EST` | Eastern Standard Time | UTC-5 |
| `EDT` | Eastern Daylight Time | UTC-4 |
| `CST` | Central Standard Time | UTC-6 |
| `CDT` | Central Daylight Time | UTC-5 |
| `MST` | Mountain Standard Time | UTC-7 |
| `MDT` | Mountain Daylight Time | UTC-6 |
| `PST` | Pacific Standard Time | UTC-8 |
| `PDT` | Pacific Daylight Time | UTC-7 |
| `UTC` | Coordinated Universal Time | UTC±0 |

### Examples

```
Th 14:30 EST    → Thursday at 2:30 PM Eastern Standard Time
Mo 09:00 UTC    → Monday at 9:00 AM UTC
Friday          → Friday (time not specified)
We 23:45 PST    → Wednesday at 11:45 PM Pacific Standard Time
```

---

## 🎯 Priority Matrix

| Priority | Label | SLA | Emoji | Description |
|----------|-------|-----|-------|-------------|
| **P0** | Critical | Today | 🔴 | Blocking issues requiring immediate attention |
| **P1** | High | This Week | 🟠 | Important items for current sprint/week |
| **P2** | Medium | Next Week | 🟡 | Planned items for near-term completion |
| **P3** | Low | Backlog | 🟢 | Nice-to-have or future consideration |

### Priority Selection Guide

| Choose P0 When... | Choose P1 When... |
|-------------------|-------------------|
| Production is down | Feature deadline this week |
| Security vulnerability | Important client request |
| Data loss risk | Team blocked on this |
| Revenue impact | Sprint commitment |

| Choose P2 When... | Choose P3 When... |
|-------------------|-------------------|
| Planned improvement | Future enhancement |
| Non-urgent bug | Research/exploration |
| Documentation update | Nice-to-have feature |
| Scheduled maintenance | Technical debt |

---

## 📊 Status Icons

### Primary Status Set

| Icon | Status | Description |
|------|--------|-------------|
| ✅ | Complete | Work finished and verified |
| 🔄 | In Progress | Actively being worked on |
| 📋 | Pending | Queued, not yet started |
| ⏳ | Blocked | Cannot proceed due to dependency |
| ⬜ | TBD | To Be Determined |

### Extended Status Set

| Icon | Status | Description |
|------|--------|-------------|
| 🚀 | Launched | Deployed to production |
| 🧪 | Testing | In QA/testing phase |
| 👀 | Review | Awaiting review/approval |
| 🔙 | Reverted | Rolled back |
| ❌ | Cancelled | Will not be completed |
| 💤 | On Hold | Paused intentionally |
| 🔁 | Recurring | Repeating task |

### Status Transitions

```
📋 Pending → 🔄 In Progress → 👀 Review → ✅ Complete → 🚀 Launched
                    ↓
                  ⏳ Blocked
                    ↓
              (resolve blocker)
                    ↓
              🔄 In Progress
```

---

## 🏷️ Category Emojis

### Core Categories

| Emoji | Category | Use Case |
|-------|----------|----------|
| 🔧 | Tools Decision | Tool selection, integration decisions |
| 🚨 | Error Resolution | Bug fixes, incident response |
| 📖 | Documentation | Docs, guides, READMEs |
| 🏗️ | Architecture | System design, infrastructure |
| 🎪 | Event Planning | Meetings, launches, community events |
| 📐 | Standards | Conventions, processes, guidelines |

### Development Categories

| Emoji | Category | Use Case |
|-------|----------|----------|
| 🐛 | Bug Fix | Bug identification and resolution |
| ✨ | Enhancement | Feature improvements |
| ♻️ | Refactor | Code restructuring |
| 🧪 | Testing | Test creation, QA activities |
| 🔐 | Security | Security-related work |
| ⚡ | Performance | Optimization work |

### Operations Categories

| Emoji | Category | Use Case |
|-------|----------|----------|
| ⚙️ | Operations | DevOps, maintenance |
| 🔍 | Health Check | Monitoring, audits |
| 📦 | Product | Product management |
| 🚀 | Launch | Deployments, releases |
| 💰 | Finance | Budget, payments, revenue |

### Creative & Growth Categories

| Emoji | Category | Use Case |
|-------|----------|----------|
| 🎨 | Creative | Design, branding, content |
| 💡 | Ideation | Brainstorming, proposals |
| 📣 | Marketing | Campaigns, outreach |
| 🎓 | Learning | Training, education |
| 📊 | Analytics | Data analysis, metrics |

### Collaboration Categories

| Emoji | Category | Use Case |
|-------|----------|----------|
| 🤝 | Collaboration | Team activities, partnerships |
| 🏛️ | Milestone | Major achievements, milestones |

---

## 📝 Entry Template

### Standard Entry Format

```markdown
> **<CCC>_<YYYY>-W<WW>_<NNN>** | <EMOJI> <Category>: <Title>
>
> | Field | Value |
> |-------|-------|
> | **Timestamp** | <Dd HH:MM TZ or Fullday> |
> | **Status** | <STATUS_ICON> <STATUS_TEXT> |
> | **Category** | <EMOJI> <Category> |
> | **Priority** | <PRIORITY_EMOJI> <PRIORITY_LABEL> |
>
> ### Description
> <Brief description of the entry>
>
> ### Details
> <Extended details, context, or notes>
>
> ### Related Entries
> - <ENTRY_ID>: <Description>
```

### Minimal Entry Format

```markdown
> **<CCC>_<YYYY>-W<WW>_<NNN>** | <EMOJI> <Category>: <Title>
> **Status:** <STATUS_ICON> <STATUS_TEXT> | **Timestamp:** <Dd HH:MM TZ>
```

### Example Entry

```markdown
> **GTM_2026-W02_017** | 🤝 Collaboration: Core TEAM CCC Adoption
>
> | Field | Value |
> |-------|-------|
> | **Timestamp** | Th 14:30 EST |
> | **Status** | 🔄 In Progress |
> | **Category** | 🤝 Collaboration |
> | **Priority** | 🟠 P1 - High |
>
> ### Description
> Collaborate with Core TEAM to review, refine, and formally adopt the CCC standard.
>
> ### Details
> - Created comprehensive CCC documentation
> - AI collaboration via AI:team-lfg at AI.WeOwn.Agency
> - Governance proposal on snapshot.box
> - AMA hosted by yonks + CoachLFG
> - ccc.bot domain registered for onchain cooperative
>
> ### Related Entries
> - GTM_2026-W02_010: CCC system established
> - GTM_2026-W02_015: Founding OG Owners Established
```

---

## 📇 Quick Reference Card

### Entry ID Format
```
<CCC>_<YYYY>-W<WW>_<NNN>
Example: GTM_2026-W02_017
```

### Founding OG CCCs
| `GTM` | `THY` | `ILO` | `RMN` | `LFG` |
|-------|-------|-------|-------|-------|
| yonks | mrsyonks | IamLotus | Roman | Coach |

### Day Codes
| Mo | Tu | We | Th | Fr | Sa | Su |
|----|----|----|----|----|----|----|

### Priorities
| 🔴 P0 | 🟠 P1 | 🟡 P2 | 🟢 P3 |
|-------|-------|-------|-------|
| Today | Week | Next | Backlog |

### Status Icons
| ✅ Done | 🔄 Progress | 📋 Pending | ⏳ Blocked | ⬜ TBD |
|---------|-------------|------------|------------|--------|

### Common Categories
| 🔧 Tools | 🚨 Error | 📖 Docs | 🏗️ Arch | 📐 Standards |
|----------|----------|---------|---------|--------------|
| 🐛 Bug | ✨ Feature | 🤝 Collab | 🚀 Launch | 🏛️ Milestone |

---

## 🔄 Contribution Workflow

### Step 1: Create Entry ID

1. Identify your CCC (e.g., `GTM`, `THY`, `ILO`)
2. Note current ISO week (e.g., `2026-W02`)
3. Get next sequential number for your CCC this week
4. Assemble: `GTM_2026-W02_017`

### Step 2: Select Metadata

1. Choose appropriate **Category** emoji
2. Set **Priority** level
3. Initialize **Status** (usually `📋 Pending` or `🔄 In Progress`)
4. Add **Timestamp**

### Step 3: Document Entry

1. Use the Entry Template
2. Write clear **Title** and **Description**
3. Link **Related Entries** if applicable
4. Add relevant details

### Step 4: Track Progress

1. Update **Status** as work progresses
2. Add notes for significant updates
3. Mark ✅ **Complete** when finished
4. Archive or reference as needed

### AI-Assisted Contributions

When creating entries with AI assistance:
1. Use your personal CCC (not a system code)
2. Reference the AI collaboration in the entry details
3. Include thread link when applicable

Example:
```markdown
### Details
- AI collaboration via AI:team-lfg at AI.WeOwn.Agency
- Thread: https://ai.weown.agency/workspace/tools/t/[thread-id]
```

---

## 📜 Version History

| Version | Date | Entry ID | Changes |
|---------|------|----------|---------|
| 2.4.0 | 2026-01-09 | GTM_2026-W02_017 | Initial public release; Governance & AMA process; ccc.bot domain; ♾️ WeOwnNet 🌐 branding |

---

## ✍️ Adoption Signatures

### Governance Vote

| Field | Value |
|-------|-------|
| **Platform** | [snapshot.box](https://snapshot.box) |
| **Proposal** | CCC v2.4.0 Adoption |
| **Proposer** | yonks (GTM) |
| **Voters** | ♾️ WeOwnNet 🌐 Core TEAM + ♾️ WeOwn.Dev 💻 TEAM |
| **Status** | 📋 Pending |

### Core TEAM Sign-Off

| CCC | Name | Vote | Date |
|-----|------|------|------|
| `GTM` | yonks | ⬜ | |
| `THY` | mrsyonks | ⬜ | |
| `ILO` | IamLotus | ⬜ | |
| `RMN` | Roman | ⬜ | |
| `LFG` | CoachLFG | ⬜ | |

---

## 🔗 Links

| Resource | URL |
|----------|-----|
| **♾️ WeOwnNet 🌐** | [weown.net](https://weown.net) |
| **CCC Cooperative** | [ccc.bot](https://ccc.bot) *(coming soon)* |
| **AI Instance** | [AI.WeOwn.Agency](https://AI.WeOwn.Agency) |
| **GitHub Org** | [github.com/WeOwnNet](https://github.com/WeOwnNet) |
| **CCC Repository** | [github.com/WeOwnNet/CCC](https://github.com/WeOwnNet/CCC) |
| **Governance** | [snapshot.box](https://snapshot.box) |

---

<div align="center">

**Document ID:** `CCC_CONTRIBUTOR-CODE-CONVENTION.md`  
**Maintained By:** Core TEAM  
**Repository:** [github.com/WeOwnNet/CCC](https://github.com/WeOwnNet/CCC)  
**Cooperative:** [ccc.bot](https://ccc.bot)

---

*♾️ WeOwnNet 🌐 | 🏡 Real Estate and 🤝 cooperative ownership for everyone. An 🤗 inclusive community, by 👥 invitation only.*

---
