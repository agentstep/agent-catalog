# Expense Categorizer — managed-agent template

Processes expense reports, categorizes line items to the correct GL accounts, flags policy violations, and generates approval summaries.

## What it does

1. Reads expense report data (receipts, credit card statements, CSV uploads)
2. Categorizes each expense to the appropriate GL account based on merchant and description
3. Validates amounts against company policy limits (per-diem, category caps)
4. Flags policy violations with specific rule citations
5. Identifies potential duplicate submissions
6. Generates an approval summary with total by category and flagged items
