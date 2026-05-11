# Compare Corrective Actions against Regulatory Standards — managed-agent template

Reviews corrective action plans against applicable regulatory standards to assess compliance and identify remediation priorities. Maps each proposed corrective action to its triggering regulatory requirement, evaluates whether the action fully addresses the deficiency, and flags gaps in remediation scope or timeline.

## What it does

1. Reads the corrective action plan and extracts each proposed remediation step
2. Reads the applicable regulatory standards, agency guidance, and enforcement actions
3. Maps each corrective action to the specific regulatory provision it addresses
4. Evaluates whether each action fully remediates the cited deficiency
5. Identifies regulatory requirements not addressed by any corrective action
6. Assesses remediation timelines against regulatory deadlines and safe harbors
7. Produces a compliance gap matrix and prioritized remediation roadmap

## Inputs

- Corrective action plan document
- Applicable regulatory standards (INA provisions, 8 CFR sections, DOL regulations, agency guidance)
- Enforcement action or audit findings that triggered the corrective actions (NOI, NOF, audit report)

## Outputs

- `./out/corrective-action-compliance-matrix.md` — mapping of actions to standards with gap analysis
- `./out/remediation-priority-roadmap.md` — prioritized action items with deadlines
