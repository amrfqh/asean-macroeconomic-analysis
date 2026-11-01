# ASEAN Macroeconomic Analysis (2000–2024)

## Project Overview

This project examines macroeconomic trends across five Southeast Asian economies — Indonesia, Malaysia, Singapore, Thailand and Viet Nam — from 2000 to 2024.

Using annual data from the World Bank's World Development Indicators (WDI), the analysis explores economic growth, inflation, unemployment, exchange-rate movements and foreign direct investment (FDI).

The objective is to identify differences in macroeconomic performance, examine how these indicators evolved during major economic disruptions, and explore relationships between selected macroeconomic variables.

## Research Questions

1. How did real GDP growth evolve across the five economies between 2000 and 2024?
2. How did inflation and unemployment trends differ across countries?
3. How did exchange rates move against the US dollar, particularly between 2019 and 2024?
4. How did FDI inflows as a share of GDP change over time?
5. What relationships can be observed between selected macroeconomic indicators?

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
| Unemployment | `SL.UEM.TOTL.ZS` | Unemployment as a percentage of the labour force |
| Exchange Rate | `PA.NUS.FCRF` | Local currency units per US dollar |
| FDI | `BX.KLT.DINV.WD.GD.ZS` | Net FDI inflows as a percentage of GDP |

## Methodology

The analysis was conducted using Python in Google Colab.

1. Retrieved annual macroeconomic indicators through the World Bank API.
2. Cleaned and organised the data using Pandas.
3. Reshaped the dataset for cross-country and time-series analysis.
4. Calculated descriptive statistics and year-on-year changes.
5. Constructed an exchange-rate index (2019 = 100) to compare currency movements.
6. Reconstructed a GDP growth index (2019 = 100) to examine cumulative changes in real GDP implied by annual growth rates.
7. Compared FDI-to-GDP ratios across pre-pandemic (2000–2019) and post-2019 (2020–2024) periods.
8. Explored correlations between selected macroeconomic indicators.
9. Created visualisations using Matplotlib.

The
