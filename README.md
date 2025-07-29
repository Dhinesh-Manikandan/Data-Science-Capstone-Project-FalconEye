# 🚀 Falcon 9 First Stage Landing Prediction

## 📌 Project Overview

This capstone project focuses on predicting the successful landing of the **Falcon 9 first stage booster** using historical launch data. The success of Falcon 9 landings significantly impacts the cost-effectiveness of rocket launches, as SpaceX reuses boosters to reduce launch costs from $165 million to $62 million. By using machine learning models, this project aims to assess the likelihood of a successful landing and provide valuable insights for competitors and stakeholders in the aerospace industry.

---


## 📊 Dataset

The dataset was collected from the SpaceX launch records and additional API endpoints, then preprocessed into structured CSV format.

### Features:
- `Payload Mass (kg)`
- `Launch Site`
- `Orbit`
- `Flight Number`
- `Booster Version`
- `Landing Pad`
- `Block`
- `Launch Outcome`

### Target:
- `Landing Success` (Binary: 1 for success, 0 for failure)

---

## 🔍 Exploratory Data Analysis (EDA)

- Frequency of successful landings by launch site
- Effect of payload mass and orbit on success rate
- Categorical encoding and feature correlation
- Visualizations:bar chart,histogram,line chart,scatter plots, pie charts etc,.,

---

## 🤖 Machine Learning Models

Trained and evaluated multiple models using GridSearchCV:

- Logistic Regression
- Decision Trees
- Support Vector Machine (SVM)
- K-Nearest Neighbors
- Gradient Boosting

**Best Model:** K-Nearest Neighbors with accuracy ~94%

---

## 🌐 Interactive Dashboard (Dash & Plotly)

An interactive dashboard was built using **Plotly Dash** that allows users to:

- View payload vs. success rate across launch sites
- Select site-specific success statistics
- Visualize landing probability by payload mass and orbit



