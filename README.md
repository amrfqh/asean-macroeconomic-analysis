# ASEAN Macroeconomic Analysis (2000–2024)

## Project Overview

This project examines macroeconomic trends across five Southeast Asian economies — Indonesia, Malaysia, Singapore, Thailand and Viet Nam — from 2000 to 2024.

Using annual data from the World Bank's World Development Indicators (WDI), the analysis explores economic growth, inflation, unemployment, exchange-rate movements and foreign direct investment (FDI).

The objective is to identify differences in macroeconomic performance, examine how these indicators evolved during major economic disruptions, and explore relationships between selected economic variables.

## Research Questions

1. How did real GDP growth evolve across the five economies between 2000 and 2024?
2. How did inflation and unemployment trends differ across countries?
3. How did exchange rates move against the US dollar, particularly between 2019 and 2024?
4. How did FDI inflows as a share of GDP change over time?
5. What relationships can be observed between macroeconomic indicators?

## Countries Covered

- Indonesia
- Malaysia
- Singapore
- Thailand
- Viet Nam

## Data Sources

**Source:** [World Bank – World Development Indicators](https://databank.worldbank.org/source/world-development-indicators)

| Indicator | World Bank Indicator Code | Measurement |
|---|---|---|
| GDP Growth | `NY.GDP.MKTP.KD.ZG` | Annual real GDP growth (%) |
| Inflation | `FP.CPI.TOTL.ZG` | Annual consumer price inflation (%) |
| Unemployment | `SL.UEM.TOTL.ZS` | Unemployment as % of labour force |
| Exchange Rate | `PA.NUS.FCRF` | Local currency units per US dollar |
| FDI | `BX.KLT.DINV.WD.GD.ZS` | Net FDI inflows as % of GDP |

## Methodology

The analysis was conducted using Python in Google Colab.

1. Retrieving annual macroeconomic indicators through the World Bank API.
2. Cleaning and organising the data using Pandas.
3. Reshaping the dataset for cross-country and time-series analysis.
4. Calculating descriptive statistics and year-on-year changes.
5. Constructing an exchange-rate index (2019 = 100) for comparison.
6. Reconstructing a GDP growth index (2019 = 100) to examine post-2020 recovery.
7. Comparing FDI-to-GDP ratios across pre-pandemic and post-2019 periods.
8. Exploring correlations between selected macroeconomic indicators.
9. Creating visualisations using Matplotlib.

## Key Findings

*To be completed with the final quantitative findings and supporting visualisations.*

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- World Bank API

## Limitations

- The analysis uses annual observations, which may not capture short-term economic fluctuations.
- Correlation analysis identifies associations, not causal relationships.
- Cross-country comparisons may be affected by differences in economic structures and statistical methodologies.
- Unemployment estimates should be interpreted with consideration of differences in labour-market conditions and measurement.
- FDI expressed as a percentage of GDP reflects both changes in FDI and changes in GDP.
- The GDP recovery index is reconstructed from annual real GDP growth rates and should not be interpreted as a separately observed GDP-level series.

## Author

Independent macroeconomic data analysis project focused on ASEAN economies, developed using Python and publicly available World Bank data.
