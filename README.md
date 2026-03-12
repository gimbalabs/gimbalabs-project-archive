# Gimbalabs Governance

Governance hub for the Gimbalabs community - proposals, DRep voting, and collective decision-making.

---

## Next Steps

- [ ] **Today at Open Spaces** - Review what's here and identify what's missing from Notion
- [ ] **Next 24 hours** - Commit anything else we want to preserve to this repo
- [ ] **EOD Friday** - Gimbalabs Notion will be shut down
- [ ] **Future** - Build systems here!

---

## Current State (March 2026)

This repository was created by exporting Gimbalabs project documentation from Notion and transforming it into an active governance hub. **All Notion content has been migrated into the active structure.**

**What's here now:**
- `projects/active/` - 10 in-progress projects
- `projects/completed/` - 26 completed projects
- `proposals/draft/` - 22 backlog/planning items ready for refinement
- `proposals/closed/` - 1 canceled proposal
- `drep/votes/` - 3 historical vote records
- `process/` - Governance documentation (consent, lifecycle, contributing)

**What's ready to use:**
- Proposal template based on our existing 11-point framework
- DRep voting process documentation
- Consent-based decision making guide
- Clear lifecycle for proposals (Draft → Open → Active → Closed)

**What needs attention:**
- Review for any missing projects from Notion
- Add actual DRep ID to `/drep/README.md`
- Review draft proposals - which should move to `open/` for consent?

---

## Quick Links

- [Submit a Proposal](./proposals/TEMPLATE.md) - Use our 11-point template
- [DRep Information](./drep/README.md) - How to delegate and participate
- [How to Contribute](./process/contributing.md) - Get involved in governance

## Structure

```
gimbalabs-governance/
├── proposals/           # Proposal lifecycle
│   ├── TEMPLATE.md      # 11-point proposal template
│   ├── draft/           # Work in progress (22 items from Notion backlog/planning)
│   ├── open/            # Open for consent (14 days default)
│   ├── active/          # Approved, being implemented
│   └── closed/          # Completed or withdrawn (1 canceled)
│
├── drep/                # DRep governance
│   ├── README.md        # Mission and delegation info
│   ├── process.md       # How votes are decided
│   └── votes/           # Vote records with rationales (3 historical)
│
├── projects/            # Project tracking
│   ├── active/          # Currently in progress (10 projects)
│   └── completed/       # Done (26 projects)
│
└── process/             # Governance documentation
    ├── consent-process.md     # How consent-based decisions work
    ├── proposal-lifecycle.md  # Draft → Open → Active → Closed
    └── contributing.md        # How to participate
```

## How We Make Decisions

Gimbalabs uses **consent-based governance**. A proposal proceeds when no one has a reasoned objection - not when everyone agrees, but when everyone can say: *"This is good enough for now, safe enough to try."*

**The consent process:**
1. **Proposal** - Author presents using our 11-point template
2. **Clarification** - Questions to understand (not critique)
3. **Reactions** - Initial thoughts from participants
4. **Consent round** - Ask for objections (not preferences)
5. **Integration** - Address valid objections, or proceed

See [consent-process.md](./process/consent-process.md) for details.

## Proposal Template

Our proposals use an 11-point framework:

1. Title or Brief Description
2. Background or Rationale
3. Intended Outcome
4. Details of the Proposal
5. Impact and Benefits
6. Evaluation Criteria
7. Timeline
8. Resources Required
9. Responsibilities
10. Potential Risks and Mitigation Strategies
11. Review and Adaptation Plan

See [TEMPLATE.md](./proposals/TEMPLATE.md) for the full template.

## DRep Participation

Gimbalabs operates as a collective DRep in Cardano's governance system. Community members collectively decide how we vote.

**To participate:**
- Join Discord `#governance` channel
- Attend Open Spaces Thursday governance segment
- Raise objections during consent rounds

**To delegate:** See [drep/README.md](./drep/README.md)

## Get Involved

1. **Join Discord** - [discord.gg/gimbalabs](https://discord.gg/gimbalabs)
2. **Attend Open Spaces** - Thursdays, weekly
3. **Read the docs** - [process/contributing.md](./process/contributing.md)

## Primary Driver

> To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems

All governance decisions should align with this driver.
