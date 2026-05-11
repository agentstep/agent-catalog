# Extract Key Terms from Foreign Credential Evaluations — managed-agent template

Reviews foreign credential evaluation reports from NACES/AICE-member agencies and produces a structured summary for use in immigration petitions. Extracts degree equivalencies, credit-hour analyses, course-by-course breakdowns, and evaluator credentials to ensure the evaluation supports the petition's educational requirements.

## What it does

1. Reads one or more foreign credential evaluation reports
2. Extracts the U.S. degree equivalency determination and methodology
3. Identifies the evaluator's credentials and agency accreditation
4. Extracts course-by-course breakdowns and credit-hour conversions
5. Assesses whether the evaluation supports the petition's degree requirements
6. Flags common evaluation weaknesses that trigger RFEs
7. Produces a structured credential summary and a petition alignment assessment

## Inputs

- Foreign credential evaluation report(s) (PDF or text)
- The immigration petition type and its educational requirements (e.g., H-1B specialty occupation, EB-2 advanced degree, EB-3 bachelor's equivalent)
- The beneficiary's educational documents (transcripts, diploma, marksheets)

## Outputs

- `./out/credential-evaluation-summary.md` — structured extraction of evaluation findings
- `./out/credential-petition-alignment.md` — assessment of whether the evaluation supports the petition
