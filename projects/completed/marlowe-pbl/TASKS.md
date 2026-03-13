# Tasks for Marlowe PBL

*Archived from Notion on 2026-03-12*

**Source Database:** https://www.notion.so/77899f9748ad4770bd0e09cc2a41c7a0
**Project:** https://www.notion.so/6110a4f229a84e92907e99cda0138d79

## Task Summary

| Task ID | Task Name | Status | Assignee | Due |
|---------|-----------|--------|----------|-----|
| GHT-182 | Draft Marlowe PBL Course Outline | Done | James Dunseith, Kevin | 2024-04-24 |
| GHT-183 | Marlowe PBL Catalyst F12 budget | Not started | — | — |
| GHT-184 | Start Marlowe PBL Discord channel | Done | James Dunseith | 2024-10-15 |
| GHT-196 | Align F12 Milestones with Marlowe 2025 Plans | Not started | — | — |
| GHT-198 | Keep meeting weekly on Tuesdays at 1300 UTC | Done | James Dunseith, Sebastian Pabon | — |
| GHT-202 | Gathering all marlowe (course) resources out there | Not started | Kevin | 2024-11-07 |
| GHT-204 | Prep_meeting_5nov24_draft_marlowe_course_outline | Not started | Kevin | — |
| GHT-256 | Get response from Catalyst Team | Done | Sebastian Pabon | 2025-02-13 |
| GHT-257 | We need to know the status of Marlowe TS SDK + Runtime | Done | James Dunseith | 2025-07-01 |
| GHT-258 | Once we know project status from Catalyst and from Marlowe teams, we pick up weekly Meetings and talk about next steps | Done | Sebastian Pabon | 2025-02-13 |
| GHT-540 | Writing blog post about Gimbalabs - Marlowe core team work | Done | Sebastian Pabon | 2025-02-15 |
| GHT-558 | Marlowe PBL Core Team members | Done | Sebastian Pabon | 2025-02-15 |
| GHT-559 | Marlowe PBL - Milestone 1 Completion Report | Done | Sebastian Pabon | 2025-02-17 |
| GHT-573 | Launching of Marlowe PBL Content Creation phase | Done | James Dunseith, Sebastian Pabon | 2025-04-14 |
| GHT-730 | Marlowe PBL - Milestone 2 Completion Report | Done | Sebastian Pabon | 2025-12-12 |
| GHT-753 | Project Cancellation Request to Catalyst team | Done | Sebastian Pabon | 2026-03-09 |


---

## Task Details

### GHT-182: Draft Marlowe PBL Course Outline

Status: Done


**Description**

Course Outline

1. Quick start with NPM
2. Existing Marlowe Starter Kit - maybe a unique module?
3. Example 1: Bet
4. Example 2: swap, vesting and escrow
5. Example 3: 
6. The future of Marlowe: Open Source
7. The future of Marlowe: Contributing

(sharing my work-in-progress (24 Apr 2024), below the contents, maybe usable, maybe not)

***how to deploy a custom financial contract***

1. [Objective](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Objective)
    - [tools](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#tools)
    - [network](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#network)
    - [contract templates](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#contract-templates)
2. [Installation](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Installation)
    - [python](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#python)
    - [versions](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#versions)
    - [modules](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#modules)
    - [server](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#server)
    - [software](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#software)
    - [cardano tools](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#cardano-tools)
    - [setup environment](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#setup-environment)
    - [helper function](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#helper-function)
    - [start services](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#start-services)
    - [socket](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#socket)
3. [Roadmap](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Roadmap)
4. [Wallet](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Wallet)
    - [generating keys](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#generating-keys)
    - [generating address](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#generating-address)
5. [Contract](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Contract)
    - [code javascript](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#code-javascript)
    - [code marlowe](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#code-marlowe)
    - [code blockly](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#code-blockly)
6. [Funding](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Funding)
    - [funds wallet](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#funds-wallet)
    - [create wallet 1-2](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#create-wallet-1-2)
    - [transfer funds](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#transfer-funds)
7. [Parameters](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Parameters)
    - [time](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#time)
8. [Tokens](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Tokens)
    - [token metadata](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#token-metadata)
    - [token minting](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#token-minting)
9. [Transactions](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Transactions)
    - [modify contract parameters](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#modify-contract-parameters)
    - [tx#1 start contract](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#transaction-#1-start-contract-(3-ADA))
    - [tx#2 first deposit](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#transaction-#2-first-deposit-(200-ADA))
    - [tx#3 second deposit](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#transaction-#3-second-deposit-(100-ADA))
    - [tx#4-5 end contract](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#transaction-#4-and-#5-contract-ended-(withdraw))
10. [Web wallet interaction](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Web-wallet-interaction)
    - [demonstration](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#demonstration)
    - [development](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/development)
11. [Cleanup](https://nbviewer.org/github/littlefish-foundation/cardano-contracts-cookbook/blob/master/code/notebooks/howto_cardano_swap_contract.ipynb#Cleanup)


**Practical Questions**

1. What are our current blockers?
2. What’s safe enough to focus on now?


**Big Ideas**

1. What does Marlowe TS SDK provide that is unique from Mesh? How can we build an example that shows what Marlowe is best at?
    1. We should not be using Marlowe to select UTxOs? Or should we?
2. What does Marlowe mean by “submitting contract to the blockchain”? Is a reference script created? We should show just enough about how this works + also talk about contract management.
    1. Look at the Tx Preview in Eternl - to understand what is being deployed → How to use it next? Show in course
3. Should we host our own Marlowe runner? What should we expect of learners/devs? Options:
    1. We host it + share endpoint
    2. We use Demeter
    3. We show learners how to run locally
4. What languages should we focus on?


**Course Structure**

- Introduce Example Projects - experience as user
    - “Oh, it works!”
    - Yes, here’s what just happened (look at Tx Preview)
- Set up development environment + learn enough about each tool to start a mental model
    - Decide:
        - Just use Demeter?
        - Docker?
        - Install Manually?
        - Just use our Endpoint?
    - Include “You Will Know You Are Successful If” at the end of each lesson
        - Checking versions
        - Logs should say “x”
        - 
- Step by step, learn how to build and extend each example
    - By using each tool
    - In order to extend mental model
- Module Outline - Examples are revisited in each Module (with some introduced in later modules)
    - Getting Started
    - About Playground
        - Create a contract with Blockly
        - Importing contract blueprints (e.g. swap) - proves how Marlowe works
    - About Runner
        - Using Runner: with options
    - About Marlowe CLI - do you recommend including Marlowe CLI in the course?
    - About TS SDK
    - Deploying your own Runner
    - Current development: what, how, why? (e.g. Oracle)


**Examples to Build**

1. Swap Example
2. Small Escrow Contract
3. @Kevin add additional project ideas here
4. Smart Gift Card Demo - as shown in [The Smart Gift Card tutorial](https://www.youtube.com/watch?v=bTpMZLmZU5k&ab_channel=InputOutput). I think we can build an example using Mesh + highlighting the best parts of Marlowe. 
    1. Getting Started Module: Show the example
    2. Use this example to go thru whole Marlowe stack (prereq: env set up)
    3. This is now a simple escrow contract
5. Bet Example - build this
    1. Getting Started: Show example and name why it’s imperfect
    2. Build this imperfect example after building Gift Card — to show what’s possible and what still needs to be improved
    3. Use an “unsecured API” and talk about what works and does not
6. Define addition projects
7. Use Catalyst Milestones for guidance, while recognizing these will change


**Video Notes**

1. [Simple Deposit Contract](https://www.youtube.com/watch?v=dsF-eADnOXE&t=35s&ab_channel=InputOutput) in Marlowe Playground
    1. dead link: [play.marlowe.iohk.io](http://play.marlowe.iohk.io) — when will we know what we can use
    2. Video Timestamp: 
    3. Send to Simulator button pops up
    4. Export to Marlowe Runner
    5. Download as JSON → for React
    6. Need link to API reference page
    7. BigInts
    8. Working with `datetoTimeout`
    9. Unanswered: What is the return type of the `mkSimpleDemo` function shown in this video?
2. [Marlowe Runner Demo](https://www.youtube.com/watch?v=B5XcH0j7Y7w&ab_channel=InputOutput)
    1. Plenty of details to think about - remake this video with a look at tx preview in Eternl
3. [Marlowe Typescript SDK](https://www.youtube.com/watch?v=0Qa1CsZUGnw&ab_channel=InputOutput)
    1. How does it compare to Mesh?
    2. Packages
        1. [https://www.npmjs.com/package/@marlowe.io/wallet](https://www.npmjs.com/package/@marlowe.io/wallet) - show an example with Mesh instead
        2. [https://www.npmjs.com/package/@marlowe.io/runtime-lifecycle](https://www.npmjs.com/package/@marlowe.io/runtime-lifecycle)
    3. We need a runtime instance
        1. Get one from Demeter
        2. Or run it on your own
    4. Show tx preview in Eternl when using the runtime…
4. [The Smart Gift Card tutorial](https://www.youtube.com/watch?v=bTpMZLmZU5k&ab_channel=InputOutput)
    1. What is the `Party` type — find in docs + get link here

Next Steps

- [ ]  Get link to Marlowe Starter Kit
- [ ]  Survey existing content


---

### GHT-183: Marlowe PBL Catalyst F12 budget

Status: Not started

**Description**

Budget Proposal areas:

- Code Examples
- Course Writing
- Video
- Live Sessions
- Project management
- Marketing
- Andamio platform
- Funding ?¿


---

### GHT-184: Start Marlowe PBL Discord channel

Status: Done

**Description**

Discord channel created in the Gimbalabs server, Project Based Learning section: [https://discord.gg/XXT7g5kdDx](https://discord.gg/XXT7g5kdDx)


---

### GHT-196: Align F12 Milestones with Marlowe 2025 Plans

Status: Not started


*2025: enhanced Marlowe Platform*

See [https://github.com/marlowe-lang/.github/blob/main/Marlowe -Status-Report-Oct-2024.md#the-remainder-of-2024-end-to-end-example](https://github.com/marlowe-lang/.github/blob/main/Marlowe%20-Status-Report-Oct-2024.md#the-remainder-of-2024-end-to-end-example)

*Marlowe DApp Starter Kit*

- Do the content creation milestones align with end-to-end example(s)? Which ones?
    - Token Plans
    - Payouts
    - Order Book Swap Prototype

*Validator Enhancements*

*Configurable Runtime Fee Mechanism*

*Marlowe Oracle Protocol*

- Maps to Milestone 5

*Seamless DApp Integration of Deep Contracts (Merkleized Contracts)*

- Maps to Milestone 4


**Milestones**

Milestone 1: Title: Preparation and Organization Setup (1 Month)

Milestone 2: Title: Content Creation, topic “*Micropayments (through Signed Inputs)*” (2 Months).

- No solution built yet
- We can show swaps, Oracle?
    - Use Wolfram in a Bet?
- “Non-seamless dapp integration”
- Learners need to see how to get oriented to a contract from within a dapp setting (”From dapp side, it can be hard to know what’s happening in the contracts…”)

Milestone 3: Title: Content Creation, topic “*Contract Execution Optimization (minimizing the number of Transactions*)” (3 Months).

- Not ready - but build reasons where this will happne
    
    
Milestone 4: Title: Content Creation, topic “*Seamless DApp Integration of Deep Contracts (Merkleized Contracts*)” (3 Months).

- The goal is to show Dapp integration right away, starting at beginning of course
- Building on Typescript
- Introduce UI Patterns
- Improving DevEx and UX from dapp integration covered in Milestone 2

Milestone 5: Title: Content Creation, topic “*Marlowe Oracle Protocol Improvements and Specification*” (1 Month).

Milestone 6: Title: Content Creation, topic “*Runtime Monetization*”. Project Close-out Report and Video (2 month)


Notes:

- These module titles are forward-looking statements
    - For example: micropayments and execution optimization are on roadmap, but still need work
    - We can indicate “this should be optimized”
- Start with Starter Kit
    - Introduce Runtime

Here is the old/deprecated starter kit: [https://github.com/input-output-hk/marlowe-starter-kit/tree/main](https://github.com/input-output-hk/marlowe-starter-kit/tree/main)


- Consider replacing `Swap` with something related to Oracle


*Course Rough Outline*

1. User-facing example:
    1. maybe an imperfect wallet-based bet - acknowledging the limitations of oracle connection
    2. Escrow - not trivial to manage escrow state using runtime API
2. Here is a minimum possible example
    1. Client side dapp
    2. Can be a simple React app
    3. Use **playground** at each step
    4. Show how **runner** works at each step
    5. Introduce Run Time Swagger docs
3. Send money from person to person
    1. Trivial (almost-static) web-app
    2. Go deeper into how it works, one detail at a time
4. Learner runs Marlowe infra (Docker?)
5. How to set up the Marlowe Runtime via CLI
6. 
7. Run simple web application?


*Mapping Catalyst milestones to the Marlowe 2025 enhanced platform roadmap*:
- Marlowe DApp Starter Kit (Token Plans, Payouts, Order Book Swap Prototype)
- Validator Enhancements
- Configurable Runtime Fee Mechanism
- Marlowe Oracle Protocol → Maps to Milestone 5
- Seamless DApp Integration of Deep Contracts (Merkleized Contracts) → Maps to Milestone 4


---

### GHT-198: Keep meeting weekly on Tuesdays at 1300 UTC
Status: Done

Meeting schedule established for Nov-Dec 2024.


---

### GHT-202: Gathering all marlowe (course) resources out there
Status: Not started

**webLinks**:

- we have some typescript SDK code from Nick [[**link**](https://github.com/nstanford5#demo-videos)] to some Youtube explanations
- here is another example from Thomasz [[**link**](https://github.com/paluh/marlowe-workshop-dapp)] to a typescript example
- here is a list of awesome marlowe effort to bundle information and examples [[**link**](https://github.com/input-output-hk/awesome-marlowe)]
- lecture material from the marlowe pioneer program [[**link**](https://github.com/bwbush/marlowe-cardano/tree/real-world/marlowe-cli/lectures)]
- bundle of lessons and infra-setup to demo marlowe as a starter-kit [[**link**](https://github.com/input-output-hk/marlowe-starter-kit/tree/main?tab=readme-ov-file#contents)]
- official marlowe docs [[**link**](https://docs.marlowe.iohk.io/docs/introduction)]
- free course on Udemy from Simon Thompson [[**link**](https://www.udemy.com/course/marlowe-programming-language/)] with course content
- introduction [[video](https://www.youtube.com/watch?v=uwV35IE68dE)]
- list of all kinds of example contracts [[**link**](https://github.com/input-output-hk/marlowe-cardano/blob/main/marlowe/example-contracts.md)]
- Brian Bush made a comprehensive marlowe-cli [[**video**](https://www.youtube.com/watch?v=Vx_ygegrY78)]

| fund # | projectName | fundingADA | proj | info | owners | discord/friends |
| --- | --- | --- | --- | --- | --- | --- |
| 11 | Marlowe Hub | 80K/100K | [link](https://www.lidonation.com/en/proposals/marlowehub-unifying-platform-for-marlowe-smart-contracts-phase-1-smart-contracts-f11) | [webapp](http://marlowehub.io) | Mike and Leon |  |
| 11 | Marlowe enhanced | 71K/80K | [link](https://www.lidonation.com/en/proposals/marlowe-enhanced-tailored-contracts-with-intuitive-design-f11) |  | Erick Romero and Taina Bugs |  |
| 11 | 10 templates | 16K/99K | [link](https://www.lidonation.com/en/proposals/10-marlowe-contract-templates-the-real-life-use-cases-f11) | [github](https://github.com/Vcoincheck/10marlowe/tree/main/training-course/curricullum) | Jimmy Lee and Mau Luu | manh_nguyen_21 |
| 11 | free course Vietnam | 25K | [link](https://www.lidonation.com/en/proposals/fimi-free-marlowe-course-for-vietnamese-f11) |  | [Do Manh Hung](https://t.me/Hung_DoManh) and [Do Viet Cuong](https://t.me/dovietcuong) |  |
| 10 | runtime SDK | 154K | [link](https://www.lidonation.com/en/proposals/marlowe-runtime-sdks-f10) |  | [**Santiago Carmuega**](https://www.linkedin.com/in/santiagocarmuega/) and Alejandro Avagnina |  |
| 10 | oracle integration | 236K | [link](https://www.lidonation.com/en/proposals/marlowe-decentralized-oracle-integration-f10) |  | [**Santiago Carmuega](https://www.linkedin.com/in/santiagocarmuega/) and [Paulo Bressan](https://www.linkedin.com/in/paulo-b-335501115/)** |  |
| 11 | 18 workshops | 9K/50K | [link](https://www.lidonation.com/en/proposals/45b-marlowe-workshops-for-business-professionals-f11) |  | Pedro Lucas |  |
| 11 | bounty bot system | 56K/170K | [link](https://www.lidonation.com/en/proposals/githoney-by-txpipe-dev-bounty-system-using-marlowe-contracts-deep-integration-with-github-f11) | [docs](https://bounties.txpipe.io/) | [**Santiago Carmueg**a](https://www.linkedin.com/in/santiagocarmuega/) and Federico Weill |  |
| 10 | study guide | 15K | [link](https://www.lidonation.com/en/proposals/study-guide-for-marlow-f10) |  | Nguyen Van Hieu and Tran Huy Hiep |  |
| 11 | AI Co-Pilot CardanoGPT | 56K/170K | [link](https://www.lidonation.com/en/proposals/cardanogpt-and-plugin-the-cardano-developer-co-pilot-tool-for-effective-development-and-efficient-debugging-f11) |  | UBIO OBU and Ediyangha Otogho |  |


---

### GHT-204: Prep_meeting_5nov24_draft_marlowe_course_outline

Status: Not started


**Revised Course Outline: Marlowe Course on Gimbalabs**


*Chapter 1: 101 - Introduction and Real-Life Scenarios*

*101.1 Welcome and Course Overview*

- **Objective:** Introduce learners to the course structure, objectives, and the engaging narrative approach.
- **Content:**
    - Overview of the course goals and expected outcomes.
    - Introduction to the storytelling method to engage both technical and business-oriented audiences.
    - Explanation of how Marlowe can solve common business challenges.

*101.2 Presenting Real-Life Scenarios*

- **Objective:** Highlight the limitations of traditional business agreements using relatable examples.
- **Content:**
    - **Scenario 1:** Alice and the Gardener
        - Issues like no-shows, miscommunication, payment delays, and lack of enforcement.
    - **Scenario 2:** Monthly Payment Contract
        - Challenges with setting up recurring payments until a wallet is drained.
    - **Purpose:** Illustrate the need for solutions like Marlowe to address common pain points in everyday business dealings.

*101.3 Introducing Financial Digital Contracts with Marlowe*

- **Objective:** Explain how financial digital contracts can address the issues highlighted in the scenarios.
- **Content:**
    - Benefits of predefined terms and automated enforcement.
    - How Marlowe facilitates the creation and execution of these contracts on the Cardano blockchain.
    - Emphasis on the accessibility of Marlowe for both technical and non-technical users.


*Chapter 2: 102 - Getting Started with Marlowe Playground*

*102.1 Introduction to Marlowe Playground*

- **Objective:** Provide immediate hands-on experience using Marlowe Playground.
- **Content:**
    - Overview of Marlowe Playground and its features.
    - Navigating the interface and exploring basic functionalities.
- **Hands-On Activity:**
    - Learners explore the Playground and familiarize themselves with the environment.

*102.2 Creating and Simulating the Swap Contract*

- **Objective:** Guide learners in creating and simulating a swap contract using Marlowe Playground.
- **Content:**
    - Introduction to the swap contract as the primary example.
    - Step-by-step instructions on creating the swap contract using the Blockly editor.
    - Simulating the contract to understand its behavior.
- **Hands-On Activity:**
    - Learners build and simulate the swap contract.
- **Checkpoints and Verification Steps:**
    - Confirming successful creation and simulation of the contract.
    - Understanding expected outcomes in the simulation.

*102.3 Understanding Transaction Previews*

- **Objective:** Teach learners how to interpret transaction previews to build their mental model.
- **Content:**
    - Using the transaction preview feature in Marlowe Playground.
    - Interpreting inputs, outputs, and the flow of funds.
- **Practical Exercise:**
    - Learners analyze transaction previews from their simulated contracts.


*Chapter 3: 103 - Deploying Contracts Using Marlowe Runtime*

*103.1 Introduction to Marlowe Runtime*

- **Objective:** Introduce Marlowe Runtime for deploying and interacting with contracts on the blockchain.
- **Content:**
    - Overview of Marlowe Runtime and its role in contract execution.
    - Advantages of deploying contracts on the Cardano testnet.
- **Preparation:**
    - Explanation of necessary tools and environment setup.

*103.2 Setting Up the Environment with Demeter*

- **Objective:** Guide learners through setting up their development environment using Demeter.
- **Content:**
    - Step-by-step instructions for setting up Demeter as the default environment.
    - Ensuring a consistent and accessible setup for all learners.
- **Hands-On Activity:**
    - Learners set up their environment and verify successful configuration.
- **Checkpoints and Verification Steps:**
    - Checking versions and confirming environment readiness.

*103.3 Deploying the Swap Contract to the Testnet*

- **Objective:** Teach learners how to deploy the swap contract using Marlowe Runtime.
- **Content:**
    - Detailed guide on deploying the swap contract to the Cardano testnet.
    - Interacting with the contract post-deployment.
- **Hands-On Activity:**
    - Learners deploy the swap contract and perform test interactions.
- **Checkpoints and Verification Steps:**
    - Confirming successful deployment and interaction outcomes.

*103.4 Interacting with Deployed Contracts Using Web Wallets*

- **Objective:** Enable learners to interact with deployed contracts using web wallets.
- **Content:**
    - Setting up a web wallet like Eternl connected to the testnet.
    - Making transactions to interact with the contract.
- **Hands-On Activity:**
    - Learners use their web wallets to perform actions on the deployed swap contract.


*Chapter 4: 104 - Visualizing Contract Execution*

*104.1 Using Visual Aids to Understand Contract Logic*

- **Objective:** Use visual aids to explain what happens during contract execution.
- **Content:**
    - Presentation of schema images and diagrams to visualize the swap contract.
    - Explanation of how these visuals correspond to contract functions and state transitions.
- **Note:**
    - This section enhances understanding without requiring learners to use Marlowe CLI directly.

*104.2 Mapping Interactions to Contract States*

- **Objective:** Help learners understand the relationship between their actions and the contract's state changes.
- **Content:**
    - Detailed explanation of how each interaction affects the contract state.
    - Visual diagrams illustrating state transitions.
- **Practical Exercise:**
    - Learners map their interactions to the corresponding changes in the contract's visual representation.


*Chapter 5: 105 - Deploying Contracts Programmatically with the TypeScript SDK*

*105.1 Introduction to the TypeScript SDK*

- **Objective:** Introduce learners to the TypeScript SDK for programmatic contract deployment.
- **Content:**
    - Overview of the TypeScript SDK and its benefits.
    - How the SDK integrates with web wallets for signing transactions.
- **Preparation:**
    - Brief primer on TypeScript and JavaScript for learners unfamiliar with these languages.

*105.2 Setting Up the Development Environment*

- **Objective:** Guide learners through setting up their development environment for the SDK.
- **Content:**
    - Installing Node.js and necessary dependencies.
    - Setting up an IDE like Visual Studio Code.
- **Hands-On Activity:**
    - Learners set up their development environment and verify installations.

*105.3 Deploying the Swap Contract Using the TypeScript SDK*

- **Objective:** Teach learners how to deploy the swap contract programmatically.
- **Content:**
    - Writing code to deploy the swap contract using the SDK.
    - Integrating with web wallets for transaction signing.
- **Hands-On Activity:**
    - Learners write and execute code to deploy and interact with the swap contract.
- **Checkpoints and Verification Steps:**
    - Confirming successful deployment through code.
    - Validating transactions on the blockchain explorer.

*105.4 Understanding the Programmatic Interaction Flow*

- **Objective:** Explain the interaction between the SDK, web wallets, and the blockchain.
- **Content:**
    - How the TypeScript SDK communicates with the blockchain.
    - The role of web wallets in signing and submitting transactions.
- **Visual Aids:**
    - Diagrams illustrating the data flow and interactions.
- **Practical Exercise:**
    - Learners trace the interaction flow based on their deployment experience.


*Chapter 6: 106 - Advanced Topics and Future Work*

*106.1 Exploring NFTs in Marlowe Contracts*

- **Objective:** Discuss how NFTs can be integrated into Marlowe contracts.
- **Content:**
    - Explanation of minting NFTs within contracts, as demonstrated in the Jupyter notebook.
    - Potential applications and benefits.
- **Note:**
    - This is an advanced topic introduced to spark interest for further exploration.

*106.2 Oracles and External Data Integration*

- **Objective:** Introduce the concept of oracles and their potential use in Marlowe contracts.
- **Content:**
    - What are oracles, and why are they important?
    - Future possibilities for integrating oracles once the technology matures.
- **Note:**
    - This topic will be expanded as Marlowe evolves.

*106.3 Preparing for Marlowe Updates*

- **Objective:** Prepare learners for future updates to Marlowe.
- **Content:**
    - Discussion about potential updates (e.g., Marlowe V2.0).
    - Importance of staying informed and adapting to changes.
- **Resources:**
    - Guidance on where to find the latest information and updates.


*Optional Advanced Modules*

*Module A: Introduction to Marlowe CLI*

- **Objective:** Provide an overview of Marlowe CLI for learners interested in command-line interaction.
- **Content:**
    - Basics of Marlowe CLI and its capabilities.
    - Setting up the CLI environment.
- **Note:**
    - This module is optional and intended for advanced learners.

*Module B: Testing and Debugging with Marlowe CLI*

- **Objective:** Teach learners how to use Marlowe CLI for testing and debugging.
- **Content:**
    - Step-by-step example using the swap contract.
    - Exploring the Jupyter notebook with the working example.
- **Hands-On Activity:**
    - Learners follow the Jupyter notebook to understand CLI commands and outputs.


*Future Topics*

- **Escrow Contract Example:**
    - Planned for future development, covering the small escrow contract.
    - Will include hands-on activities similar to the swap contract sections.
- **Advanced Projects:**
    - **Monthly Payment Contract:**
        - A contract that handles recurring payments until the wallet is drained.
        - An engaging project for learners interested in more complex contract design.


*Additional Course Features*

- **Checkpoints and Verification Steps:**
    - Each chapter includes specific checkpoints for learners to verify their progress.
    - Examples include version checks, transaction validations, and expected outputs.
- **Hands-On Focus:**
    - Emphasis on practical exercises and real-world application.
    - Encouraging learners to engage actively with the material for better retention.
- **Accessibility:**
    - Designed to be approachable for both technical and business-oriented individuals.
    - Complex concepts are explained in simple terms, with optional advanced modules for deeper exploration.
- **Self-Paced Learning:**
    - The course is structured as a Massive Open Online Course (MOOC) that learners can progress through at their own pace.


*Prerequisites and Target Audience*

- **Prerequisites:**
    - Basic understanding of blockchain concepts.
    - Familiarity with using web wallets like Eternl, Nami, or Yoroi.
    - Some programming experience is helpful but not required for core chapters.
- **Target Audience:**
    - Developers interested in learning about Marlowe and financial smart contracts on Cardano.
    - Business professionals looking to understand how Marlowe can solve real-world problems.
    - Learners seeking hands-on experience with smart contract development.


*Course Summary*

This course offers a comprehensive introduction to Marlowe, focusing on practical application through the swap contract example. By prioritizing hands-on learning and providing clear, step-by-step guidance, learners will gain a solid understanding of how to create, deploy, and interact with financial smart contracts on the Cardano blockchain using Marlowe.

Advanced topics and additional projects are reserved for later chapters and future development, allowing learners to continue their learning journey as Marlowe evolves. The course is designed to be engaging and accessible, making it suitable for a wide range of learners interested in the potential of financial smart contracts.


---

### GHT-256: Get response from Catalyst Team

Status: Done


Catalyst team has authorized the resetting of the current milestones to a more convenient ones.  

In the link https://milestones.projectcatalyst.io/projects/1200144, `change request` field, the content of the new milestones can be found.

Currently, the process of changing the milestones is in progress.


---

### GHT-257: We need to know the status of Marlowe TS SDK + Runtime

Status: Done


---

### GHT-258: Once we know project status from Catalyst and from Marlowe teams, we pick up weekly Meetings and talk about next steps

Status: Done


Date: 13/feb/2025

**Project status from Catalyst**

- All the changes requested has been approved and processed by the Catalyst team.
- Including the change in delivery dates.
- Check the new milestones here:

[https://milestones.projectcatalyst.io/projects/1200144](https://milestones.projectcatalyst.io/projects/1200144)


---

### GHT-540: Writing blog post about Gimbalabs - Marlowe core team work

Status: Done

https://x.com/gimbalabs/status/1890822577351733631
https://www.linkedin.com/posts/gimbalabs_at-gimbalabs-were-constantly-broadening-activity-7296589087946276865-3ClN?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAUjCbcB2s-3j0lKoMquR0aVTyCf5mkzlgA
https://forum.cardano.org/t/coming-soon-marlowe-pbl/143200?u=sebastian_pabon


---

### GHT-558: Marlowe PBL Core Team members

Status: Done

**Core Team**

*@James Dunseith - Project Lead and Content Creator*

Responsabilities: 

- Define the direction of the project
- Create the lessons assigned.


*@Kevin Kevin Albert - Content Creator*

Responsabilities:

- Create the lessons assigned.


*@Sebastian Pabon  - Project Manager*

Responsabilities:

- Track progress on content creation activities assigned to team members.
- Create and submit PoAs reports to the Project Catalyst milestone platform.
- Create and summit any other report related to the project.


---

### GHT-559: Marlowe PBL - Milestone 1 Completion Report

Status: Done

***NOTE: Notion was deprecated as Gimbalabs project management tool and database. `gimbalabs-project-archive` is the new database of the evidence of the work done in Marlowe PBL project. However, all the evidence provided in the past via the Catalyst Milestones platform that redirected to Notion, can be found here.*** 

**1. List of core team members of the project, stored in Notion**

- *See `GHT-558: Marlowe PBL Core Team members` in this file*

- Also, find the register of the core team in the *item #9 Responsabilities* of the project’s database: [responsabilities](/projects/completed/marlowe-pbl/PROJECT.md)

**2. Access to the Notion of the project**

- Notion is the Project Management tool that the Gimbalabs community uses for participation, collaboration, and contribution in its different project. The following is the link to the Notion database assigned to the Marlowe PBL project: [Marlowe PBL](/projects/completed/marlowe-pbl/PROJECT.md)   From there, all the activities and work the core team must executed will be orchestrated. 

Why Notion? Notion is a versatile and intelligent tool that creates an optimized environment for collaboration: documents, databases, task distribution, information update, team communication, etc. Everything you need for agile teamwork is provided by Notion.

- To facilitate communication between the Marlowe PBL project core team and various stakeholders, including:

    - The [Marlowe core team](https://x.com/marlowe_io), led by Prof. Simon Thompson.
    - Tutors and students interested in contributing to the project
    - Tutors, students, and members of the Gimbalabs community who wish to follow the project
    - Members of the Cardano community interested in tracking the project's progress

a dedicated public channel for the Marlowe PBL  has been created in the Gimbalabs Discord server, in the *Project Based Learning* section. You can access it here: [Marlowe PBL Discord Channel](https://discord.com/channels/767416282198835220/1295720033577865270).

**3. JSON defining the course outline.**

The Marlowe PBL Course Outline (the course modules and the lessons of each module) can be accessed through the following link: https://app.andamio.io/studio/course/marlowe-2025

Clarification: after months of updates to the Andamio platform, the JSON file format is no longer used to build the Outline (modules+lessons) of a course from the user's side. This process has been made more user friendly, so that today it is only required to go to the platform and register the set of modules and lessons that will constitute the course.

In the following Notion document you can find the analysis process developed by the Gimbalabs team, which resulted in the Outline presented: *See `GHT-182: Draft Marlowe PBL Course Outline` in this file.*

**4. Access to the Andamio platform instance assigned to the project.**

The following is the URL to access the Andamio platform instance where the Marlowe PBL course is hosted: https://app.andamio.io/studio/course/marlowe-2025 

This instance guarantees public access to all course content. 

**5.1 Milestone 1 report published directly on the Milestones platform, or link to Milestone 1 report.**

Item is satisfied with this report.

**5.2 Links to Social Media publications**

- From the Gimbalabs X account: https://x.com/gimbalabs/status/1890822577351733631
- Reposted from Project Catalyst X account: https://x.com/gimbalabs/status/1854985767371915728
- From Gimbalabs Linkedin account: https://www.linkedin.com/posts/gimbalabs_at-gimbalabs-were-constantly-broadening-activity-7296589087946276865-3ClN?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAUjCbcB2s-3j0lKoMquR0aVTyCf5mkzlgA
- From Reddit: https://www.reddit.com/r/cardano/comments/1iq7icb/coming_soon_marlowe_pbl/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button
- From Cardano Forum: https://forum.cardano.org/t/coming-soon-marlowe-pbl/143200?u=sebastian_pabon

- Reposted from the Marlowe official X account: https://x.com/gimbalabs/status/1854985767371915728

- Document “**Marlowe Platform status report**” by Prof. Simon Thompson, Marlowe core team lead, where our collaboration with the Marlowe team is stated as part of the Marlowe roadmap: https://github.com/marlowe-lang/.github/blob/main/Marlowe%20-Status-Report-Oct-2024.md#marlowe-roadmap

- From the Gimbalabs X account: https://x.com/gimbalabs/status/1854985767371915728


---

### GHT-573: Launching of Marlowe PBL Content Creation phase

Status: Done

**Objective**

To invite content creators interested in contributing to building the Marlowe PBL course outline.

**Prerequisites to be a Marlowe PBL course content creator**

- Have knowledge of Marlowe development
- Be an active Marlowe builder (personal, professional projects).
- Take the following modules on content creation:

**List of tasks to be covered to execute on the goal**

1. Decide on the economics of the course: how much will be paid per lesson?
2. Make individual contacts with builders who show signs of being involved in the language and even looking to build with it.
3. Make a public call on social networks (gimbalabs X, Discord servers, Reddit, Cardano Forum, etc).
4. Make a public call in podcasts of Gimbalabs friends: Cardano Over Coffee, Pete, etc.
5. Call out to the Vietnamese community: actively work on the language and build educational material on the topic (talk to Alex, since he is working with the Vietnamese community).
6. Talk to Advocates at Intersect's Open Source office, to promote the search for Marlowe content creators in their areas of influence.
7. Conduct Gimbalabs Open Office in X as a way to contact those interested in creating content for the Marlowe PBL.

**2025-04-14 thru 2025-04-28**

- @Sebastian Pabon and @James Dunseith will deliver Milestone 1
    - Build Example App
    - Write Module 101 → Deliver Milestone 2
    - Confirm Module 102 SLTs
    - Write Module 102
    - Create Prerequisite and Project for future Course Development at [https://app.andamio.io/studio/course/b48c3718f2175f05cdb2767a4721d03e2df2f69f9302241ba200b792](https://app.andamio.io/studio/course/b48c3718f2175f05cdb2767a4721d03e2df2f69f9302241ba200b792)
    - Prereq is:
        - *Course Content Creator*, Modulo 101: [https://app.andamio.io/course/66d620b0bbb78d9198aba4d3430510a4bd9960bff62dd0882caad8d2/101](https://app.andamio.io/course/66d620b0bbb78d9198aba4d3430510a4bd9960bff62dd0882caad8d2/101)
        - *Getting Started with Andamio*, Modulo 101: [https://app.andamio.io/course/86affc4de251b0fb7636c376383bcebf6ca7ca426528f9b7a5adc298/101](https://app.andamio.io/course/86affc4de251b0fb7636c376383bcebf6ca7ca426528f9b7a5adc298/101)
        - Marlowe PBL 101 and 102
- In May
    - Share first two modules and “how to contribute” with Gimbalabs community
    - Make a public call on social networks (gimbalabs X, Discord servers, Reddit, Cardano Forum, etc).
    - Make a public call in podcasts of Gimbalabs friends: Cardano Over Coffee, Pete, etc.

**Short-term goal (Low-hanging fruit):**

Deliver on milestone 2 of the Catalyst proposal: https://milestones.projectcatalyst.io/projects/1200144/milestones/2

Module 101 in Andamio: https://app.andamio.io/course/b48c3718f2175f05cdb2767a4721d03e2df2f69f9302241ba200b792/101


---

### GHT-730: Marlowe PBL - Milestone 2 Completion Report

Status: Done


**1. Link to access the content created in the Andamio platform.**

[https://app.andamio.io/course/b48c3718f2175f05cdb2767a4721d03e2df2f69f9302241ba200b792/101](https://app.andamio.io/course/b48c3718f2175f05cdb2767a4721d03e2df2f69f9302241ba200b792/101)

**2. Links to Social Media publications**

- Gimbalabs official X account:

[https://x.com/gimbalabs/status/1999512993957056699](https://x.com/gimbalabs/status/1999512993957056699)

- Cardano community group:

[https://x.com/gimbalabs/status/1999521267355934986](https://x.com/gimbalabs/status/1999521267355934986)

- Cardano Over Coffee community group:

[https://x.com/gimbalabs/status/1999524869667483768](https://x.com/gimbalabs/status/1999524869667483768)

- Gimbalabs official Linkedin page:

[Marlowe PBL - Lesson 101.3: Someone is Stealing from You | Gimbalabs](https://www.linkedin.com/posts/gimbalabs_marlowe-pbl-lesson-1013-someone-is-stealing-activity-7405280523104854016-96Lq?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAUjCbcB2s-3j0lKoMquR0aVTyCf5mkzlgA)

- Subreddit /cardano on Reddit :

[https://www.reddit.com/r/cardano/comments/1pkw91w/the_marlowe_journey_has_officially_begun_the/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button](https://www.reddit.com/r/cardano/comments/1pkw91w/the_marlowe_journey_has_officially_begun_the/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)

- Cardano Forum, `education` category:

[🚀 The Marlowe journey has officially begun! The Gimbalabs Marlowe Project-Based Learning (PBL) 2026, Module 101, is now live on Andamio](https://forum.cardano.org/t/the-marlowe-journey-has-officially-begun-the-gimbalabs-marlowe-project-based-learning-pbl-2026-module-101-is-now-live-on-andamio/151858?u=sebastian_pabon)

- Cardano official telegram group:

[https://t.me/Cardano/860471](https://t.me/Cardano/860471)

- Gimbalabs community discord server: [https://discord.com/channels/767416282198835220/1207345802675097690/1449091049447489647](https://discord.com/channels/767416282198835220/1207345802675097690/1449091049447489647)


---

### GHT-753: Project Cancellation Request to Catalyst team

Status: Done

**09-03-2026**

The cancellation of Marlowe PBL proposal was approved by the Catalyst team.

Link to the conversation: [https://catalystiog.zendesk.com/auth/v3/signin?brand_id=18719230675346&locale=en-us&return_to=https%3A%2F%2Fcatalystiog.zendesk.com%2Fhc%2Fen-us%2Frequests%2F8319%3Fpage%3D1&role=end_user](https://catalystiog.zendesk.com/auth/v3/signin?brand_id=18719230675346&locale=en-us&return_to=https%3A%2F%2Fcatalystiog.zendesk.com%2Fhc%2Fen-us%2Frequests%2F8319%3Fpage%3D1&role=end_user)

**26-02-2026**

*Marlowe PBL 2025: Current Situation*

Proposal #1200144, Fund 12 | Status: Cancellation request under Catalyst team review

Gimbalabs proposed building a Project-Based Learning course on Marlowe through Project Catalyst. Milestone 1 was completed. Before course content development could begin, the underlying technology broke.

After IOG transitioned Marlowe to community stewardship, the Marlowe core development team moved to other projects. The Marlowe compiler (the component every hands-on
learning artifact depends on) became unmaintainable. Course development was technically blocked, not abandoned. Gimbalabs documented this in real time and communicated proactively with both the Marlowe team and the Catalyst team throughout.

The Catalyst team reviewed the situation, confirmed that the Catalyst proposal of the Marlowe team to maintain Marlowe core infra was also unexecutable  (catalyst proposal #1300131), and proposed wrapping up at the current Marlowe PBL checkpoint with supposedly no enforced penalties. 

A cancellation video was recorded and the Project Cancellation Statement was submitted on Feb 21, 2026. The request is now in the Catalyst team's sign-off pipeline: [https://youtu.be/pd05tnwMc3w?si=VvTd7jeilZfGjlxn](https://youtu.be/pd05tnwMc3w?si=VvTd7jeilZfGjlxn) 

Pending approval, this also unblocks two Fund 14 proposals that have been on hold pending resolution of this legacy commitment.

Note: the evolution of the conversation with the Catalyst team (dated from months ago) is hosted here: [https://catalystiog.zendesk.com/auth/v3/signin?brand_id=18719230675346&locale=en-us&return_to=https%3A%2F%2Fcatalystiog.zendesk.com%2Fhc%2Fen-us%2Frequests%2F8319%3Fpage%3D1&role=end_user](https://catalystiog.zendesk.com/auth/v3/signin?brand_id=18719230675346&locale=en-us&return_to=https%3A%2F%2Fcatalystiog.zendesk.com%2Fhc%2Fen-us%2Frequests%2F8319%3Fpage%3D1&role=end_user)


---

## All Task References (18 total)

| # | Notion URL |
|---|------------|
| 1 | https://www.notion.so/f5ba72b099104587ab89d2683ef5934d |
| 2 | https://www.notion.so/091627bb28ff4d02b82f87d164966cc1 |
| 3 | https://www.notion.so/55ef1675fbbd4322938d6743d057b9ff |
| 4 | https://www.notion.so/1270db6d1d5d80a9ab31cade76ef0852 |
| 5 | https://www.notion.so/12e0db6d1d5d80db8a63f42246226b54 |
| 6 | https://www.notion.so/1300db6d1d5d803380abf0fe28339582 |
| 7 | https://www.notion.so/1340db6d1d5d803196b7e13a9b272bcb |
| 8 | https://www.notion.so/1350db6d1d5d80ef81e7ce9d39d2eec6 |
| 9 | https://www.notion.so/1740db6d1d5d8055aca1f20f69c3ee80 |
| 10 | https://www.notion.so/1740db6d1d5d800fbefcfe4786fb60a9 |
| 11 | https://www.notion.so/1740db6d1d5d8074bd38f15ee10e1047 |
| 12 | https://www.notion.so/19b0db6d1d5d800d80dbe2dc94b846bb |
| 13 | https://www.notion.so/19b0db6d1d5d8057ab10c55da8341617 |
| 14 | https://www.notion.so/1b90db6d1d5d80d58699fee65351cce6 |
| 15 | https://www.notion.so/1d40db6d1d5d80c5a953ceaebda561b0 |
| 16 | https://www.notion.so/2c50db6d1d5d803683b3df9970a6017e |
| 17 | https://www.notion.so/3130db6d1d5d8077bf79d0dcc9361599 |

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
