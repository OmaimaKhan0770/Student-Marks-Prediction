# Student Marks Prediction using Linear Regression

## Project Overview

This project aims to predict students' academic performance using Machine Learning techniques. It analyzes different student related features and builds predictive models to estimate examination marks.

The project applies both **Simple Linear Regression (SLR)** and **Multiple Linear Regression (MLR)** models and compares their performance against a **Dummy Regressor (Baseline Model)**.

---

# Objectives

The main objectives of this project are to:

- Predict student academic performance using Linear Regression.
- Compare Simple Linear Regression and Multiple Linear Regression.
- Evaluate model performance using different evaluation metrics.
- Compare trained models with a baseline Dummy Regressor.
- Analyze prediction errors using residual plots.
- Visualize relationships between features and target variables.

---

# Dataset

The project uses the following dataset:

```
marks_dataset.xlsx
```

The dataset contains students' academic records including different assessment marks that are used to predict final performance.

Typical attributes include:

- Assignment Marks
- Quiz Marks
- Midterm Marks
- Attendance
- Final Exam Marks
- Other academic performance indicators

---

# Machine Learning Models

The following regression models were implemented.

## 1. Simple Linear Regression (SLR)

Used to predict a target variable using a single independent feature.

Example:

```
Target = Assignment Marks
Feature = Quiz Marks
```

---

## 2. Multiple Linear Regression (MLR)

Used to predict a target variable using multiple independent variables.

Example:

```
Target = Final Exam Marks

Features:

- Assignment Marks
- Quiz Marks
- Midterm Marks
- Attendance
```

---

## 3. Dummy Regressor

A baseline regression model used for comparison.

The Dummy Regressor predicts a constant value (usually the mean of the training target values) and helps determine whether the Linear Regression models actually learn useful patterns.

---

# Research Questions

The notebook answers three research questions.

## RQ1

Build and evaluate a Simple Linear Regression model.

---

## RQ2

Build and evaluate a Multiple Linear Regression model.

---

## RQ3

Predict Final Exam Marks using Multiple Linear Regression and compare it with the Dummy Regressor.

---

# Project Workflow

The project follows these steps:

1. Import required libraries.
2. Load dataset.
3. Explore dataset.
4. Data preprocessing.
5. Feature selection.
6. Train-Test Split.
7. Train regression models.
8. Generate predictions.
9. Evaluate model performance.
10. Compare models.
11. Plot prediction graphs.
12. Plot residual distributions.
13. Draw conclusions.

---

# Libraries Used

The following Python libraries are used:

```python
numpy
pandas
matplotlib
seaborn
scikit-learn
scipy
```

---

# Evaluation Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- Confidence Interval
- Residual Analysis

---

# Visualizations

The notebook contains several visualizations including:

- Scatter Plots
- Regression Line
- Actual vs Predicted Graphs
- Residual Distribution
- Residual Histogram
- Model Comparison Plots

---

# Folder Structure

```
Student-Marks-Prediction/
│
├── assignment 04.ipynb
├── marks_dataset.xlsx
├── README.md
```

---

# How to Run

## Step 1

Clone the repository.

```bash
git clone <repository-link>
```

---

## Step 2

Install required libraries.

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy openpyxl
```

---

## Step 3

Open Jupyter Notebook.

```bash
jupyter notebook
```

---

## Step 4

Open

```
assignment 04.ipynb
```

---

## Step 5

Run all notebook cells from top to bottom.

---

# Results

The project demonstrates that:

- Multiple Linear Regression provides better prediction performance than Simple Linear Regression.
- The Dummy Regressor serves as a useful baseline for comparison.
- Residual analysis helps verify model assumptions and identify prediction errors.
- Using multiple academic features improves prediction accuracy.

---

# Applications

This project can be useful for:

- Educational Institutions
- Teachers
- Academic Advisors
- Student Performance Analysis
- Early Identification of At-Risk Students
- Educational Data Analytics

---

# Future Improvements

Possible future enhancements include:

- Polynomial Regression
- Decision Tree Regression
- Random Forest Regression
- XGBoost Regression
- Cross Validation
- Hyperparameter Tuning
- Feature Engineering
- Web-based Student Prediction Dashboard

---

# Author

Omaima Khan & Dua Fatima

Course:
Data Science

Language:
Python

Notebook:
Jupyter Notebook
