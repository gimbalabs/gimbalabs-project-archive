# Tasks for DRep Community Platform

*Archived from Notion on 2026-03-09*
*Updated 2026-03-12: Full task export with 68 tasks*

**Source Database:** https://www.notion.so/2780db6d1d5d80b7a4fae86238b2a5d3
**Project:** https://www.notion.so/2780db6d1d5d80ae9c1ceeb7a318b3a8
**Live Site:** https://drep.gimbalabs.com/
**GitHub:** https://github.com/gimbalabs-builders/drep-community-platform

## Task Schema

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

## Task Summary (68 tasks)

| Task ID | Task Name | Status | Priority | Tags |
|---------|-----------|--------|----------|------|
| GHT-650 | 1st October meeting | Done | — | Non-task |
| GHT-651 | Deploy discord bot | Done | — | — |
| GHT-652 | drep.gimbalabs.com subdomain | Done | — | — |
| GHT-653 | Move repo from glbuilders to main GL repo | Done | — | — |
| GHT-656 | 2nd Oct Meeting | Done | — | Non-task |
| GHT-661 | Move bot repo from gimbalabs-builders | Done | — | — |
| GHT-664 | Meeting Oct 6 | Done | — | Non-task |
| GHT-682 | Lewis on contributing.md | Done | — | — |
| GHT-691 | Bug: discord invite is expired | Done | Medium | Bug |
| GHT-711 | meeting 2025-10-23 | Done | — | — |
| GHT-743 | Task (placeholder) | Not started | — | — |

*Additional tasks exist in Notion - see full project database for complete list.*

---

## Detailed Task Content

### GHT-650: 1st October Meeting

**Status:** Done | **Tags:** Non-task

**Action Items:**
- [ ] Setting up an Andamio Project
- [x] drep.gimbalabs.com subdomain
- [x] Set up discord space for async comm
- [ ] Discord bot deployment: https://github.com/gimbalabs-builders/gimbalabs-drep-discord-bot
- [ ] Platform repo: https://github.com/gimbalabs-builders/drep-community-platform
- [ ] Get Nelson sustain and maintain contributor tokens
- [ ] Documentation - user support
- [ ] Show in Open Spaces
- [ ] Collect links - GL DREP repo
- [ ] Clear the tension: GL DREP is inactive

**Features to work on immediately:**
- [ ] Change backend API to use api from blockfrost.io
  - gov.tools for an API with more info on gov actions
  - cexplorer.io
- [ ] Get proposal titles to live proposals (Blockfrost API)
- [ ] Database - storing off-chain votes - unique gov action
- [ ] Dashboard interface - shows votes plus rationale (make rationale mandatory)
- [ ] Voter interface - get names of proposals (also in discord bot messages)
- [ ] Before on-chain vote - publish to the DREP repo
- [ ] Change to multi-sig contract - validators build, new DRep ID (NFT allowed to vote)
  - Audit? Maybe DatumDons
  - Validators from Adrian

**Portal walkthrough:**
- Index page
- Gov-actions page (blockfrost filter proposals, filter which GL hasn't voted)
- Cast vote page (if contributor token from sustain and maintain course/project)

---

### GHT-651: Deploy Discord Bot

**Status:** Done

Deployed to test server. Technical documentation for the bot:

**Environment Variables (.env):**

| Variable | Type | Description |
|----------|------|-------------|
| `DISCORD_TOKEN` | string | Discord bot authentication token |
| `DISCORD_CHANNEL_ID` | string | Discord channel for proposal updates |
| `DREP_ID` | string | Gimbalabs DRep ID for fetching votes |
| `CATALYST_API_URL` | string | API base URL for Catalyst proposals |
| `USE_SAMPLE_PROPOSALS` | boolean | Load sample data for testing |

**Core Constants:**

| Constant | File | Purpose |
|----------|------|---------|
| `GIMBALABS_DREP_ID` | gimbalabs-drep.ts | Static DRep ID |
| `cron.schedule(...)` | bot.ts | Recurring schedule for proposal checks |

**Core Functions:**

**bot.ts:**
- `postProposalsToDiscord()` - Fetches pending proposals and posts as embeds
- `main()` - Starts bot, logs into Discord, sets up cron job

**get-proposals.ts:**
- `fetchProposalsPage(pageNumber)` - Fetches single page of proposals
- `fetchAllProposals()` - Fetches all proposals across pages
- `fetchProposalsSample()` - Loads local sample JSON for testing

**gimbalabs-drep.ts:**
- `getDrepVotes(drepId)` - Fetches all votes by specified DRep
- `filterUnvoted(proposals, votes)` - Returns proposals not yet voted on

**pending-proposals-utils.ts:**
- `pendingProposalGimbalabsDrepHasNotVotedYet()` - Main logic for unvoted proposals
- `enrichProposalsWithTitles()` - Adds readable titles
- `getUnvotedProposalsForDiscord(max)` - Prepares Discord embeds

**Architecture Notes:**
- FigJam outline: https://www.figma.com/board/DtzQer1EErSk8QKBH0bTQ0/Asteria-T3-Frontend
- Discord embed types: https://discord-api-types.dev/api/discord-api-types-v10/interface/APIEmbed

---

### GHT-652: drep.gimbalabs.com subdomain

**Status:** Done

Set up drep.gimbalabs.com subdomain for the platform.

---

### GHT-653: Move repo from glbuilders to main GL repo

**Status:** Done

- Move everything (validator)? Yes, Nelson will do
- Newman will change local/remote to have new upstream

---

### GHT-656: 2nd October Meeting

**Status:** Done | **Tags:** Non-task

**Discussion topics:**
- Voting power and how to validate users of the portal
  - Delegate to the DRep as a qualifier
  - Complete the "Getting started in GL" course / credential
  - Adrian's concern: can be multiple - the idea of "proof of life"
  - How to qualify the votes in the Portal

---

### GHT-661: Move bot repo from gimbalabs-builders

**Status:** Done

- From: https://github.com/orgs/gimbalabs/repositories
- To: https://github.com/gimbalabs-builders/gimbalabs-drep-discord-bot

---

### GHT-664: Meeting Oct 6

**Status:** Done | **Tags:** Non-task

Attendees: Lewis, Harsha, Newman, Nelson

**Blockers:**
- Setting up course in Andamio

---

### GHT-682: Lewis on contributing.md

**Status:** Done

Lewis working on the contributing.md documentation.

---

### GHT-691: Bug: Discord invite is expired

**Status:** Done | **Priority:** Medium | **Tags:** Bug

**User Story:**
As a user, when I click the "Join Us" button, I expect to be directed to a valid Discord invite link so I can join the community. However, if the Discord link has expired, I receive an error or am unable to join, which prevents me from connecting with the group and participating in discussions. I want the link to be updated or to receive a helpful message so I know how to join without frustration.

**Assignee:** Lewis

---

### GHT-711: Meeting 2025-10-23

**Status:** Done

**Agenda:**
- How it works - steps - getting started at Gimbalabs at Andamio course
- Rewards program
- Get to the point -> please go and use
  - Today in OpenSpaces

---

## All Task URLs (68 total)

For reference, here are all task URLs linked to this project:

1. https://www.notion.so/27f0db6d1d5d8045b836ea7e1e0a9815
2. https://www.notion.so/2800db6d1d5d805fbedaeddd3237d31c
3. https://www.notion.so/27f0db6d1d5d80b586c9c4bfbd452bd6
4. https://www.notion.so/27f0db6d1d5d80a294c9c0def429e9b5
5. https://www.notion.so/2810db6d1d5d805da0f1c6ceb67738c4
6. https://www.notion.so/27f0db6d1d5d806e93c4f73cedd3ed0c
7. https://www.notion.so/27e0db6d1d5d806ba9c1d2716fb34343
8. https://www.notion.so/2810db6d1d5d8084b4feec1e70ea113b
9. https://www.notion.so/27f0db6d1d5d8010a205c5511c335385
10. https://www.notion.so/27f0db6d1d5d804cb7a2fae32658b095
11. https://www.notion.so/2810db6d1d5d804290f1c9d42a919ce6
12. https://www.notion.so/2840db6d1d5d80518ac0eea5b7febb55
13. https://www.notion.so/2840db6d1d5d80a781eadda14e0402d3
14. https://www.notion.so/2840db6d1d5d80d7bbfcfd16cd319d6f
15. https://www.notion.so/2840db6d1d5d800d877afa88125cdf73
16. https://www.notion.so/2840db6d1d5d80aba5a0e66be080e8fd
17. https://www.notion.so/2840db6d1d5d80a4ba03c9ae2e71a678
18. https://www.notion.so/2840db6d1d5d80c59fe0f327ecd77dcd
19. https://www.notion.so/2840db6d1d5d80cbae3fd2c019b50348
20. https://www.notion.so/2810db6d1d5d8089a45ffad6513359d2
21. https://www.notion.so/2840db6d1d5d80b09c65e8d995903863
22. https://www.notion.so/2840db6d1d5d80318035c1691c0cc139
23. https://www.notion.so/2840db6d1d5d8040b9decac1f1a66a29
24. https://www.notion.so/2840db6d1d5d807baa27cbd4f7de2ab4
25. https://www.notion.so/2840db6d1d5d800ea8fbc1e20cfb38c4
26. https://www.notion.so/2840db6d1d5d8046b2d5c47b3189f319
27. https://www.notion.so/2850db6d1d5d8015a275efeddce047d6
28. https://www.notion.so/2850db6d1d5d80b6af25f8d34429ba37
29. https://www.notion.so/2850db6d1d5d8053ae31e656301b049f
30. https://www.notion.so/2870db6d1d5d8034af8deab45373feac
31. https://www.notion.so/2870db6d1d5d80df8529f471f7489bd9
32. https://www.notion.so/2870db6d1d5d8023bf6bee75202adabc
33. https://www.notion.so/2870db6d1d5d8062a401dbb4d881be00
34. https://www.notion.so/2870db6d1d5d8016985ac2c3bb275e74
35. https://www.notion.so/2870db6d1d5d802f9af4d9fe536a5186
36. https://www.notion.so/2880db6d1d5d803da438d4f29f880421
37. https://www.notion.so/28b0db6d1d5d806ba85fc5df22ddd3df
38. https://www.notion.so/28b0db6d1d5d80718fc9f6e457ff53de
39. https://www.notion.so/28b0db6d1d5d80a69070c84523173ef2
40. https://www.notion.so/28b0db6d1d5d8090ab04de3f90c88678
41. https://www.notion.so/28b0db6d1d5d80fd828ae31686eb091e
42. https://www.notion.so/28b0db6d1d5d8014aab3fe7dc6460ab0
43. https://www.notion.so/28b0db6d1d5d80db8fcefe205ede846e
44. https://www.notion.so/28b0db6d1d5d804ba09df70beca1bccd
45. https://www.notion.so/28d0db6d1d5d80c387def66ea60708b6
46. https://www.notion.so/28d0db6d1d5d804b9f0ef8f623730090
47. https://www.notion.so/28d0db6d1d5d80a596ddd1e6ea1eec81
48. https://www.notion.so/28e0db6d1d5d8047b1c1e28db63d07d9
49. https://www.notion.so/28f0db6d1d5d80908a2cf1a40e2ed7d8
50. https://www.notion.so/2930db6d1d5d808195acd10bdec3bf1d
51. https://www.notion.so/2950db6d1d5d80fbb461e399f27967aa
52. https://www.notion.so/29c0db6d1d5d80569306d5db96876232
53. https://www.notion.so/29c0db6d1d5d80b1aca5e37155a6d50d
54. https://www.notion.so/29c0db6d1d5d80e2b99df91cf2227f94
55. https://www.notion.so/2b10db6d1d5d8073914afa71b8564412
56. https://www.notion.so/2b10db6d1d5d808c8ef6f9a682e51942
57. https://www.notion.so/2c00db6d1d5d808284a6f214cf4be66a
58. https://www.notion.so/2c00db6d1d5d8091a8c2f36aeecf023e
59. https://www.notion.so/2c40db6d1d5d80649927cb8269719226
60. https://www.notion.so/2c40db6d1d5d8002ac42e8e9e6b3b079
61. https://www.notion.so/2c60db6d1d5d802091bfdab971d4fe20
62. https://www.notion.so/2c60db6d1d5d8015b8d5f8d1a93b2718
63. https://www.notion.so/2ca0db6d1d5d8036b727f562debc9e3e
64. https://www.notion.so/2d20db6d1d5d80dd8a44d1c1a937cc45
65. https://www.notion.so/2d30db6d1d5d80f09325c779f0052adf
66. https://www.notion.so/2e90db6d1d5d80cda980e9a4259fbb5e
67. https://www.notion.so/2e90db6d1d5d80c08d08cb15f7707125
68. https://www.notion.so/2e90db6d1d5d8026b03ee362fb3127f4
