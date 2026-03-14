# System Diagram

> Starter file. Add your architecture diagram here (Mermaid or linked image).

## High-level architecture

```mermaid
graph TD
    A[Customer Evidence] --> B[pm-ai-skills: Discovery]
    B --> C[pm-ai-skills: Strategy]
    C --> D[pm-ai-skills: Execution]
    D --> E[pm-ai-skills: Communication]
    E --> F[Stakeholder / Engineering]

    G[pm-ai-os: Workflows] --> B
    G --> C
    G --> D
    G --> E

    H[pm-ai-os: Templates] --> D
    H --> E

    I[NotebookLM] --> B
    J[Automation / Relay] --> G
```

## Notes

- Replace this diagram with your actual system architecture.
- Use Mermaid for version-controlled diagrams or link to a Figma/Miro board.
