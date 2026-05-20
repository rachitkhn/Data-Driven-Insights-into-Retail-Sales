# 🛒 Data-Driven Insights into Retail Sales

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-green?style=flat-square&logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

> Sales forecasting project combining machine learning and deep learning to model seasonal trends, marketing impact, and revenue drivers in retail data.

---

## 📌 Project Overview

Understanding retail sales patterns is essential for inventory planning, marketing strategy, and revenue optimisation. This project applies ML and deep learning techniques to a retail sales dataset to uncover seasonal trends, assess the influence of marketing campaigns, and build accurate sales forecasting models.

The analysis goes beyond simple regression — it explores time-based patterns, promotional effects, and the interaction between marketing spend and consumer demand.

---

## 🎯 Objectives

- Identify seasonal and temporal patterns driving retail sales fluctuations
- Quantify the impact of marketing campaigns on revenue
- Build and compare machine learning and deep learning forecasting models
- Deliver actionable insights for retail business decision-making

---

## 📂 Repository Structure

```
Data-Driven-Insights-into-Retail-Sales/
│
├── Retail Sales.ipynb              # Complete analysis and modelling notebook
├── retail_sales_data__new.csv      # Retail sales dataset with marketing and seasonal features
├── README.md
└── LICENSE
```

---

## 📊 Dataset

The dataset contains retail transaction records with features capturing sales volume, marketing investment, and temporal attributes. Key fields include:

| Feature Category | Examples |
|---|---|
| Sales Metrics | Revenue, Units Sold, Transaction Volume |
| Marketing Data | Campaign Spend, Promotion Flags |
| Temporal Features | Date, Month, Season, Week Number |
| Product Data | Product Category, Store Region |

---

## 🔬 Methodology

### 1. Data Preprocessing & Cleaning
- Handled missing values and outliers
- Parsed and engineered date-based features (month, quarter, season, day-of-week)
- Normalised continuous features for model compatibility

### 2. Exploratory Data Analysis (EDA)
- Seasonal decomposition of sales trends across time periods
- Correlation analysis between marketing spend and sales uplift
- Visual breakdown of top-performing product categories and regions
- Heatmaps, time-series line plots, and bar charts for trend identification

### 3. Feature Engineering
- Derived lag features and rolling averages to capture temporal dependencies
- Encoded categorical variables (region, product category, campaign type)
- Created interaction features between marketing spend and seasonal periods

### 4. Model Development

| Model Type | Algorithm |
|---|---|
| Machine Learning | Linear Regression, Random Forest Regressor, Gradient Boosting |
| Deep Learning | LSTM / Sequential Neural Network |

### 5. Evaluation Metrics
- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)
- **R² Score** (Coefficient of Determination)

---

## 📈 Key Insights

- Clear seasonal peaks identified in Q4 — holiday period drives the largest revenue uplift
- Marketing campaign spend shows a statistically significant positive correlation with weekly sales
- Deep learning models captured non-linear temporal dependencies better than linear regressors
- Gradient Boosting consistently outperformed other ML models on holdout test data

---

## 🛠️ Technologies Used

- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow / Keras
- **Environment:** Jupyter Notebook

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/rachitkhn/Data-Driven-Insights-into-Retail-Sales.git
cd Data-Driven-Insights-into-Retail-Sales

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow jupyter

# Launch the notebook
jupyter notebook "Retail Sales.ipynb"
```

---

## 💡 Business Applications

- **Inventory Management:** Forecast demand ahead of peak seasons to reduce stockouts
- **Marketing ROI:** Quantify return on marketing investment across campaigns
- **Revenue Planning:** Build data-backed quarterly revenue forecasts
- **Promotional Strategy:** Identify the most impactful timing and channels for promotions

---

## 👤 Author

**Rachit Khandelwal**
[GitHub](https://github.com/rachitkhn) · [LinkedIn](https://linkedin.com/in/rachitkhn)

---

*This project was developed as part of a data science portfolio focusing on practical business analytics and forecasting.*
