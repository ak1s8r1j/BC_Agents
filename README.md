# BC Agents

A collection of specialized AI agent definitions for Microsoft Dynamics 365 Business Central (BC) work, designed for use with Claude Code.

## Agents

| Agent | File | Use for |
|---|---|---|
| **bc-solution-architect** | [Agents/bc-solution-architect-agent.md](Agents/bc-solution-architect-agent.md) | Solution blueprints and architecture decision records, fit-gap and configure-vs-extend-vs-buy decisions, environment/tenant strategy, multi-company and multi-country rollout design, integration architecture, data migration and cutover strategy, ALM and update governance, licensing and sizing, security and compliance models, performance-at-scale planning, ISV selection, and technical risk assessment. |
| **bc-functional-consultant** | [Agents/bc-functional-consultant-agent.md](Agents/bc-functional-consultant-agent.md) | Requirements discovery and process mapping, fit-gap analysis, module setup and configuration (Finance, Sales, Purchasing, Inventory, Warehouse, Manufacturing, Jobs, Service, Fixed Assets), posting-group and dimension design, chart of accounts and financial reporting, data migration mapping and opening balances, test script and UAT design, key-user training, go-live cutover and hypercare, and diagnosing standard-functionality behaviour. |
| **bc-al-developer** | [Agents/bc-al-developer-agent.md](Agents/bc-al-developer-agent.md) | AL extension design and code, base-app behaviour questions across every BC module, posting-routine and costing-engine analysis, performance tuning, upgrade/data-upgrade work, C/AL-to-AL conversion, and integration work (APIs, OData, webhooks, S2S auth, Power Platform, Dataverse, D365 Sales/Field Service, Shopify, Azure services, EDI, third-party ISV apps). |

## How they fit together

- Use **bc-solution-architect** for landscape- and program-level architecture decisions.
- Use **bc-functional-consultant** for module configuration, business-process fit-gap, and functional design documents.
- Use **bc-al-developer** for writing AL code and technical integration work.

## Usage

These are agent definition files intended for use with [Claude Code](https://claude.com/claude-code) — place them where your Claude Code setup loads custom agents from, or reference them directly when starting a task that matches their scope.
