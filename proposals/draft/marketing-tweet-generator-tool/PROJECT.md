---
title: "Marketing: Tool to parse and create tweets from Open Spaces Transcripts"
notion_url: "https://www.notion.so/1cd0db6d1d5d80afbb2ec311d16b4bf4"
status: "Planning"
priority: "Medium"
owner: []
collaborators: []
funding_source:
  - "F12: Sustain + Maintain"
circle:
  - "Advocacy&Outreach"
ada_inflows: null
ada_outflows: 1000
budget_spent_ada: null
operational_dates:
  start: "2025-04-17"
  end: null
review_date: "2025-07-10"
archived_at: "2026-03-09"
has_tasks: true
---

# Marketing: Tool to parse and create tweets from Open Spaces Transcripts

## Gimbalabs Primary Driver
To provide open, replicable safe spaces to learn, to explore, and to empower individuals and organizations anywhere so that we can solve meaningful problems

## Proposal Driver
Currently, Gimbalabs' governance is becoming very effective at directing the internal communities' efforts but does not communicate its effectiveness to the wider Cardano community. The current long-form YT videos demand a huge time commitment.

## Proposal

### 1. Title or Brief Description
AI driven tool to parse the Open Spaces transcripts and suggest tweets for the Marketing team to edit and post to X directly from the tool.

### 2. Background or Rationale
Gimbalabs produces a wealth of insightful discussions through its Open Spaces sessions, yet most of this content remains locked in long-form transcripts or videos. The AI Tweet Generator bridges this gap by automatically converting transcripts into categorized tweet suggestions. It enables faster and more consistent communication of internal governance and proposal updates to the broader Cardano ecosystem, reducing the effort and time required from the marketing team.

### 3. Intended Outcome
1. Increase Gimbalabs' tweet volume
2. Ease posting workload for marketing team
3. Cardano community has a better insight into Gimbalabs' governance and proposal implementation

### 4. Details of the Proposal
We propose deploying and testing an open-source tool that processes Open Spaces transcripts and generates tweet suggestions using Anthropic Claude. Tweets are reviewed and posted via a simple dashboard, offering the ability to edit, delete, or send tweets directly to X. The tool includes local file storage, configurable admin access, and modular architecture for easy updates. Prompt instructions used for tweet generation can be updated by the marketing team.

**GitHub Repository:** https://github.com/gulla0/ai-tweet-generator

### 5. Impact and Benefits
1. Publicize Gimbalabs' governance model to the Cardano ecosystem
2. Communicate individual proposal updates to the ecosystem
3. AI generated tweets w/ human approval before posting
4. Ease marketing team's workload
5. Marketing team can update prompt wrap to increase the relevance of the tweets
6. The marketing team can request updates and changes to the tool through the course of the proposal

### 6. Evaluation Criteria
The proposal will be evaluated by the marketing team itself. The team can continue using the tool beyond the scope of the proposal, request for additional features, or stop using it any time before the proposal end date if it does not provide enough value.

### 7. Timeline
3 months

### 8. Resources Required
1. Anthropic API (3.5 haiku): $15 for the whole of 3 months
2. The marketing team's effort to deploy the tool locally and test it
3. 1000 ADA donation to builder at the end of the proposal: To be strictly approved/denied by the marketing team

### 9. Responsibilities
- **Harsha:** Maintain and build additional features as per the marketing team's requests
- **Marketing team:** Sebastian Pabon and any other member that is responsible for posting on X

### 10. Potential Risks and Mitigation Strategies
1. **Too hard to deploy and use:** The marketing team can ask for support from Harsha or choose to dump the tool without any significant financial loss
2. **There are bugs that affect usability:** Bug fixes and feature updates can be requested and it's Harsha's responsibility to follow through

### 11. Review and Adaptation Plan
The marketing team will review tweet quality and tool usability weekly during the 3-month period. If issues arise, Harsha will provide technical support or feature updates. Feedback will guide prompt tuning or UI enhancements. At the end of the proposal, the team can decide whether to adopt, expand, or retire the tool based on utility and results.
