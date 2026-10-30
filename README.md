# financial-planning-and-modeling

Revenue Forecast & Variance Review · Integrated Three-Statement Model

Independent, AI-assisted portfolio research using traceable public historical inputs. Real observations and analyst-created scenarios are labelled separately.

## Projects
- [Revenue Forecast & Variance Review](projects/rolling-forecast/README.md) — FP&A · Budgeting · Management reporting
- [Integrated Three-Statement Model](projects/three-statement-model/README.md) — Corporate finance · Financial modelling

## Reproduce
Requires Node.js 22 or later; no third-party packages. Run `node analysis.mjs`. Frozen inputs are included under data/. Calculated outputs are in projects/. Raw source documentation and assumptions are in each project README.

## Data provenance
Apple FY2025 10-K: https://www.sec.gov/Archives/edgar/data/320193/000032019325000079/aapl-20250927.htm, pp. 29, 31, 33. Financial statement facts manually transcribed in USD millions; FY2023–2025. Forecasts, budgets and investment parameters are analyst assumptions.

Retrieved 2026-10-30. Upstream data remain subject to their source terms; no ownership of source data is claimed.

## Checks
The script checks date alignment, valid observations, risk contribution totals, a standard option-pricing reference value and the projected balance-sheet equation.
