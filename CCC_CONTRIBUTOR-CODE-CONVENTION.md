# Contributor Code Convention (CCC) Standard

## ♾️ WeOwnNet 🌐 — Official Documentation

| Field | Value |
|-------|-------|
| Version | 2.4.1 |
| Established | 2026-W02 |
| Updated | 2026-01-26 (W05) |
| Repository | https://github.com/WeOwnNet/CCC |
| Domain | https://ccc.bot *(coming soon)* |
| Status | 🔒 LOCKED |

---

## 📖 Table of Contents

1. [Overview](#-overview)
2. [CCC Format Specification](#-ccc-format-specification)
3. [CCC-ID Format Specification](#-ccc-id-format-specification)
4. [CCC-ID Rules](#-ccc-id-rules)
5. [Registered Contributor Codes](#-registered-contributor-codes)
6. [Agent Identity Format](#-agent-identity-format)
7. [Timestamp Format Standards](#-timestamp-format-standards)
8. [Priority Matrix](#-priority-matrix)
9. [Status Icons](#-status-icons)
10. [Category Emojis](#-category-emojis)
11. [Entry Template](#-entry-template)
12. [Quick Reference Card](#-quick-reference-card)
13. [Version History](#-version-history)

---

## 📖 Overview

The **Contributor Code Convention (CCC)** is the official standard for tracking, organizing, and attributing contributions across the ♾️ WeOwnNet 🌐 ecosystem.

### Purpose

| Goal | Description |
|------|-------------|
| **Consistent Attribution** | Every contribution is properly credited |
| **Traceability** | All entries can be traced back to their source |
| **Collaboration** | Team members can easily reference and build upon each other's work |
| **Automation-Ready** | Structured format enables tooling and automation |

### Design Principles

| Principle | Description |
|-----------|-------------|
| **Human-Readable** | Entry IDs should be immediately understandable |
| **Machine-Parseable** | Format supports automated processing |
| **Chronologically Sortable** | Entries sort correctly by date |
| **Uniquely Identifiable** | No two entries share the same ID |
| **Context-Rich** | Each entry carries meaningful metadata |

---

## 📐 CCC Format Specification

### Format

```
[A-Z0-9]{3}
```

A **3-character alphanumeric code** that uniquely identifies contributors.

### Rules

| Rule | Description |
|------|-------------|
| Length | Exactly 3 characters |
| Characters | A-Z uppercase and 0-9 only |
| Uniqueness | Each CCC must be unique across the organization |
| Permanence | Once assigned, a CCC is never reassigned to another contributor |

### Examples

| CCC | Contributor |
|-----|-------------|
| GTM | yonks (Jason Younker) |
| THY | mrsyonks (Tyler Younker) |
| RMN | Roman Di Domizio |
| IAL | IAmLotus |
| LFG | CoachLFG (Mike LeMaire) |
| LDC | Dhruv |
| SHD | Shahid |

---

## 🆔 CCC-ID Format Specification

### Format Structure

```
<CCC>_<YYYY>-W<WW>_<NNN>
```

### Component Breakdown

| Component | Description | Format | Example |
|-----------|-------------|--------|---------|
| `<CCC>` | Contributor Code | 3 alphanumeric | `GTM` |
| `_` | Primary delimiter | Underscore | `_` |
| `<YYYY>` | 4-digit year | ISO 8601 | `2026` |
| `-` | Date separator | Hyphen | `-` |
| `W` | Week indicator | Literal "W" | `W` |
| `<WW>` | ISO week number | 01-53, zero-padded | `05` |
| `_` | Secondary delimiter | Underscore | `_` |
| `<NNN>` | Sequential number | 001-999, zero-padded | `021` |

### Complete Example

```
GTM_2026-W05_021
│   │    │   │
│   │    │   └── Sequential entry #021
│   │    └────── ISO Week 05
│   └─────────── Year 2026
└─────────────── Contributor: yonks (GTM)
```

### Validation Rules

| Rule | Requirement |
|------|-------------|
| CCC Length | Exactly 3 characters |
| CCC Characters | A-Z uppercase and 0-9 only |
| Year Range | 2024-2099 (current era) |
| Week Range | 01-53 (ISO 8601 compliant) |
| Sequence Range | 001-999 per contributor per week |
| Delimiters | Underscores and hyphens as specified |

### RegEx Pattern

```regex
^[A-Z0-9]{3}_[0-9]{4}-W(0[1-9]|[1-4][0-9]|5[0-3])_[0-9]{3}$
```

---

## 📋 CCC-ID Rules

### R-168: CCC-ID Ownership

| ID | Rule |
|----|------|
| R-168 | CCC-ID sequence tied to CCC (contributor), NOT username/session |

**Meaning:** Your CCC-ID sequence follows YOU across all workspaces and sessions. If you're GTM, your sequence continues whether you're in CCC, MAIT, or ADMIN workspace.

### R-169: ISO Week Reset

| ID | Rule |
|----|------|
| R-169 | CCC-ID resets to _001 ONLY at ISO week boundary |

**Meaning:** Each Monday (ISO week start), sequence resets to 001.

| Week | First CCC-ID | Last CCC-ID |
|------|--------------|-------------|
| W04 | GTM_2026-W04_001 | GTM_2026-W04_339 |
| W05 | GTM_2026-W05_001 | GTM_2026-W05_??? |

### R-181: Weekly Summary Reservation

| ID | Rule |
|----|------|
| R-181 | CCC-ID _001 of each ISO week is RESERVED for weekly summary |

**Meaning:** `<CCC>_<YYYY>-W<WW>_001` is always the weekly summary entry.

| Week | Reserved CCC-ID | Purpose |
|------|-----------------|---------|
| W05 | GTM_2026-W05_001 | Weekly summary |
| W06 | GTM_2026-W06_001 | Weekly summary |

---

## 👥 Registered Contributor Codes

### 🏛️ Founding OG ♾️ WeOwn.Agency Owners

**Established:** 2026-W02

> *"Forever OG"* 🫡

| CCC | Contributor | Handle | Role | Status |
|-----|-------------|--------|------|--------|
| `GTM` | yonks | yonks.box｜🤖🏛️🪙｜Jason Younker ♾️ | Co-Founder / Chief Digital Alchemist | 🏛️ Founding OG |
| `THY` | mrsyonks | Tyler Younker (mrsyonks) | Co-Founder | 🏛️ Founding OG |
| `IAL` | IAmLotus | IAmLotus.eth | Co-Founder | 🏛️ Founding OG |
| `RMN` | Roman | Roman Di Domizio (@LLMfeed) | AI Platform Engineer | 🏛️ Founding OG |
| `LFG` | CoachLFG | Mike LeMaire (Coach) | Co-Host / Coach | 🏛️ Founding OG |

### Contributors (2026-W02+)

| CCC | Contributor | Role | Status |
|-----|-------------|------|--------|
| `LDC` | Dhruv | Contributor | ✅ Registered |
| `SHD` | Shahid | Contributor | ✅ Registered |

### System Codes

| CCC | Purpose | Description |
|-----|---------|-------------|
| `ORG` | Organization-wide | Shared entries not attributed to individuals |
| `SYS` | System | Automated or system-generated entries |
| `TMP` | Temporary | Draft or temporary entries pending assignment |

### Requesting a New CCC

1. Request via Core TEAM channel
2. Approval by existing Founding OG member
3. Registration in this document
4. Announcement in community channels

---

## 🤖 Agent Identity Format

### R-171: Agent Identity Format

| ID | Rule |
|----|------|
| R-171 | Agent identity format: CCC=`AI:@<CCC>`, MAIT=`MAIT:@<CCC>`, ADMIN=`ADMIN:@<CCC>` |

### Identity Matrix

| Workspace | Metaphor | Agent Identity | Username Format |
|-----------|----------|----------------|-----------------|
| CCC | 🤝 THE HANDS | `AI:@<CCC>` | `u-<ccc>_user` |
| MAIT | 🧠 THE BRAIN | `MAIT:@<CCC>` | `m-<ccc>_mait` |
| ADMIN | ⚙️ THE ENGINE | `ADMIN:@<CCC>` | `a-<ccc>_dev` |

### Examples

| Workspace | @GTM Identity | @SHD Identity |
|-----------|---------------|---------------|
| CCC | AI:@GTM | AI:@SHD |
| MAIT | MAIT:@GTM | MAIT:@SHD |
| ADMIN | ADMIN:@GTM | ADMIN:@SHD |

---

## ⏰ Timestamp Format Standards

### Primary Format

| Scenario | Pattern | Example |
|----------|---------|---------|
| Time known | `Dd HH:MM TZ` | `Mo 07:16 EST` |
| Time unknown | `Fullday` | `Monday` |

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

### ISO Week Reference

| Field | Description |
|-------|-------------|
| Standard | ISO 8601 |
| Week Start | Monday |
| Week End | Sunday |
| W05 2026 | 2026-01-26 → 2026-02-01 |

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
| 🔒 | Locked | Finalized, no changes |

---

## 🏷️ Category Emojis

| Emoji | Category | Description |
|-------|----------|-------------|
| 📐 | Standards | CCC, protocols, conventions |
| 🤝 | Collaboration | Team coordination, meetings |
| 💻 | Development | Code, technical work |
| 📄 | Documentation | Docs, guides, specs |
| 🎯 | Strategy | Planning, roadmap |
| 🐛 | Bug | Issue, defect |
| ✨ | Feature | New capability |
| 🔧 | Maintenance | Updates, fixes |
| 🧠 | Learning | Training, research |

---

## 📝 Entry Template

```markdown
# <CCC>_<YYYY>-W<WW>_<NNN>

## ♾️ WeOwnNet 🌐

| Field | Value |
|-------|-------|
| Entry ID | <CCC>_<YYYY>-W<WW>_<NNN> |
| Timestamp | <Dd HH:MM TZ> |
| Category | <emoji> <Category> |
| Priority | <emoji> P<N> |
| Status | <emoji> <Status> |

---

## 📋 Summary

<Brief description>

---

## 📋 Details

<Detailed content>

---

## 🎯 Quick Commands

| # | Option |
|---|--------|
| 1 | <option> |
| 2 | <option> |

---

#FlowsBros #FedArch

♾️ WeOwnNet 🌐
```

---

## 📇 Quick Reference Card

### CCC-ID Format
```
<CCC>_<YYYY>-W<WW>_<NNN>
Example: GTM_2026-W05_021
```

### Founding OG CCCs
| `GTM` | `THY` | `IAL` | `RMN` | `LFG` |
|-------|-------|-------|-------|-------|
| yonks | mrsyonks | IAmLotus | Roman | Coach |

### Contributor CCCs
| `LDC` | `SHD` |
|-------|-------|
| Dhruv | Shahid |

### Day Codes (Week starts Monday)
| Mo | Tu | We | Th | Fr | Sa | Su |
|----|----|----|----|----|----|----|

### Priorities
| 🔴 P0 | 🟠 P1 | 🟡 P2 | 🟢 P3 |
|-------|-------|-------|-------|
| Today | Week | Next | Backlog |

### Status Icons
| ✅ Done | 🔄 Progress | 📋 Pending | ⏳ Blocked | ⬜ TBD |
|---------|-------------|------------|------------|--------|

### Agent Identity
| CCC | MAIT | ADMIN |
|-----|------|-------|
| AI:@<CCC> | MAIT:@<CCC> | ADMIN:@<CCC> |

---

## 📋 Version History

| Version | Date | Changes |
|---------|------|---------|
| 2.4.0 | 2026-W02 | Initial release |
| 2.4.1 | 2026-W05 | +R-168 (CCC-ID ownership), +R-169 (ISO week reset), +R-171 (Agent identity format), +R-181 (Weekly summary reservation), +@SHD (Shahid) registered, @GTM role updated to Co-Founder / Chief Digital Alchemist |

---

#FlowsBros #FedArch #CCC

♾️ WeOwnNet 🌐 | 🏡 Real Estate and 🤝 cooperative ownership for everyone. An 🤗 inclusive community, by 👥 invitation only.
