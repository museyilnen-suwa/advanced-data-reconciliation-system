# Advanced Data Reconciliation System

Cleans, validates, and reconciles 535 real-world messy order records against a
60-customer master list — simulating the kind of multi-source data reconciliation
common in data entry and back-office roles.

## What it does
- Cleans inconsistent text (spacing, casing) and mixed date/currency formats
- Validates quantities and flags missing or invalid data
- Reconciles orders against a customer master list using INDEX/MATCH
- Flags exact and near-duplicate entries
- Live dashboard: total orders, error rate, revenue by region, chart

## Result
535 raw orders processed → 162 automatically flagged for review (30.3% error rate),
covering invalid dates, invalid amounts, invalid quantities, duplicates, and
unmatched customer records — without manual row-by-row checking.

## Tools used
Excel formulas: INDEX, MATCH, IFERROR, TRIM, PROPER, UPPER, SUBSTITUTE, VALUE,
DATEVALUE, COUNTIF, COUNTIFS, SUMIFS, data validation, conditional formatting.
