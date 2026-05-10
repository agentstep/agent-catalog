# SOC 2 Evidence Collector — managed-agent template

Maps SOC 2 Trust Services Criteria to infrastructure configuration, collects evidence artifacts, and flags compliance gaps requiring remediation.

## What it does

1. Maps each SOC 2 Trust Services Criterion (CC1-CC9, availability, confidentiality, etc.) to relevant infrastructure controls
2. Queries cloud provider configurations (IAM policies, encryption settings, logging configs)
3. Collects screenshots and exports of control evidence (access reviews, change management logs)
4. Validates that evidence is current and covers the audit period
5. Identifies gaps where no evidence exists for a required criterion
6. Generates an evidence package organized by criterion with status indicators
