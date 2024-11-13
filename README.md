# FAANG Stock Performance and Risk Analysis

This project provides a comprehensive risk and return analysis of FAANG companies—Facebook (Meta), Amazon, Apple, Netflix, and Google (Alphabet)—using historical stock data and Python's data science libraries. By leveraging both traditional risk measures and predictive simulations, this analysis offers insights into each stock's performance and potential future behavior to aid in informed investment decisions.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Collection](#data-collection)
3. [Analysis and Metrics](#analysis-and-metrics)
4. [Risk Assessment](#risk-assessment)
5. [Visualizations](#visualizations)
6. [How to Run the Project](#how-to-run-the-project)
7. [Technologies Used](#technologies-used)
8. [Results Summary](#results-summary)

---

## Project Overview
The goal of this project is to evaluate the FAANG stock performance over the past year by analyzing price changes, technical indicators, and daily returns. It integrates quantitative methods to assess investment risk and uses Monte Carlo simulations to generate probabilistic future price scenarios. Key objectives include:
- Calculating daily returns and moving averages for each stock.
- Estimating risk metrics such as volatility, Value-at-Risk (VaR), and potential future performance using simulations.
- Comparing inter-stock correlations and overall risk for better portfolio decision-making.

## Data Collection
The dataset comprises historical daily price data for the FAANG companies, retrieved from Yahoo Finance using the `yfinance` Python library. Key focus is on:
- **Adjusted Closing Prices**: These prices account for splits and dividends, ensuring accurate performance comparison.
- **Timeframe**: Analysis is based on the previous 365 days to capture recent trends and volatility.

## Analysis and Metrics
The project includes the following analyses and technical indicators:
1. **Moving Averages**: Simple moving averages (50-day and 200-day) highlight trends and long-term performance.
2. **Daily Returns**: Daily return percentages reveal short-term price changes, volatility, and return distribution.
3. **Correlation Analysis**: A correlation matrix and heatmap illustrate how each stock's returns relate to the others, useful for portfolio diversification.

## Risk Assessment
Several risk assessment techniques are applied:
1. **Volatility (Standard Deviation)**: Measures each stock's price fluctuation, indicating risk level.
2. **Value-at-Risk (VaR)**: Quantifies potential loss in a specific time period at a given confidence level, providing insight into downside risk.
3. **Monte Carlo Simulations**: Thousands of simulated price paths estimate potential future returns, highlighting possible gains and losses under different scenarios.

## Visualizations
Key visualizations are generated to communicate findings:
- **Time Series Plots**: Show price changes and moving averages over time for each stock.
- **Daily Return Distributions**: Histograms and kernel density plots reveal the shape and spread of returns.
- **Correlation Heatmap**: Displays the correlation between stocks, aiding in identifying diversification opportunities.
- **Monte Carlo Simulation Output**: Illustrates potential future price ranges based on simulated scenarios.

## How to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourGithub/FAANG_Stock_Analysis.git
Install Required Libraries:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook: Launch the notebook to explore the analysis and visualizations:
bash
Copy code
jupyter notebook FAANG_Stock_Analysis.ipynb
Technologies Used
Programming Language: Python
Libraries:
pandas for data manipulation and cleaning.
yfinance for stock data retrieval.
matplotlib and seaborn for data visualization.
numpy for numerical operations and Monte Carlo simulations.
Results Summary
This project provides insight into the relative performance and risk associated with FAANG stocks. Key findings include:

Amazon and Netflix exhibit higher volatility compared to Apple and Google.
Correlations between stocks vary, offering diversification potential for portfolios.
Monte Carlo simulations suggest possible price ranges under different future scenarios, helping in risk-adjusted decision-making.
