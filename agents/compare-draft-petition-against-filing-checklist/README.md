# Compare Draft Petition against Filing Checklist — managed-agent template

Reviews a draft immigration petition package against a filing checklist to identify completeness and accuracy issues before submission. Catches missing forms, unsigned pages, incorrect fee amounts, and evidentiary gaps that would result in a rejection or Request for Evidence.

## What it does

1. Reads the filing checklist (firm-generated or USCIS-published) and parses each required item
2. Reads the draft petition package and inventories every document, form, and exhibit
3. Maps each checklist item to corresponding petition documents
4. Flags missing items, incomplete forms, signature gaps, and fee discrepancies
5. Cross-checks form editions against current USCIS accepted editions
6. Validates filing fees against the USCIS fee schedule (effective April 2024)
7. Produces a structured gap analysis report in ./out/

## Inputs

- Draft petition package (PDF, DOCX, or directory of files)
- Filing checklist (PDF, DOCX, or text file)
- Petition type (e.g., I-140 EB-1A, I-129 H-1B, I-485 AOS)

## Outputs

- `./out/petition-checklist-gap-analysis.md` — structured gap report with pass/fail per item
- `./out/petition-checklist-summary.md` — executive summary with risk assessment
