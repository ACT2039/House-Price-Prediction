# 🏠 House Price Prediction using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge\&logo=python)

![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?style=for-the-badge\&logo=pandas)

![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge\&logo=scikitlearn)

![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)

![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?style=for-the-badge\&logo=googlecolab)

</p>

---

# 📌 Project Overview

House Price Prediction is a Machine Learning Regression project developed as part of a Machine Learning Internship.

The objective is to predict house prices using different housing features such as area, bedrooms, bathrooms, stories, parking, furnishing status, air conditioning, and other property characteristics.

The project follows an end-to-end machine learning workflow, including:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Machine Learning Model Development
* Model Evaluation
* Business Insights

---

# 🎯 Objectives

* Predict house prices accurately using machine learning.
* Understand relationships between housing features.
* Compare multiple regression models.
* Interpret model performance using evaluation metrics.
* Generate actionable business insights.

---

# 📂 Dataset

**Dataset Name**

Housing Prices Dataset

**Source**

Kaggle

Target Variable

```
price
```

Number of Features

```
12
```

Problem Type

```
Regression
```

---

# 🛠 Technologies Used

| Category         | Tools               |
| ---------------- | ------------------- |
| Programming      | Python              |
| Notebook         | Google Colab        |
| Data Analysis    | Pandas, NumPy       |
| Visualization    | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn        |

---

# ⚙️ Machine Learning Workflow

```
Business Problem

↓

Data Collection

↓

Data Cleaning

↓

EDA

↓

Feature Engineering

↓

Visualization

↓

Train-Test Split

↓

Linear Regression

↓

Random Forest

↓

Model Evaluation

↓

Business Insights
```

---

# 📊 Exploratory Data Analysis

The dataset was explored to understand

* Missing values
* Duplicate records
* Feature distributions
* Correlation between variables
* Numerical and categorical features

---

# 📈 Visualizations

The project includes

* Price Distribution Histogram
* Correlation Heatmap
* Area vs Price Scatter Plot
* Actual vs Predicted Scatter Plot
* Feature Importance Plot

---

# 🤖 Models Used

### Linear Regression

Used as the baseline regression model.

### Random Forest Regressor

Used to compare ensemble learning performance.

---

# 📏 Evaluation Metrics

The models were evaluated using

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

# 🏆 Results

| Model             | R² Score  |
| ----------------- | --------- |
| Linear Regression | **0.653** |
| Random Forest     | **0.612** |

Linear Regression achieved the highest predictive performance for this dataset.

---

# 💡 Key Insights

* Area is the strongest predictor of house price.
* Houses with more bathrooms generally have higher prices.
* Additional stories increase property value.
* Furnished houses tend to be more expensive.
* Houses located on the main road generally command higher prices.

---

# 📁 Project Structure

```
House-Price-Prediction/

│── analysis.ipynb

│── Housing.csv

│── summary.pdf

│── README.md

│── requirements.txt

│

├── charts/

│     ├── histogram.png

│     ├── heatmap.png

│     ├── actual_vs_predicted.png

│     ├── area_vs_price.png

│     └── feature_importance.png
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/ACT2039/House-Price-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open

```
analysis.ipynb
```

Run all cells.

---

# 🚀 Future Improvements

* Compare Ridge Regression
* Compare Lasso Regression
* Add XGBoost
* Hyperparameter Optimization
* Deploy using Streamlit
* Build REST API using Flask

---

# 👨‍💻 Author

**Charan Teja Arangi**

Machine Learning Intern

---

# ⭐ If you found this project useful, consider giving it a star.
