# Stock-analysis-Tesla-

This repository contains a short financial analysis project built with Python and Pandas.
It demonstrates how to retrieve stock price data, compute basic indicators, and analyze volatility.

For **security reasons**, the API key used to download the data has been removed from the notebook.
Anyone reviewing the project will need to _**insert their own API key**_ if they wish to re-run the data retrieval cells.



# Stock Analysis – Assignment
Project Overview

This mini-project aims to introduce the student to basic financial time-series analysis using Python, Pandas, and Matplotlib.
The task consists of retrieving historical stock price data, computing simple indicators, visualizing trends, and interpreting the main patterns observed in the data.

# Objectives

Load and structure financial time-series data.
Compute essential analytical metrics (daily returns, moving averages).
Produce clear visualizations to support interpretation.
Identify and quantify high-volatility periods.
Formulate a concise analytical conclusion.

# Tasks
## 1. Data Retrieval

Retrieve historical daily price data for a publicly traded company using an external API.
Store the information in a Pandas DataFrame with a properly formatted datetime index.

## 2. Data Preparation

Compute the following indicators:
Daily returns (returns)
20-day moving average (MA20)
Clean the dataset if necessary (handling missing values, formatting issues).

## 3. Visualization

Produce a figure displaying:
the closing price of the asset
the 20-day moving average
The plot must clearly illustrate the general price trend and the smoothing effect of the moving average.

## 4. Volatility Analysis

Compute the absolute value of daily returns and sort the dataset by this measure to identify the most volatile days.
Report the dates and magnitudes of the largest positive and negative variations.

## 5. Conclusion

Write a short, structured interpretation summarizing:
the main trends observed in the price evolution
the usefulness of the MA20 in identifying trend changes
the key periods of volatility revealed by the numerical analysis

# Expected Output

A Jupyter Notebook (stock_analysis.ipynb) containing all code, figures, and written commentary.
Clean, readable, and properly structured code cells.
A final conclusion summarizing the analytical insights obtained from the dataset.
