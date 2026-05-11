# Compare I-9 Records against Employee Roster — managed-agent template

Compares an employee roster against an I-9 record log to identify all compliance gaps and discrepancies. Catches missing I-9s, retention violations, reverification lapses, and name/date mismatches that create penalty exposure under INA Section 274A.

## What it does

1. Reads the employee roster and normalizes employee records
2. Reads the I-9 record log and normalizes I-9 entries
3. Matches employees to I-9 records by name, date of birth, or employee ID
4. Identifies employees with no I-9 on file
5. Identifies I-9s with no matching employee (orphaned records)
6. Checks retention compliance based on hire and termination dates
7. Flags reverification gaps for employees with expiring work authorization
8. Produces a comprehensive reconciliation report

## Inputs

- Employee roster (CSV, XLSX, or text — must include name, hire date, termination date if applicable)
- I-9 record log (CSV, XLSX, or text — must include employee name, Section 1 date, Section 2 date)

## Outputs

- `./out/i9-roster-reconciliation.md` — full reconciliation with every discrepancy
- `./out/i9-roster-summary.md` — executive summary with penalty exposure estimate
