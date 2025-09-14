# SpaceX Launch Records Capstone Project

## Overview
This repository contains all the files and notebooks for the **SpaceX Launch Records Data Analysis Capstone Project** from Coursera’s Applied Data Science Capstone course. The project focuses on exploring SpaceX launch data, performing predictive analysis, and creating interactive visualizations using Python, SQL, and data science libraries.

---

## Project Objectives
1. Explore and clean SpaceX launch data.
2. Perform exploratory data analysis (EDA) using Python and SQL queries.
3. Visualize launch site locations and success/failure metrics using Folium and Plotly Dash.
4. Develop machine learning models to predict launch success based on historical data.
5. Compare the performance of various classifiers (Logistic Regression, SVM, Decision Tree, KNN).
6. Prepare a final presentation summarizing methodology, analysis, and insights.

---

## Key Tasks Completed
1. **Data Wrangling and Cleaning**
   - Loaded SpaceX datasets.
   - Handled missing and inconsistent data.
   - Created target variable (`Class`) for predictive analysis.

2. **Exploratory Data Analysis (EDA)**
   - SQL queries to explore launch site statistics, payload mass, and landing outcomes.
   - Python visualizations for Flight Number vs Launch Site, Payload Mass vs Orbit Type, and other relationships.
   - Yearly trends of launch successes.

3. **Visualization**
   - Interactive maps using Folium to mark launch sites and success/failure outcomes.
   - Plotly Dash dashboards for interactive analysis.

4. **Predictive Modeling**
   - Standardized features using `StandardScaler`.
   - Trained and optimized classifiers:
     - Logistic Regression
     - Support Vector Machine (SVM)
     - Decision Tree
     - K-Nearest Neighbors (KNN)
   - Evaluated models using test set accuracy.
   - Identified the best-performing model.

5. **Presentation**
   - Summarized methodology, EDA insights, predictive analysis results, and conclusions in a PDF presentation.

---

## Tools and Libraries Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (for ML models and preprocessing)
- SQL (SQLite queries for EDA)
- Folium (interactive maps)
- Plotly Dash (interactive dashboards)
- Jupyter Notebook

```bash
git clone https://github.com/yourusername/spacex-capstone.git
