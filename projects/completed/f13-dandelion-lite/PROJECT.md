---
title: "F13 - Dandelion-lite: Decentralized nodes for dummies for GameChanger, Gimbalabs, Roundtable and devs"
notion_url: "https://www.notion.so/8643ce045d37423597e423bf21eb41b6"
status: "Done"
priority: null
owner: []
collaborators: []
funding_source:
  - "F13: Dandelion"
circle:
  - "Builder"
ada_inflows: 199000
ada_outflows: null
budget_spent_ada: null
operational_dates:
  start: "2024-09-26"
  end: null
review_date: "2025-01-24"
archived_at: "2026-03-09"
has_tasks: true
task_count: 1
tasks_exported: true
---

# F13 - Dandelion-lite: Decentralized nodes for dummies for GameChanger, Gimbalabs, Roundtable and devs

## Project Meetings

This project has been funded by Catalyst in F13! Now the real fun can begin.
- Soft launch meeting: 24 January

Catalyst milestones: https://milestones.projectcatalyst.io/projects/1300078/milestones/2

[Jitsy meeting link](https://meet.jit.si/moderated/d2b4d761960b5ead162c5f3e522166be2eef812bffd500a35b28f79885b18ffc)

### Meeting Notes Archive
- Agenda 2 December 14:00 UTC
- Agenda 9 December 14:00 UTC
- Agenda 16 December 14:00 UTC
- Agenda 23 December (No meeting)
- Agenda 30 December (No meeting)
- Agenda 6 January
- Agenda 13 January
- DNO operator list
- Milestone 4 Maintenance ideas
- Hardware

## Gimbalabs Primary Driver

To run a Cardano dApp other than the Cardano node, several other services are essential. Dandelion-lite intends to make running these services effortless. Setting up a local development environment or production servers. Cardano nodes are decentralized and here we want to fill a huge gap in this global system. Essential services need to be decentralized. With Dandelion-lite we can do this.

## Proposal Driver

1. **What is the current situation:** Dandelion has a long history running in the Gimbalabs organisation. Running useful services for free to run dApps and to learn building on Cardano. From this originated a dependency of the Gamechanger wallet on this infrastructure. Dandelion is build to run on Kubernetes. A highly scalable micro service architecture. The original Dandelion requires significant devOps knowledge to maintain and run. Limiting scaling. From this originated Dandelion-lite a version of Dandelion using a single docker-compose.yml to define all running services.

2. **Impact:** To truly scale Cardano and educate new developers the barrier to entry needs to be as low as possible. Dandelion-lite will empower everybody to run indexers and query services. Demystifying the system and reduce dependencies on 3rd parties. Allowing every body to scale the system creating exponential growth.

## Links

- Dandelion: https://dandelion.link/
- Gimbalabs Dandelion GitLab: https://gitlab.com/gimbalabs/dandelion
- Dandelion-lite (fork of Koios-lite with Dandelion services added): https://github.com/GameChangerFinance/gc_node

## Proposal

### 1. Title or Brief Description

Run essential Cardano services, indexers and query services on a local computer with minimal effort. Dandelion lite uses a single docker-compose.yml file.

### 2. Background or Rationale

Every dApp has specific needs. Having a customizable system for running services allows for deeper knowledge building in the community. Running services on system that fit the budget and requirements of the developers.

The beauty of Dandelion, Roberto's dream, was to help students, devs but also decentralize Cardano services more, so think that wallets, dapps, services SHOULD be interested in helping us all somehow with The Dandelion Network.

### 3. Intended Outcome

Ecosystem growth. Developer growth in knowledge of running Cardano blockchain services
- Inspire + enable people to run Dandelion nodes
- Prepare a Fund 13 Proposal - dev ecosystem - administering via Gimbalabs
- ...then GET THE WORD OUT!
- Dandelion PBL course...
- ...and contribution tasks for people who complete it
- Create a central point for the maintainer / contributor community
  - Now people doing it by themselves. GL people come together and not duplicating effort. Build community knowledge
  - no solo suffering

### 4. Details of the Proposal

**In Scope:**
- Drafting a F13 Proposal(s) to Project Catalyst / Intersect
  - [Fund12 proposal](https://www.lidonation.com/en/proposals/dandelion-lite-decentralized-nodes-for-dummies-for-gc-gimbalabs-roundtable-and-devs-f12): https://cardano.ideascale.com/c/idea/120108
- Make it easier for anyone to run their own Dandelion-lite node
- Education / Documentation
  - How to use the endpoints / services + why they're needed
  - How to run Dandelion-lite node
  - How to use command-line GUI
  - Spaces to do outreach and community / troubleshooting
- Server costs (fund a small number of operators)
  - machine: A suggested setup for concurrent Cardano Mainnet and Preproduction Testnet consists on 128GB RAM (DDR4 ECC RAM), 2TB M2 NVME for storage, Dual Intel Xeon E5 2680 v4 (LGA 2011-3 motherboard). That could be taken as a minimal for concurrent network setup
  - electric: running at Maarten's office, backup power?
  - AWS - not cost effective more than 700 Euros / month
- Codebase maintenance

**Outside of Scope:**
- Dandelion load balancer
- Long-term incentive models
- Micro-payments + subscription fees

**Services to be included:**
- GraphQL
- Koios
- Ogmios
- Cardano Token Registry
- Dandelion PostGREST

### 5. Impact and Benefits

Everybody starting developer will be able to run Cardano services and start a bare bones local testnet in 20 seconds.

### 6. Evaluation Criteria

1. How many projects are using Dandelion
2. Developers contributing to development on github
3. Has Traffic flow increased and steady
4. Do we have a viable Fund13 Project Catalyst or Intersect proposal
5. Are education materials ready
6. Are dashboards making sense

### 7. Timeline

Dandelion-lite is already running Gamechanger wallet infrastructure.
- 10-10-2024: Submit Project Catalyst F13 Proposal
- 1-11-2024: Cleanup codebase and user testing
- 1-12-2024: Build a course on running the system
- 1-3-2025: Traffic flow and query analysis dashboard
- 1-6-2025: Build an access system. Tokenized or otherwise. (optional)

### 8. Resources Required

Running Dandelion requires continuing maintenance and improvements. As Cardano will be constantly evolving.
1. Server costs
2. Code maintenance
3. Education

### 9. Responsibilities

Maarten Menheere: Engineer and maintainer

### 10. Potential Risks and Mitigation Strategies

Running and maintaining the service infrastructure requires considerable resources. Without build-out of a business model, the system could end up not being used or under funded. The project could be forced to stop and development effort will have been wasted.

### 11. Review and Adaptation Plan

Initial project has be released on github. Code can be discussed and suitability can be determined from here.
