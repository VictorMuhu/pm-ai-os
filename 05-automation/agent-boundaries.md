# Agent Boundaries

> Defines what AI agents in this system can and cannot do autonomously.

## Principles

- AI agents assist judgment — they do not make final decisions on strategy, hiring, or customer commitments
- Agents should not send external communications (email, Slack) without human review
- Agents should not write to production systems or push to main branches without human approval
- Agents should flag uncertainty rather than guess

## Approved autonomous actions

- Drafting documents for human review
- Running analysis on provided data
- Summarizing and synthesizing inputs
- Generating options and trade-off analyses

## Actions requiring human review before execution

- Sending any external communication
- Creating or modifying GitHub issues or PRs
- Updating shared documents or wikis
- Any action that affects other people's work

## Out of bounds (never autonomous)

- Making commitments to customers or partners
- Accessing systems not explicitly configured in the connector map
- Sharing confidential data outside approved channels

## Notes

- Review and update this document when adding new AI capabilities to the system.
