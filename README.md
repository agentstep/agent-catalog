# Agent Catalog

Pre-built managed agent templates for [AgentStep](https://agentstep.com). Browse and deploy from the Agent Catalog UI.

## Structure

Each agent is a directory under `agents/` containing an `agent.yaml` manifest:

```
agents/
├── contract-reviewer/
│   ├── agent.yaml
│   └── README.md
├── another-agent/
│   ├── agent.yaml
│   └── README.md
```

## Manifest Format

See the [managed agents spec](https://github.com/agentstep/agentstep-product/blob/main/docs/superpowers/specs/2026-05-09-managed-agents-registry-design.md) for the full `agent.yaml` schema.

Required fields: `name`, `version`, `description`, `category`, `model`, `system`.
