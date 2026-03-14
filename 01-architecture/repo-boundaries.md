# Repo Boundaries

Defines what belongs in each repository and how they relate.

## pm-ai-skills

- **What:** Skill definitions — structured prompt frameworks for PM tasks
- **Audience:** Personal use, potentially shared with other PMs
- **Sensitivity:** Low — no real customer data or confidential content
- **Changes:** Update when a skill is refined, added, or deprecated

## pm-ai-os

- **What:** Architecture, workflows, templates, evals, automation config
- **Audience:** Personal use — the "engine room" of the system
- **Sensitivity:** Medium — may reference internal tooling or workflows
- **Changes:** Update when workflows or templates evolve

## pm-ai-demo

- **What:** Sanitized demo materials for interviews and external presentations
- **Audience:** Interviewers, collaborators, public portfolio (if desired)
- **Sensitivity:** Low — must remain fully sanitized and fictional
- **Changes:** Update when preparing for a specific interview or demo

## Cross-repo rules

- Real customer data never leaves pm-ai-os (and ideally doesn't live there either)
- Demo materials in pm-ai-demo must be independently verifiable as fictional
- Skills in pm-ai-skills should not encode company-specific context
