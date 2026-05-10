# Database Migration Planner — managed-agent template

Analyzes database schemas, generates migration scripts, identifies breaking changes, and produces rollback plans for safe schema evolution.

## What it does

1. Reads the current schema definition and the desired target state
2. Computes a diff between current and target schemas
3. Identifies breaking changes (column drops, type narrowing, constraint additions on populated columns)
4. Generates forward migration scripts with proper ordering for foreign key dependencies
5. Produces a matching rollback script for each migration step
6. Estimates lock duration and recommends online vs. offline migration strategies
