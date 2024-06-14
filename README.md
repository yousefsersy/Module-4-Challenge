# Portfolio Performance Analysis and Custom Portfolio Creation

## Overview

This project aims to analyze and compare the performance of various portfolios, including algorithmic trading strategies, famous whale investors' portfolios, and major hedge and mutual funds, against the S&P 500 Index. The objective is to determine which portfolio performs the best across several metrics such as volatility, returns, risk, and Sharpe ratios. Additionally, a custom portfolio is created and compared against the other portfolios and the S&P 500.

## Project Structure

1. Prepare the Data

* Read and Clean Data:

  * Imported data from whale_returns.csv, algo_returns.csv, and sp500_history.csv.

  * Converted dates to a DateTimeIndex.

  * Cleaned data by removing null values and non-numeric values.
    
  * Converted S&P 500 closing prices to daily returns.

* Data Integration:
  
  * Merged whale, algorithmic, and S&P 500 returns into a single DataFrame for comprehensive analysis.

2. Perform Quantitative Analysis

    **Performance Analysis**

* Calculated and plotted daily returns for all portfolios.
  
* Calculated and plotted cumulative returns to determine if any portfolio outperforms the S&P 500.
  
    **Risk Analysis**

* Created box plots for each portfolio's returns.
  
* Calculated the standard deviation for each portfolio to assess risk.
  
* Compared the portfolios' risks to the S&P 500.
  
* Calculated annualized standard deviations.

    **Rolling Statistics**

* Computed and plotted the rolling standard deviation using a 21-day window.
  
* Analyzed correlations between each portfolio and the S&P 500.
  
* Calculated and plotted the 60-day rolling beta for selected portfolios.

    **Sharpe Ratios**

* Calculated daily Sharpe ratios for all portfolios.
  
* Visualized Sharpe ratios in a bar plot to compare performance.

* Determined if algorithmic strategies outperform the market and whale portfolios.

3. Create a Custom Portfolio
   
* Selected 3-5 stocks using Google Sheets' GOOGLEFINANCE function.

* Downloaded and calculated portfolio returns from CSV files.
  
* Assumed equal shares per stock and calculated weighted returns.
  
* Integrated custom portfolio returns into the main DataFrame.
  
    **Custom Portfolio Analysis**

* Calculated annualized standard deviation.

* Computed and plotted rolling standard deviation with a 21-day window.

* Analyzed and plotted correlation with other portfolios.

* Calculated and plotted the beta of the custom portfolio against the S&P 500.

* Calculated Sharpe ratios and visualized them in a bar plot to compare performance.

# Conclusion

The analysis helps determine which portfolios outperform the S&P 500 based on various metrics.
Custom portfolio performance is assessed and compared against established portfolios and the market.
Provides insights into risk-adjusted returns, aiding investment managers in making informed decisions.

# Resources

* Pandas API documentation
* Exponential weighted function in Pandas
* GOOGLEFINANCE function help
* Fetching Stock Data Using Google Sheets

# Key Technologies and Libraries

* Python
* Pandas
* NumPy
* Seaborn


This analysis notebook serves as a comprehensive tool for evaluating portfolio performance, risk, and returns, providing a robust framework for quantitative investment analysis.
