
## Project Overview
This project investigates the relationship between the price stability of Gold and the volatility of Cryptocurrencies (Bitcoin and FTX) from 2019 to 2024. The analysis combines statistical hypothesis testing with machine learning to determine if gold price fluctuations can predict cryptocurrency market trends.

## Key Features
*   **Data Integration:** Merged multiple datasets including US Stock Market data and historical exchange records for Bitcoin and FTX.
*   **Hypothesis Testing:** Conducted Pearson correlation analysis, resulting in p-values < 0.05, leading to the rejection of the null hypothesis and confirming a significant correlation between gold and crypto assets.
*   **Predictive Modeling:** Developed and evaluated multiple regression models:
    *   **Linear Regression:** Established baseline trends for gold vs. bitcoin.
    *   **K-Nearest Neighbors (KNN):** Optimized via GridSearchCV, emerging as the top-performing model.
    *   **Decision Tree Regressor:** Tested for non-linear predictive capabilities.
*   **Visual Analytics:** Created advanced comparative visualizations, including scaled time-series plots and distribution histograms.

## Tech Stack
*   **Language:** Python
*   **ML Libraries:** Scikit-Learn 
*   **Analysis:** Pandas, NumPy, SciPy, Statsmodels
*   **Visualization:** Matplotlib
