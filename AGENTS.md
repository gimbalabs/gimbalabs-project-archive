# AGENTS.md

Project instructions for AI agents working with this repository.

## Repository Purpose

This is the **Gimbalabs Governance Hub** - an active repository for collective decision-making, DRep voting, and proposal management.

## Structure

```
gimbalabs-governance/
├── proposals/           # Proposal lifecycle
│   ├── TEMPLATE.md      # 11-point proposal template
│   ├── draft/           # Work in progress (22 items)
│   ├── open/            # Open for consent (14 days default)
│   ├── active/          # Approved, being implemented
│   └── closed/          # Completed or withdrawn
│
├── drep/                # DRep governance
│   ├── README.md        # Mission and delegation info
│   ├── process.md       # How votes are decided
│   └── votes/           # Vote records (3 historical)
│
├── projects/            # Project tracking
│   ├── active/          # In progress (10 projects)
│   └── completed/       # Done (26 projects)
│
└── process/             # Governance documentation
    ├── consent-process.md     # Consent-based decisions
    ├── proposal-lifecycle.md  # Draft → Open → Active → Closed
    └── contributing.md        # How to participate
```

## Key Concepts

### Consent-Based Governance
Proposals proceed when no one has a **valid objection** (not when everyone agrees). Valid objections identify concrete harms or conflicts with the primary driver.

### 11-Point Proposal Framework
All proposals use this structure:
1. Title
2. Background/Rationale
3. Intended Outcome
4. Details
5. Impact and Benefits
6. Evaluation Criteria
7. Timeline
8. Resources Required
9. Responsibilities
10. Risks and Mitigation
11. Review and Adaptation Plan

### Proposal Lifecycle
- **Draft** → In development, not yet open
- **Open** → Open for consent (default 14 days)
- **Active** → Approved, being implemented
- **Closed** → Completed, withdrawn, or superseded

### DRep Voting Process
1. Identification (monitor gov.tools)
2. Analysis (prepare unbiased summary)
3. Discussion (Discord + Open Spaces)
4. Decision (consent round)
5. Documentation (record rationale)
6. Publication (on-chain vote)

## Context

Gimbalabs is a Cardano ecosystem education organization focused on:
- Project-Based Learning (PBL) courses
- Andamio platform development
- DRep governance participation
- Open Spaces and live coding sessions

**Primary Driver:** To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems

## Common Tasks

### Creating a New Proposal
1. Copy `proposals/TEMPLATE.md`
2. Fill in all 11 sections
3. Save to `proposals/draft/`
4. Move to `proposals/open/` when ready for consent

### Recording a DRep Vote
Create `drep/votes/YYYY-MM-DD-action-name.md` with frontmatter:
```yaml
---
action: "Action title"
gov_tools_url: "https://..."
vote: Yes | No | Abstain
voted_on: YYYY-MM-DD
epoch: NNN
---
```

### Moving a Proposal Through Lifecycle
- Draft → Open: Move file from `proposals/draft/` to `proposals/open/`, update frontmatter
- Open → Active: After consent, move to `proposals/active/`, set `decision: Approved`
- Active → Closed: When complete, move to `proposals/closed/`

## Frontmatter Schemas

### Proposal Files
```yaml
title: "Proposal Name"
status: "Draft" | "Open" | "Active" | "Closed"
author: ""
created: "YYYY-MM-DD"
consent_opens: null
consent_closes: null
decision: null | "Approved" | "Withdrawn" | "Rejected"
decision_date: null
```

### Vote Records
```yaml
action: "Action title"
gov_tools_url: "https://..."
vote: Yes | No | Abstain
voted_on: YYYY-MM-DD
epoch: NNN
```

### Project Files
```yaml
title: "Project Name"
notion_url: "https://..."
status: "Done" | "In progress" | "Backlog" | "Planning" | "Canceled"
priority: null | "High" | "Medium" | "Low"
owner: []
collaborators: []
funding_source: []
circle: []
ada_inflows: null
ada_outflows: null
budget_spent_ada: null
operational_dates:
  start: "YYYY-MM-DD"
  end: "YYYY-MM-DD"
review_date: null | "YYYY-MM-DD"
archived_at: "YYYY-MM-DD"
has_tasks: true | false
```
