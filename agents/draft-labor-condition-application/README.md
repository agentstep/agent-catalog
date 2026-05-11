# Draft Labor Condition Application — managed-agent template

Prepares a Labor Condition Application (LCA) preparation memorandum for one or more H-1B beneficiaries. Analyzes job positions, determines correct SOC codes, identifies prevailing wage levels, validates worksite information, and produces a field-by-field completion guide for ETA Form 9035/9035E.

## What it does

1. Reads beneficiary and position information for each H-1B worker
2. Determines the appropriate SOC code and prevailing wage level for each position
3. Validates the actual wage against the prevailing wage
4. Identifies all worksites requiring LCA coverage
5. Assesses H-1B dependency status and additional attestation requirements
6. Produces a field-by-field LCA preparation memorandum and a compliance checklist

## Inputs

- Position descriptions for each beneficiary (job title, duties, requirements, salary)
- Employer information (name, FEIN, address, NAICS code, number of employees)
- Worksite information for each beneficiary (address, MSA/non-MSA)
- Employer's H-1B workforce data (for dependency determination)

## Outputs

- `./out/lca-preparation-memo.md` — field-by-field completion guide for each LCA
- `./out/lca-compliance-checklist.md` — pre-filing and post-filing compliance requirements
