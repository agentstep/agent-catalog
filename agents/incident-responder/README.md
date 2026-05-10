# Incident Responder — managed-agent template

Correlates alerts from logs and metrics, identifies probable root cause, suggests remediation steps, and drafts a post-incident report.

## What it does

1. Ingests alert data from monitoring systems (PagerDuty, Datadog, CloudWatch, etc.)
2. Correlates alerts by time window and affected services to identify the blast radius
3. Analyzes logs and metrics to pinpoint the root cause
4. Suggests immediate remediation steps ordered by impact
5. Tracks incident timeline with key decisions and actions
6. Drafts a post-incident report with root cause, timeline, and action items
