---
title: "Deliver Plutus PBL 2024"
notion_url: "https://www.notion.so/cce4c83cc4fd426b9e0d7af4932505a8"
status: "Done"
priority: null
owner: []
collaborators: []
funding_source:
  - "F11: Treasury R&D"
circle:
  - "Educations / PBLs"
ada_inflows: null
ada_outflows: 13500
budget_spent_ada: null
operational_dates:
  start: "2024-09-26"
  end: "2024-11-06"
review_date: "2024-11-28"
archived_at: "2026-03-09"
---

# Deliver Plutus PBL 2024

## Gimbalabs Primary Driver
To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems.

## Proposal Driver
Currently the Gimbalabs Plutus PBL course is out of date and needs revision. It also has a general scope that is too big to be approachable to many learners.

The current course does not support students to learn up-to-date Cardano development skills, and often, students get stuck. The effect is that Gimbalabs does not currently have an up-to-date course for onboarding new Cardano developers. We need to update and focus the Plutus PBL course to a "2024" version, and to consider what some other PBL courses could be.

The new version of PPBL 2024 can focus on guiding developers to understand the architecture of an application built on Cardano by implementing validator logic and corresponding transactions across a series of applied examples. The course should be adaptable to changes in the Cardano development ecosystem.

## Proposal

### Title or Brief Description
Develop Plutus PBL 2024

### Background or Rationale
**Plutus PBL is a course for people who want to learn how to develop applications on Cardano. The course is due for updates.**

The previous version of "Plutus PBL 2023" is currently live at https://plutuspbl.io/. PPBL 2023 was initially published in March through May, 2023. It was the fourth iteration of the Plutus PBL course, which first launched in 2021.

PPBL 2023 is outdated, and needs to be updated. All on-chain functionality has been disabled, so even if they want to, students cannot make progress in the course.

**Course updates take various forms, including:**
- Updates to dependencies: like which `checkout` of PlutusTx or version of Mesh
- New dependencies: new libraries and associated design patterns that are beginner-friendly
- Versions of key infrastructure, like `cardano-node` and links to network config files
- New ideas: we've all learned a lot about what we want to teach and in what order
- General improvements: Lessons can be improved by being more succinct or more concrete

**Why make these updates?**
We need to make sure that people can learn productively in PPBL. Getting in permanently stuck isn't a "safe space to learn", and does not empower people.

### Intended Outcomes
1. Plutus PBL 2024 will be published and freely available to learners
2. The Gimbalabs Education Circle will establish processes for building courses together
3. PPBL 2024 creates ways for Gimbalabs community to collaborate: as Learners, as Course Facilitators, and as Course Creators
4. PPBL 2024 gives people a place to get stuck (temporarily) and get unstuck together

### Details of the Proposal
The course focuses on: **understand the architecture of an application built on Cardano by implementing validator logic and corresponding transactions across a series of applied examples**.

1. **Understand the architecture of an application built on Cardano:**
   - Help each learner build a robust mental model of how Cardano applications work
   - Focus on transaction building, UTxOs, and the general role of validators
   - Simple examples of indexers, transaction chaining, and concurrency solutions

2. **Implementing validator logic:**
   - Teach what a validator is and what it can and can't do
   - Build examples in PlutusTx, Aiken, Helios, and others
   - Expose learners to spending, minting, and staking validators

3. **Corresponding transactions:**
   - Learn to build a transaction with `cardano-cli` by copy and paste
   - Learn to modify a bash script to build, sign, and submit transactions
   - Learn about transaction building in Mesh

4. **Applied examples:**
   - Projects at the heart of Plutus PBL
   - Canonical contracts like the Vesting Contracts
   - Opportunities to explore: Asteria, custom indexers, SanchoNet, PlutusV3

### Impact and Benefits
- Plutus PBL 2024 is up to date
- People are empowered to solve problems
- Gimbalabs + Education Circle get to practice working together
- We build a better understanding of the UTxO Model
- We meet new builders
- The Gimbalabs community will grow or stabilize around an effective size

### Evaluation Criteria
- By 2024-03-31: A draft of Course Module list and Student Learning Targets is open for feedback
- By 2024-04-15: A clear timeline is established for publishing content
- To follow: Course content is published by shared deadlines
- Q3 2024: Measure course enrollment, course success, contributor onboarding

### Timeline
**Phase 1: Building the Team + Planning the Course (14-March to 15-April)**
1. Convene the Gimbalabs Education Circle
2. Write a revised list of Modules and Student Learning Targets
3. Create a list of "future" PBL Courses
4. Research and Development

**Phase 2: Writing the Course (8-April to 1-July)**
1. Build Examples (simply start hacking something)
2. Write Lessons
3. Create Videos
4. Create a public release schedule
5. Start rolling out!

**Phase 3: Awareness + Outreach (upcoming proposal)**

**Phase 4: Learner Support (upcoming proposal)**

### Resources Required
Phase 1 Budget = 0 Ada
Phase 2 Budget = 13,500 Ada

**Roles + Responsibilities:**
- For each Lesson, Author earns: 300 Ada
- For each Lesson, Editor earns: 150 Ada
- Assuming 30 Lessons at 450 Ada/Lesson = 13,500 Ada total

### Responsibilities
- James will facilitate Phase 1
- Create shared facilitation for Phase 2
- Writers and Editors can opt into building the course

### Potential Risks and Mitigation Strategies
It takes a lot of work to build a great Plutus PBL Course. We've done it before. The risk is to not get started.

### Review and Adaptation Plan
- Pay close attention to how work is shared and who contributes
- Review progress and draft proposals for Phase 3 and Phase 4 work
- Publish a "Mid-Course Survey" before July 2024
- Write a proposal for funding course maintenance
- In September 2024, review: Is "Plutus PBL" the right name for this course?
