---
title: "Handshake - F13 Proposal"
notion_url: "https://www.notion.so/1a00db6d1d5d806ebf93e01b488d8876"
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
  start: null
  end: null
review_date: null
archived_at: "2026-03-09"
---

# Handshake - F13 Proposal

## Gimbalabs Primary Driver
To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems

## Proposal Driver
**Recognizing the critical need for genuinely decentralized and self-sovereign alternatives in the domain name system (DNS) space**, which is currently dominated by central authorities like ICANN, and where existing blockchain-based solutions often rely on centralized layer 2 networks, compromising security. We are driven to **empower individuals and organizations globally** by providing open, replicable, and secure infrastructure.

Our goal is to **solve the meaningful problem** of centralized control and its associated risks, such as the potential loss of domains due to political changes. By developing an open-source, decentralized DNS marketplace powered by Cardano smart contracts and Handshake top-level domains, we aim to enable users to own and manage their domain assets natively on the Cardano blockchain without needing a third party. This project will not only provide a decentralized naming system for building decentralized applications on Cardano but also foster greater collaboration between the Handshake and Cardano communities, expanding the reach of decentralized naming solutions.

## Proposal

### 1. Title or Brief Description
Create an open-source decentralized domain name system (DNS) marketplace powered by Cardano smart contracts and Handshake top-level domains.

### 2. Background or Rationale
Existing blockchain-based "decentralized" domain name system (DNS) markets often rely on centralized layer 2 networks instead of native assets on Cardano, which compromises security. In the current Internet Domain Name System (DNS), the Internet Corporation for Assigned Names and Numbers (ICANN) is a single entity that determines allowed top-level domains and controls who can sell second-level domains. This central authority holds the power to grant and potentially take away names. As an example, a recent political change regarding the ownership of the Chagos Archipelago has raised questions about the future of the ".io" top-level domain.

The Handshake blockchain is a purpose-built, self-sovereign solution for decentralizing top-level domains, utilizing the proof-of-work algorithm. By replacing a central authority with a decentralized, blockchain-based system, Handshake removes single points of control over names.

### 3. Intended Outcome
The intended outcome is to build a fully open-source and self-service, cross-chain domain name system with marketplace infrastructure using Cardano smart contracts. This infrastructure will enable Handshake top-level domain owners to create marketplaces for second-level domains on Cardano. These domains will be stored as native assets on the Cardano blockchain, following the Cardano-DNS specification. Second-level domain owners will be able to maintain their DNS domains using smart contracts without requiring a third party. A custom DNS server, cdnsd, which is already built and open-sourced, will track and index these domain assets. A DNS network will be built using this server to service DNS requests.

A key final output of this project will be a **functional proof of concept (PoC)** demonstrating the core infrastructure of the Decentralized Domain Name System marketplace powered by Cardano and Handshake blockchains. This PoC will showcase the integration and functionality developed throughout the project milestones.

### 4. Details of the Proposal
This proposal outlines the development of a decentralized DNS marketplace infrastructure. The entire project lifecycle, including proposal management, task tracking, and community engagement, will be managed transparently on the Andamio platform. This platform will serve as the central hub for all project activities, ensuring clear communication and providing a structured environment for collaboration, particularly for contributions from developers within the Gimbalabs community.

The development process is broken down into five key milestones, designed to build the core components incrementally over seven months:

#### Milestone 1: Research and Validation for Handshake Signatures in Cardano Smart Contracts (Months 1-2)
**Goal:** Research and demonstrate Handshake signatures within Cardano smart contracts.

**Possible Contribution Areas:**
- **Literature Review & Research**
  - Investigate existing cross-chain signature schemes, especially Handshake signature mechanics.
  - Summarize findings in a clear, accessible document.
- **Smart Contract Prototype Development**
  - Write Plutus v3 contracts for signature validation.
  - Build open-source contracts with clear comments and test cases.
- **Transaction Building & Testing**
  - Develop scripts to build and submit transactions on Cardano preprod testnet.
  - Integrate Handshake signatures into the transaction signing process.
- **Documentation & Demo**
  - Create comprehensive documentation on the usage and validation approach.
  - Record or script a demonstration of successful transaction submission using Handshake signatures.

#### Milestone 2: Development of Controller Contract and Example Marketplace Site (Months 3-4)
**Goal:** Enable ownership validation of Handshake domains and showcase via a marketplace site.

**Possible Contribution Areas:**
- **Controller Contract Development**
  - Design and implement contract logic to validate ownership of Handshake domains.
  - Write unit tests and security checks.
- **Domain Registration Contract**
  - Build secure registration contracts for Handshake domains on Cardano.
  - Provide contract deployment scripts and tests.
- **Marketplace Frontend**
  - Develop a simple, user-friendly marketplace website demonstrating the registration flow.
  - Integrate backend contracts with frontend UI.
- **Documentation & Demonstrations**
  - Document contract APIs, usage, and marketplace site features.
  - Record video walkthroughs showing the domain registration process.

#### Milestone 3: Development of Domain Contracts for Minting and Updating Domain Assets (Month 5)
**Goal:** Create minting and update contracts for second-level domains (SLDs) aligned with Cardano-DNS standards.

**Possible Contribution Areas:**
- **Minting Contract for SLDs**
  - Implement a contract allowing Handshake owners to mint SLDs.
  - Ensure the contract enforces ownership and permissions.
- **DNS Configuration Contract**
  - Develop a contract allowing SLD holders to update DNS records/settings.
  - Implement validation to prevent unauthorized changes.
- **Standard Compliance**
  - Research Cardano-DNS standards and ensure contract compatibility.
  - Write test cases demonstrating standards adherence.
- **Testing & Documentation**
  - Write comprehensive tests and examples for minting and DNS updates.
  - Provide technical documentation describing contract functionality.

#### Milestone 4: Integration of Contracts with a Command-Line Interface (CLI) (Month 6)
**Goal:** Build a CLI tool to interact with contracts for domain registration, minting, and DNS configuration.

**Possible Contribution Areas:**
- **CLI Design & Development**
  - Create CLI commands to register domains with the controller contract.
  - Implement CLI commands for minting SLDs and configuring DNS settings.
- **Validation & Ownership Checks**
  - Ensure the CLI performs necessary validation before transactions.
  - Provide meaningful error messages and confirmations.
- **User Documentation**
  - Write clear step-by-step user guides for the CLI.
  - Provide examples and troubleshooting tips.
- **Testing & Demos**
  - Automate tests for CLI commands.
  - Create demo videos or logs showcasing CLI usage.

#### Milestone 5: Final Evaluation and Project Closure (Month 7)
**Goal:** Summarize and present the project outcomes.

**Possible Contribution Areas:**
- **Project Report Writing**
  - Compile a comprehensive report outlining objectives, methods, results, and future work.
  - Include links to repositories, demos, and test results.
- **Video Production**
  - Create a summary video highlighting key achievements.
  - Demonstrate final infrastructure and workflows.
- **Project Review & Feedback**
  - Collect and incorporate feedback from contributors and stakeholders.
  - Finalize documentation for public release.

### 5. Impact and Benefits
The creation of this marketplace infrastructure will foster greater collaboration between the Handshake and Cardano blockchain communities. It will expose Handshake-based domains to the Cardano community and provide Cardano with a decentralized naming system suitable for building decentralized applications.

This project offers meaningful opportunities for the Gimbalabs community to get involved, particularly through contributions from developers. The engineering responsibilities are split between Blink Labs and Gimbalabs. James Dunseith from Gimbalabs leads development alongside Chris Gianelloni from Blink Labs. Gimbalabs' capability, grounded in their extensive experience in blockchain technology, software development, and educational technology, coupled with their focus on providing open, replicable safe spaces to learn and explore, and to empower individuals and organizations, makes them well-suited to involve community developers in the technical implementation and testing, contributing to the project's open-source nature and their goal of empowering individuals and organizations. The use of the Andamio platform, a product of Gimbalabs designed specifically for structured learning, collaboration, and project management within the Cardano ecosystem, will be instrumental in facilitating this community involvement and developer contribution throughout the project's lifecycle.

### 6. Evaluation Criteria
Project evaluation will be based on the successful completion and documented evidence of each milestone. Key criteria for acceptance of milestone deliverables are detailed in the milestone descriptions above. All evidence and progress tracking will be available for review on the Andamio platform.

### 7. Timeline
The project timeline spans **seven months**, aligned with the five key technical milestones:
- Milestone 1: Months 1-2
- Milestone 2: Months 3-4
- Milestone 3: Month 5
- Milestone 4: Month 6
- Milestone 5: Month 7

This timeline and associated task management will be tracked and communicated via the Andamio platform.

### 8. Resources Required
The total fund requested from the Catalyst Project for this project was **200,000 ADA**. These funds will primarily cover engineering time from the Blink Labs and Gimbalabs teams. A portion is allocated for administrative staff involved in project management and community reporting. The budget includes infrastructure costs for running the DNS network for 6 months.

**Cost breakdown per milestone:**
| Milestone | Budget |
|-----------|--------|
| Milestone 1 | 60,000 ADA |
| Milestone 2 | 60,000 ADA |
| Milestone 3 | 40,000 ADA |
| Milestone 4 | 10,000 ADA |
| Milestone 5 | 30,000 ADA |
| **Total** | **200,000 ADA** |

**Required staff positions:**
- Senior Golang-Blockchain Software Engineer
- Golang Engineer
- Smart Contract Developer
- Project Manager
- Frontend developer

Infrastructure costs are based on running 4 m7g.medium machines continuously in AWS, including additional costs for IP addresses, network traffic, and storage.

### 9. Responsibilities
Project development will be completed by the Blink Labs and Gimbalabs teams. Primary developers assigned are Chris Gianelloni of Blink Labs and MIxAxIM of Gimbalabs. Additional team developers will provide code review, documentation, and support. Administrative functions like project management and community reporting may utilize additional Blink Labs staff. Engineering responsibilities will be split between Gimbalabs and Blink Labs.

Project responsibilities, task assignments, and progress tracking will be centrally managed and transparently communicated through the Andamio platform, enabling streamlined collaboration between the Blink Labs and Gimbalabs teams and facilitating community contributions. Supplementing GitHub tracking, the Andamio platform will provide an additional layer of structured project management, communication channels, and milestone tracking, further mitigating risks associated with coordination and transparency, and actively inviting community participation.

### 10. Potential Risks and Mitigation Strategies
The project has no dependencies on other organizations, technical or otherwise. Blink Labs and Gimbalabs have proven track records of delivery and accurate time/cost estimates due to cohesive teams working together for years. The project's commitment to being fully open source and public allows for transparency and community oversight. Work items will be tracked using GitHub issues and a project Kanban board on GitHub, providing a clear view of progress and facilitating adaptation if needed.

### 11. Review and Adaptation Plan
Review of progress will occur continuously through the use of GitHub issues and the Kanban board. Each milestone has defined acceptance criteria and evidence of completion, which serve as formal review points. The final Milestone 5 includes a closeout report and video to comprehensively review the project's objectives and achievements. The open-source nature allows for community feedback and potential future adaptations or extensions of the infrastructure.

The Andamio platform will serve as the primary tool for structured project review and adaptation. Milestones, deliverables, and evidence will be formally documented and tracked within Andamio. Regular updates, discussions, and feedback loops involving the core team and potentially community contributors will be facilitated through the platform, ensuring a transparent and adaptive project execution process.
