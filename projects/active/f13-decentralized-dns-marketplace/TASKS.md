# Tasks for F13 Decentralized DNS Marketplace

*Archived from Notion on 2026-03-12*

**Source Database:** https://www.notion.so/1610db6d1d5d81258adede244e5502fd
**Project:** https://www.notion.so/1610db6d1d5d80c89593e0be2111143a

## Task Summary

This project has an embedded tasks database but no tasks have been created yet.

The project is tracked primarily through Catalyst milestones rather than Notion tasks.

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

---

## Related Resources

**Catalyst Proposals:**
- [Decentralized Domain Name System (DNS) Marketplace powered by Cardano and Handshake blockchains](https://projectcatalyst.io/funds/13/f13-cardano-open-developers/decentralized-domain-name-system-dns-marketplace-powered-by-cardano-and-handshake-blockchains)
- [Handshake decentralized DNS blockchain integration with cDNSd by Blink Labs](https://projectcatalyst.io/funds/13/f13-cardano-open-developers/handshake-decentralized-dns-blockchain-integration-with-cdnsd-by-blink-labs)

**Related Project:**
- [Cardano Go Course Update & DNS CLI Development](../cardano-go-course-update/PROJECT.md) - Developer onboarding for CLI milestone

---

## Notes

This project serves as a Gimbalabs tracker for the F13 Catalyst proposal. Detailed implementation tasks are tracked through:
1. Catalyst milestone reporting
2. The related Cardano Go Course Update project
3. GitHub issues on the project repositories
