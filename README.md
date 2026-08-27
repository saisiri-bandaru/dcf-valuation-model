# DCF valuation model

Unlevered DCF for a fictional CPG company (**Northline Consumer Products**): free cash flow build, WACC, Gordon-growth terminal value, equity bridge, NPV and IRR.

**File to open:** `Northline_DCF_Valuation_Model.xlsx`

## What you will see

- Five-year revenue → EBITDA → NOPAT → unlevered FCF build
- CAPM cost of equity, after-tax cost of debt, and WACC
- Enterprise value from discounted FCFs + terminal value
- Equity value (EV − net debt) and value per share
- IRR on (−EV, FCF₁…FCF₄, FCF₅+TV)
- A WACC × terminal-growth sensitivity grid on equity value

Yellow cells with blue font are inputs. Black font is formulas.

## How to use

1. Open `01_Assumptions` and change the yellow cells (growth, margins, WACC inputs, g, net debt).
2. Read `02_FCF_Build` for the cash-flow bridge.
3. Confirm WACC on `03_WACC`.
4. Read enterprise value, equity value, NPV, and IRR on `04_Valuation`.
5. Stress the case on `05_Sensitivity`.

## Tabs

| Tab | Role |
| --- | --- |
| `00_Cover` | Purpose and how to use |
| `01_Assumptions` | Forecast drivers, WACC inputs, terminal g, net debt |
| `02_FCF_Build` | Unlevered free cash flow |
| `03_WACC` | CAPM and capital-structure blend |
| `04_Valuation` | Discounting, TV, EV, equity value, IRR |
| `05_Sensitivity` | Equity value vs WACC and g |
| `06_Data_Dictionary` | Field definitions |

## Stack

Excel (formulas only — no VBA). Built so another analyst can inherit the file from the data dictionary.

## Not included on purpose

- Live market prices or ticker pulls
- Confidential employer data
- A full three-statement LBO or football-field (this is the *unlevered DCF*)

All sample numbers are fictional.

## Profile

Sai Siri Bandaru — Financial Analyst | FP&A | forecasting, variance analysis, Excel
