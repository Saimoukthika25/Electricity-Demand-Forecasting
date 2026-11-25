Electricity Demand and Peak Load Forecasting using Machine Learning
# Electricity Demand Forecasting Using Machine Learning

**A Machine Learning-Based Approach for Next-Day Electricity Demand and Peak Load Forecasting in India**

## Project Overview

This project focuses on forecasting daily peak electricity demand across 36 states and regions in India using Machine Learning techniques.

The study uses historical electricity data from January 2020 to March 2025. It applies time-series feature engineering, statistical analysis, and multiple machine learning approaches to predict next-day electricity demand.

The project also evaluates high-demand day classification and identifies similarities between electricity demand patterns across different regions.

## Objectives

- Analyze historical electricity demand patterns across Indian states and regions.
- Forecast next-day maximum electricity demand.
- Apply and compare five machine learning approaches.
- Identify high-demand days using classification techniques.
- Group regions based on electricity demand characteristics.
- Evaluate model performance against a naive forecasting baseline.

## Dataset Description

- **Dataset:** India Electricity Demand Data
- **Period:** January 2020 – March 2025
- **Coverage:** 36 states and regions
- **Total observations:** 69,012
- **Target variable:** Max Demand Met (MW)

The dataset includes electricity demand, energy supply, peak shortage, drawal schedule, and other electricity-related variables.

The dataset was obtained from Kaggle, with underlying records compiled primarily from publicly available official Indian electricity-sector sources.

## Machine Learning Models

Five approaches were implemented:

1. **Multiple Linear Regression:** Predicts next-day electricity demand using multiple input variables.
2. **PCA + Neural Network (MLP):** Uses Principal Component Analysis for dimensionality reduction followed by a Multi-Layer Perceptron.
3. **Random Forest Regression:** Uses an optimized ensemble of decision trees for demand forecasting.
4. **Random Forest Classification:** Identifies high-demand days.
5. **K-Means Clustering:** Groups entities according to electricity demand patterns.

## Methodology

The project follows these major steps:

1. Data loading and exploration.
2. Data cleaning and missing-value handling.
3. Exploratory Data Analysis (EDA).
4. Historical lag feature generation.
5. Rolling average and standard deviation calculation.
6. Calendar and cyclic feature engineering.
7. Chronological training and testing split.
8. Machine learning model implementation.
9. Model evaluation and comparison.
10. State-wise forecasting and feature importance analysis.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** Jupyter Notebook
- **Data Format:** CSV

## Results and Performance

The research paper reports the following results:

| Model | Evaluation Result |
|---|---|
| Random Forest Regression | MAE: 235.19 MW |
| Random Forest Regression | RMSE: 468.83 MW |
| Random Forest Regression | R²: 0.9959 |
| Multiple Linear Regression | R²: 0.9935 |
| PCA + MLP | R²: 0.9862 |
| Random Forest Classification | F1 Score: 0.828 |
| K-Means Clustering | Silhouette Score: 0.565 |

Random Forest Regression achieved the best forecasting performance among the evaluated forecasting models.

The study also compares machine learning predictions against a naive baseline that assumes the next day's demand will equal the previous day's demand.

## Project Structure

```text
Electricity-Demand-Forecasting/
│
├── PROJECT ELECTRICITY DEMAND FORECASTING.ipynb
├── India_Elec_data_(Jan2020-Mar2025).csv
├── Electricity Demand Forecasting Revised.pdf
└── README.md
```

## How to Run the Project

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `PROJECT ELECTRICITY DEMAND FORECASTING.ipynb`.
6. Ensure the CSV dataset is in the same directory as the notebook.
7. Run the notebook cells sequentially.

## Research Paper

The complete research paper is available in this repository:

**Electricity Demand Forecasting Revised.pdf**

It describes the dataset, methodology, machine learning approaches, experimental results, and conclusions.

## Conclusion

This project demonstrates the application of machine learning techniques to electricity demand forecasting in India.

The results indicate that Random Forest Regression can provide accurate next-day demand predictions. However, comparison with a naive baseline highlights the importance of evaluating forecasting models against simple real-world benchmarks.

The study provides insights into electricity demand patterns and the potential use of machine learning in power system planning.

---

**Author:** Thanda Sai Moukthika  
**Department:** Computer Science and Engineering  
**University:** Lovely Professional University, Punjab, India

**Project Domain:** Data Science | Machine Learning | Electricity Demand Forecasting
