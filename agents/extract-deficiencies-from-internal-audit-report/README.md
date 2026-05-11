# Extract Deficiencies from Internal Audit Report — managed-agent template

Extracts every compliance deficiency from an internal immigration compliance audit report and produces a structured deficiency matrix. Classifies each deficiency by regulatory domain, severity, and remediation urgency. Designed for I-9 audits, H-1B/LCA compliance reviews, PERM audit file reviews, and general immigration program assessments.

## What it does

1. Reads the internal audit report and identifies every finding, observation, and recommendation
2. Classifies each deficiency by regulatory domain (I-9, LCA, PERM, visa status, anti-discrimination)
3. Maps each deficiency to the specific regulatory provision violated
4. Assigns severity and remediation priority
5. Calculates aggregate penalty exposure by deficiency category
6. Produces a structured deficiency matrix and remediation tracker

## Inputs

- Internal immigration compliance audit report (PDF, DOCX, or text)
- Scope of audit (which compliance areas were covered)
- Employer size and industry (for penalty calculation context)

## Outputs

- `./out/deficiency-matrix.md` — structured extraction of every deficiency
- `./out/remediation-tracker.md` — prioritized remediation plan with deadlines
