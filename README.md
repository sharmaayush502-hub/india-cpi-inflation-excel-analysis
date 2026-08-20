# india-cpi-inflation-excel-analysis
Excel analysis of India CPI inflation trends, food prices, COVID impact, and oil-price linkage.
# India CPI Inflation Analysis Dashboard

## Project Overview

This project analyzes monthly Consumer Price Index (CPI) data for India using Microsoft Excel. The analysis covers rural, urban, and combined consumer data across food, energy, transport, health, housing, education, personal care, and other categories.

The project focuses on inflation trends, broader-category contribution, food inflation, COVID-19 impact, and the relationship between fuel movements and category-level inflation.

## Tools Used

- Microsoft Excel
- PivotTables
- Excel formulas
- Data cleaning
- Charts and dashboards
- Year-over-year analysis
- Month-over-month analysis
- Correlation analysis

## Analysis Covered

- Broader CPI category contribution using equal-weight assumptions.
- Year-over-year CPI inflation trends from 2017 onward.
- Identification of the peak average inflation year.
- Food inflation trends for the 12 months ending May 2023.
- Month-over-month food inflation changes.
- COVID-19 impact using March 2020 as the benchmark.
- Relationship between Fuel and Light movements and other CPI categories during 2021–2023.

## Broader Categories

The detailed CPI categories were grouped into broader buckets:

- Food
- Pan, Tobacco and Intoxicants
- Clothing
- Housing
- Energy
- Household
- Health
- Transport
- Education and Recreation
- Personal Care
- Miscellaneous

The assignment required equal weights for the broader buckets. Therefore, the contribution analysis uses an equal-weight assumption and does not represent official CPI expenditure weights.

## Key Findings

- Latest month analyzed: May 2023.
- Highest broader-bucket contribution in the workbook: Pan, Tobacco and Intoxicants.
- Highest average inflation year in the workbook analysis: 2022.
- Strongest relationship with the Fuel and Light proxy: Transport.
- COVID-19 benchmark month: March 2020.

## Methodology

### Year-over-Year Inflation

```text
((Current Month CPI - CPI in the Same Month of the Previous Year)
 / CPI in the Same Month of the Previous Year) × 100
```

### Month-over-Month Change

```text
((Current Month CPI - Previous Month CPI)
 / CPI in the Previous Month) × 100
```

### COVID-19 Analysis

March 2020 was used as the COVID-19 and first-lockdown benchmark. Inflation patterns before and after this month were compared for food, health, essential services, and the overall index.

### Oil-Price Linkage

The workbook does not contain a separate imported crude-oil price series. Therefore, the Fuel and Light category was used as a proxy for oil-price movements. Correlation analysis was performed using monthly movements during 2021–2023.

## Limitations

- Equal weights were used as required by the assignment; official CPI weights were not used.
- CPI index values should not be summed across months.
- Fuel and Light was used as a proxy because a separate crude-oil series was unavailable.
- Correlation shows association and does not prove causation.
- Missing values and pandemic-period data availability may affect comparisons.

## Files

- `India_CPI_Inflation_Analysis.xlsx` — Excel workbook containing the analysis and dashboard.
- `screenshots/` — Dashboard and visualization screenshots.

## Data Source

Government of India CPI dataset supplied with the case study.
