# Tasks for Original Proposal: Gimbalabs DRep

*Archived from Notion on 2026-03-12*

**Source Database:** https://www.notion.so/1290db6d1d5d81bb8c90d1256cc4cdee
**Project:** https://www.notion.so/1290db6d1d5d80e0abaadd516aff722f

## Task Summary

| Task ID | Task Name | Status | Assignee | Due |
|---------|-----------|--------|----------|-----|
| GHT-199 | Add some user stories | Not started | — | — |
| GHT-200 | Research existing technologies | Not started | — | — |
| GHT-201 | Craft proposal driver | Not started | — | — |
| GHT-250 | (New task - untitled) | Not started | — | — |

---

## Task Details

### GHT-199: Add some user stories
- **Status:** Not started
- **URL:** https://www.notion.so/12f0db6d1d5d805ba320fd0167523af3

User stories needed to define how the Gimbalabs DRep collective will serve different community members.

---

### GHT-200: Research existing technologies
- **Status:** Not started
- **URL:** https://www.notion.so/12f0db6d1d5d80deb849eb2378e708bf

Research into existing DRep tooling and governance technologies to inform the Gimbalabs approach.

---

### GHT-201: Craft proposal driver
- **Status:** Not started
- **URL:** https://www.notion.so/12f0db6d1d5d804986d1eaad9719c753

Define the proposal driver for the Gimbalabs DRep initiative using S3 patterns.

---

### GHT-250: (New task)
- **Status:** Not started
- **URL:** https://www.notion.so/1600db6d1d5d8074b382eb9ba36ac95e

Placeholder task created during planning phase.

---

## Notes

This project established the foundation for Gimbalabs becoming a DRep collective. The tasks were in early planning stages when the project was completed, with the main focus being on:

1. Defining what the "Gimbalabs DRep function" means
2. Technical implementation using validators and on-chain voting mechanisms
3. Building tools for collective governance

**Related Reference Projects:**
- [Sociocratic DREPs: A Representation Framework for Democratic Pluralism](https://projectcatalyst.io/funds/11/cardano-open-ecosystem/sociocratic-dreps-a-representation-framework-for-democratic-pluralism) (Photrek)
- [AI Assistant for Governance: Empowering Team-Based DReps](https://projectcatalyst.io/funds/12/cardano-open-developers/ai-assistant-for-governance-empowering-team-based-dreps) (Photrek)

---

## Database Schema

The embedded Tasks database uses the standard Gimbalabs task schema:

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
