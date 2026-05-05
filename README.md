# 📈 Predicting Customer Response to Telemarketing Campaigns

A machine learning and data analysis project leveraging bank telemarketing data to identify high-potential customers, optimize outreach strategies, and maximize campaign conversion rates.

## 🚀 Overview
This project analyzes comprehensive Portuguese bank telemarketing data to extract actionable insights for future term deposit marketing strategies. By conducting in-depth exploratory data analysis (EDA) on customer demographics, financial conditions, and historical campaign outcomes, this study uncovers key behavioral patterns that influence telemarketing success and builds predictive models to target the most receptive demographics.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression, Multiple Linear Regression, Decision Trees, K-Neighbors, Gaussian NB)

## 📁 Repository Structure
* `/data` - Contains the raw and cleaned `.csv` datasets used for analysis.
* `/notebooks` - Jupyter notebooks containing the Exploratory Data Analysis (EDA) and Model Training code.
* `/docs` - Contains the final comprehensive project report and presentation slides.

## 📄 Project Documentation
* [Read the Full Project Report](docs/Gopesh_report.pdf)

## 📊 Key Findings & Strategic Recommendations
Through rigorous Exploratory Data Analysis and predictive modeling, the following strategies were identified to optimize marketing efforts:
* **Target Demographics:** Prioritize clients with average-to-high account balances, particularly older clients (60+) who demonstrate the highest likelihood of subscription.
* **Occupational Targeting:** Students and retired individuals show the highest baseline conversion rates.
* **Optimal Timing:** Initiate telemarketing campaigns during Fall or Spring. Historical data indicates that March, September, October, and December yield the highest success rates.

## ⚙️ Methodology
1. **Data Cleaning:** Handled missing/ambiguous values (e.g., 'unknown', 'others') and removed outliers using standard deviation thresholds to ensure model accuracy.
2. **Exploratory Data Analysis:** Visualized feature distributions and correlation matrices to identify mathematical relationships between age, balance, job type, and subscription rates.
3. **Feature Engineering:** Transformed categorical string data into dummy numerical variables for machine learning compatibility.
4. **Model Building & Evaluation:** Trained and evaluated multiple classification models to predict customer response, alongside regression models to estimate phone call duration.
