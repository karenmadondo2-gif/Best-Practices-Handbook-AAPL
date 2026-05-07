# Project #1: Best-Practices Handbook for Time Series Analysis
**Prepared by:** Karen Madondo (Student Number: R2425078)  
**Major:** Actuarial Science  
**Course:** Application of Time Series Models (Project #1)

---

## 1. Project Overview
This handbook serves as a guide for identifying and resolving common challenges in financial time series modeling. Using daily closing prices for Apple Inc. (AAPL) from 2018 to 2025, this project demonstrates foundational best practices in data preparation, diagnostic testing, and model validation.

## 2. Key Objectives
* **Data Integrity:** Establishing protocols for handling historical financial data and calculating log returns.
* **Diagnostic Testing:** Implementing tests for stationarity (ADF), autocorrelation, and multicollinearity to ensure model assumptions are met.
* **Model Selection:** Utilizing information criteria (AIC/BIC) to select the most parsimonious model structures.
* **Error Resolution:** Documenting strategies to address common issues like heteroscedasticity and non-normality in residuals.

## 3. Technical Implementation
The analysis is contained within the `Jupyter Notebook Ass1.ipynb` file and includes:
* Automated data cleaning and transformation (log-returns calculation).
* Visual exploratory data analysis (EDA) and trend identification.
* Statistical proofing of Gauss-Markov assumptions to ensure BLUE (Best Linear Unbiased Estimator) properties.

## 4. Files in this Repository
* `Jupyter Notebook Ass1.ipynb`: The technical handbook and code implementation.
* `AAPL_historical_data.xlsx - Sheet1.csv`: The historical dataset used for the handbook examples.

## 5. Bibliography (MLA Format)
Brooks, Chris. *Introductory Econometrics for Finance*. 4th ed., Cambridge University Press, 2019.

Gujarati, Damodar N., and Dawn C. Porter. *Basic Econometrics*. 5th ed., McGraw-Hill, 2009.

Hull, John C. *Options, Futures, and Other Derivatives*. 11th ed., Pearson, 2021.

Tsay, Ruey S. *Analysis of Financial Time Series*. 3rd ed., Wiley, 2010.

---
*This project was completed as part of the Actuarial Science curriculum at the University of Zimbabwe.*
