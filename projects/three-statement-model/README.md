# Integrated Three-Statement Model

Do operating assumptions flow consistently into cash and the balance sheet?

## Role relevance
Corporate finance · Financial modelling

## Data
Apple FY2023–FY2025; scenarios explicitly labelled. Source: https://www.sec.gov/Archives/edgar/data/320193/000032019325000079/aapl-20250927.htm. Retrieved 2026-10-30.

## Method
FY2025 audited closing balance sheet is the opening position. FY2026 scenario: products +3%, services +10%, COGS proportional to revenue, opex +5%, D&A/capex/AR/inventory/AP proportional to revenue. Hold other balance-sheet lines constant, other expense at $321m and dividends at $15,421m. Apply FY2025 effective tax rate. No buybacks, new debt, SBC or OCI in this simplified scenario. D&A is included in operating costs and added back only in CFO.

## Findings
Projected closing cash is $137.98bn. The balance sheet balances to numerical precision, with retained earnings linked to net income and dividends.

- Scenario revenue $436.29bn
- Scenario closing cash $137.98bn
- Balance check $0m

## Interpretation and limits
This is an analyst scenario, not Apple guidance. Omitting buybacks and other financing means it cannot be interpreted as a likely cash balance. Public filing aggregates constrain operating detail.

See [computed results](results.csv). Reproduce with `node analysis.mjs` from the repository root. This is an independent, AI-assisted portfolio case study, not employment experience or a company-issued forecast.
