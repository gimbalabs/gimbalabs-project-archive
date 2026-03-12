---
title: "BlockPrint x Gimbalabs to build BlockGov"
notion_url: "https://www.notion.so/2aa0db6d1d5d8014a648f2022456cfb0"
status: "Proposal Ready for Review"
priority: null
owner: []
collaborators: []
funding_source: []
circle: []
ada_inflows: null
ada_outflows: null
budget_spent_ada: null
operational_dates:
  start: "2025-11-13"
  end: null
review_date: null
archived_at: "2026-03-09"
has_tasks: true
tasks_database_url: "https://www.notion.so/2aa0db6d1d5d80a5ac20d8240ae6fb44"
---

# BlockPrint x Gimbalabs to build BlockGov: all-in-one Cardano governance platform

## Gimbalabs Primary Driver

To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems

## Proposal Driver

**Background and Motivation:**

**This is a project catalyst proposal**

**BlockPrint** is an emerging Cardano developers community that grew out of the **Gimbalabs African Developer Education Initiative**. Through this educational foundation, they've developed a deep understanding of both the **technical** and **community-driven** aspects of decentralized systems.

**Why This Proposal:**

As a community of early builders and learners, we recognize that **governance and treasury transparency** are vital to the sustainability and inclusiveness of Cardano. However, many participants especially new developers and community members struggle to understand how governance actions, treasury spending, and proposals actually work in practice.

This realization inspired us wanting to design a platform that:
- Makes **governance participation approachable** and **educational**
- Enables **real-time transparency** of Cardano's decision-making and treasury systems
- Creates **replicable, open tools** that others can learn from and extend

We see Gimbalabs not just as a partner, but as a **continuation of our curiosity and collaboration** the right place to grow BlockPrint's contribution to the Cardano ecosystem.

This proposal is also related to this Andamio course bringing it to a broader sense: https://app.andamio.io/course/ea6d1b39fac233e06fedad5ccc3e512e74261b72ec985a278703473d

## Proposal

### 1. Title or Brief Description

**BlockGov: Cardano Governance & Treasury Platform (Mono-Repo Web-App)**

An open-source platform integrating a **Governance Action Proposer**, **Governance Explorer**, and **Treasury Explorer** to simplify governance participation, visualize treasury data, and foster transparency across the Cardano ecosystem.

**Live:** https://block-gov.vercel.app/

### 2. Background or Rationale

With the introduction of **CIP-1694** Cardano's community now holds a direct voice in decision-making. However, current governance participation tools are fragmented across multiple platforms and lack educational clarity.

This limits community engagement and creates barriers for new contributors who want to learn how proposals are created, approved, and funded.

The proposed platform bridges this gap by:
- Consolidating governance interaction into one intuitive interface
- Enabling users to explore governance data, treasury spending, and proposals
- Providing open-source components that can be **replicated, modified, or integrated** into educational or civic engagement projects

### 3. Intended Outcome

- A **fully functional governance dashboard** where users can create, submit, and track governance proposals
- A **Cardano Treasury Explorer** with clear visual analytics on treasury inflows, outflows, and funding trends
- A **Governance Explorer** that maps out actions, DReps, and voting outcomes in an easy-to-understand format

### 4. Details of the Proposal

#### 1. Governance Action Proposer (with Constitution Validator)

The **Governance Action Proposer** module enables users to **create, validate, and submit** governance actions such as:
- **Parameter Change Actions**
- **Hard Fork Initiation Actions**
- **Info Actions**
- **Treasury Withdrawals**

However, unlike the main governance frontends like Govtools, this proposer does **not allow unrestricted submission** of proposals.

Before a proposal is built and signed, it is automatically subjected to a **Cardano Constitution Compliance Check** reducing stress on dReps on making votes and other governance action.

##### Constitution Compliance Layer

This feature ensures that every proposal aligns with the **Cardano Constitution**, which defines the guiding principles of Cardano governance - including decentralization, sustainability, and transparency.

#### 2. Governance Explorer

- Browse and visualize all active and past governance actions
- See voting results, DRep participation, and proposal metadata including **constitutional alignment scores**
- View proposal evolution through lifecycle states
- Integrate with governance APIs (Koios, db-sync, and upcoming governance indexers)

#### 3. Treasury Explorer

- Visualize the **Cardano Treasury** with live balance tracking and spending summaries
- Explore treasury withdrawals by purpose, proposer, epoch, and category
- Include analytics for transparency metrics like spending concentration and success ratios
- Aggregate data from **Cardano db-sync**, **Koios**, and replicating **GovTools**

### 5. Impact and Benefits

| Stakeholder | Benefit |
|-------------|---------|
| **Community Members** | Easy proposal submission and understanding of how governance works |
| **DReps and SPOs** | Transparent tracking of governance actions and treasury decisions |
| **Developers & Educators** | Access to open-source, replicable components for teaching and building governance tools |
| **Researchers & Analysts** | Clear data visualization of treasury and governance activity for empirical studies |

Overall, the project **democratizes governance participation** by removing barriers to entry and fostering informed decision-making.

### 6. Evaluation Criteria

- Successful submission of real or test governance actions via the proposer tool
- Number of active users interacting with governance and treasury explorers
- Availability of educational guides and developer documentation
- Community feedback on usability and clarity
- Open-source adoption and replication by other educators or developers

### 7. Timeline

- **Phase 1** - Research, Design & Setup
- **Phase 2** - Governance Proposer
- **Phase 3** - Governance Explorer
- **Phase 4** - Treasury Explorer
- **Phase 5** - Testing & Documentation

**Estimated Total Duration:** 8 months

### 8. Resources Required

3 Gimbalabs contributors (subject to changes):
- Full-stack devs (2)
- Cardano governance interest person (1) - Tevo Kask

BlockPrint is giving out 50% of the total proposed budget est. (50k - 60k ADA)

### 9. Responsibilities

**BlockPrint** currently has twelve (12) contributors: https://living-poison-3e2.notion.site/Contributors-22ebe756428e80f4b607d3fd6367f823

- Completion of UI/UX
- Giving of the Product requirement Documentation (PRD)
- Fullstack devs
- Marketing and Management

**Gimbalabs contributors** (same as roles in resources)

**From last openspaces feedback:**

We can build blockGov one step at a time focusing on what is urgent and important rather than creating a cluster of workload.

We propose to build a cardano treasury explorer first.

**Why?**

1. **Transparency for governance** - there is currently no single, intuitive, public dashboard that shows where funds come from, how they accumulate, and how governance decisions affect them

2. **Helps Developers and Ecosystem Plan Funding**
   - Shows total treasury available for grants
   - Predicts treasury runway based on network activity and inflation

3. **Bridges Community Misunderstanding & Misinformation**
   - Many users don't know how the treasury grows or what determines treasury inflow

4. **Governance Maturity vs Tooling Gaps**
   - Cardano has the treasury and governance foundations, but lacks the visual and analytical infrastructure Polkadot has
   - Reference: https://polkadot.dotreasury.com/#/
   - Reference: https://cardanotreasury.fi/
   - Not explicitly a treasury explorer: https://cgov.io/ (Mesh and SidanLabs project)

**Is it worthwhile to build this project in collaboration with Gimbalabs?**

Our initial thinking is **yes**, because:
- Gimbalabs has strong community reach and hands-on experience in participating and building GovTool (e.g Discord dRep bot)
- Partnering with them could help ensure the product becomes sustainable and widely adopted

If collaboration with Gimbalabs isn't the best fit, would it make sense to propose this project instead to Intersect, Cardano Foundation, LidoNation, Mesh, or any governance-focused organization within the ecosystem?

### 10. Potential Risks and Mitigation Strategies

- **Low user engagement:** Partner with community educators for demos and workshops
- **Governance spec updates:** As governance structure might change overtime - Modular architecture allows quick adaptation to CIPs

### 11. Review and Adaptation Plan

- **Quarterly Reviews:** Evaluate usability, participation, and feature adoption
- **Community Feedback:** Gather input via Discord, GitHub discussions, and Gimbalabs sessions
- **Iterative Updates:** Align with new governance standards (CIP-1694+, Treasury withdrawal mechanisms)
- **Educational Integration:** Adapt platform for use in Andamio and other learning environment
