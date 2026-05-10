# Deploy Orchestrator — managed-agent template

Generates deployment scripts, validates environment variables and secrets, produces pre-deploy checklists, and coordinates multi-service rollouts.

## What it does

1. Reads service configuration and infrastructure-as-code definitions
2. Validates that all required environment variables and secrets are set for the target environment
3. Generates deployment scripts with proper ordering for dependent services
4. Produces a pre-deploy checklist with manual verification steps
5. Coordinates canary/blue-green rollout strategies with health check gates
6. Provides rollback commands for each deployment step
