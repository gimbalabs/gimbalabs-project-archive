# Proposal Lifecycle

This document describes how proposals move through the Gimbalabs governance system.

## States

```
Draft → Open → Active → Closed
              ↘ Withdrawn
```

### Draft

**Location:** `proposals/draft/`

A proposal in development, not yet ready for community consent.

**What happens here:**
- Author develops the proposal using TEMPLATE.md
- May share informally for early feedback
- Not visible to broader community decision-making

**To move to Open:**
- Complete all 11 sections of the template
- Identify a sponsor (if not the author)
- Move file to `proposals/open/`
- Announce in Discord `#governance`

### Open

**Location:** `proposals/open/`

A proposal open for community review and consent.

**What happens here:**
- Community reviews the proposal
- Discussion in Discord and/or Open Spaces
- Objections can be raised
- Proposal may be amended to address concerns

**Default period:** 14 days

**To move to Active:**
- Consent period completes with no unresolved objections
- Record decision date in frontmatter
- Move file to `proposals/active/`

**To move to Withdrawn:**
- Author chooses to withdraw (any reason)
- Or objections cannot be resolved
- Record withdrawal reason
- Move file to `proposals/closed/` with status "Withdrawn"

### Active

**Location:** `proposals/active/`

An approved proposal being implemented.

**What happens here:**
- Implementation work proceeds
- Progress tracked (Discord, tasks, or project docs)
- Regular check-ins per the Review and Adaptation Plan

**To move to Closed:**
- Implementation complete (success)
- Implementation abandoned (with documented reason)
- Review determines proposal should end
- Move file to `proposals/closed/`

### Closed

**Location:** `proposals/closed/`

A proposal that has completed its lifecycle.

**Statuses:**
- **Completed** - Successfully implemented
- **Withdrawn** - Removed before or during consent
- **Rejected** - Failed consent (rare, usually withdrawn instead)
- **Superseded** - Replaced by a newer proposal

## File Naming

Use lowercase with hyphens:
```
proposals/draft/contributor-tokens.md
proposals/open/2025-03-drep-process-v2.md
proposals/active/open-spaces-governance-segment.md
proposals/closed/2024-10-gimbalabs-drep-original.md
```

Include date prefix for Open and Closed proposals.

## Quick Reference

| State | Location | Duration | Exit Criteria |
|-------|----------|----------|---------------|
| Draft | `proposals/draft/` | Until ready | Author moves to Open |
| Open | `proposals/open/` | 14 days default | Consent reached or withdrawn |
| Active | `proposals/active/` | Until done | Implementation complete |
| Closed | `proposals/closed/` | Permanent | Archive |

## Amending Active Proposals

To make significant changes to an active proposal:
1. Create a new proposal referencing the original
2. Follow the standard Open → Active flow
3. When approved, update or supersede the original

Minor clarifications can be made directly with a note in the proposal.

## Urgency

Some proposals may need expedited handling:
- DRep votes with short deadlines
- Operational emergencies
- Time-sensitive opportunities

For urgent proposals:
1. Note "URGENT" in the title
2. Specify shortened consent period (minimum 24 hours)
3. Announce prominently in Discord
4. Require synchronous consent at next available meeting

## Tracking

Current proposals are visible in the directory structure. For broader tracking:
- Active proposals may link to task tracking
- Discord `#governance` pins current Open proposals
- Open Spaces agenda includes proposal status updates
