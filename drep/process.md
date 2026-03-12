# DRep Decision Process

This document outlines how Gimbalabs makes decisions about DRep votes on Cardano governance actions.

## Overview

The Gimbalabs DRep represents our collective voice in Cardano governance. We use a consent-based process that prioritizes transparency, community input, and documented reasoning.

## Process Stages

### 1. Identification

**Who:** Governance role holder or any community member

**Actions:**
- Monitor [gov.tools](https://gov.tools) for new governance actions
- Watch community channels (Discord, X) for discussion
- Post new governance actions to Discord `#governance` channel

**Timeline:** Ongoing, check at least weekly

### 2. Analysis

**Who:** Governance role holder with community input

**Actions:**
- Create a summary post in Discord with:
  - Link to the full proposal
  - Plain-language summary of what it proposes
  - Key points for and against
  - Deadline for on-chain voting
- Tag `@governance` role to notify interested members

**Output:** Unbiased summary document

### 3. Discussion

**Who:** Open to all community members

**Venues:**
- Discord `#governance` channel (async)
- Open Spaces Thursday meeting (10-15 min dedicated segment)

**Actions:**
- Collect viewpoints from community members
- Identify concerns and questions
- Discuss relevance to Gimbalabs mission
- Consider conflicts of interest

**Timeline:** Minimum 3 days before vote deadline

### 4. Decision

**Who:** Community members present at Open Spaces

**Method:** Consent-based decision making

**Process:**
1. **Proposal round** - Present the recommended vote with rationale
2. **Clarifying questions** - Address any confusion about the proposal
3. **Reaction round** - Each participant shares initial thoughts
4. **Consent round** - Ask for objections (not preferences)
   - No objections = proposal proceeds
   - Objections must articulate genuine concerns about harm or misalignment
5. **Integration** - If objections raised, modify proposal or reasoning to address them

**Valid objections:**
- "This contradicts our primary driver because..."
- "This creates risk X that hasn't been addressed..."
- "We don't have enough information about..."

**Invalid objections:**
- "I personally prefer a different option"
- "I don't think this is the best choice"
- Objections based on personal relationships or politics

### 5. Documentation

**Who:** Governance role holder

**Actions:**
- Create vote record in `/drep/votes/YYYY-MM-DD-action-name.md`
- Include: context, arguments for/against, our rationale, acknowledged concerns
- Note any conflicts of interest

**Template:** See vote record template below

### 6. Publication

**Who:** DRep key holder (currently James)

**Actions:**
- Submit vote on-chain with rationale
- Share summary in Discord
- Archive final documentation

## Vote Record Template

```markdown
---
action: "Full title of governance action"
gov_tools_url: "https://gov.tools/governance_actions/..."
vote: Yes | No | Abstain
voted_on: YYYY-MM-DD
epoch: NNN
---

# [Action Title]

## Context

[What this governance action proposes, in plain language]

## Arguments For

[Reasons to vote yes]

## Arguments Against

[Reasons to vote no]

## Our Rationale

[Final reasoning, acknowledging concerns from both sides]

## Conflicts of Interest

[Any relationships with proposers or affected parties]

## Community Input

[Summary of discussion points raised]
```

## Timing Guidelines

| Governance Action Type | Minimum Discussion Time |
|------------------------|------------------------|
| Parameter changes | 3 days |
| Treasury withdrawals | 5 days |
| Constitutional amendments | 7 days |
| Hard fork initiations | 7 days |
| Info actions | 3 days |

If a deadline doesn't allow adequate discussion, we may abstain and note the rushed timeline.

## When We Don't Vote

We may choose not to vote (abstain) when:
- Insufficient time for community discussion
- The action doesn't affect Gimbalabs interests
- Community cannot reach consent
- Required expertise isn't available

## Role Responsibilities

**Governance Role Holder:**
- Monitor for governance actions
- Prepare summaries
- Facilitate discussions
- Document decisions
- Ensure process is followed

**DRep Key Holder:**
- Execute on-chain votes
- Ensure votes align with documented decisions
- Maintain security of keys

**Community Members:**
- Participate in discussions
- Raise objections when warranted
- Share expertise and perspectives

## Review

This process is reviewed every 3 months or when significant issues arise.

---

*Based on practices developed in Gimbalabs governance experiments, 2024-2025. See archive for historical context.*
