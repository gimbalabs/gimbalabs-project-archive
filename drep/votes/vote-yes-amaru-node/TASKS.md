# Tasks for Vote Yes on Amaru Node Development 2025

*Archived from Notion on 2026-03-12*

**Source Database:** https://www.notion.so/1ed0db6d1d5d80e6bb6cfde1a6f628ca
**Project:** https://www.notion.so/1ed0db6d1d5d805f87c0dd83ae3aa77f

## Task Summary

No tasks were linked to this project in Notion. This was a governance decision project focused on casting a DRep vote.

---

## Notes

This project documented Gimbalabs DRep's decision to vote Yes on the Cardano Blockchain Ecosystem Budget: Amaru Node Development 2025.

**Governance Action:**
- Full Proposal: https://gov.tools/governance_actions/bd488931f792651fefa9c6fda185a2c6cec83245b51d994e33090ce36e29cc26#0
- Requested: 1.5M Ada for 6 months of Amaru development
- Timeline: Feedback period 2025-05-08 to 2025-05-12, Vote with rationale 2025-05-13

**Key Benefits Identified:**
- Diversifies Cardano's technical implementation (Rust node alternative to Haskell)
- Reduces systemic risk from single-implementation dependency
- Improves specifications for future implementations
- Sets a high standard for direct budgeting proposals

---

## Database Schema

The embedded Tasks database uses the standard Gimbalabs task schema (filtered view of main Tasks collection):

| Field | Type | Options |
|-------|------|---------|
| Task ID | Auto-increment | GHT-### |
| Task name | Title | — |
| Status | Status | Not started, In progress, QA, Blocked, Video to be edited, Done, Release, Awaiting Treasury Commitment, Archived |
| Priority | Select | Low, Medium, High, Unknown |
| Tags | Multi-select | Admin, Non-task, Feature, Bug |
| Assignee | Person | — |
| Due | Date | — |
| Sub-tasks | Relation | — |
