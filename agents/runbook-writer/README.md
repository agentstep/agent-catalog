# Runbook Writer — managed-agent template

Converts tribal knowledge and ad-hoc procedures into structured runbooks with decision trees, escalation paths, and verification steps.

## What it does

1. Interviews the operator or reads existing notes/Slack threads about a procedure
2. Identifies the trigger conditions (when should someone use this runbook?)
3. Structures the procedure into clear, numbered steps with decision points
4. Adds verification commands after each step to confirm success
5. Defines escalation paths for when the standard procedure doesn't resolve the issue
6. Includes rollback/undo steps and links to related runbooks
