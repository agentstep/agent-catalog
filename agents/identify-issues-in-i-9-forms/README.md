# Identify Issues in I-9 Forms — managed-agent template

Conducts a comprehensive I-9 compliance audit by reviewing individual Form I-9 records to identify every deficiency — from missing fields and incorrect document entries to substantive verification failures. Classifies each issue as technical or substantive, determines whether it is correctable, and calculates penalty exposure under current ICE fine schedules.

## What it does

1. Reads I-9 forms (individual or batch) and examines every field in Sections 1, 2, and Supplement B
2. Checks each field against the I-9 completion requirements in the M-274 Handbook
3. Identifies technical/procedural errors, substantive violations, and document-related issues
4. Classifies each error by type, section, correctability, and severity
5. Determines whether errors constitute document abuse or discrimination indicators
6. Calculates per-form and aggregate penalty exposure
7. Produces a detailed audit findings report and correction guide

## Inputs

- I-9 forms to audit (PDF, scanned images, or structured data)
- Employee hire dates and termination dates (for timeliness and retention analysis)
- Current form edition reference (08/01/23, expires 05/31/2027)

## Outputs

- `./out/i9-audit-findings.md` — detailed findings for every I-9 reviewed
- `./out/i9-correction-guide.md` — correctable errors with step-by-step correction instructions
