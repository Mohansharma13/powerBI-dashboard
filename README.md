# Credit Card Transaction Analysis using Power BI

## Overview

This project aims to analyze credit card transaction data to uncover insights related to customer spending behavior, fraud detection, and overall transaction trends. The analysis is conducted using Power BI for interactive data visualization.

## Table of Contents

- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Data Preparation](#data-preparation)
- [Power BI Dashboard](#power-bi-dashboard)
- [Analysis and Insights](#analysis-and-insights)
- [How to Use](#how-to-use)
- [Project Documentation](#project-documentation)
- [Results](#results)

## Introduction

Understanding credit card transactions can provide valuable insights for financial institutions and businesses. This project leverages Power BI to create a comprehensive analysis of transaction data, enabling users to visualize patterns and detect anomalies.

## Data Sources

- `credit_card.csv`: Contains transaction data including transaction ID, date, amount, merchant, and more.
- `customer.csv`: Contains customer information including customer ID, name, age, and gender.

## Data Preparation

Data preparation is a crucial step to ensure data quality and relevance. The following steps were taken:
1. **Data Cleaning**: Removing duplicates, handling missing values, and correcting data types.
2. **Data Transformation**: Creating new features such as transaction day of the week, transaction category, etc.
3. **Data Integration**: Merging transaction data with customer data for enriched analysis.

## Power BI Dashboard

The Power BI file included in the repository is designed to provide a comprehensive view of the credit card transactions:
- `project1.pbit`: The Power BI template file that includes all the visualizations and reports.

### Key Visualizations

1. **Spending Trends**: Line charts showing transaction volumes and amounts over time.
2. **Fraud Detection**: Scatter plots and anomaly detection visuals highlighting suspicious transactions.
3. **Customer Segmentation**: Bar charts and pie charts categorizing customers based on spending patterns and demographics.

## Analysis and Insights

### Spending Trends
- **Monthly Trends**: Identify peak spending months.
- **Daily Trends**: Discover daily transaction patterns.

### Fraud Detection
- **Anomaly Detection**: Highlight outliers and unusual transactions.
- **Risk Analysis**: Assess risk based on transaction amounts and locations.

### Customer Segmentation
- **Demographic Analysis**: Analyze spending behavior across different age groups and genders.
- **High-Value Customers**: Identify top spenders and frequent users.

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/Mohansharma13/powerBI-dashboard.git

