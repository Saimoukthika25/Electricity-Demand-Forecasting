# ⚡ Electricity Demand Forecasting Using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Domain-Data%20Science-purple" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

<p align="center">
  <b>📊 Predicting India's Next-Day Electricity Demand Using Historical Data and Machine Learning</b>
</p>

---

## 🌟 About The Project

Electricity demand forecasting plays an important role in power system planning, energy management, and reliable electricity distribution.

This project focuses on predicting **next-day maximum electricity demand** across 36 states and regions in India using historical electricity consumption and supply-related data.

The study uses machine learning algorithms, historical demand patterns, feature engineering, and statistical analysis to develop and evaluate forecasting models.

📅 **Study Period:** January 2020 – March 2025

📍 **Geographical Coverage:** 36 States and Regions in India

📈 **Dataset Size:** 69,012 observations

---

## 🎯 Project Objectives

- ⚡ Forecast next-day maximum electricity demand.
- 📊 Analyze historical electricity demand patterns.
- 🗺️ Study electricity demand variations across Indian states.
- 🤖 Implement and compare five machine learning approaches.
- 🔍 Identify high-demand days using classification.
- 📉 Evaluate forecasting accuracy using performance metrics.
- 💡 Identify important features influencing electricity demand.

---

## 📂 Dataset Information

| Attribute | Description |
|---|---|
| Dataset | India Electricity Demand Data |
| Time Period | January 2020 – March 2025 |
| Observations | 69,012 |
| Coverage | 36 States and Regions |
| Target Variable | Next-Day Demand |
| Dataset Format | CSV |

**Important Features:**

- 📅 Date
- 🗺️ State
- ⚡ Max Demand Met
- 🔋 Energy Met
- 📊 Drawl Schedule
- 📉 Shortage During Peak
- 📈 Energy Shortage
- 🔄 Historical Demand Features

---

## 🛠️ Technologies & Tools

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Development Environment | Jupyter Notebook |
| Dataset Format | CSV |

---

## 🤖 Machine Learning Approaches

Five machine learning approaches were implemented in this project.

| No. | Model | Purpose |
|---|---|---|
| 1️⃣ | Multiple Linear Regression | Electricity demand prediction |
| 2️⃣ | PCA + Multi-Layer Perceptron (MLP) | Demand prediction using dimensionality reduction |
| 3️⃣ | Random Forest Regression | Next-day demand forecasting |
| 4️⃣ | Random Forest Classification | High-demand day identification |
| 5️⃣ | K-Means Clustering | Grouping states based on demand characteristics |

---

## 🔬 Project Workflow

```text
       📂 Dataset Collection
                |
                ▼
       🧹 Data Preprocessing
                |
                ▼
       📊 Exploratory Data Analysis
                |
                ▼
       ⚙️ Feature Engineering
                |
                ▼
       ✂️ Train-Test Split
                |
                ▼
       🤖 Machine Learning Models
                |
                ▼
       📈 Model Evaluation
                |
                ▼
       🏆 Performance Comparison
                |
                ▼
       ⚡ Electricity Demand Forecasting
```

---

## 📊 Model Performance & Results

The following results are reported in the research paper.

### ⚡ Regression Performance

| Model | MAE (MW) | RMSE (MW) | R² Score |
|---|---:|---:|---:|
| Multiple Linear Regression | 314.88 | 593.56 | 0.9935 |
| PCA + MLP | 469.86 | 864.91 | 0.9862 |
| Random Forest Regression | **235.19** | **468.83** | **0.9959** |

### 🎯 Classification Performance

| Metric | Random Forest Classifier |
|---|---:|
| F1 Score | 0.8282 |
| Recall | 0.976 |

### 🔍 Clustering Performance

| Algorithm | Silhouette Score |
|---|---:|
| K-Means (3 Clusters) | 0.5652 |

🏆 **Best Forecasting Model: Random Forest Regression**

Random Forest Regression achieved the lowest reported forecasting errors and the highest R² score among the three regression models.

---

## 📈 Evaluation Metrics

The project uses the following evaluation metrics:

- **MAE (Mean Absolute Error):** Measures the average absolute prediction error.
- **RMSE (Root Mean Squared Error):** Measures prediction errors while penalizing larger errors.
- **R² Score:** Measures how well the model explains variations in the target variable.
- **Precision:** Measures the correctness of positive classifications.
- **Recall:** Measures how many actual high-demand cases are identified.
- **F1 Score:** Combines precision and recall.
- **Silhouette Score:** Evaluates the quality of clustering.

---

## 📁 Repository Structure

```text
⚡ Electricity-Demand-Forecasting/
│
├── 📓 PROJECT ELECTRICITY DEMAND FORECASTING.ipynb
│
├── 📂 India_Elec_data_(Jan2020-Mar2025).csv
│
├── 📄 Electricity Demand Forecasting Revised.pdf
│
└── 📘 README.md
```

---

## 🚀 How to Run This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Saimoukthika25/Electricity-Demand-Forecasting.git
```

### 2️⃣ Navigate to the Project Directory

```bash
cd Electricity-Demand-Forecasting
```

### 3️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5️⃣ Execute the Project

1. Open `PROJECT ELECTRICITY DEMAND FORECASTING.ipynb`.
2. Ensure the CSV dataset is in the same directory.
3. Run the notebook cells sequentially.
4. Explore the analysis, predictions, visualizations, and model comparisons.

---

## 📄 Research Paper

📚 The complete research paper is included in this repository.

**File:** `Electricity Demand Forecasting Revised.pdf`

The paper covers:

- Introduction and research background.
- Dataset description and methodology.
- Feature engineering and machine learning techniques.
- Experimental results and model comparisons.
- Conclusions and future scope.

---

## 🔮 Future Scope

- 🌦️ Integrate weather and temperature information.
- 🧠 Explore advanced deep learning forecasting models.
- 📊 Develop an interactive electricity demand dashboard.
- ⚡ Improve forecasting for individual states and regions.
- 🔄 Integrate real-time electricity demand data.

---

## 👩‍💻 Author

**Thanda Sai Moukthika**

🎓 B.Tech – Computer Science and Engineering  
📍 Lovely Professional University, Punjab, India

**Areas of Interest:** Data Science | Machine Learning | Artificial Intelligence | Predictive Analytics

---

<p align="center">
  ⭐ If you find this project interesting, consider giving this repository a star!
</p>

<p align="center">
  <b>⚡ Turning Historical Electricity Data into Intelligent Demand Forecasts ⚡</b>
</p>
