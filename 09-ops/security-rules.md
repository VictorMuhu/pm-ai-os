# Security Rules

> Rules for keeping the PM AI OS secure and compliant.

## Data handling

- Never store customer PII in any of the three repos
- Never commit API keys, tokens, or passwords — use environment variables or a secrets manager
- Keep pm-ai-os and pm-ai-skills as private GitHub repos unless explicitly decided to make public
- pm-ai-demo may be made public but only after thorough sanitization review

## Access control

- Use SSH or personal access tokens for GitHub authentication (not passwords)
- Rotate GitHub tokens annually or after any suspected exposure
- Do not share repo access with unauthorized users

## AI input/output hygiene

- Do not paste confidential documents directly into Claude.ai chat (use Claude Code or API with appropriate controls instead)
- Review AI outputs before sharing externally — AI can hallucinate or surface context inappropriately
- Do not use AI to generate content that could be mistaken for real customer evidence

## Incident response

- If a secret is accidentally committed: rotate it immediately, then use `git filter-branch` or BFG Repo Cleaner to remove it from history
- If confidential data is pushed: take the repo private immediately, audit access, notify relevant stakeholders

## Notes

- Review this document annually or after any security incident.
