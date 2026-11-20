# environmental-tax-revenue-co2
Data and code for "Environmental Tax Revenue and CO2 Emissions: Tax Base or Policy? Machine Learning Evidence from 125 Countries"
# Environmental Tax Revenue and CO₂ Emissions: Tax Base or Policy?

Replication files for the paper "Environmental Tax Revenue and CO₂ Emissions:
Tax Base or Policy? Machine Learning Evidence from 125 Countries"
by Khawaja Muhammad Ali (Applied Economics Research Centre, University of Karachi).

## Files

| File | What it is |
|---|---|
| `Causal_CO2_ET_Data_File.xlsx` | Country-year panel, 2000–2023 (sheet `Panel_Format`) |
| `Python_Script_Latest_20-11-2026_.ipynb` | Jupyter notebook with all estimations |
| `estimation_sample.pkl` | Estimation sample saved by the first script (2,700 observations, 125 countries) |

## Data sources

- Environmental tax revenue (% of GDP): OECD
- All other variables: World Bank World Development Indicators
- Governance indicators: Worldwide Governance Indicators

## How to run

1. Install the libraries: `pip install doubleml xgboost econml statsmodels openpyxl`
2. Put the data file and the notebook in one folder.
3. Set `DIRECTORY` at the top of each cell to that folder.
4. Run the cells in order. The first script creates `estimation_sample.pkl`,
   which the later cells load.

## Contact

Khawaja Muhammad Ali — khwajaali@aerc.edu.pk
