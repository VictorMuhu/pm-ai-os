# PM AI Operating System Architecture

## Overview

The PM AI Operating System is a layered system designed to help product managers move from raw information to product decisions quickly and consistently.

The system is composed of five layers:

1. Demo Layer
2. Operating System Layer
3. Skill Layer
4. Knowledge Layer
5. Tool Layer

Each layer has a specific role in the workflow.

---

## Layer 1 — Demo Layer

**Repository:** pm-ai-demo

**Purpose:**
Provide a sanitized environment for demonstrating the PM AI system in interviews or presentations.

**Contents:**
- demo scripts
- walkthrough examples
- sanitized artifacts
- sample outputs

This layer should contain no confidential information.

---

## Layer 2 — Operating System Layer

**Repository:** pm-ai-os

**Purpose:**
Define how the system works.

**Contents:**
- workflows
- templates
- evaluation rubrics
- automation rules
- architecture documentation

This layer acts as the coordination hub for the system.

---

## Layer 3 — Skill Layer

**Repository:** pm-ai-skills

**Purpose:**
Store reusable Claude Code skills that perform repeatable PM tasks.

**Examples:**
- customer synthesis
- PRD writing
- metric definition
- experiment design
- stakeholder updates

Each skill defines a structured method for turning inputs into high-quality outputs.

---

## Layer 4 — Knowledge Layer

**Tool:** NotebookLM

**Purpose:**
Store the research corpus that feeds the system.

**Examples:**
- customer interviews
- product documentation
- analytics summaries
- market research
- competitor insights

This layer acts as the system's memory.

---

## Layer 5 — Tool Layer

External tools that generate signals used by the PM system.

**Examples:**
- product analytics
- support systems
- research tools
- experimentation platforms

These tools provide the raw signals that feed the knowledge layer.

---

## Workflow Example

Typical workflow:

```
Customer interview
→ stored in NotebookLM
→ synthesized using Claude skills
→ problem framed
→ PRD generated
→ work broken into tickets
→ metrics defined
→ stakeholder updates generated
```

---

## Design Principles

The system is built around several principles:

1. Separate knowledge from methods.
2. Use repeatable skills instead of ad-hoc prompting.
3. Keep confidential information out of reusable systems.
4. Structure workflows for clarity and leverage.
5. Make the system easy to demonstrate and evolve.
