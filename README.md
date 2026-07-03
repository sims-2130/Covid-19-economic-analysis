# Covid-19-economic-analysis
Macroeconomic analysis and SARIMAX policy simulations tracking pandemic-era structural breaks in Sri Lanka. Implemented in Python via statsmodels using an exogenous Lockdown Stringency Index to isolate policy shocks. Optimized to a Mean Absolute Error (MAE) of 2.47 to evaluate index trends and alternative regulatory scenarios.
# Sri Lanka Macroeconomic Pandemic Analysis & Policy Simulation

An econometric time-series analysis framework designed to isolate structural breaks, measure volatility, and run counterfactual policy simulations tracking pandemic-era economic indicators in Sri Lanka.

##  Architecture & Tools
* **Development Environment:** 

Google Colab Cloud Resources


* **Programming Language:** Python 3
* **Core Frameworks:** `statsmodels` (SARIMAX implementation), `scikit-learn`
* **Data Processing & Analytics:** `pandas`, `NumPy`
* **Data Visualization:** `matplotlib`

##  Methodology & Pipeline
1. **Exploratory Data Analysis:** Profiled structural breaks corresponding to core pandemic restriction windows using historical baseline trend mapping.
2. **Stationarity Verification:** Evaluated sequential dependencies using the Augmented Dickey-Fuller (ADF) test. Implemented first-order differencing to stabilize non-stationary variance scales across macro indicators.
3. **Exogenous Feature Integration:** Incorporated a dynamic, time-aligned Lockdown Stringency Index to cleanly isolate regulatory intervention shocks from baseline market contraction patterns.
4. **Counterfactual Policy Simulations:** Engineered a parallel evaluation pipeline passing a 50% modified policy index during out-of-sample forecasting windows to quantify cumulative index variations under alternative regulatory scenarios.

##  Operational Validation Metrics
* **Mean Absolute Error (MAE):** 2.47 index points
* **Root Mean Squared Error (RMSE):** 2.98 index points
* **Statistical Insights:** The narrow gap between MAE and RMSE values confirms a highly stable error distribution, demonstrating that the SARIMAX architecture successfully resisted volatile outlier variance during severe macroeconomic shocks.

