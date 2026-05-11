# Extract Filing Requirements from Regulatory Guidance — managed-agent template

Reviews regulatory guidance documents — USCIS policy memoranda, Federal Register notices, AAO precedent decisions, DOL Field Assistance Bulletins, and agency policy manuals — to extract actionable filing requirements, evidentiary standards, and procedural changes that affect immigration case preparation.

## What it does

1. Reads the regulatory guidance document(s) and identifies the document type and authority level
2. Extracts every actionable filing requirement and procedural change
3. Identifies changes to evidentiary standards or adjudication criteria
4. Maps requirements to affected petition/application types
5. Notes effective dates, transition rules, and superseded guidance
6. Produces a structured requirements digest and a practice impact assessment

## Inputs

- Regulatory guidance document(s) (USCIS Policy Manual updates, Policy Memoranda, Federal Register notices, AAO decisions, DOL FABs, DOS Cable updates)
- Context: which practice areas or petition types the user is focused on

## Outputs

- `./out/regulatory-requirements-digest.md` — structured extraction of all requirements
- `./out/practice-impact-assessment.md` — assessment of how the guidance changes current practice
