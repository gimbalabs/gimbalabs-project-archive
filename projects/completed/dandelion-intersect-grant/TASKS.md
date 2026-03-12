# Tasks for Dandelion Intersect Grant

*Archived from Notion on 2026-03-12*

**Source Database:** https://www.notion.so/77fd0c07e43f4197a47e64341de4e329
**Project:** https://www.notion.so/91d3f126f12348e79c2c5f1798baa2df

## Task Summary

| Task ID | Task Name | Status | Assignee | Due |
|---------|-----------|--------|----------|-----|
| GHT-10 | Schedule a meeting with Roberto and Nelson to discuss deployment + correct connection to load balancer | Archived | — | — |
| GHT-11 | Check the health of my deployment on Scaleway | Archived | — | — |
| GHT-12 | Ask Roberto if my load balancer is set up correctly | Archived | — | — |

---

## Task Details

### GHT-10: Schedule a meeting with Roberto and Nelson to discuss deployment + correct connection to load balancer
- **Status:** Archived
- **URL:** https://www.notion.so/1f85916ae19446af8134368bb2cb3ae0

---

### GHT-11: Check the health of my deployment on Scaleway
- **Status:** Archived
- **URL:** https://www.notion.so/81dd6627140443f48cccf339d2056294

---

### GHT-12: Ask Roberto if my load balancer is set up correctly
- **Status:** Archived
- **URL:** https://www.notion.so/152d84cfae9b43988a0d432aaeeb48d8

---

## Notes

This project was funded by an Intersect Grant (70,000 ADA). The grant covered Dandelion server maintenance, Conway Era updates, a treasury tracking tool PoC, and Andamio integration work.

**Key Deliverables:**
- Dandelion servers until May 31, 2024
- Conway Era / SanchoNet endpoint updates
- Treasury tracking tool proof of concept
- Dandelion PBL Course foundations

**Team:** Roberto, James, Nelson

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
