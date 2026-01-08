## 📖 Overview

The **Contributor Code Convention (CCC)** is the official standard for tracking, organizing, and attributing contributions across the WeOwnNet ecosystem. This convention ensures:

- **🎯 Consistent Attribution** — Every contribution is properly credited
- **🔍 Traceability** — All entries can be traced back to their source
- **🤝 Collaboration** — Team members can easily reference and build upon each other's work
- **⚙️ Automation-Ready** — Structured format enables tooling and automation

---

## 🆔 Entry ID Format

```
<CCC>_<YYYY>-W<WW>_<NNN>
```

### Example

```
GTM_2026-W02_017
│   │    │   │
│   │    │   └── Sequential entry #017
│   │    └────── ISO Week 02
│   └─────────── Year 2026
└─────────────── Contributor: YonksTEAM (GTM)
```

### Components

| Component | Description | Example |
|-----------|-------------|---------|
| `<CCC>` | 3-letter Contributor Code | `GTM` |
| `<YYYY>` | 4-digit year | `2026` |
| `<WW>` | ISO week number (01-53) | `02` |
| `<NNN>` | Sequential number (001-999) | `017` |

---

## 👥 Founding OG ♾️ WeOwn.Agency Owners

**Established:** 2026-W02

> *"Forever OG"* 🫡

| CCC | Contributor | Handle | Role |
|-----|-------------|--------|------|
| `GTM` | YonksTEAM | yonks.box｜🤖🏛️🪙｜Jason Younker ♾️ | Chief Digital Alchemist |
| `THY` | mrsyonks | Tyler Younker | CEO / CFO |
| `ILO` | IamLotus | IamLotus.eth | Chief Catalyst Officer |
| `RMN` | Roman | Roman Di Domizio (@LLMfeed) | AI Platform Engineer |
| `LFG` | CoachLFG | Mike LeMaire (Coach) | Head of Business Development |

### System Codes

| CCC | Purpose |
|-----|---------|
| `ORG` | Organization-wide shared entries |
| `SYS` | Automated/system-generated entries |

---

## 📇 Quick Reference

### Priorities

| Priority | Label | SLA | Emoji |
|----------|-------|-----|-------|
| P0 | Critical | Today | 🔴 |
| P1 | High | This Week | 🟠 |
| P2 | Medium | Next Week | 🟡 |
| P3 | Low | Backlog | 🟢 |

### Status Icons

| Icon | Status |
|------|--------|
| ✅ | Complete |
| 🔄 | In Progress |
| 📋 | Pending |
| ⏳ | Blocked |
| ⬜ | TBD |

### Day Abbreviations

| Su | Mo | Tu | We | Th | Fr | Sa |
|----|----|----|----|----|----|----|
| Sunday | Monday | Tuesday | Wednesday | Thursday | Friday | Saturday |

### Timestamp Format

| Scenario | Pattern | Example |
|----------|---------|---------|
| Time known | `Dd HH:MM TZ` | `Th 14:30 EST` |
| Time unknown | `Fullday` | `Thursday` |

---

## 🏷️ Category Emojis

| Emoji | Category | Emoji | Category |
|-------|----------|-------|----------|
| 🔧 | Tools Decision | 🐛 | Bug Fix |
| 🚨 | Error Resolution | ✨ | Enhancement |
| 📖 | Documentation | 🧪 | Testing |
| 🏗️ | Architecture | 🔐 | Security |
| 🎪 | Event Planning | ⚙️ | Operations |
| 📐 | Standards | 🔍 | Health Check |
| 🎨 | Creative | 📦 | Product |
| 💡 | Ideation | 🚀 | Launch |
| 🤝 | Collaboration | 💰 | Finance |
| 📊 | Analytics | 📣 | Marketing |
| 🎓 | Learning | 🏛️ | Milestone |

---

## 📝 Entry Template

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
```

### Example Entry

```markdown
> **GTM_2026-W02_017** | 🤝 Collaboration: Core TEAM CCC Adoption
>
> | Field | Value |
> |-------|-------|
> | **Timestamp** | Th 14:30 EST |
> | **Status** | ✅ Complete |
> | **Category** | 🤝 Collaboration |
> | **Priority** | 🟠 P1 - High |
>
> ### Description
> Collaborate with Core TEAM to review, refine, and formally adopt the CCC standard.
```

---

## 📚 Documentation

| Document | Description |
|----------|-------------|
| [CCC_CONTRIBUTOR-CODE-CONVENTION.md](CCC_CONTRIBUTOR-CODE-CONVENTION.md) | Full specification |
| [CHANGELOG.md](CHANGELOG.md) | Version history |

---

## 🤝 Contributing

1. **Request a CCC** — Contact Core TEAM for contributor code assignment
2. **Follow the Standard** — Use Entry ID format for all contributions
3. **Submit PRs** — Propose changes via pull request

---

## 📜 Version History

| Version | Date | Entry ID | Changes |
|---------|------|----------|---------|
| 2.4.0 | 2026-01-09 | GTM_2026-W02_017 | Core TEAM CCC Collaboration & Adoption |
| 1.0.0 | 2026-W02 | GTM_2026-W02_010 | Initial CCC standard established |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🔗 Links

| Resource | URL |
|----------|-----|
| **WeOwnNet** | [weown.net](https://weown.net) |
| **AI Instance** | [AI.WeOwn.Agency](https://AI.WeOwn.Agency) |
| **GitHub Org** | [github.com/WeOwnNet](https://github.com/WeOwnNet) |

---

<div align="center">

*♾️ WeOwnNet 🌐 | 🏡 Real Estate and 🤝 cooperative ownership for everyone. An 🤗 inclusive community, by 👥 invitation only.*

</div>
