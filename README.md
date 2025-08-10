# Airbnb Price Prediction for Cape Town

This project predicts Airbnb listing prices in Cape Town using machine learning techniques. The goal is to analyse various property features and location data to build predictive models that assist hosts and potential investors in estimating listing prices.

## Project Overview

The notebook explores the end-to-end data science workflow:
1. **Data Loading & Cleaning** – Reading Airbnb dataset(s) and handling missing values.
2. **Exploratory Data Analysis (EDA)** – Visualising relationships between variables using Plotly, Matplotlib, and Seaborn.
3. **Feature Engineering** – Creating new variables and transforming existing ones for better predictive power.
4. **Model Building** – Training multiple regression models including:
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
5. **Model Evaluation** – Comparing models using metrics like MAE, RMSE, and R².
6. **Insights & Recommendations** – Providing actionable insights for Airbnb hosts.

## Requirements

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## File Structure

```
.
├── Airbnb_Price_Prediction_for_CT.ipynb  # Main analysis notebook
├── requirements.txt                       # Python dependencies
├── README.md                              # Project documentation
```

## How to Run

1. Clone the repository:
```bash
git clone <repository_url>
cd <repository_folder>
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Open the Jupyter Notebook:
```bash
jupyter notebook Airbnb_Price_Prediction_for_CT.ipynb
```

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn
- XGBoost

## Author
Oscar Msizi Mzobe

---
**Note:** Dataset used in this project may be subject to Airbnb's data sharing policies and licensing.
