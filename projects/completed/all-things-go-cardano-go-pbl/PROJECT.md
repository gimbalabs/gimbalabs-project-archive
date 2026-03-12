---
title: "All Things Go + Cardano Go PBL"
notion_url: "https://www.notion.so/10b0db6d1d5d808eac6dc803a28692a5"
status: "Done"
priority: null
owner: []
collaborators: []
funding_source: []
circle: []
ada_inflows: null
ada_outflows: null
budget_spent_ada: null
operational_dates:
  start: null
  end: null
review_date: null
archived_at: "2026-03-09"
---

# All Things Go + Cardano Go PBL

## Gimbalabs Primary Driver
To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems

## Starting Points

### Course Building - CGPBL
1. To follow Aiken PBL
2. Shout out to HK dev series (tweet)
3. Shifting focus based on what we have learned and Conway updates (see closeout)

### Planning Notes
- Last week: Starter Kits and Course Development, side by side
- Read Path and Write Path
- What's an application that can tie it all together?
- Share Aiken Game example
- Sketching Timelines (post-Digitialis release)

### Cardano Go PBL Course Ideas

**From Digitalis:**
- Use the Digitalis Tx Backend for example material - most impactful, common use case, this is our end-to-end example
- We won't need to cover Indexers again
- In general, open sourcing the Tx Backend "exposing the magic"

**Focus on evaluating transactions**

**Lean on Blink Labs - transactions for testing:**
- "Build a transaction that looks right for **this** testnet"

**See "use or Ouroboros mock" in Go Node repo:**
- Now extend from there to generate mock transactions that look correct on the mock wire
  - Random generate
  - Inputs, outputs
- Let's build some "mock state" into the Ouroboros library so that we can give students tasks defined in our learning course
- Reproducible test environment
- Sometimes you don't want all the power of the distributed system - you just want to build UX (for example) quickly and have instant tx settlement. This mock ledger gives you access to that kind of api...

### Next Steps
- Build a course module, look at Starter Kits with Nelson
- Figure out an example app - looking at how to port an existing app to UTxO RPC - and use it in CGPBL
  - Here is a simple backend app
  - Here is how it works
  - Let's convert it UTxO RPC

## Proposal (Template - Not Filled In)

### 1. Title or Brief Description
(Not specified)

### 2. Background or Rationale
(Not specified)

### 3. Intended Outcome
(Not specified)

### 4. Details of the Proposal
(Not specified)

### 5. Impact and Benefits
(Not specified)

### 6. Evaluation Criteria
(Not specified)

### 7. Timeline
(Not specified)

### 8. Resources Required
(Not specified)

### 9. Responsibilities
(Not specified)

### 10. Potential Risks and Mitigation Strategies
(Not specified)

### 11. Review and Adaptation Plan
(Not specified)
