# Flight Price Forecast & Airline Clustering Analysis

This is my first machine learning and web scraping project!
I developed this project after spending most of the semester on reserve duty. 
It demonstrates an end-to-end data science workflow—from data cleaning and feature engineering to model building, hyperparameter tuning, and airline clustering analysis.

---

## Overview

- **Goal:** Forecast flight prices and analyze airline pricing strategies.
- **Data Sources:** Flight data from Kiwi (prices in NIS) and Momondo (converted from USD to NIS).
- **Methods:**  
  - Data cleaning (price parsing, date & duration conversion, feature creation)  
  - Regression models (Linear Regression, Decision Trees, Random Forest, XGBoost, HistGradientBoosting, KNN, MLP, Gaussian Process)  
  - Hyperparameter tuning using GridSearchCV  
  - Model interpretability via residual plots and permutation importance  
  - Clustering (KMeans and hierarchical clustering) to group airlines based on pricing

---

## Project Structure

- **Data Cleaning & Feature Engineering:** Parsing prices, converting dates and durations, and deriving features such as flight duration (in minutes), number of stops, departure weekday, and days until the end of the month.
- **Modeling:** Building and comparing multiple regression models to predict flight prices.
- **Clustering Analysis:** Grouping airlines based on aggregated price statistics to reveal insights about premium vs. low-cost carriers.
- **Comparative Analysis:** Evaluating differences between Kiwi and Momondo data and exploring performance across various data splits.

---

## How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/flight-price-forecast.git
   cd flight-price-forecast
