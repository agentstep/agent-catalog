# Compare Filing Receipt against Petition Submission — managed-agent template

Compares a USCIS filing receipt notice (Form I-797C, Notice of Action) against the original petition submission documents to identify discrepancies in beneficiary data, classification, fees, and priority dates that could affect case processing or require immediate correction.

## What it does

1. Reads the USCIS receipt notice (I-797C) and extracts all data fields
2. Reads the original petition submission and extracts corresponding fields
3. Compares every field for discrepancies
4. Assesses the downstream impact of each discrepancy
5. Identifies required corrective actions and their urgency
6. Produces a discrepancy report with recommended actions

## Inputs

- USCIS receipt notice (I-797C or I-797, PDF or text)
- Original petition forms and cover letter (PDF, DOCX, or text)
- Any supporting documentation with key data points (e.g., passport, EAD, prior receipt notices)

## Outputs

- `./out/receipt-discrepancy-report.md` — field-by-field comparison with impact assessment
- `./out/receipt-action-items.md` — prioritized corrective actions
