# Connector Map

> Starter file. Map the data flows between tools in your PM AI stack.

## Connector inventory

| Source | Destination | Data / signal | Method | Notes |
|---|---|---|---|---|
| Customer interviews | NotebookLM | Anonymized transcripts | Manual upload | |
| NotebookLM | pm-ai-os | Synthesized research | Manual export | |
| GitHub | Claude | Repo context | MCP or manual | |

## Design principles

- No real customer data should flow through unapproved connectors
- Every connector should be documented here before it is used
- Review connector map quarterly to remove stale or unused connections

## Notes

- Add your actual connectors as you configure them.
- Flag connectors that handle sensitive data with a ⚠️ marker.
