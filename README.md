# Electricity-Trend-Analysis-and-Prediction-in-India

📌 Project Overview

This project focuses on analyzing electricity data in India to understand trends in electricity generation, capacity, and emissions. It also applies machine learning techniques to predict future electricity trends.

The project involves data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling using Linear Regression.

🎯 Objectives

Clean and preprocess raw electricity dataset
Analyze trends in electricity generation over time
Identify top contributing states and energy sources
Visualize patterns using charts and graphs
Build a predictive model using Linear Regression
Evaluate model performance using MSE and R² score

📊 Dataset

Contains electricity-related data such as:
Year
State
Category (Generation, Capacity, Emissions)
Variable (Energy sources)
Value
YoY Change and YoY % Change

🧹 Data Preprocessing

Removed duplicates
Handled missing values
Converted data types to numeric format
Standardized text columns
Removed outliers using IQR method

📈 Exploratory Data Analysis (EDA)

Year-wise trend analysis
State-wise electricity production comparison
Top energy sources analysis
Correlation analysis
Distribution visualization using boxplots

📉 Visualizations

Line charts (trend over years)
Bar charts (state-wise comparison)
Stacked bar charts (energy sources contribution)
Heatmap (correlation analysis)
Boxplots (outlier detection)

🤖 Machine Learning Model

Model Used: Linear Regression
Input Features:
Year
Energy variables (Fossil, Renewable, etc.)
Output:
Electricity value prediction

📊 Model Performance

MSE: 24354274769.126453
R²: 0.962926070352964

👉 The model shows good predictive performance and explains ~80% of variance in the data.

🛠️ Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

🚀 How to Run the Project

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

Run the Jupyter Notebook:

jupyter notebook
Open the project file and execute all cells

📌 Conclusion

The project successfully analyzes electricity trends in India and builds a predictive model. The insights help in understanding growth patterns, major contributors, and future electricity trends.
