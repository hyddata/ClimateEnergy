# Climate Extremes and Energy Market Vulnerability  
### Oil & Gas Price Fluctuations in Qatar

This repository contains an exploratory analysis investigating relationships between **climate extremes** and **energy market behavior** with a focus on Qatar. The notebook uses observational and climate-model data (including CMIP6) together with global energy price series (Brent) to perform descriptive analysis, visualizations, and bias-correction of climate model outputs.

## Objectives
- Process and visualize climate observations and **CMIP6** model outputs.
- Apply bias-correction to CMIP6 variables.
- Compare climate indicators with oil & gas prices.
- Perform simple correlations and lagged inspection.
- This project includes only a simple statistical forecast based on 5-year event frequency trends.

## Content
- CMIP6 ingestion via xarray/netCDF.
- Bias correction routines.
- yfinance Brent price download.
- Time-series and anomaly computation.
- Plots and rolling correlations.
- No ML — ML is only in future work.

## Future Improvements
- ML forecasting

If you use this code or analysis, please cite it as:

Zare, M. (2025). Climate Extremes and Energy Market Vulnerability: Analysis for Qatar. 
GitHub repository. https://github.com/hyddata/ClimateEnergy

