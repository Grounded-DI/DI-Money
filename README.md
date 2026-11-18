# DI-Money — FinanceWise Demonstrations and Reports

## Overview

The 2025 FinanceWise and DI-Money archive contains an architecture note, a simulated checking-account analysis, retail optimization results, a Q4 finance forecast, and visual records. The documents report the calculations and projections shown below.

## FinanceWise architecture note — 2025-08-15

[FinanceWise_DI2_Flagship_8-15-25.md](FinanceWise_DI2_Flagship_8-15-25.md) describes FinanceWise as a deterministic financial-analysis system built on DI2, AGDI, and DIA. It names a risk-audit engine using entropy-tier scoring and a market-signal interpreter for CPI, earnings, or headline inputs. The note describes scroll-linked outputs at ΔH = 0.03, a one-input/one-output rule, authorship trace, ScrollGlow 1–137, Vault-linked identity at Scroll 106, and a no-override posture.

The architecture note describes the control design. This archive publishes the note and resulting documents for review.

## Consumer checking simulation — 2025-08-04

[Invisible_Yield_Checking_Demo.md](Invisible_Yield_Checking_Demo.md) is a generic, simulated $0-fee checking account analysis, not a named bank account. The scenario uses a $100 minimum balance, no interest, and fee drift beginning at month 12 through paper-statement and overdraft fees. It reports:

- Average balance after 24 months: **$73.75**
- Total structural fees: **$227.40**
- Annualized true-yield loss: **−154.17%**

The source discusses maintenance fees below the $100 threshold, hold mismatch, and clause drift. The figures are the result recorded in this scenario; it is not a production account history.

## Retail optimization records — 2025-08-14

The dated report is [Retail_Optimization_Report_8-14-25.md](Retail_Optimization_Report_8-14-25.md), accompanied by [README_Retail_Optimization_Report_8-14-25.md](README_Retail_Optimization_Report_8-14-25.md). The report gives a retail stability score of **89/100**, a drift-warning threshold above 0.10, and the following segment record:

| Segment | Drift | Tier | Trust score |
| --- | ---: | --- | ---: |
| Grocery | 0.02 | High | 96 |
| Electronics | 0.06 | Medium | 84 |
| Household durable | 0.07 | Medium-High | 81 |
| Seasonal apparel | 0.10 | Low | 70 |
| Tools/DIY | 0.03 | High | 93 |

Its Tiered Pack Modeling formula is **Pₙ = P₁(1 − μ)ⁿ⁻¹**, with **μ ≈ 0.08** for essentials. The report records ΔH = 0.02 and a **7.2% average margin increase** in Q2 test regions; it projects a **+4.1 trust-score increase**. The repository does not include the source retail dataset or test-region data.

## Q4 finance forecast — dated 2025-09-15

The extensionless [Q4_Finance_Report](Q4_Finance_Report) is a forecast record, not a current market update. It lists core inflation at 2.6%, housing up 5.4% year over year, and compression between 3-month Treasury bill and 10-year bond yields. It reports forecast horizons and metrics including:

| Forecast horizon | Record in the report |
| --- | --- |
| 3 months | ΔH ≈ 0.14; certainty 92 |
| 6 months — rent | ΔH ≈ 0.26; certainty 76 |
| 12 months — crypto/high risk | ΔH ≈ 0.17; certainty 85 |
| Safe-sector composite | Certainty 90; ΔH ≈ 0.18–0.28 |

The forecast inputs and calculation series are not included in the repository, so these remain the report’s dated forecasts rather than regenerated figures or present-day recommendations.

## Captures, license, and how to review

The archive also preserves visual captures [IMG_4017.png](IMG_4017.png), [IMG_6332.png](IMG_6332.png), and [IMG_6333.png](IMG_6333.png).

The repository’s LICENSE_DI-Money.txt states educational/evaluative use with attribution and requires a license for commercial/API use. See that file for its complete terms.

Start with the dated source documents above. The previous README pointed to financewise_demo.ipynb, outputs/, metadata/, and Retail_Optimization_Report.md; none of those paths is present. The corresponding records available here are the Markdown files, extensionless Q4_Finance_Report, license text, and three PNG captures.