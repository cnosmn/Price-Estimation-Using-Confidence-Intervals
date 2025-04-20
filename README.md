# Confidence Interval Pricing Strategy

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.21-green.svg)](https://numpy.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11-red.svg)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Overview

This project demonstrates the application of statistical confidence intervals to determine optimal pricing strategies for new products. Using simulated customer survey data, the notebook shows how to establish price points that would be acceptable to a majority of potential customers.

## Table of Contents

- [Confidence Interval Pricing Strategy](#confidence-interval-pricing-strategy)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Methodology](#methodology)
  - [Results](#results)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Dependencies](#dependencies)

## Introduction

Price determination is a critical factor in product marketing strategy. This project simulates a scenario where a store distributes samples of a new product to 1,000 customers and asks them what price they would be willing to pay. The collected data is then analyzed to determine the optimal price range that would appeal to the majority of potential customers.

## Features

- Generation of simulated customer price preferences
- Statistical analysis of price distribution
- Visualization of price distribution using kernel density estimation (KDE)
- Calculation of confidence intervals for price determination
- Data-driven pricing recommendation

## Methodology

1. **Data Simulation**: 
   - Generate 1,000 random price points between 10 and 110 units to simulate customer responses

2. **Data Preparation**:
   - Convert array data to a pandas DataFrame for easier manipulation
   - Check for missing values
   - Rename columns for clarity

3. **Exploratory Data Analysis**:
   - Visualize the distribution of price preferences using seaborn's KDE plot
   - Calculate basic statistics (mean price preference)

4. **Statistical Analysis**:
   - Calculate the 95% confidence interval for the mean price preference
   - Use this interval to recommend a pricing strategy

## Results

The analysis revealed that a price point between 57 and 61 units would appeal to approximately 95% of the surveyed customers. This provides a statistically sound basis for pricing the new product to maximize market acceptance.

## Installation

1. Clone this repository
```bash
git clone https://github.com/yourusername/confidence-interval-pricing.git
cd confidence-interval-pricing
```

2. Install required packages
```bash
pip install numpy pandas seaborn statsmodels jupyter
```

## Usage

1. Launch Jupyter Notebook
```bash
jupyter notebook
```

2. Open the `confidence_interval_price_determination.ipynb` file
3. Run all cells to see the analysis and results

## Dependencies

- Python 3.x
- NumPy: For numerical operations and random number generation
- Pandas: For data manipulation
- Seaborn: For data visualization
- Statsmodels: For statistical calculations
- Jupyter Notebook: For interactive code execution

---

*Note: The analysis in this notebook uses simulated data. In a real-world scenario, actual customer survey data would be used to determine pricing strategies.*