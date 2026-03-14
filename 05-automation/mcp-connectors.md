# MCP Connectors for PM AI OS

MCP (Model Context Protocol) connectors allow Claude Code to interact with external systems and retrieve signals automatically.

These integrations transform the PM AI OS from a static workflow into a live operating system.

---

## GitHub Connector

**Purpose:**
Allow Claude to interact with repositories and issues.

**Use cases:**
- generate tickets from PRDs
- review specs
- manage roadmap docs
- analyze repository history

**Example prompts:**

> "Generate tickets from this PRD"

> "Review recent issues for customer problems"

---

## Slack Connector

**Purpose:**
Ingest internal conversations and detect product signals.

**Use cases:**
- summarize customer complaints
- identify recurring product issues
- detect internal product friction

**Example prompts:**

> "Summarize customer complaints from the support channel this week"

> "Identify repeated product issues mentioned in Slack"

---

## Docs / Notion Connector

**Purpose:**
Allow Claude to read and analyze documentation.

**Use cases:**
- summarize specs
- extract decisions
- detect inconsistencies across docs

**Example prompts:**

> "Summarize the onboarding spec"

> "Identify open questions across product docs"

---

## Design Principle

Connectors should be used to retrieve signals and context.

Sensitive data should not be copied into GitHub repositories.

The system should rely on external sources for raw data and use Claude skills for analysis.
