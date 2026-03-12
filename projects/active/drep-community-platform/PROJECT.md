---
title: "DRep Community Platform"
notion_url: "https://www.notion.so/2780db6d1d5d80ae9c1ceeb7a318b3a8"
status: "In progress"
priority: "High"
owner: []
collaborators: []
funding_source: []
circle:
  - "Builder"
ada_inflows: null
ada_outflows: null
budget_spent_ada: null
operational_dates:
  start: null
  end: null
review_date: null
archived_at: "2026-03-09"
has_tasks: true
task_count: 68
tasks_exported: true
---

# DRep Community Platform

**Full task export available:** See [TASKS.md](./TASKS.md) for all 68 tasks with detailed content including meeting notes, Discord bot technical documentation, and action items.

## Proposal Driver

Gimbalabs has been registered as a **DRep (Delegated Representative)** in the Cardano governance framework but has remained inactive, leaving community members without a reliable delegate voice. This tension highlights the immediate need for a functional solution to support governance participation.

The **DRep Community Platform** provides a fast, actionable response: deliver an MVP within 2–3 months that reactivates Gimbalabs' DRep role, engages community members, and sets the foundation for scaling into a full-fledged governance product through a Catalyst Fund 15 proposal.

---

## Proposal

### 1. Title or Brief Description
**DRep Community Platform MVP** — Fast-track solution to re-activate Gimbalabs as an active delegate representative, ready in 2–3 months.

---

### 2. Background or Rationale
- Gimbalabs is an important hub for Cardano education and experimentation, but its DRep registration has been inactive.
- This creates a gap: community members who delegated to Gimbalabs lack active representation.
- A minimal, working platform now will provide both **credibility** and **functionality**, while also building momentum for a larger scaling proposal in Fund 15.

---

### 3. Intended Outcome
- Deliver a functional MVP within 2–3 months that:
  - Reactivates Gimbalabs as a visible, accountable DRep.
  - Enables stakeholders to view proposals, see how Gimbalabs is voting, and give feedback.
  - Provides basic community engagement tools (e.g., voting rationale, discussion threads).
- Deliver a discord bot that sends reminder each day about unvoted proposals.
- Gather feedback from people who are interested in helping out build the platform and what other criteria should be supported to grow participation.
- Develop an incentivization program (at least allow people who are participating to redeem *Gimbals* as a token of gratitude) - later even to delegators.
- Establish trust and demonstrate traction before Fund 15.

---

### 4. Details of the Proposal (MVP Scope)

**MVP Features (2–3 months)**
- **DRep Profile Dashboard**: display voting history, rationale, upcoming proposals.
- **Community Participation**: a democratic voting mechanism for gimbalabs community to help in the DRep decision making process.
- **Transparency Layer**: publish decisions openly, with rationale linked to governance proposals. (https://github.com/gimbalabs/gimbalabs-drep)
- **Basic Notifications (Discord bot)**: alerts when Gimbalabs votes or when new proposals are active.

**Technical Notes**
- Use existing prototype (https://drep-community-platform.vercel.app/) as the base.
- Focus on modular architecture -> easily expanded in Fund 15.

---

### 5. Impact and Benefits
- **Immediate**: Restores trust in Gimbalabs' role as a DRep.
- **Community**: Delegators gain transparency and voice in decision-making.
- **Ecosystem**: Demonstrates fast response to governance gaps; builds a governance participation culture.
- **Future Growth**: Positions the platform as a candidate for Catalyst Fund 15 scaling.
- **Incentivization through Gimbals**: Early adopters and active community participants can be rewarded with Gimbal tokens for activities such as giving feedback, participating in discussions, or delegating through the platform. This strengthens community bonds and creates a sustainable participation loop.

---

### 6. Evaluation Criteria
- MVP delivered within 2–3 months.
- **Engagement metrics**: number of comments/feedback received.
- User activity on the platform.
- Feedback loop -> survey to measure community satisfaction.

---

### 7. Timeline

| Phase | Deliverables | Duration | Complete |
|-------|--------------|----------|----------|
| Week 1–2 | Finalize MVP scope, refine prototype | 2 weeks | yes |
| Week 3–6 | Build core features (dashboard, rationale, feedback) | 4 weeks | yes |
| Week 7–8 | Testing, deploy MVP, onboard community | 2 weeks | yes |
| Post-Launch | Collect feedback, stabilize MVP, prepare Fund 15 proposal | ongoing | in progress |

**Total:** 2–3 months

---

### 8. Resources Required
- **People**:
  - Nelson, Harsha, Newman are onboard to share the responsibilities
  - Open to anyone interested - reach out to any of us or drop by during our calls
- **Time**:
  - We will meet 2 times in a week openly in discord (everyone's welcomed)
  - We will work on specific tasks async
- **Tools/Infra**:
  - Hosting (Vercel / cloud backend)
  - Product management (Notion)
- **Budget**: Gimbalabs treasury to get to MVP -> full funding request in Fund 15 for scale-up.
- **Incentive Pool**: Allocate a small pool of Gimbals to reward MVP testers, delegators, and active contributors.
- drep.gimbalabs.com subdomain to use for this project
- new channel in `current projects` category in gimbalabs discord
- Andamio course and project for project membership and funding

### Budget (MVP Phase)
- 12000 ADA in an Andamio Treasury for transparency
  - Half, 6000 ADA as down payment
  - Remaining 6000 ADA based on the user consent model
- 50% of Gimbalabs' current gimbal holdings ready to deploy - for incentivization program experiment (5 million gimbals)
  - OR
- Unlock the next allocation (#1) of gimbals (34,441,853.61) for an incentivization program experiment

---

### 9. Responsibilities

**Development**
- Discord API and maintenance
  - Cron job
  - Notification format
- Backend
  - Blockfrost Integration - sync gov actions
  - Database - store platform votes
  - Andamio API - Access gating
- User Interface
  - Voting Interface
  - Dashboard Interface
- Github Integrations for publishing final rationale before onchain vote

**Code maintenance**
- Repo maintainer - https://github.com/gimbalabs-builders/drep-community-platform

**Community Manager**
- Incentivization program planning
  - some allocation of Gimbal Tokens, intent to distribute and circulate for dRep governance
  - who and how to distribute
- Contribution guidelines
  - contributing.MD like the README.md in a open source repo - there are standards to use, with our own twist
- Bring updates to Open spaces
- Gather community requests - participation criteria, user feedback
- Reply to any queries in discord, X regarding the platform

**On Chain vote Submission**
- For now James

**Catalyst Proposal Writer**
- Gather value propositions
- Gather technical/feature backlogs
- Budget planning

---

### 10. Potential Risks and Mitigation Strategies

| Risk | Mitigation |
|------|------------|
| Scope creep delays MVP | Strict focus on MVP (dashboard + rationale + feedback) |
| Low community engagement | Leverage Gimbalabs community + Cardano channels for outreach |
| Technical blockers with data | Use reliable APIs / adapt MVP scope for simpler manual updates if needed |
| MVP seen as "too minimal" | Frame clearly as a **stepping stone** toward Fund 15 full product |

---

### 11. Review and Adaptation Plan
- Weekly dev syncs to stay on track.
- MVP release -> 1 month of user testing with community.
- Collect feedback -> adjust features or UI quickly.
- Incorporate results into **Fund 15 proposal** with evidence of adoption, lessons learned, and clear roadmap to scale.

## Questions
- Who participates in the dRep community portal? any wallet delegated to Gimbalabs DRep vs. require a Gimbalabs course for Sybil resistance?

## Links
- Live: https://drep.gimbalabs.com/
- GitHub: https://github.com/gimbalabs-builders/drep-community-platform
