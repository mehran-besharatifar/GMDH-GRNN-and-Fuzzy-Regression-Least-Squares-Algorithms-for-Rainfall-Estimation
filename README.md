# 🌧️ Rainfall Estimation Using Neural and Fuzzy Networks
Hydroinformatics Final Project
Algorithms: GMDH, GRNN, and Fuzzy Regression (Least Squares)

📌 Project Overview
This project focuses on monthly rainfall estimation in the Zayandeh Rood basin, using data-driven approaches grounded in neural and fuzzy modeling. The study assumes access to sufficient and reliable hydrological data, and applies three advanced algorithms:

GMDH (Group Method of Data Handling)

GRNN (General Regression Neural Network)

Fuzzy Regression based on Least Squares

The objective is to develop, train, and evaluate these models using meteorological inputs to estimate rainfall with high accuracy.

🧠 Methodology
🔹 Data Preprocessing & Feature Extraction
Raw hydrological and meteorological data (provided in .xlsx format) were cleaned and standardized.

Principal Component Analysis (PCA) was applied for dimensionality reduction and feature extraction, helping improve model efficiency and performance.

🔹 Model Implementation
Three modeling approaches were implemented:

GMDH Model: A self-organizing algorithm that selects the optimal structure from a range of polynomial models.

GRNN Model: A type of radial basis network suited for function approximation with a probabilistic approach.

Fuzzy Regression (Least Squares): Incorporates uncertainty and imprecision in the data using fuzzy logic, optimized via least squares.

All models were developed and trained using the processed inputs and rainfall data.

📊 Model Evaluation
The models were assessed using a comprehensive set of statistical performance metrics:

R² (Coefficient of Determination) – Indicates how well predictions approximate real values.

RMSE (Root Mean Square Error) – Measures the average magnitude of the prediction errors.

KGE (Kling-Gupta Efficiency) – Combines correlation, bias, and variability in one metric.

MAE (Mean Absolute Error) – Represents the mean of absolute differences between predicted and observed values.

Bias – Assesses the overall tendency of the model to overestimate or underestimate.

These indicators provide a robust evaluation framework for comparing model effectiveness.
