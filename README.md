# Sharpe Ratio Analysis for Amazon and Facebook Stocks

# Overview 

An investment may make sense if we expect it to return more money than it costs. But returns are only part of the story because they are risky - there may be a range of possible outcomes. How does one compare different investments that may deliver similar results on average, but exhibit different levels of risks?

## Introduction

In the world of finance, comparing different investments requires considering not only the expected returns but also the associated risks. One widely used metric for this purpose is the Sharpe Ratio, introduced by Professor William Sharpe in 1966. The Sharpe Ratio measures the additional return per unit of risk an investor could obtain by choosing one investment over another. A higher Sharpe Ratio indicates a more favourable risk-return profile. You can read more about it [here](https://web.stanford.edu/~wfsharpe/art/sr/sr.htm)

In this analysis, we'll calculate the Sharpe Ratio for two tech giants, Amazon and Facebook, using the S&P 500 as a benchmark. The Sharpe Ratio is typically calculated for a portfolio, but for simplicity, we'll use individual stocks and a stock index as a benchmark.

## Prerequisites

Ensure you have the necessary Python libraries installed before running the Jupyter Notebook:

- pandas
- numpy
- matplotlib

```pip install pandas numpy matplotlib```

## Getting Started

- Clone the repository:
- Open the Jupyter Notebook: sharpe_ratio_analysis.ipynb
- Run the notebook cells to perform the analysis.

## Usage

The notebook covers the following key steps:

- Importing required modules and setting up the environment.
- Exploring the dataset and summarizing the daily prices for Amazon and Facebook stocks.
- Visualizing and summarizing daily values for the S&P 500 benchmark.
- Calculating daily returns for Amazon and Facebook stocks.
- Calculating daily returns for the S&P 500 benchmark.
- Calculating excess returns for Amazon and Facebook compared to the S&P 500.
- Computing the Sharpe Ratio, including the average difference in daily returns and the standard deviation of the return difference.
- Visualizing and interpreting the results.

## Key Finding

Given the two Sharpe ratios, which investment should we go for? In 2016, Amazon had a Sharpe ratio twice as high as Facebook. This means that an investment in Amazon returned twice as much compared to the S&amp;P 500 for each unit of risk an investor would have assumed. In other words, in risk-adjusted terms, the investment in Amazon would have been more attractive.

You can view the analysis step-by-step [here](sharpe_ratio_analysis.ipynb)

![sharpe_ratio](annualized_sharpe_ratio.png)

## Contributing

If you'd like to contribute to this analysis or make improvements, follow these steps:

- Fork the repository.
- Create a new branch: git checkout -b feature_branch
- Make your changes and commit them: git commit -m 'Add new feature'
- Push to the branch: git push origin feature_branch

## Acknowledgments

- Professor William Sharpe for introducing the Sharpe Ratio.
- Data sourced from the provided Amazon, Facebook, and the S&P 500 dataset.
