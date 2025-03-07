
# DummyBank2 Project

## Overview

DummyBank2 is a data analysis project focused on understanding customer behavior, credit profiles, and transaction patterns. The project involves various analyses and hypothesis testing to derive insights from the provided datasets.

## Project Structure

The project is organized into several Jupyter notebooks, each focusing on different aspects of the analysis:

- `Credit.ipynb`: Analysis of credit profiles and outstanding debts.
- `Customer.ipynb`: Analysis of customer data.
- `Transaction.ipynb`: Analysis of transaction data.
- `Hypothesis_Testing.ipynb`: Hypothesis testing on various claims related to the data.

## Data

The data used in this project is stored in the `Data` directory and includes the following CSV files:

- `avg_transactions_after_campaign.csv`: Average transactions after a campaign.
- `credit_profiles.csv`: Credit profiles of customers.
- `customers.csv`: Customer information.
- `transactions.csv`: Transaction records.

## Notebooks

### Credit.ipynb

This notebook focuses on analyzing credit profiles and outstanding debts. Key analyses include:

- Identifying customers with outstanding debt greater than their credit limit.
- Exploring correlations between different credit-related variables.

### Customer.ipynb

This notebook analyzes customer data, including:

- Reading and exploring customer data.
- Creating a copy of the customer dataset for analysis.
- Analyzing customer demographics and other attributes.

### Transaction.ipynb

This notebook focuses on transaction data analysis, including:

- Reading and exploring transaction data.
- Analyzing transaction patterns before and after campaigns.
- Creating a copy of the transaction dataset for analysis.

### Hypothesis_Testing.ipynb

This notebook involves hypothesis testing, including:

- Defining null and alternative hypotheses.
- Performing various statistical tests (Z-Test, T-Test, Chi-Square Test, ANOVA) to validate hypotheses.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies.
3. Open the Jupyter notebooks and run the cells to perform the analyses.

## Dependencies

The project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn

You can install the dependencies using the following command:

```sh
pip install pandas numpy matplotlib seaborn