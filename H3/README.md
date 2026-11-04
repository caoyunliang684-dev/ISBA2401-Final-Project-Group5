# H3 Initial Findings

Food inflation and gender differences in food insecurity, using pandas and matplotlib.pyplot. The English notebook contains 19 chapters with explanations, executed tables and charts.

## Read and run

Open [the English notebook](H3_Initial_Findings_English.ipynb) to view the analysis on GitHub.

To run locally, download [the complete package](H3_Initial_Findings_English.zip), extract the entire ZIP, and open the notebook in Jupyter through Anaconda Navigator. Keep the included data folder beside the notebook and run cells from top to bottom. pandas uses openpyxl to read Excel.

## Data and interpretation

The package includes the supplied FAOSTAT Food Security CSV, World Bank OGHIST workbook, and FAOSTAT Consumer Price Indices CSV. Food_CPI.csv is the original CPI CSV with a shorter filename. CPI source https://www.fao.org/faostat/en/#data/CP

Periods are 2014–2016, 2017–2019 and 2020–2022. Annual inflation is the percentage change in annual-average Food CPI. All 12 months and all three annual rates are required.

The matched sample has 360 country-periods from 147 countries or economies. Adjacent-period comparisons use 212 observations from 117 countries. These descriptive initial findings show mixed patterns across periods and may be sensitive to extreme observations. Statistical significance and causal effects are not established.
