# 🏠 House Price Prediction Using Machine Learning

## 📌 Project Overview

This project predicts house prices using **Machine Learning** and **Multiple Linear Regression**.

The project uses the `HousingData.csv` dataset and performs data preprocessing, exploratory data analysis, correlation analysis, feature scaling, model training, prediction, and model evaluation.

## 🎯 Objective

The main objective of this project is to build a machine learning model that can predict the median value of houses based on different housing-related features.

## 📊 Dataset

The dataset contains **506 records and 14 columns**. The target variable is:

* `MEDV` — Median value of owner-occupied homes

The input features include:

* `CRIM`
* `ZN`
* `INDUS`
* `CHAS`
* `NOX`
* `RM`
* `AGE`
* `DIS`
* `RAD`
* `TAX`
* `PTRATIO`
* `B`
* `LSTAT`

The notebook checks missing values and handles them using the median value of each respective column.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Missing Value Detection
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Correlation Analysis
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Linear Regression
   ↓
Prediction
   ↓
Model Evaluation
```

## 🧹 Data Preprocessing

The dataset is checked for:

* Missing values
* Duplicate records
* Data types
* Dataset dimensions

The dataset initially contains missing values in several columns. These missing values are replaced using the median of the corresponding column. The notebook also verifies that there are no duplicate rows.

## 📈 Exploratory Data Analysis

The project performs exploratory analysis using:

* Statistical summaries
* Correlation analysis
* Correlation heatmap
* Distribution plots
* Boxplots
* Actual vs predicted visualization

## 🤖 Machine Learning Model

### Multiple Linear Regression

Multiple Linear Regression is used to learn the relationship between the input housing features and the target variable `MEDV`.

The dataset is divided into training and testing sets before training the model.

Feature scaling is also applied using `StandardScaler`.

## 📏 Model Evaluation

The model is evaluated using:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

These metrics help measure how closely the predicted house prices match the actual values.

## 📊 Results

The notebook generates predictions and compares the **actual values with predicted values** using visualizations and evaluation metrics.

The exact performance values are available in the executed notebook.

## 📁 Repository Structure

```text
House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── HousingData.csv
└── README.md
```

> If the dataset's license or source does not permit redistribution, do not upload `HousingData.csv`. Instead, provide the dataset source and instructions for obtaining it.

## ▶️ How to Run

### Option 1 — Google Colab

1. Open the notebook.
2. Upload `HousingData.csv` when prompted.
3. Run the cells from top to bottom.
4. View the analysis, graphs, predictions, and evaluation results.

### Option 2 — Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Then open:

```text
House_Price_Prediction.ipynb
```

and run the cells sequentially.

## 💡 Key Learning Outcomes

Through this project, I learned:

* How to load and explore a real-world dataset
* How to identify and handle missing values
* How to perform exploratory data analysis
* How to analyze correlations between variables
* How to prepare data for machine learning
* How to train a Linear Regression model
* How to make predictions
* How to evaluate a regression model using different metrics
* How to visualize actual and predicted values

## 👨‍💻 Author

**Kiran**

MCA — Artificial Intelligence, Machine Learning & Data Science

---

⭐ If you find this project useful, feel free to explore the notebook and learn from the implementation.

