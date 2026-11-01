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


## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- World Bank API
  
## Key Findings

### 1. Economic Growth and Recovery

- Viet Nam recorded the highest average real GDP growth between 2000 and 2024, at approximately 6.33%.
- During 2020, Viet Nam was the only economy among the five countries to maintain positive GDP growth, at 2.87%.
- By 2024, Viet Nam's reconstructed real GDP growth index (2019 = 100) had reached approximately 128.66, compared with 103.04 for Thailand.

### 2. Inflation Trends

- Indonesia and Viet Nam recorded the highest average inflation rates over the study period, at approximately 5.82% and 5.70%, respectively.
- Viet Nam experienced the highest annual inflation rate in the dataset, reaching approximately 23.12% in 2008.
- In 2022, inflation increased across the selected economies, with Singapore recording approximately 6.13% and Thailand 6.08%.

### 3. Exchange-Rate Movements

Between 2019 and 2024, the annual-average exchange-rate index (2019 = 100) showed:

- Thailand: 13.68% increase in local currency units per USD.
- Indonesia: 12.07% increase.
- Malaysia: 10.48% increase.
- Viet Nam: 4.84% increase.
- Singapore: 2.05% decrease.

These results indicate relative depreciation against the US dollar for the first four currencies and relative appreciation for the Singapore dollar over this comparison period.

### 4. Foreign Direct Investment

- Singapore recorded the highest average net FDI inflows relative to GDP, at approximately 20.95% between 2000 and 2024.
- Viet Nam recorded an average of 4.81%, followed by Malaysia at 3.24%, Thailand at 2.57% and Indonesia at 1.37%.
- Between the 2000–2019 and 2020–2024 periods, Singapore's average FDI-to-GDP ratio increased by approximately 6.57 percentage points, while Thailand's declined by approximately 0.90 percentage points.

### 5. Relationships Between Macroeconomic Indicators

- The pooled correlation between inflation and the exchange-rate level was approximately +0.42.
- Country-level analysis showed variation in the relationship between GDP growth and FDI-to-GDP ratios.
- Year-on-year changes in FDI-to-GDP ratios were positively correlated with GDP growth in all five economies, with correlations ranging from approximately +0.14 in Indonesia to +0.42 in Thailand.

These correlations are exploratory and do not establish causal relationships.

## Limitations

- The analysis uses annual observations, which may not capture short-term economic fluctuations.
- Correlation analysis identifies associations, not causal relationships.
- Cross-country comparisons may be affected by differences in economic structures and statistical methodologies.
- Unemployment estimates should be interpreted with consideration of differences in labour-market conditions and measurement.
- FDI expressed as a percentage of GDP reflects both changes in FDI and changes in GDP.
- The GDP recovery index is reconstructed from annual real GDP growth rates and should not be interpreted as a separately observed GDP-level series.

## Author

Independent macroeconomic data analysis project focused on ASEAN economies, developed using Python and publicly available World Bank data.
