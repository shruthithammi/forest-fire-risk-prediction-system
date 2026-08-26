# 🌲 Forest Fire Risk Prediction System

This project analyzes weather conditions from the Algerian Forest Fires dataset to understand the factors that influence forest fire risk and predict the **Fire Weather Index (FWI)** using Python.

The goal of this project was to practice the complete data analysis workflow — starting from cleaning raw data, performing exploratory analysis, and building a basic machine learning model for prediction.

---

## 📌 Project Overview

The dataset contains weather observations from two regions in Algeria (Bejaia and Sidi-Bel Abbes). I cleaned the dataset, explored the relationship between weather variables, and trained a regression model to predict the Fire Weather Index, which is commonly used to estimate fire risk.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📂 Dataset

* **Dataset:** Algerian Forest Fires Dataset
* **Records:** 244 weather observations
* **Features:** Temperature, Humidity, Wind Speed, Rain, FFMC, DMC, DC, ISI, BUI, FWI, and Region.

---

## 🔍 Project Workflow

1. Imported and explored the raw dataset.
2. Cleaned missing and inconsistent values.
3. Converted data types and prepared the dataset for analysis.
4. Performed exploratory data analysis using visualizations.
5. Studied correlations between weather variables and fire risk.
6. Built and evaluated a regression model to predict Fire Weather Index (FWI).

---

## 📊 Exploratory Data Analysis

The notebook includes:

* Fire class distribution.
* Monthly fire occurrence analysis for both regions.
* Correlation heatmap of weather variables.
* Distribution plots for temperature, humidity, wind speed, and rainfall.
* Outlier analysis using boxplots.

---

## 💡 Key Insights

* Higher temperature and lower humidity were associated with higher fire risk.
* Fire activity showed different monthly patterns in the two regions.
* Weather indices such as FFMC, DMC, and ISI had strong relationships with the Fire Weather Index.
* The correlation analysis helped identify the most influential features for prediction.

---

## 🤖 Machine Learning

Built a regression model using Scikit-learn to predict the **Fire Weather Index (FWI)** after preprocessing and feature selection.

---

## 📁 Project Structure

forest-fire-risk-prediction-system/
├── data/
├── notebooks/
├── reports/screenshots/
├── requirements.txt
├── .gitignore
└── README.md

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Regression Modeling
* Python Data Analysis
