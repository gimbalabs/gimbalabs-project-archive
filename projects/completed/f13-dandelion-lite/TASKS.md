# Tasks for F13 - Dandelion-lite

*Archived from Notion on 2026-03-12*

**Source Database:** https://www.notion.so/2d466787598f4bfaab510eddce067369
**Project:** https://www.notion.so/8643ce045d37423597e423bf21eb41b6

## Task Summary

| Task ID | Task Name | Status | Assignee | Due |
|---------|-----------|--------|----------|-----|
| GHT-181 | Ask for feedback | Not started | — | — |

---

## Task Details

### GHT-181: Ask for feedback
- **Status:** Not started
- **URL:** https://www.notion.so/464d82eb4cd64dd3ae1ffb4feaa07c37

**Description:**
Task to collect feedback on the Dandelion-lite project.

---

## Notes

This project was funded by Catalyst in F13 (199,000 ADA inflow). The focus is on making it easy for anyone to run Cardano services with a single docker-compose.yml file.

**Related Resources:**
- Catalyst milestones: https://milestones.projectcatalyst.io/projects/1300078
- Dandelion link: https://dandelion.link/
- GameChanger gc_node: https://github.com/GameChangerFinance/gc_node
- Gimbalabs Dandelion: https://gitlab.com/gimbalabs/dandelion

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
