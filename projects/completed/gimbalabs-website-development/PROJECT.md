---
title: "Gimbalabs Website Development"
notion_url: "https://www.notion.so/20eff1ffceaa42d283b29319f77287fb"
status: "Done"
priority: null
owner: []
collaborators: []
funding_source: []
circle: []
ada_inflows: null
ada_outflows: 2000
budget_spent_ada: 2000
operational_dates:
  start: "2024-05-15"
  end: "2024-06-19"
review_date: "2024-09-26"
archived_at: "2026-03-09"
---

# Gimbalabs Website Development

## Gimbalabs Primary Driver

To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems.

**What does this mean:**

- **Openness**
  - Allow people the freedom to see how things work
  - Sharing information for the benefit of others
- **Replicability**
  - Allow people to take your code or workflows to use elsewhere
- **Safe spaces to learn and explore**
  - Provide information in a way that allows people to discover ideas and how they fit together
  - Promoting exploration while lowering the risks involved
- **Empowering people to solve meaningful problems**
  - What are meaningful problems?
  - How do you empower people to solve them?

Should the website contribute towards these goals?

## Proposal Driver

The website doesn't currently reflect the Gimbalabs primary driver. This can hinder newcomers from understanding what Gimbalabs is all about. We should look at how the website can be more open, replicable, a safe space to learn and explore, and more empowering to people.

**Questions to explore:**
- How can the website be more open?
- How can it be more replicable?
- Can the website promote a safer learning and exploration experience?
- How can it become something that empowers both individuals and organizations?
- Can it contribute towards finding solutions to meaningful problems?

## Proposal

### 1. Brief Description

A rewrite of the Gimbalabs website in a way that addresses all the questions above, allowing contributors to push dynamic and interconnected content to an open source knowledge base that can be freely forked and adapted for other use cases. Maybe even providing a way for different forks of the web application to link to each other's content and build meaningful connections between them!

### 2. Background or Rationale

The website is an entry point into the Gimbalabs community. It connects people with opportunities to join Zoom meetings, or read a few articles, but does its current state embody the values of Gimbalabs as an organization? Does it hinder us from meeting our objectives?

Let's paint a picture for how a website could ideally reflect the Gimbalabs primary driver:

- **Openness** means transparency. An open website allows people the freedom to see how it works and to reuse its code.
- A site is **replicable** if people can take its code and deploy it elsewhere for similar use cases.
- The website should allow people to feel **safe** to share ideas, whether they converge into a shared course of action, or diverge into competing experiments.
  - The goal is to find out which paths forward stand up to scrutiny and show the most functional resilience under possible internal and external pressures.
- A website that promotes **learning and exploration** would provide information in a way that allows people to discover new ideas and find connections between existing ideas.

Along with the concerns above, it's also important to consider what would make the website more reliable and easier to adapt to changing needs in the future. This is one of the reasons why Elm is a good choice for this project:

- Elm is known for its reliability and simplicity.
- It's a pure functional language that compiles to JavaScript, but offers correctness guarantees that cannot be achieved in TS or JS.
- The simplicity of the Elm language allows its compiler to guarantee that your code won't produce runtime errors. This is true even for projects with hundreds of thousands of lines of code.
- Because all functions you write in Elm are pure, you don't end up with spaghetti code.
  - Elm code is a joy to refactor!
- Elm is known for having one of the friendliest compilers.
  - It often suggests the change that you need to make to fix a problem with your code.
- Elm code is very similar to Haskell without the need to understand some of the more complex topics like type classes or monads.
- The Elm Architecture guarantees that the state of your application is within the scope of a single type, and that all of your possible state transitions are clearly defined within a single function.

### 3. Intended Outcome

That Gimbalabs would have a website that actually embodies the goals given in the primary driver! The website will be open and reusable for similar use cases in different communities, without the need to do many changes to the code itself. The code will be easy to learn about, maintain, or change for those who want to do so. The website will also become a useful place to explore different ideas and connect them together. Maybe even allowing content creators to put together little interactive choose-your-own-adventure games to give people a more engaging experience with the information they produce.

### 4. Details of the Proposal

- Build a Gimbalabs website that actually embodies the goals given in the primary driver!
- The website will be open and reusable for similar use cases in different communities, without the need to do many changes to the code itself.
- The code should be easy to learn about, maintain, or change for those who want to do so.
- All work on the site will be available here: https://thistent.github.io/gimbalabs/
- Ken can take care of the design and development work, but everyone is free to provide input to this process.
- Code will be cleaned up to make it as easy as possible for newcomers to get acquainted with how the code-base works.
- The site itself could introspectively allow users to explore and learn about its own source.
- Building some interactive experiences to showcase what the site could do in the future.

### 5. Impact and Benefits

- A site that embodies what Gimbalabs stands for could improve community interaction as well as providing value, through replicability, to people outside our community.
- It will provide insight into the ideas being developed by our community, as well as more expressive ways for people to produce interactive content.
- The open-source Elm code-base could be useful as a teaching/learning tool.
  - It can be a stepping stone on the way to Haskell development.
- Code could be repurposed for use by other communities that want to achieve similar goals, while providing a way to link what you're working on with ideas developed in these other knowledge bases.
  - Enhancing collaborative learning and innovative thinking between communities.

### 6. Evaluation Criteria

- Progress on the website will be visually verifiable and self-explanatory.
- Choosing a short initial timeline will provide the community a chance to reassess the value of the work provided, and make a decision about whether continued work is worth funding.

### 7. Timeline

- Funding for this project will cover one month of work
- Continuation will be reassessed on a month-by-month basis.
- Ken will be available for questions during weekly meetings.

### 8. Resources Required

- 2000 Ada for one month
- People can share their ideas

### 9. Responsibilities

- Ken can handle all development responsibilities for this project.

### 10. Potential Risks and Mitigation Strategies

- All development work will be pushed to GitHub, so people can see progress.
- If work is not satisfactory, further funding after the first month can be discontinued.

### 11. Review and Adaptation Plan

- A review of progress can be held at the end of each month to determine whether continued funding is needed or justified.
