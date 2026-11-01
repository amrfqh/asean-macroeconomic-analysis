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

The analysis uses annual observations from 2000 to 2024. Data-processing steps, calculations and visualisations are documented in the Jupyter notebook included in this repository.

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
- During 2020, Viet Nam was the only economy among the five countries to maintain positive real GDP growth, at approximately 2.87%.
- By 2024, Viet Nam's reconstructed real GDP growth index (2019 = 100) had reached approximately 128.66, compared with 103.04 for Thailand.

### 2. Inflation Trends

- Indonesia and Viet Nam recorded the highest average inflation rates over the study period, at approximately 5.82% and 5.70%, respectively.
- Viet Nam experienced the highest annual inflation rate in the dataset, reaching approximately 23.12% in 2008.
- In 2022, inflation increased across the selected economies, with Singapore recording approximately 6.13% and Thailand approximately 6.08%.

### 3. Exchange-Rate Movements

Between 2019 and 2024, the annual-average exchange-rate index (2019 = 100) showed the following changes:

- Thailand: 13.68% increase.
- Indonesia: 12.07% increase.
- Malaysia: 10.48% increase.
- Viet Nam: 4.84% increase.
- Singapore: 2.05% decrease.

An increase in the index indicates that more units of local currency were required to purchase one US dollar, representing nominal depreciation against the US dollar. Conversely, Singapore's decrease indicates nominal appreciation over the comparison period.

These figures are based on annual-average exchange rates and do not capture intra-year currency fluctuations.

### 4. Foreign Direct Investment

- Singapore recorded the highest average net FDI inflows relative to GDP, at approximately 20.95% between 2000 and 2024.
- Viet Nam recorded an average of 4.81%, followed by Malaysia at 3.24%, Thailand at 2.57% and Indonesia at 1.37%.
- Comparing the 2000–2019 and 2020–2024 periods, Singapore's average FDI-to-GDP ratio increased by approximately 6.57 percentage points, while Thailand's declined by approximately 0.90 percentage points.

Singapore's relatively high FDI-to-GDP ratio reflects its position as a major international investment hub. However, the ratio should not be interpreted as a direct comparison of absolute FDI inflows between countries.

### 5. Relationships Between Macroeconomic Indicators

- The pooled correlation between inflation and the exchange-rate level was approximately +0.42.
- Country-level analysis showed variation in the relationship between GDP growth and FDI-to-GDP ratios.
- Year-on-year changes in FDI-to-GDP ratios were positively correlated with GDP growth in all five economies, with correlation coefficients ranging from approximately +0.14 in Indonesia to +0.42 in Thailand.

These correlations are exploratory and do not establish causal relationships. Pooled correlations may also reflect differences between countries rather than relationships occurring within individual economies over time.

## Limitations

- The analysis uses annual observations, which may not capture short-term economic fluctuations.
- Correlation analysis identifies statistical associations, not causal relationships.
- Cross-country comparisons may be affected by differences in economic structures and statistical methodologies.
- Unemployment estimates should be interpreted with consideration of differences in labour-market conditions, informal employment and measurement methodologies.
- FDI expressed as a percentage of GDP reflects changes in both FDI inflows and GDP.
- The GDP recovery index is reconstructed from annual real GDP growth rates using 2019 as the base year. It represents cumulative changes implied by the growth rates and is not a separately observed GDP-level series.
- The analysis is descriptive and does not control for other macroeconomic factors that may influence the observed relationships.

## Author

Independent macroeconomic data analysis project focused on ASEAN economies, developed using Python and publicly available World Bank data.
