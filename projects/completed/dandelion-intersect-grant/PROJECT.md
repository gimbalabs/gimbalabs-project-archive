---
title: "Dandelion Intersect Grant"
notion_url: "https://www.notion.so/91d3f126f12348e79c2c5f1798baa2df"
status: "Done"
priority: null
owner: []
collaborators: []
funding_source: []
circle:
  - "Admin"
ada_inflows: 70000
ada_outflows: null
budget_spent_ada: null
operational_dates:
  start: null
  end: "2024-05-31"
review_date: null
archived_at: "2026-03-09"
has_tasks: true
task_count: 3
tasks_exported: true
---

# Dandelion Intersect Grant

## Gimbalabs Primary Driver

To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems

## Proposal Driver

Gimbalabs received 70k Ada from Intersect to work on Dandelion.

## Next Steps 2024-08-06

1. Dandelion Status
2. Updated deployments + timeline
3. How to update Intersect
   1. email
   2. discord short video
   3. discord presentation

### Updates from Roberto 2024-08-06

- As of yesterday, GraphQL (which is enabled by DB Sync) is hard-fork ready
- Roberto can deploy the latest versions and communicate it by next week - we'll be able to point to the GraphQL release
  - https://github.com/cardano-foundation/cardano-graphql/releases/tag/8.2.0
  - Koios is not yet updated to latest DB Sync

James will report to Intersect
- We will have Dandelion hard-fork ready on August 19
- James will have the Contributor indexer ready to pass to Roberto on August 19 - try to get a good docker image working first

## Description of Work - From Intersect Grant

### Dandelion Servers (time + funding)

- Pay for Dandelion's servers until 31st May 2024 to keep the free Dandelion community service running reliably
- Dandelion server support, including but not limited to maintaining free Dandelion community service
- Use part of funds to onboard Dandelion operators via DPBL

### Update each Dandelion endpoint for Conway Era / SanchoNet (time + funding)

Including but not limited to:
- Rosetta API
- PostgREST API
- Submit API
- Ogmios API
- GraphQL API
- Explorer API
- Dandelion Alpha Network
- Cardano Node Socket

### Treasury Tracking Tool (time + funding)

- Create a demonstration of a proof of concept tool for treasury tracking, with the use case being this 70,000 Ada grant
- Delivery of proof of concept treasury tracking tool
- Build Dandelion PBL Course that teaches the basics
- Use the course to onboard 5 new Dandelion operators
- Compensate the operators
- Also compensate Dandelion PBL Course Builders

### Andamio and Dandelion Integrations (time + funding)

- Update or create Dandelion API so that; Proof of concept treasury tool can be built upon
- Update or create Dandelion APIs to make it easy for anybody to build upon this proof of concept treasury tracking tool
- First example being a simple indexer

**Key Responsibilities:**
1. In Go, Build an indexer that is helpful to Andamio Treasury (dev hours x 300 ada/hour)
2. Deploy the indexer on Dandelion, as a proof of concept (dev and devops hours)
3. Create a DPBL Module about how this works (writing lesson content and documentation)
4. Use the Indexer to improve Treasury performance (outcome)

### Project Management + Reporting (20 total hours + 6000 ada)

- Close-out reporting Close-Out Report (as defined in Due May 31, 2024 Section 3b of the Agreement)
- James will handle project management and reporting. 5 hours/month x 300 ada/hour = 1500 ada month x 4 months = 6000 ada

## About this project

1. Develop Helm Charts with Ledger Sync for SanchoNet
2. Build Dandelion PBL, and show people how to use those new Helm Charts (along with some basic Kubernetes and other prerequisites)
3. Goal: Get 8 (?) people running Dandelion nodes and contributing to Load Balancer
4. Do Some R+D Projects in DPBL
   1. GraphQL?
   2. 3Fold?
   3. Deploying our own microservices?
      - Like an indexer. This project could be DPBL x Cardano Go PBL

**Costs:**
1. Servers - RCM says low needs, but we should pay for new Gardeners
2. Upgrades - RCM just wants to do it (but should get paid)
3. SanchoNet endpoints? Hard to say for sure.
4. CF Ledger Sync - let's do it, right?
5. Helm Charts = Easier to Deploy (Update August 6: Not really worth it)
6. Develop DPBL Course
7. Reward Gardeners (Probably not...)
8. Rewards for new documentation + workshops, etc

**Links:**
- https://stats-ian.dandelion.link

## S3 Proposal (to be drafted)

### 1. Title or Brief Description
(Empty)

### 2. Background or Rationale
(Empty)

### 3. Intended Outcome
(Empty)

### 4. Details of the Proposal
(Empty)

### 5. Impact and Benefits
(Empty)

### 6. Evaluation Criteria
(Empty)

### 7. Timeline
- All deliverables are due by the end of May: 2024-05-31
- Therefore this project has a 3-month scope

### 8. Resources Required
- Roberto, James, Nelson

### 9. Responsibilities
(Empty)

### 10. Potential Risks and Mitigation Strategies
(Empty)

### 11. Review and Adaptation Plan
(Empty)
