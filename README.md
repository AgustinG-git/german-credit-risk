# German Credit Risk Analysis

![Python Version](https://img.shields.io/badge/python-3.9%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-academic-yellow)

## Project Overview
This project addresses the **Credit Risk Classification** problem using the famous German Credit dataset. 

The main challenge is not just mathematical accuracy, but **business profitability**. In credit scoring, failing to detect a defaulter (False Negative) is significantly more costly than rejecting a good client (False Positive).

This repository implements a **Cost-Sensitive Decision Tree** model that penalizes risky miss-classifications according to a specific cost matrix (5:1), prioritizing financial safety over raw accuracy.

## Key Objectives
- **Exploratory Data Analysis (EDA):** Identify correlations between age, credit amount, and duration.
- **Cost-Sensitive Learning:** Implementation of a custom cost matrix where *Cost(False Negative) = 5 * Cost(False Positive)*.
- **Model Comparison:** Evaluating standard Decision Trees vs. Business-Oriented Trees.

## Project Structure
```text
german-credit-risk/
├── data/               # Raw dataset (german.data)
├── notebooks/          # Jupyter Notebooks for EDA and modeling
├── src/                # (Planned) Modular source code for production
├── .gitignore          # Files to exclude from Git
└── README.md           # Project documentation
```

## Installation

### Prerequisites
- Python 3.x
- Pandas, Scikit-learn, Matplotlib, Seaborn

### Installation procedure
- Clone the repository:
```bash
git clone [https://github.com/YOUR_USERNAME/german-credit-risk.git](https://github.com/YOUR_USERNAME/german-credit-risk.git)
```
- Navigate to the project directory:
```bash
cd german-credit-risk
```
- Install dependencies (coming soon).

## Results
The Business Model successfully reduced the number of undetected defaulters compared to the Standard Model, effectively minimizing potential financial loss for the bank, even at the cost of rejecting some valid applicants.

## Author
Agustín Galiana Carballido - AI Master's Student

