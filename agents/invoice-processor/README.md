# Invoice Processor — managed-agent template

Extracts structured data from invoice PDFs, matches line items against purchase orders, validates totals, and outputs journal entries for the accounting system.

## What it does

1. Reads invoice documents (PDF, image, or structured data)
2. Extracts vendor info, line items, quantities, unit prices, tax, and totals
3. Matches the invoice against the corresponding purchase order
4. Validates that quantities, prices, and totals match within tolerance
5. Identifies discrepancies and routes for manual resolution
6. Outputs formatted journal entries ready for import into the accounting system
