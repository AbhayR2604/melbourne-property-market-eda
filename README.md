# Melbourne Property Market Analysis and Price Prediction

## Project Overview

This project analyses property transaction data from Greater Melbourne to explore market trends, suburb-level transaction activity, property price patterns, keyword associations in property descriptions, capital gains, price volatility, and future price prediction.

The analysis was completed using R and RMarkdown, with the final output provided as an HTML report. The project demonstrates exploratory data analysis, data cleaning, feature engineering, visualisation, and basic predictive modelling.

## Objectives

The project focuses on the following analytical goals:

1. Identify suburbs with the highest property transaction volumes.
2. Compare monthly transaction trends across selected suburbs.
3. Analyse property description keywords associated with higher prices.
4. Examine the relationship between property price and land size.
5. Identify properties with strong capital gains over time.
6. Analyse suburb-property type combinations with high price volatility.
7. Predict future house prices for selected Melbourne suburbs.

## Tools and Technologies

- R
- RMarkdown
- dplyr
- ggplot2
- stringr
- lubridate
- tidyverse
- Regression modelling
- Data visualisation
- HTML reporting

## Key Analysis Areas

### 1. Transaction Volume Analysis

The dataset was analysed to identify suburbs with the highest number of property transactions. Monthly transaction counts were then visualised to compare activity across selected suburbs.

### 2. Property Description Keyword Analysis

Text analysis was applied to property descriptions to identify keywords associated with higher property prices. This helped explore how language used in property listings may relate to market value.

### 3. Price and Land Size Correlation

The relationship between property price and land size was examined across selected suburbs and property types to understand how land size may influence property value.

### 4. Capital Gain Analysis

Properties with repeated transactions were analysed to identify those with the highest capital gains between their first and last recorded sale.

### 5. Price Volatility Analysis

Monthly median property prices were compared across suburb-property type combinations to identify which groups showed the highest price volatility.

### 6. Price Prediction

A predictive model was developed to estimate future property prices for selected Melbourne suburbs based on historical transaction patterns and property characteristics.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Time-based trend analysis
- Text analysis
- Correlation analysis
- Feature engineering
- Regression-based prediction
- Data visualisation using ggplot2
- RMarkdown reporting
- Property market analysis

## Files in This Repository

```text
melbourne-property-market-eda/
│
├── README.md
├── melb_Property_Market_EDA.Rmd
└── melb_Property_Market_EDA.html
