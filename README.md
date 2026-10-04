# DataStorm: Who Is Nigeria's 2026 Budget Really For?

A group data project (DataStorm Analytics, Group 10) analysing Nigeria's 2026 federal budget: where the money goes, the debt burden, and the reliability of revenue projections. Completed during the HNG Internship May 2026.

> **Note:** This is an early project, kept close to the original version to show my starting point. See "Limitations".

## Team
**My role:** I worked on the Power BI dashboard.

## Deliverables
- `dashboard/`: 3-page Power BI dashboard (The Choice, The Debt Shadow, The Credibility Gap)
- `presentation/`: 8-slide deck
- `report/`: broadcast-style analytical story
- `data/`: budget tables, debt files, CPI and analysis questions

## Key findings
- Total 2026 budget: N58.47tn; debt service N15.91tn (27.2%)
- Debt service is 6.2x education and 6.5x health, and 3.17x the two combined
- Debt service rose 323% from 2022 to 2026 (2025-26 are budgeted figures)
- 63.86% of debt service is domestic debt, 33.69% foreign
- Revenue targets were missed in 8 of 9 years (2025 is as at June only)

## Sources
Budget Office of the Federation, BudgIT, Debt Management Office (DMO), National Bureau of Statistics (NBS)

## Limitations (and what I'd do differently)
- UNESCO's benchmark is 15-20% of public expenditure (not 15-26%) and covers all levels of government, not only the federal budget.
- Statutory transfers may include basic-education funding, so education may be understated.
- The N23.85tn deficit figure does not match the data (58.47 - 33.19 = 25.28). The N20tn revenue scenario is based on the median historical achievement rate (about 61%).
- 2025 revenue is a half-year figure but is treated as a full year in the dashboard.
- Food inflation peaked at 40.87% (June 2024) in the CPI file, which also mislabels 2024 months as 2023.
- Part of the N25tn debt rise is naira revaluation of foreign debt, not new borrowing.
- The sector table mixes budget categories and overlapping sectors, so its percentages sum to more than 100%.
- Some data files have formatting errors (duplicate header, corrupted cell, one typo in summary_usd).

## Author
Rukky Ujara | https://www.linkedin.com/in/rhukhi/ | rukkyujara@gmail.com
